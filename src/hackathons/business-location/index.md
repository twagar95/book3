---
layout: layout.hbs
---

# Hackathon - Business Locations

You are approached by a business developer to get advice on where to build a
new store in Phoenix, AZ. There are currently six candidates. Use the Yelp
dataset and come up with your own scoring scheme to identify the best location
to recommend.

## Report

[Read the Report](report.html)

## Business Types
As a team, choose one of the following business types to work on:

- A new full-service daycare center
- A new full-service car wash
- A new 24-hours gym
- A new 24-hours diner
- A new swimming pool
- A new organic food store
- A new sushi buffet

## Scoring Method

For this hackathon, you will use a scoring method that is based on a series of
20 Yes/No questions that can be applied to each candidate location. The candidate
location that has the most number of Yes's is the most viable location.

Each Yes/No question generally should take on the form of

  _Does the location have X nearby?_

where X is a feature that you think would be useful for the business to be viable.

Two examples of such questions are:
1. Does the location have _at least one McDonald's within one mile_?
1. Does the location have _at least ten businesses with 100 or more reviews within one mile_?

## Coding

Implement scoring functions and visualize how these candidate locations are
scored. The skeleton code is provided for you in [report.html](report.html).

## Grading

Each person must implement at least two questions to receive credits for this
hackathon.

## Submissions

### Business Type

Our team chose to analyze candidate locations for a new full-service daycare center.

### Contributors

The team members who contributed to this hackathon are:

- Nicole Woytarowicz
- Satchel Spencer
- Tristan Wagar
- John Murphy
- Sushant Mittal

### 20 Questions

Our team came up with the following relevant questions:

1. __Nicole__ Does the location not have any liquor stores within 3km? contributed by Nicole Woytarowicz

  Generally might signify a less nice part of town if there are liquor stores near by.

1. Is the location within 10km of the city center? contributed by Satchel Spencer

  You don't want kids easily running off into the desert.

1. __Tristan__ Does the location have a park within 5 miles? contributed by Tristan Wagar

  Children like to play outside.

1. Does the location not have a lot of clubs and bars within 2km? contributed by Nicole Woytarowicz

  Generally don't want to involve children in the nightlife of a city.

1. Does the location have pre-school or elementary school within 1km? contributed by Tristan Wagar

  Can drop your kids off at daycare after or before school.

1. __Tristan__ Does the location have a grocery store within 5 miles? contributed by Tristan Wagar

  Can easily do your grocery shopping after picking up or dropping off your kids.

1. __Satchel__ Does the location have any competeing daycares within 6km? contributed by Satchel Spencer

  Don't want to be competing with other daycares.

1. Does the location have any 4 star or above restaurants within 5km? contributed by Satchel Spencer

  Indicator of affluence and better neighborhood.

1. Does the location have any restaurants with a price range above 3 within 3km? contributed by Nicole Woytarowicz

  Another indicator of affluence and better neighborhood.

1. Does the location have any restaurants within 5 km that are good for kids? contributed by Tristan Wagar

  So you can take your kids out to eat after picking them up.

1. Does the location have any locations within 3km that have free wifi? contributed by Satchel Spencer

  In case a parent needs internet to get some work done, they can do so near by the kids.

1. __Nicole__ Is there a hospital within 5km? contributed by Satchel Spencer

  In case something happens to a child and they need to be seen by a doctor.

1. __John__ Is there street parking within 1km of the location? contributed by Satchel Spencer

  So parents can park somewhere when dropping off their kids.

1. Are there any businesses with an upscale ambience within 5km of the location? contributed by Satchel Spencer

  Indicator of affluence and nice neighborhood again.

1. Are there a lot of businesses good for dessert within 1km of the location? contributed by Nicole Woytarowicz

  Children love sweets.

1. __Satchel__ Are there mostly quiet businesses within 1km of the location? contributed by Satchel Spencer

  Want to keep things peaceful.

1. __John__ Is there a lice service provider within 1km? contributed by Satchel Spencer

  Children are prone to getting lice, especially when in groups.

1. __Sushant__ Is there an ice cream/frozen yogurt place within 2km of the location? contributed by Satchel Spencer

  Children love ice cream.

1. __Sushant__ Is there a police department within 3km of the location? contributed by Satchel Spencer

  Want police departments to signify safety of location.

1. Are there any businesses with a classy ambience within 3km of the location? contributed by Nicole Woytarowicz

  Another indicator of affluence.


### Conclusion

Our team collectively has implemented 10 scoring functions. Based on
the scores, our team recommends location 1 from west to east,
because it receives 7 out of 10 possible scores.
