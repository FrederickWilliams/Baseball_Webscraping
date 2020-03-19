# **Web Scraping for Baseball Stats**

Collecting sports statistics is almost the &quot;Hello World&quot; of web scraping projects. Let&#39;s see if we can make it a little more interesting.

**Data Source**

We will be using https://www.baseball-reference.com/ (https://www.baseball-reference.com/) to gather our statistics. Their data is very well organized, and the HTML is well-labeled and easy to navigate.

**Japan Data**

Japan Central League: https://www.baseball-reference.com/register/league.cgi?code=JPCL&amp;class=Fgn

The Japan Central League is composed of 6 teams, Chunichi Dragons, Hanshin Tigers, Hiroshima Carp, Yakult Swallows, Yokohama Bay Stars, Yomiuri Giants (actually, some years had more teams), with data stretching back to 1950 organized into a table of links for teams for each year. It should be a relatively easy task to scrape a list of links for each year (hint: think &quot;dictionary&quot;)

**Batting Stats**

Clicking a year link will take you to tables of league statistics for that year. To keep things simple, we will only scrape the second table -- &quot;League Batting&quot;.

**Deliverable**

Your job is to present a comparative analysis between Japanese Central League baseball teams and Major League Baseball division teams using the **&quot;base run&quot;** statistic calculated from data scraped from the Baseball-Reference website. This analysis should contain tables and visualizations to support an ultimate answer to which country&#39;s baseball teams are stronger. You are free to use any combination of requests, beautifulsoup, gazpacho, scrapy, etc. that you feel comfortable with to gather the data and any visualization library you want.
