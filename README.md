# Berkeley_Practical_Application-1

Write up analysis for practical application 1
There are 26 columns in the Coupons dataset.
I was able to visualize the missing data as a heatmap and it looks like the field - Car has the most missing values and this can be deleted from the dataset without having any impact to the analysis.
car                     12576
Bar                       107
CoffeeHouse               217
CarryAway                 151
RestaurantLessThan20      130
Restaurant20To50          189

While the missing data for the remaining fields can be addressed through various means such as - 
1. Dropping the missing rows
2. Replacing the missing values with a specific value such as mean, median, or mode.
3. Flag the missing the missing value in a new column and then replacing so that the information about the missing data is retained.

I chose to keep the dataset intact to avoid misrepresentation of data.


**What proportion of the total observations chose to accept the coupon?**
Proportion of total observations that accepted the coupon: 56.84%

**As prompted in the initial section, I analyzed the data for the Bar accepted coupons**
**What proportion of bar coupons were accepted?**
Proportion of bar coupons that were accepted: 41.00%

**Compare the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more.**
Acceptance rate for those who go to a bar 3 or fewer times a month: 37.06%
Acceptance rate for those who go to a bar more than 3 times a month: 76.88%

**Compare the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others. Is there a difference?**

Acceptance rate for drivers who go to a bar more than once a month and are over the age of 25: 69.52%
Acceptance rate for all other drivers: 33.44%
Difference in acceptance rates: 36.08%

**Use the same process to compare the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry.**

Acceptance rate for drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry: 68.79%
Acceptance rate for all other drivers: 29.35%


**Compare the acceptance rates between those drivers who:
go to bars more than once a month, had passengers that were not a kid, and were not widowed OR
go to bars more than once a month and are under the age of 30 OR
go to cheap restaurants more than 4 times a month and income is less than 50K.**


Acceptance rate for drivers who go to bars more than once a month, had passengers that were not a kid, and were not widowed: 62.21%
Acceptance rate for drivers who go to bars more than once a month and are under the age of 30: 62.81%
Acceptance rate for drivers who go to cheap restaurants more than 4 times a month and income is less than 50K: 59.40%

**Based on these observations, what do you hypothesize about drivers who accepted the bar coupons?**

Based on the observations, we can hypothesize several factors that influence whether drivers accept bar coupons:

**Frequency of Bar Visits:** Drivers who visit bars more frequently (more than 3 times a month) are significantly more likely to accept bar coupons (76.88%) compared to those who visit bars less frequently (37.06%). This suggests that familiarity and habitual behavior play a crucial role in coupon acceptance.

**Age Factor:** Drivers over the age of 25 who go to bars more than once a month have a higher acceptance rate (69.52%) compared to all other drivers (33.44%). This indicates that older drivers who are regular bar-goers are more inclined to accept bar coupons.

**Passenger and Occupation Influence:** Drivers who go to bars more than once a month, have passengers that are not kids, and have occupations other than farming, fishing, or forestry show a higher acceptance rate (68.79%) compared to all other drivers (29.35%). This suggests that the presence of adult passengers and certain occupational backgrounds may positively influence coupon acceptance.

**Combined Factors:**

Drivers who go to bars more than once a month, have passengers that are not kids, and are not widowed have an acceptance rate of 62.21%.
Drivers who go to bars more than once a month and are under the age of 30 have an acceptance rate of 62.81%.
Drivers who go to cheap restaurants more than 4 times a month and have an income of less than $50K have an acceptance rate of 59.40%.
These combined factors indicate that younger drivers, those with adult passengers, and those with lower incomes who frequently visit inexpensive restaurants are more likely to accept bar coupons.

**Hypothesis**
Drivers who are regular bar-goers, especially those over the age of 25, with adult passengers, and certain occupational backgrounds, are more likely to accept bar coupons. Additionally, younger drivers and those with lower incomes who frequently visit inexpensive restaurants also show a higher propensity to accept bar coupons. This suggests that both habitual behavior and contextual factors (such as age, passenger type, and occupation) significantly influence coupon acceptance.



**Similar analysis done to Coffee House coupons**

Proportion of Coffee House coupons that were accepted: 50.00%
Acceptance rate for those who go to a Coffee House 3 or fewer times a month: 44.94%
Acceptance rate for those who go to a Coffee House more than 3 times a month: 67.50%
Acceptance rate for drivers who go to a Coffee House more than once a month and are over the age of 25: 63.84%
Acceptance rate for all other drivers: 42.67%
Difference in acceptance rates: 21.17%
Acceptance rate for drivers who go to Coffee Houses more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry: 66.02%
Acceptance rate for all other drivers: 34.62%

Based on these observations, we can hypothesize several factors that influence whether drivers accept Coffee House coupons:

**Frequency of Coffee House Visits:** Drivers who visit coffee houses more frequently (more than 3 times a month) are significantly more likely to accept coffee house coupons (67.50%) compared to those who visit less frequently (44.94%). This suggests that habitual behavior and familiarity with coffee houses play a crucial role in coupon acceptance.

**Age Factor:** Drivers over the age of 25 who go to coffee houses more than once a month have a higher acceptance rate (63.84%) compared to all other drivers (42.67%). This indicates that older drivers who are regular coffee house-goers are more inclined to accept coffee house coupons.

**Passenger and Occupation Influence:** Drivers who go to coffee houses more than once a month, have passengers that are not kids, and have occupations other than farming, fishing, or forestry show a higher acceptance rate (66.02%) compared to all other drivers (34.62%). This suggests that the presence of adult passengers and certain occupational backgrounds may positively influence coupon acceptance.

**Hypothesis**
Drivers who are regular coffee house-goers, especially those over the age of 25, with adult passengers, and certain occupational backgrounds, are more likely to accept coffee house coupons. Additionally, the frequency of visits and contextual factors (such as age, passenger type, and occupation) significantly influence coupon acceptance.
Visualization for these codes has been provided in the python notebook.

**Next Steps**

**Actionable Items**
**1. Target Frequent Visitors:** Marketing campaigns should focus on individuals who frequently visit bars and coffee houses. Personalized offers and loyalty programs can be designed to attract these customers. For example, providing exclusive discounts or rewards for frequent visitors can encourage repeat business.

**2. Age-Specific Promotions:** Create age-specific promotions targeting older drivers who are regular visitors to bars and coffee houses. These promotions can be tailored to their preferences and habits. For instance, offering special deals during times when older customers are more likely to visit can increase coupon acceptance.

**3. Consider Passenger and Occupation:** Develop marketing strategies that consider the presence of adult passengers and the driver's occupation. For example, offers can be designed for professionals who are likely to visit bars or coffee houses after work. For example, offers can be designed for professionals who are likely to visit bars or coffee houses after work. Additionally, promoting family-friendly environments for coffee houses can attract drivers with adult passengers. 

**4. Combined Marketing Strategies:** Implement combined marketing strategies that consider multiple factors such as age, frequency of visits, passenger type, and occupation. This holistic approach can increase the effectiveness of coupon campaigns. For instance, targeting younger drivers who frequently visit inexpensive restaurants and have lower incomes with special offers can boost coupon acceptance.


