# Can we build a model to determine whether a taxi driver follows their predicted route?

## Scenario

Customers request taxi journeys through an app. The app then estimates the route that the driver will take (to be able to set a price), and then the driver arrives to pick up and drop off the person. To understand if the price estimate is correct, it's important to understand whether the estimated aroute and the real route the driver did are the same

## Dataset

To this end, a dataset was created based on:
* 5000 randomly selected journeys
* People employed to view the estimated and real route on the map, and decide whether they were the same or different (or didn't know)
* Sometimes multiple people can review the same route and give their feedback (which may not necessarily agree - part of the fun of this challenge)

The dataset included:
* journey_id
* person_id
* person_annotation (Same, different, don't know)
* estimated_journey_coordinates
* real_journey_coordinates

## Challenge

The challenge that my notebook addresses is:
* how to deal with having multiple annotations per journey, human error, etc
* create additional features based on the columns we have
* build a model to imitate human evaluation of this
* evaluation of different models
