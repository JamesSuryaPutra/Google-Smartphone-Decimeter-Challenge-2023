# Google Smartphone Decimeter Challenge 2023-2024
![header](https://github.com/JamesSuryaPutra/Google-Smartphone-Decimeter-Challenge-2023-2024/assets/155945814/65927988-3d67-4aeb-b4f3-63fdadbc1418)

# Goal of the competition
The goal of this competition is to determine the limit of smartphone GNSS positioning accuracy: that could be down to the decimeter or even centimeter level. You will develop a model based on raw GNSS measurements from Android phones.

Your work will help produce better positions, bridging the connection between the geo-spatial information of finer human behavior and mobile internet with improved granularity. Additionally, the more precise data could lead to new navigation methods.

# Description
Precise smartphone positioning services enable many of the navigation features that we use today. Yet, current mobile phones only offer 3-5 meters of positioning accuracy. Lane-specific directions aren’t always possible, which can lead to missed exits or inaccurate arrival times.

Machine learning models could improve the accuracy of Global Navigation Satellite System (GNSS) data, enabling billions of Android users to have a more fine-tuned positioning experience.

Google’s Precise Location Team, part of Android, hosted the Smartphone Decimeter Challenge in 2021 and 2022. This year, this competition is again dedicated to finding innovative research in smartphone GNSS positioning accuracy to enhance people's ability to navigate the world around them.

Your work will help improve positioning accuracy to sub-meter level, or even centimeters. As a result, Android users could gain better lane-level navigation or carpool estimates during congestion. Beyond the car, better location data could enable augmented reality walking tours, precise agriculture via phones, and more.

# Evaluation
Submissions are scored on the mean of the 50th and 95th percentile distance errors. For every phone and once per second, the horizontal distance (in meters) is computed between the predicted latitude/longitude and the ground truth latitude/longitude. These distance errors form a distribution from which the 50th and 95th percentile errors are calculated (i.e. the 95th percentile error is the value, in meters, for which 95% of the distance errors are smaller). The 50th and 95th percentile errors are then averaged for each phone. Lastly, the mean of these averaged values is calculated across all phones in the test set.
