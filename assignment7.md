# Assignment 7: Find a Story

Using either the FEC, Senate lobbying portal, congressional disclosure forms or White House disclosure forms, find a newsworthy story that hasn't been previously reported. This can be something of interest to a local or national news audience.

Write a pitch to your editor about how you would pursue this story. This may include what other sources you would check with, what further data analysis you may perform and how long the story might take you.

Turn in:

1. A brief summary of what you found
1. The pitch to your editor
1. A step-by-step data diary of how you obtained the data and any cleaning/analysis you did
1. A sample headline and nut graf based on your finding

**Example**

I found that employees of Northwestern University overwhelmingly favored Hillary Clinton over Donald Trump with political contributions in the 2016 election.

To follow up on this story, I would compare this to how Northwestern employees contributed during the 2012 and 2008 presidential races and see if it lines up with the split between Clinton and Trump. I also would interview some of the few individuals who donated to Trump to see how they feel about working at an organization where they are in the minority. This story would likely take two days to report.

In order to find my story, I did the following:

1. Searched the FEC website for donations in the 2016 election cycle from employees of "Northwestern Univ"
2. Filtered to only contributions to Hillary For America and exported a CSV file of the results
3. Repeated the previous step for Trump's presidential campaign committee
4. For both CSVs, I: 
    * took the sum of the `contribution_receipt_amount` column
    * made a pivot table to get the unique number of donors to each campaign

Hed: Clinton's Donors Far Outnumber Trump's At Northwestern

Nut graf: Last election cycle's split wasn't even close. The Hillary For America campaign committee reported to the Federal Election Commission receiving donations from nearly 270 employees at Northwestern. 

How many gave to Donald Trump? Eight.


**Example**

I found that a lot of music artists, espeically from the hip hop community overwhelmingly favored Hillary Clinton over Donald Trump with verbal political endorsments in the 2016 election but I wondered who put money into her campaign.

To follow up on this story, I researched the web to find articles of artists that came out vocally for Hillary Clinton and then look up on the FEC site to see who actually donated to her campain only to find out that out of 22 people that came out in support for Hillary Clinton, only three people actually made a financial contribution. So the main story is why these other high profile artists didnt kick in any money to the Campaign This story would likely take two days to report.

In order to find my story, I did the following:

1. Searched the FEC website for donations in the 2016 election cycle from the names of artists that vocally supported Hillary Clinton
2. Filtered to only contributions to Hillary For America and exported a CSV file of the results
3. For the CSV, I didnt have to do too much because there were only three artists out of 22 that actually made a financial contribution to the Hillary for America Campaign: Young Jeezy, Kanye West and Beyonce.

Hed: Clinton has vocal supporters but little donors

Nut graf: Many artists from the music industry, primarly hip hop, came out in droves to show their vocal support for Hillary Clinton Presidential Campain against Donald Trump. However, when I looked up the 22 artists to see who actually chipped in financially to the Campaign, only three artists made a fiancial contribution to the effort. Those artists were Young Jeezy, Kanye West and Beyonce. 
