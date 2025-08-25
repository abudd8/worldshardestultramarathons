# What are the hardest ultramarathons in the world?

## Introduction
Ultra running as a sport has been around for over 100 years but has rapidly grown in popularity recently in large part because of people such as David Goggins and Cam Hanes. An ultramarathon is a race that is longer than the typical 26.2 mile marathon distance. These races range from 50k (31.1 miles) to 50 miles to 100 miles and beyond. Due to the nature of the courses they are run on, factors such as terrain, weather, and elevation change have a huge impact on the difficulty of the course.

## Data
This analysis attempts to rank ultramarathons around the world based on factors such as distance, participant average speed, and average number of finishers. The data was sourced from Kaggle.com (https://www.kaggle.com/datasets/fatihyavuzz/two-centuries-of-um-races) and contains data on 1,048,575 ultramarathon finishers between the years of 2016 and 2018.

The data set contains variables such as finish time, average speed, and event number of finishers. The data only contains information on competitors who finished the race, not on those who DNF.

 ## Criteria for Quantifying Difficulty

   With so many factors coming into play during an ultramarathon, there are numerous ways to quantify the difficulty of a race. The criteria I ended up deciding on were:

      1. Finisher average speed (65%)
      2. Event distance (25%)
      3. Event number of finishers (10%)

Without information on the number of runners who start the race but don't finish, it eliminates the ability to use DNF rate which is a crucial part in determining difficulty. Finisher average speed is the most prevalant factor to determine difficulty of the race. The more difficult the terrain and conditions, the slower the average runner will move. This accounts for 65% of the composite difficulty score is composed 65% of average speed. Race distance is already factored into average speed, but makes up another 25% of the composite difficulty score. And average finally the number of finishers of a given event determines the remaining 10%. All 3 parts are scaled to be between 0 and 1.

## So What are the Hardest Ultramarathons in the World?  
