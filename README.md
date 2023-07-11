This is a practical application assignment that focuses on using data analysis skills, in an effort to seek answer to the question based on survey results, “Will a driving customer accept the coupon if offered for visiting a restaurant/bar/coffee_shop on their way to destination?”.

Link to Explore Notebook:
https://github.com/seetharamanr86/customer_coupon_acceptance/blob/main/Explore-Coupon-Acceptance-Factors-by-Vehicle-Drivers.ipynb

Data Used: (in-vehicle coupon recommendation)
https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation

General findings:

- A total '13370' null values, spread across 6 columns and of which 'car' column has the most number of null values.

car                     12576

- Following are the remaining columns that had minimal null values that can be ignored.

Bar                       107
CoffeeHouse               217
CarryAway                 151
RestaurantLessThan20      130
Restaurant20To50          189

Bar Coupon related findings:

- The bar coupon acceptance overall was 41% and non acceptance stood at 59%.

- The 'more frequent visitors' to bar have accepted the coupons to the most (~76%) compared to the 'less frequent visitors' who have showed only less interest in coupon acceptance (~37%).

- The 'frequent elderly visitors' to bar have accepted the coupons to the most (69%) compared to 'less frequent young visitors' who have showed only less interest (33%).

- The 'frequent elderly visitors without farming/fishing/forestry job' to bar have accepted the coupons to the most (70%) compared to 'less frequent young visitors with farming/fishing/forestry job' who have showed only less interest (30%).

- The 'frequent younger visitors' to bar have accepted the coupons to the most (39%) compared to 'frequent visitors that are elder and widowed' who have slightly less interest (37%) or 'frequent visitors to cheap restaurants with low income' who have even less interest (24%).

- In general, those drivers, who has the habit of going to bar more frequently are taking advantage of the coupon and acceoting the same more compared to anyone else.

- Drivers who are within low income or use cheap restaurants does not much care about the bar coupons and that was evident from the outcomes.

Coffee Coupon related findings:

- Coffee coupons were accepted comparatively more by the passanger with friends group whereas comparatively less when travelling alone.

- Income does not influence much when it comes to coffee coupon acceptance and it mostly shows around 50% acceptance on all income groups.

- Gender does not influence much either when it comes to coffee coupon acceptance and it mostly shows around 50% acceptance for both male and female.

- It is interesting to notice the young drivers with age below 21 has higher acceptance for coffee coupons, whereas elderly population with 50 plus shows slightly less acceptance but all other intermediate groups show around 50% acceptance. 

- There is wide acceptance of coffee coupon from students, unemployed folks. Drivers belong to 'building/grounds cleaning/maintenance' have close to 100% acceptance, similar case for 'farmiing/fishing/forestry' & 'healthcare' jobs as well. 'Sales' job folks show comparatively less interest on coffee coupons.

- While one can normally think the weather could play a role in coffee consumption, but it was not creating any impact in acceptance of coupons. Infact, the acceptance was slightly low when snowy, so the guess is the driving comfort could have influenced.


