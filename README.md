# Sports-Betting-Arbitrage

Essentially, this is made to screen scrape the data off of major sports betting websites to calculate any sports arbtitrage opportunities. It uses Selenium to do this, because most of these websites try to avoid you from getting their data (but that won't stop me!). Currently, however, it was a huge difficulty to get all of this done, as it primarily had to be manually programmed for each website to get accurate data. Because of this, I only looked at the data for only betting on the games, not any sub-bets that might happen (betting on players, plays, etc.), and I also only looked at Football teams, and only international ones. This was severely limited, hence why I was unable to really get any arbitrage opportunities myself, but it's a very tedious process to collect more data. 

Ideally this will calculate and output the right data. HOWEVER, since the data has such high variance in the naming of teams (which I didn't expect going into this), there is a normalizer algorithm that went in to try to normalize the team names, and get there to essentially be a consistent catalog among them. I got the master_team_names scraped from espn.com, to encapsulate all the football teams. This allowed for some variance which I would not like to happen, but it's alright and not that big of a deal. 
