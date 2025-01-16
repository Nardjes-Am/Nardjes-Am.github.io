---
title: "Client-side and Server-side Tracking on Meta: Effectiveness and Accuracy"
collection: publications
category: Conferences
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Winner of The Andreas Pfitzmann Best Student Paper Award..'
date:  Jul 2024, Bristol, United Kingdom.
venue: '24th Privacy Enhancing Technologies Symposium (PETS 2024)'
slidesurl: ''
paperurl: 'https://hal.science/hal-04665102v1/file/popets-2024-0086.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---




Growing concern over digital privacy has led to the widespread use of tracking restriction tools, such as ad blockers, Virtual Private
Networks (VPN), and privacy-focused web browsers. All major browser vendors have also deprecated, or plan to deprecate, third party cookies to reduce tracking. Despite these efforts, advertising companies continuously innovate to overcome these restrictions.
Recently, advertising platforms, like Meta, have been promoting server-side tracking solutions to bypass traditional browser-based
tracking restrictions. This paper explores how server-side tracking technologies can link website visitors with their user accounts on Meta products.
The goal is to assess the effectiveness and accuracy of employing this technology, as well as the effect of tracking restrictions on online
tracking. Our methodology involves a series of experiments where we integrate Meta’s client-side tracker (the Meta Pixel) and serverside technology (the Conversions API) on different web pages. We then drive traffic to these pages and evaluate the success rate of linking website visitors to their profiles on Meta products.
Our findings show that Meta’s server-side technology can match between 34% and 51% of website visitors to user profiles on Meta products using basic information like the visitor’s IP address, user agent, and location data. This is comparable to Pixel-based user matching in optimal conditions (i.e., in the absence of tracking restrictions), which links between 42% and 61% of user profiles. Nevertheless, we see a considerable difference in accuracy: while the Pixel-based tracking achieves 100% accuracy, less than 65% of the profiles matched by server-side tracking are accurate.
