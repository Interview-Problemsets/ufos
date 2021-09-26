# UFOs
Getting to the bottom of all this alien business.

# The Problem
You have been engaged to help analysts and business users answer some burning questions regarding the nature of UFO reports.

Your goal is to ingest data and transform it into a more useful and friendly form for end users. You will present your solution to a panel, assume you will have roughly 30 minutes to demo and another 30 for questions.

You do *NOT* have to complete all of these requirements, and feel free to add anything you think might be useful or fun.

You are free to use any tools or technology, but be prepared to discuss the reasoning for your choices.

The end users would like a data mart that helps answer some of the following questions:
  - How many sightings have there been by Month/Year?
  - Does the longitude of the sighting have any correlation with the number of sightings or the shape of the UFO?
  - Which areas have the highest reported UFO sightings?
  - When we normalize for population, which areas have the highest reported UFO sightings.
  - Sometimes, the moderator will provide commentary on the sighting report or indicate that it's a hoax. We would like to move these into a new column or two.
  - Can we group these reports into events that might have been commonly observed? For instance, two reports from Pittsburgh that occured within 30 minutes from each other may indicate the same event being reported twice.

# The Data
You can find UFO report data at the National UFO Reporting Center: http://www.nuforc.org/index.html

Specifically, you will find the following page useful: http://www.nuforc.org/webreports.html

An example sighting report: http://www.nuforc.org/webreports/164/S164518.html

Useful Zip Code to Lat/Long dataset: https://gist.github.com/erichurst/7882666

Zip Code population data can be found in the data/ folder of this repository.
