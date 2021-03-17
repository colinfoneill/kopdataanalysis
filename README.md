# kopdatascience
All content included in the "master" branch.
Analysis of small-scale logisitcs app data. Visualiations and Analysis highlight included below (all charts generated using Matplotlib, all data cleaning performed using python/pandas):

**fee_charge_diff_scatter**
The scatter plot shows all those orders with differences between "fee" and "charge" (order ID on x axis, difference on y axis). Useful to pinpoint orders with significant differences and investigate why these orders might have large differences between fee and charge.

**regular_custom_quotes_boxplot**
Boxplot of "regular" and "custom" quote amounts. Custom has a little higher median and is a little more compact dataset. This shows that custom quotes will be more lucrative on the whole, and tend to have a smaller variance.

**sessions_duration_regression**
Regression of # of Visits per User vs. Duration. Moderately strong correlation coefficient of .61 which is probably to be expected and indicates that the longer a user spends on the site/app, the more visits in the future.

**user_visits_per_day_bar & orders_per_day_bar**
These 2 bar graphs should be looked at in tandem. I think the interesting trend here is that there is a lag effect between orders and visits (i.e. orders spike a couple days after visits spike). While this is to be expected, it proves out that orders will trend directly (with a lag of a couple days) with site visits.
