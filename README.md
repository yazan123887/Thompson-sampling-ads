This project demonstrates Thompson Sampling, a reinforcement learning algorithm used to solve the multi-armed bandit problem.
We apply it to ad selection using the dataset Ads_CTR_Optimisation.csv.

How it works:
-Each row of the dataset represents a user.
-Each column (10 total) represents an ad.
-1 = user clicked the ad, 0 = no click.

-The algorithm runs 10,000 rounds, selecting ads using Thompson Sampling and updating success/failure counts.

-At the end, it displays a histogram of how many times each ad was chosen.

Requirements:
-Python 3
-Libraries: numpy, pandas, matplotlib
