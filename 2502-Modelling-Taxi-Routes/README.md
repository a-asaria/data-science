# Can we build a model to determine whether a taxi driver follows their predicted route?

We have a scenario where a taxi app, where customers request journeys through an app. The app then estimates the route that the driver will take (to be able to set a price), and then the driver arrives to pick up and drop off the person. To understand if the price estimate is correct, it's important to understand whether the estimated aroute and the real route the driver did are the same

The task here is to build a model that determines whether the real and estimated route were the same. To that end we have a dataset of:
* 5000 journeys randomly selected
* People employed to view the estimated and real route on the map, and decide whether they were the same or different (or didn't know)
* Sometimes multiple people can review the same route and give their feedback (which may not necessarily agree - part of the fun of this challenge)

The dataset included:
* journey_id
* person_id
* person_annotation (Same, different, don't know)
* estimated_journey_coordinates
* real_journey_coordinates

Where the challenge here that my notebook addresses was:
* how to deal with having multiple annotations per journey, human error, etc
* create additional features based on the columns we have
* build a model to imitate human evaluation of this
* evaluation of different models
