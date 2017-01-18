Destiny Item Manager has a feature called "stats quality" that will show you how good or bad a roll you have for the Intellect, Discipline, or Strength statistic on your armor, allowing you to compare the armor pieces you have to determine which ones are worth upgrading and infusing. You can turn on this feature by going to Settings menu and then checking the option for "Enable advanced stat quality comparison features."

![](https://cloud.githubusercontent.com/assets/10524305/15339883/73369eb4-1c3b-11e6-9a41-09f557157618.png)

![](https://cloud.githubusercontent.com/assets/10524305/15339921/a3d23204-1c3b-11e6-8c91-16558b23bd8d.png)

Once you have turned this feature on each armor item will display a percentage at the bottom of it's tile, next to the Defense number. This shows you what percentage of the maximum roll that item has for it's combined Intellect, Discipline, and Strength stats.

![](https://cloud.githubusercontent.com/assets/10524305/15340078/75993094-1c3c-11e6-8032-2642d60e2ee3.png) 

The overall stat quality is also color coded for ease of use - blue if the item is a perfect 100% roll, green if it is 96-99%, yellow if it is 91-95%, orange if it is 86-90%, and red if it is 85% or less. You can view the item details (by clicking on the item) in order to see the quality of the individual Intellect, Discipline, or Strength statistics. 

![](https://cloud.githubusercontent.com/assets/10524305/15340089/88923c36-1c3c-11e6-9274-3421b81fe262.png)

The stat quality for an item is based on the estimated stats if you were to Infuse the item up to 335.  After 335, stats are locked and will not change with infusion.  The stat quality percentage grows more accurate as an item approaches 335 light, roughly 1% for every 15 light.

There is some amount of error in this estimation because the Bungie API only provides rounded whole number values, which Destiny Item Manager uses to make its estimations. This should not impact the final infused quality by more than a couple of percentage points, and DIM tries to be conservative in its estimates so that if there is an error the final stat quality will be higher than the estimated quality. Destiny Item Manager currently only provides a stat quality estimate for items with 280 or higher defense, as the error margin increases the greater the difference between the current defense value and the maximum value.

You can read more in this article (FORTHCOMING) about how stat quality is calculated and estimated, as well as how the Intellect, Discipline, and Strength stats change as an armor item's Defense Value is infused up.