# ECOS: Electric Consumption Optimization Score
ECOScore brings meritocracy into the electricity bill, reducing fees for virtuous households.

[Andrea Spreafico](https://www.linkedin.com/in/sprea22/) | andrea.spreafico22@gmail.com \
[Francesco Prete](https://www.linkedin.com/in/fprete/) | francesco.prete.eu@gmail.com \
[Mirko Rima](https://www.linkedin.com/in/mirko-rima-b3b141172/) | mirko.rima@vedrai.com \
[Demetrio Carrara](https://www.linkedin.com/in/demetrio-carrara-051ab6122/) | carrarademetrio@gmail.com \
[Chiara Sergio](https://www.linkedin.com/in/chiara-sergio-/) | chiara.sergio@aalto.fi 

![Cover Image](https://github.com/Sprea22/ECOS_Junction2022/blob/main/Pics/Cover.PNG)

## Problem Statement
Disattentive energy consumption in households is an ever-increasing problem, resulting in inefficient infrastructure usage.
Electrical grid capacities have limits, beyond which the system would collapse leading to disruptive power outages. Finland is more at risk now than ever.

## Our Solution: ECOScore
ECOScore aims to reduce electricity misusage within households, thanks to a Scalable AI Approach based on Cloud and a focus on fairness, meritocracy and explainability.
Given a group of similar consumers, ECOScore quantifies how good an household consumption is compared with the rest of the peers within the same group.

![Cover Image](https://github.com/Sprea22/ECOS_Junction2022/blob/main/Pics/ECOS.PNG)

## How it works
Firstly, to calculate the ECOScore, we take into account anagraphic information regarding the consumers and group them into clusters. 
Then, collecting the information regarding energy consumption and weather forecast, we combine them and feed them into the scoring mechanism.
At this point an ECOScore is assigned to each customer, which identify how good (or bad) the consumption behavior of a consumer is compared with the peers within the same cluster.

## Case Studies
The ECOScore can be used from both Electricity Providers and Public entities, in order to bring meritocracy into the electricity bill, reducing fees for virtuous households.
This would be the starting point to obtain a systematic energy optimization.
In fact, replacing part of the fixed costs of electricity taxes with a variable fee based on ECOScore, would allow them to have more influence on consumers behaviour. giving them the possibility to drive an overall decrease consumption of electricity 

![Cover Image](https://github.com/Sprea22/ECOS_Junction2022/blob/main/Pics/CaseStudies.PNG)

## Business Model
ECOS locates itself as a SaaS B2B business.
Firstly, the idea is to have a Data Driven monetization in order to incentivize people to use the service and quickly grow our framework.
Then, a subscription-based model can be introduced in order to expand the system and make it more resourceful.

## ECOScore and existing contracts
Existing consumers have different plans, how could the energy provider affect their consumption?
-	Fixed-price plan: ECOScore can be used to adjust only the VAT Tax.
-	Spot-price plan: ECOScore can be used to adjust both providers margins and VAT Tax.

## How much does it cost to implement the framework?
Fixed Costs:
-	Cloud Infrastracture —> 200€/month
-	Weather service —> 150€/month

Dynamic:
-	Costs are based on number of requests —> ~0,0025€/request
-	The more requests the lower the price per unit overall 

## How long would it take to implement the framework?
The idea would be to have a proof of concept within 3 months, to understand and prove the validity of the framework. Then, in order to amplify and make the system robust enough for big use cases, it would be probably extended for other 9 months to sum up to 12 months of work.

