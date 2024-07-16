---
title: Flights Search Engine
layout: default
parent: Product Experience
nav_order: b
heading_anchors: true
---

# Product: Flight Search Engine

## The Product
{: .d-inline-block }

API
{: .label .label-purple }


The Flights API is a multi-sided platform that connects travel sellers on the demand side and 300+ airlines on the supply side.

## My Role
I was hired as the first PM of a previously engineer-led team. Tasked with reconciling product discovery of a new customer segment and technical requirements of airlines, into a single product roadmap.

## The Team
5 senior back-end software engineers <br>
1 product designer

### Project 1: Improving itinerary coverage
<div class="code-example" markdown="1">

<strong>The problem</strong> - On certain flight routes, the combined result was missing some direct flight itineraries causing friction with end users.

<strong> The discovery</strong> - Our supplier's APIs ordered itinerary results from lowest to highest price by default and cut the result set at 50 itineraries. The direct flight missing results were set at a higher price point, for which they were being dropped at the supplier level.

<strong> The result</strong> - By defining and testing 3 approaches towards maximizing itinerary coverage, we were able to improve coverage on these cases, from 80% to 99%
</div>

### Project 2: Enriching ticket conditions and attributes
<div class="code-example" markdown="1">
<strong>The problem</strong>  - 60% of our offers showed inconsistencies with baggage, refund and exchange attributes. To fill in the information gaps, we needed to create metrics to identify the problem and evaluate solutions to fix it.

<strong>The discovery</strong>  - Through granular metrics, we discovered that hot spots shifted through time depending use case, supplier and search behaviour. We had to approach this problem dynamically.

<strong>The result</strong>  - In 6 weeks, we were able to improve consistency for routes consisting on 80% of our search volume and partnered with a 3rd party to address the long tail.
</div>

### Project 3: Project 3: Search speed
<div class="code-example" markdown="1">

<strong>The problem</strong> - Search speed latency percieved as to slow and delayed 2 key customer go live target dates.

<strong>The discovery</strong> - 80% of latency depended on 3rd party APIs. Duffel search speed could be addressed in two very different approaches: a design choice, and a technical solution.

<strong>The result </strong> - Two fold solution: First, we modified our customer onboarding playbook to address search speed at the design stage. Second, we created a long-pull endoint to accelerate application's Time to Interactive.

</div>