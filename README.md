# Amazon Vine Analysis

## Overview

This project was to look at review data for luggage collected by Amazon. Using spark, the review data was split into four tables and sent to an AWS postgres database. The Vine reviews table was then export and analyzed using pandas to determine if there was any bias between paid and unpaid reviewers.

## Result

* How many Vine reviews and non-Vine reviews were there?

    * There were 19 vine reviews and 6017 non-Vine reviews that were determined helpful.

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

    * 9 vine reviews were 5 stars and 3200 non-vine reviews were 5 stars.

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

    * 47.37% of the vine reviews were 5 stars; 53.18% of the non-vine reviews were 5 stars.

## Summary

There does not seem to be bias visible for paid reviews in this data selection since the percentage of 5-star reviews is less than the unpaid percentage. However, only having 19 vine reviews that were deemed helpful is a small sample to draw any meaningful trends. Perhaps a wider dataset might indicate any trends present with the reviews.