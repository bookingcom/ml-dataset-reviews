# ml-dataset-reviews

This repository contains the training set of the user-generated review dataset of Booking.com reviews. The training set contains about 1.6M reviews from 40k accommodations around the world. All reviews were written by guests who stayed at the accommodation.

The dataset consists of English reviews published in 2023. All reviews have passed a moderation process ensuring they are genuine and do not violate the platform guidelines. To avoid displaying reviews that do not reflect of the accommodation's overall sentiment, reviews with two points or more below the average accommodation score were excluded. In order to preserve user privacy, no personally identifiable information was included in the data. Similarly, to protect business-sensitive statistics, the dataset is limited to only tens of thousands accommodations. Finally, we selected only informative reviews that include at least 3 topics.

The following table describes the fields in the dataset:
|Column                     | Description                                       |
| ------------------------- |:-------------------------------------------------:|
| review_title              | The title of the review                           |
| review_positive           | Positive ("liked") section in review.             |
| review_negative           | Negative ("disliked") section in review.          |
| guest_score               | Review score for the stay                         |
| review_helpful_votes      | How many users marked the review as helpful       |
| guest_type                | There are 4 types of traveller types: Solo<br>traveller (1 adult) / Couple (2 adults) /<br>Group (>2 adults) / Family with children<br>(adults & children) |
| guest_country             | Anonymized country from which the reservation was<br>made |
| room_nights               | The length of the reservation, i.e. number of<br>nights booked |
| month                     | The month of the check-in date of the reservation |
| accommodation_id          | An anonymized accommodation ID                    |
| accommodation_type        | The type of the accommodation, e.g. hotel,<br>apartment, hostel |
| accommodation_score       | The overall average guest review score for the<br>accommodation |
| accommodation_country     | Country of the accommodation                      |
| accommodation_star_rating | Accommodation star rating is provided by the<br>property, and is usually determined by an<br>official accommodation rating organisation or<br>another third party |
| location_is_beach         | Is the accommodation located in a beach location  |
| location_is_ski           | Is the accommodation located in a ski location    |
| location_is_city_center   | Is the accommodation located in the city center   |

The dataset is published under the following non-commercial [license](https://creativecommons.org/licenses/by-sa/4.0/deed.en)




