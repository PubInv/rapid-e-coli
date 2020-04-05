# Rapid E. coli Detection

## Introduction

This is a project to detect the bacterium [E. coli](https://en.wikipedia.org/wiki/Escherichia_coli), commonly used as an indicator organism of fecal contamination,
rapidly in drinking water in developing countries where a laboratory is not available.

## Problem

> [WASH](https://en.wikipedia.org/wiki/WASH) (or Watsan, WaSH) is an acronym that stands for "water, sanitation and hygiene". Universal, affordable and sustainable access to WASH is a key public health issue within international development and is the focus of Sustainable Development Goal 6.[1]

From the same article:

> Lack of sanitation contributes to about 700,000 child deaths every year due to diarrhea, mainly in developing countries.

Providing water, sanitation and hygiene for the whole planet is a big job, and
a tiny part of it is to be able to tell when your water is polluted.
Of may possible sources of pollution, fecal contamination may be the most
dangerous. E. coli is an bacterium which has been shown to be a valuable
indicator organism of fecal contamination that is relatively easy to detect.
These methods generally require 24 to 48 hours.

### Motivation

Imagine that we had a magic instrument, not unlike the fictional [tricorder](https://en.wikipedia.org/wiki/Tricorder) of Star Trek,
that at no cost instantly determines if E. coli is present in drinking water
and if so, how much.

Such an instrument would not make polluted water safe to drink.
However, it could be used to save lives around the world by:
1. Ensuring water is safe to drink,
2. Allowing water sources to be compared, and
3. Helping to locate sources of contamination.



The goal of this project is to build a free-libre, open source, portable, rugged, reliable instrument that can be
taken into the field in developing countries and reliable measure the presence and quanity of E. coli.

## Status of Project

In conjunction with volunteers for Engineers Without Borders, we developed a battery-powered [portable incubator](http://jhe.ewb.org.au/index.php/jhe/article/view/127)
that allowed this test to be performed in 48 hours with no electricty. All Public Invention project are open-source, you can build your own following this [instructable](https://www.instructables.com/id/Portable-Petrifilm-Incubator-for-Inexpensive-In-Fi/).
![MainImageOfArmadillo](https://user-images.githubusercontent.com/5296671/71315292-9a072600-241e-11ea-917a-c014b15cba7c.jpg)
![ExlplodedView Large](https://user-images.githubusercontent.com/5296671/71315291-95427200-241e-11ea-8860-0841ea66a634.jpg)


However, there is more to do:
1. Although small, the incubator could be made much smaller and easier to use.
2. Although not requiring an electrical grid as an advance, the 48 hours is still a limitation.
3. The colonies have to be counted by eye from photographs; the instrument is not fully automatic.
4. The Petrifilm-based approach is good at detecting E. coli in dirty water; it is not good at telling that water is clean enough to meet WHO standards.

## Call to Action

Public Invention is a 501c3 tax-exempt public charity that "Invents in the public, for the public."
We are seeking an "Invention Coach" to lead the Rapid E. coli detection project team by volunteering
the drive and expertise about eight hours per week.

Such an "Invention Coach" would get the satisfaction of knowing they made a major contribution to
high impact technical problem that will eventually save lives.

Inventors, who volunteer to work on the project but not to take responsibility for leading,
will also have the satisfaction of knowing they worked on a high-impact project. In all likelihood,
academic or other publications will be produced which may advance the professional careers of undergraduates,
graduates, and professionals.

This is a multi-dimensional problem. It may be that the problem has been solved in the laboratory, and
the need may be to make rugged, portable instruments for use in the field.
Possibly computer vision integrated into a camera/microscope would be useful.
It may be that additional basic biological and bio-hacking research is required.
It might even be that this is primarily an education effort.
What is really needed is someone willing to dive in and master this material to make
rapid field-based E. coli testing a practical reality to keep children from dying from drinking contaminated water.

## Existing Approaches

There are a number of approaches to detecting bacteria generally
(rather E. coli specifically) in [bacteriological water analysis](https://en.wikipedia.org/wiki/Bacteriological_water_analysis).

It is a remarkable fact that there are reagents,
[X-gal](https://en.wikipedia.org/wiki/X-gal) and [X-Gluc](https://en.wikipedia.org/wiki/X-Gluc), which
turn blue or purple in the presence of enzymes very specifically produced by
the E. coli organism. Therefore, although bacteria are too small to see,
This is the basis of several approaches to detecting E. coli. However,
all of these approaches require time for E. coli organisms to reproduce
to detectable levels.

The method of [Petrifilms](https://en.wikipedia.org/wiki/Petrifilm)
manufactured by the 3M corporation are an illustrative
example. In this method, a single milliliter of sampled water is
placed on a playing-card like film which contains agar, nutrients, and
reagents. After 48 hours, colonies of bacteria may grow which are
visible to the naked eye and identifiable as E. coli by their color
and having generated a bubble of CO2 under a cellophane-like film.

![DualPetrifilmWC (Figure 7)](https://user-images.githubusercontent.com/5296671/71315308-316c7900-241f-11ea-8701-bdc6cabad5e5.png)

# Related Research

This research claims to have reduced times to 6.5 hours: [https://www.sciencedirect.com/science/article/pii/S0167701200001937](https://aem.asm.org/content/aem/61/12/4505.full.pdf)
Same author, related work with pdf available: [https://aem.asm.org/content/aem/61/12/4505.full.pdf](https://aem.asm.org/content/aem/61/12/4505.full.pdf)


[https://link.springer.com/article/10.1007/s11274-008-9747-x](https://link.springer.com/article/10.1007/s11274-008-9747-x)

This paper claims to have reduced the time to approximate seven hours:
[https://onlinelibrary.wiley.com/doi/full/10.1046/j.1472-765x.2000.00683.x](https://onlinelibrary.wiley.com/doi/full/10.1046/j.1472-765x.2000.00683.x)

This method gets it down to 45 minutes using an luminometer. However, it requires between 100 and 1000 cells, so it is not clear how rapidly this
could be applied in the field:
[https://ieeexplore.ieee.org/abstract/document/1037094](https://ieeexplore.ieee.org/abstract/document/1037094)


## Rapid coliform presence/absence test

One of the means of determining drinking water safety is to perform a coliform presence/absence test such as those made by
[Hach](https://www.hach.com/presence-absence-test-pk-12/product-downloads?id=7640249610) or
[IDEXX](https://www.idexx.com/en/water/water-products-services/colilert/).

These methods require incubation at a certain temperature an produce a color change in the presence of the organism.
Generally they require 24 hours or 48 hours.

It seems possible to produce a rapid test by building a machine that takes the place of the human eye that tests
the transmissivity of a certain color, perhaps through a large linear quanity of the material. In theory
this might detect a color change more rapidly than 24 hours.

For example, suppose that we could build a waveguide for water, consisting of a plastic tube with an index
of refraction less than water. (The only plastic I know of that has this property is Teflon AF, made by DuPont,
which can [specifically](http://www.biogeneral.com/teflon-af/) be used to make a light wave guide.) The tube, when filled with water, would resemble a glass optical fiber.
Light shined into one end would be totally internally reflected.

If we made a helical coil, we could easily produce several meters of light path in a compact space, still
containing 100 ml of water, the normal test sample size.

![rapid detection of colorimetric change in water](https://user-images.githubusercontent.com/5296671/48650617-994ec580-e9bc-11e8-870c-d317e262a797.png)

Then, the machine could, wich some sensitivity, report a graph of transmissivity over time, using a simple LED
and a photodiode.

In theory, it might be possible to detect changes in the color in a rapid period of time.

The increase light path would multiply the sensitivity to transmissivity changes into a range detectable by
a normal analog-to-digital converter, so long as the decreased trasmissivity was due solely to reaction of the
reagent with the bacterial by product (if the water were very turbid, transmissivity might be so low this would not be possible.)

The result might be the ability to perform this test in a much lower time than 24 hours.

This would be a great boon in emergency situations. You could essentially test a an unkown source of water for
fecal contamination indicator organisms in, for example, 30 minutes, to rapidly determine safety.

An improvement would be to use the same LED and the same photodiode for measuring both the control and the sample. However, we sould then need some sort of switch to shut off light to one of the tubes. One can imagine a mechanical switch of
physical device in an air gap; some sort of Faraday effect with polarization might be possible but is probably not worth it.

# Update: Test of Light Guide

In February of 2019, we filled a teflon tube with water and attempted to use it as a light guide. At the scale of a meter, it appeared to fail completely. On the other, as would be theoretically predicted, when the tube was filled with nearly pure Ethanl (5% water), it worked as expected, sending all most all of the entering light to the exit end.
The index of refraction of Ethanol is much higher than the index of refraction of water.


# Understanding colorimetric changes

Here is the description of [Petrifilm Chemistry](https://www.3m.com/3M/en_US/company-us/all-3m-products/~/ECOLICT-3M-Petrifilm-E-coli-Coliform-Count-Plates/?N=5002385+3293785155&rt=rud):

>The 3M Petrifilm E. coli/Coliform Count Plate is a sample-ready-culture-medium system which contains Violet Red Bile (VRB) >nutrients, a cold-water-soluble gelling agent, an indicator of glucuronidase activity (BCIG), and a tetrazolium indicator >that facilitates colony enumeration in food and beverage samples.

Violet Red Bile (VRB) is an [interesting chemical](https://catalog.hardydiagnostics.com/cp_prod/Content/hugo/VioletRedBileAgar.htm):

>Violet Red Bile Agar is a selective medium used to detect and enumerate lactose-fermenting coliform microorganisms. The medium is recommended for use in the microbiological analysis of milk and other dairy products, and for use in the examination of water. (1,2)

>The medium contains bile salts and crystal violet which serve as inhibitory agents toward some gram-positive microorganisms, especially staphylococci. Neutral red is employed as the pH indicator.

>Lactose-fermenting microorganisms produce pink to red colonies that are generally surrounded by a reddish zone of precipitated bile. Non-lactose-fermenting microorganisms result in colorless colonies.

Note: [E. coli](https://en.wikipedia.org/wiki/Escherichia_coli) is a Gram-negative facultative anearobic bacteria.


This is a description of [BCIG](https://foodsafety.neogen.com/en/dc-medium-bcig):

>DC Medium with BCIG is used in the chromogenic differentiation of E. coli from other coliforms in water samples using the membrane filtration method in a laboratory setting. DC Medium with BCIG is not intended for use in the diagnosis of disease or other conditions in humans.

>DC (Differential Coliform) Medium with BCIG is a selective and differential medium for the presumptive identification of E. coli. This medium is enhanced by the addition of a chromogenic agent, BCIG, 5-bromo-4-chloro-3-indolyl-β-D-glucuronide to detect glucuronidase activity. The presence of the enzyme β-D-glucuronidase differentiates most E. coli spp. from other coliforms, and is the same enzyme used in the MUG reaction. BCIG reacts slightly differently, and when released into the medium is insoluble, accumulating within the cell, imparting a blue to purple color to presumptive E. coli colonies.


>Formula	Liter
>Lactose	10 g
>Tryptose	10 g
>Yeast Extract	3 g
>Sodium Chloride	5 g
>Proteose Peptone	5 g
>Bile Salts	1.5 g
>BCIG	0.2 g
>Neutral Red	0.08 g
>Agar	15 g

Note: There are two chemicals, [X-Gal](https://en.wikipedia.org/wiki/X-gal) and [X-Gluc](https://en.wikipedia.org/wiki/X-Gluc), which are slightly different, both of which can detect E. coli.
