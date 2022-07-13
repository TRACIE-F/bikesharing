# Bikesharing #
This analysis utilized Tableau, Jupyter Notebooks, and Python to clean data and create a Tableau story to determine how to successfully translate bikesharing data from New York City to a successful bikesharing launch in Des Moines, Iowa.

## Link to Dashboard ##
[Bikesharing Dashboard](https://public.tableau.com/views/bikesharinghw/BikesharingDash?:language=en-US&:display_count=n&:origin=viz_share_link)

### Results ### 

The results of this analysis show clear patterns and some strong foundational knowledge as the client works to bring bikesharing to Des Moines.

**Trip Duration**
![Trip Duration](https://github.com/TRACIE-F/bikesharing/blob/main/Resources/Checkout%20Time.png)

The overall trend is that trips are incredibly short - a vast majority of users are riding for less than an hour, peaking overall at about 10 minutes.
The trend tracks between men & women, unknown trends a little flatter toward a slightly longer ride. Mostly, this indicates that men are the largest demographic.

When translating this to Des Moines, I would consider that any ride is likely going to look a little longer depending on the locations chosen. Midwest distance and Manhattan distance are definitely not the same, and customers might be willing to take longer rides for the right destinations.


**Trips by Gender, Day, and Time**
The next set of visualizations demonstrate the concentration of trips by time of day and gender.
 * ![Trips1](https://github.com/TRACIE-F/bikesharing/blob/main/Resources/Trips%20wbh.png)
  * The first visualization demonstrates a clear pattern - overall there's a lot of volume M-F during rush hours (7-10am and 4-6pm) and strong upticks beginning Thursday through the weekend.
 * ![Trips2](https://github.com/TRACIE-F/bikesharing/blob/main/Resources/Trips%20by%20Gender%20wbh.png)
  * This visualization indicates no distinct patterns between male, female, and unknown riders. This indicates that the primary users are male.
 * ![Trips3](https://github.com/TRACIE-F/bikesharing/blob/main/Resources/Trips%20by%20Gender%20By%20Weekday.png)
  * Saturdays and Sundays see an uptick an anonymous customers, but the bulk of the batch is subscribing males, all week. I do see a lighter weekend rate for the female subscribers, especially on Sunday. 

**Starting & Ending Points in NYC**

While understanding the target demographic for the biking service is a helpful piece of analysis, I would consider the placement of the bikes even more crucial. Comparing New York City to Des Moines is a little challenge, but there are some over-arching key clues to leverage.

![NYC Start](https://github.com/TRACIE-F/bikesharing/blob/main/Resources/Top%20Starting%20Locations%20-%20Unmarked.png)

Top 5 Starting: Pershing Square (Grand Central Terminal), E 17th & Broadway (Union Square Park), West St. & Chambers Street (Near schools, Rockefeller Park, and One World Observatory), 12 Ave & W 40th St (Lincoln Tunnel), 8th Ave & W 31 St (Penn Station)

The Top 5 Ending stations appear to align with the top starting locations, indicating these are simply popular stops.

Many of these common spots are near parks, transit hubs (Grand Central Station), or near the Hudson. Usage got lighter starting at and going north from Central Park, and outside of Manhattan. The Financial District did look quite a bit lighter, but the trip timing indicates spikes during traditional commute times M-F 8 to 5. 

###Summary###
Overall, I believe that a bikesharing culture could work in Des Moines, utilizing lessons learned from the NYC bikesharing. Here are some of the questions I'd ask to move forward in Des Moines:

  * Are colleges and universities part of the strategy? Based on the popular starting and ending points, there does appear to be a high volume of usage near NYU and a couple of high schools in Manhattan.
  * ![nycollege](https://github.com/TRACIE-F/bikesharing/blob/main/Resources/NY%20College.png)
  * ![dcollege](https://github.com/TRACIE-F/bikesharing/blob/main/Resources/DesMoines%20College.png)
  * Could biking be part of the culture at the Iowa State Fair? Partner with the butter booth and do some "Bike to Butter" promos?
  * Are there waterfront trails that lead from practical location to practical location?
  * How pivotal is downtown Des Moines to the strategy?
  
At the end of the day, the clients working on this project are familiar with Des Moines and know the area well enough to ask these questions and more to run some successful tests.
