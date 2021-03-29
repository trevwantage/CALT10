---
title: CALT10 user's frequently asked questions
subtitle: Quick answers to common questions
summary: This section contains quick answers to common questions.  For more at length explanations see the technical posts section.
authors:
- admin
tags: []
categories: []
date: "2019-02-05T00:00:00Z"
lastMod: "2021-03-16"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---




----
## Shouldn't the package be completely free of leaks?
--------------------------------------------------
The pressure drop and pressure rise leakage tests (also known as pressure decay test) are measuring the air leaking from or to the test space.  During the leak test the interspace is pressurised and any flow of air leaking from the interspace determined by the pressure change. The pass-rate for the package will have been determined by making calculations to determine the size of a hole that would be needed for that amount of air to leak under the conditions of the test.  The test pass-rate is set such that the size of that hole is sufficiently small to prevent any unacceptable loss of contents.  The pass rate is set by the package designers who know about the form of the contents to be carried in the package.

So although air can leak out of the interspace the contents are retained.


----
## Why is there an option to measure the volume multiple times?
------------------------------------------------------------
If there are small differences between measurements these are averaged out by the software.  If an error is made during the initial volume measurement this is quickly noticed when the second measurement is made and the volume measurement can be discarded.  During the volume measurement process the valve is closed and opened twice with connections being change from the pressurisation tube to the reference volume.  If a mistake is made such as residual pressure being read as down stream pressure this would be noticed.

So if you do not know what the approximate volume will be then multiple reading will guard against errors in applying the process

----
## Should I measure the test volume every time I test?
--------------------------------------------------
When measuring the test volume of small and medium sized containers with precision machined O-ring grooves, normally there will be only minor variations in volume, particularly where the same leak tester (ie valve, connector and pressure transducer) is being used.  Large containers such as an ISO container with a dumbbell seal will likely have more variation due to variations in the seating and compression of the seal.

Experience with any particular container provide the answer on how repeatable the volume is between opening and closing of the container closure.  If there is variation then the impact on the accuracy/certainty of the leak test result can then be calculated and you can decide accordingly.  See our technical posts for discussions on leakage testing.



----
## What size reference volume should I use?
----------------------------------------

A reference volume that is a similar volume to the volume being measured is idea.
Volumes that are very much bigger or very much smaller should be avoided as they can introduce significant errors.
If for example a very large reference volume were used to measure a small test volume when the air is expanded from the test volume to the large reference volume the pressure would drop to almost atmospheric pressure.  Likewise if a very small reference volume is used to measure a very large test volume there will be a very small pressure drop.  See the CALT user manual for more guidance or our technical paper on leakage testing if you want to consider a particular combination.


----
## What is the settling period for at the beginning of the test
----
When a system containing elastomer seals are initially pressurised there can be a number of changes that can effect the pressure

 * seals can move and settle down - this might due to the design of the sealing system so will vary between package designs
 * with some materials sorption can take place
 * if the volume is large the air can be heated by the pressurisation and will need time to stabilise
 * if the air is of a different temperature to the container then cooling or heating of the air will give rise to a pressure change

Experience with specific container designs, environmental conditions and various contents will enable you to judge how long is required for the pressure to stabilise before starting the test.

>At the end of the settling period if the temperature is still changing you might decide to extend the settling period if you think it will stabilise or if not you might decide to abandon the test and check the seals.  initially check the connections of the CALT to the container


----
## How do I decide how long to test for?
-------------------------------------
The length of test is dependent upon the test volume and pass rate for the particular container and the test pressure that is going to be used.
We recommend that a test be of such a length that the pressure would need to drop by at least 4mbar for the test to fail.  Although the CALT is quite capable of measuring fractions of a mbar pressure change, a 4mbar failure rate provides a high-level of confidence in the result.  The CALT will display a warning if an inappropriate test is being setup.

For small test volumes this will be equivalent to a test of 20 minutes or so for a large test volume it will be very much longer.  Look out for our technical post on designing a leakage test for more detail on how to calculate an appropriate length of test.



----
## Is a longer test always better?
-------------------------------
A longer test is not always better.  It is dependent upon the test volume, the test pressure and the pass leak rate.
Lets compare two every day items.  A bicycle tyre and a large tractor tyre.  If the were both inflated to the same pressure and they both have a small leak.  If the hole allowing the air to leak is the same size (diameter and length) in both tyres, as the pressure is the initially the same in both the air will escape at the same rate.  The pressure in the bicycle tyre will drop much more quickly than the pressure in the tractor tyre due to difference in the size the reservoir of air molecules.

This is much the same situation with leak testing interspace volume in containers.  A container with say a 2cc test volume could lose all of it pressure if the test is too long.  Yet a leaking container with a very large test volume may need a long test before the pressure drop is confidently detected.

Look out for our technical posts on leakage testing for discussion on calculating an appropriate length of test.   


----
## Why do the standards say the container is to be a thermal equilibrium?
----------------------------------------------------------------------

If the temperature of the container is changing it can change the pressure of the air in the test space by the air expanding or contracting making it appear that the container is leaking when it isn't or worse masks a leak.  A temperature change of 2 degrees will result in a significant pressure change.



----
## I have forgotten my password can I get it back?
-----------------------------------------------

Without the utilities password you will not be able to access that area of the software.  If you have forgotten your password contact us and we will talk you through the process required to recover your password.  This will involve you providing us with information from the CALT so you will need access to the working CALT. This can be done via phone or email.
