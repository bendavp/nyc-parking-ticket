# Final Project for DS4400: Machine Learning 1

Final project for DS4400 (Machine Learning 1) taken at
Northeastern University

## Authors:

- Victoria Staada: <https://github.com/victoriastaada>
- Benjamin Kosiborod (myself): <https://github.com/bendavp>

## Summary:

For our machine learning final project, we train a machine learning model to predict the violation code of a
ticket written in New York City. The violation code is a standardized number used throughout the
five boroughs of New York City that denotes the specific violation that occurred during parking.
We do this by using a 2019 dataset provided by Open Data NYC that contains approximately 11.5 million
rows of parking ticket examples with around 43 columns.

We hope that this project can help people make a decision as to where to park their car in NYC, 
as well as what time is the most optimal for them to park. For instance, some areas might be more 
heavily or more strictly patrolled, with higher fines associated with a particular violation. 
Even though different violation codes may be associated with the same type of violations, 
they can come with different fines. It would also certainly be helpful to know whether particular 
attributes of a vehicle or particular attributes of a specific area of NYC are associated with 
certain violation codes. Perhaps trucks parked on Broadway are less likely to receive a street
cleaning violation, but are more likely to receive a double parking violation, while trucks 
parked in a more suburban area of Queens are less likely to receive a double parking violation, 
but more likely to receive a street cleaning violation. Such a model can help not only drivers
of passenger cars, but also taxi operators, truck drivers, and the management of these respective
companies. It can allow them to plan their budget on parking violations more accordingly.

Additionally, this can be an incredibly useful tool for police accountability, as this model can 
double-check their work. It can possibly anticipate whether a ticket should be written with a higher 
or lower fine, especially if a police officer is new or patrolling outside of their usual precinct 
and may not be familiar with the typical procedures and protocols of a precinct in which they do not
usually work. Moreover, it can help police chiefs and administrators evaluate whether they are writing
tickets throughout the five boroughs in a fair way, or determine whether they are biassed towards
a particular vehicle make/model, a particular day, time, or so forth.

To learn more about the project, please see the presentation slides or the final
report in the root of this repo.

## Contents:

- the jupyter notebook with all code used to clean data, train & test ML models, etc.
- powerpoint, summarizing key points of project goals and outcomes
- a final report pdf discussing the project in detail
