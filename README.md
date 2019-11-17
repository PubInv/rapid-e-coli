# Rapid E. coli Detection

## Introduction

This is a project to detect E. coli more rapidly in drinking.
E. coli is probably the best indicator organism of fecal contanimation and
therefore water that will eventually make you sick.

## Problem

> [WASH](https://en.wikipedia.org/wiki/WASH) (or Watsan, WaSH) is an acronym that stands for "water, sanitation and hygiene". Universal, affordable and sustainable access to WASH is a key public health issue within international development and is the focus of Sustainable Development Goal 6.[1]

From the same article:

> Lack of sanitation contributes to about 700,000 child deaths every year due to diarrhea, mainly in developing countries.

Providing water, sanitation and hygiene for the whole planet is a big job, and
a tiny part of it is to be able to tell when your water is polluted.
Of may possible sources of pollution, fecal contamination may be the most
dangerous. E. coli is an bacterium which has been shown to be a valualbe
indicator organism of fecal contamination that is relatively easy to detect.
These methods generally require 24 to 48 hours.

### Motivation

Imagine that we had a magic machine, not unlike the fictional [tricorder](https://en.wikipedia.org/wiki/Tricorder) of Star Trek,
that at no cost instantly tells you if E. coli is present in drinking water
and quanitifies if so.

Such an instrument would not make polluted water safe to drink.
However, just as a geiger counter can warn you to take precaution against
radiation, such a device would help you protect yourself from and
identify polluted water.

The goal of this project is to build such a machine, or, more realistically,
reduce the time and complexity of detecting E. coli as much as possible.

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
example. In this method, a single millileter of sampled water is
placed on a playing-card like film which contains agar, nutrients, and
reagents. After 48 hours, colonies of bacteria may grow which are
visible to the naked eye and identifiable as E. coli by their color
and having generated a bubble of CO2 under a cellophane-like film.
