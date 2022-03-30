# Rapor Part For The Practical Test 

I am able to get
- Username
- Displayed Name
- Description
- Number of Followers
- Number of Following
- Birthday
- Data that joined Twitter
- Website 
This information from the profiles but the problem is occurs twitters htmls. They changed their html bodies and almost all the classes name are same. That is the resaon getting information is hard with web scrapping. I don't use any of api like twitter-scrapper 0.4.4 or twitter api. I used Selenium for 100 % percent scrapping data. For this reason I can't get the tweet part of the users. Because It was hard to do that also learning selenium and html tree of twitter. 

For the usage of the program is basic. We need to write our twitter username and password to the code. Then, we can write the name who is have bigger than 1000 follower.
The program takes the first 50 of the user. Because otherwise the time takes too much time.

For the analysis part. I don't have the information for the tweets. That is the reason I can't do that part. But if I would the data. I was pllaning to convert them data frame of the pandas. Then easily, I can get the all analysis within 20-50 codes. 



Some Examples of the users.

{'Username': '@rioferdy5', 'Displayed': 'Dr Rio Ferdinand', 'Description': 'Official Twitter Account of Rio Ferdinand / Media & Commercial Enquiries - Info@neweraltd.co.uk / \n@_Jmallen', 'Location': 'www.neweraglobalsports.com', 'Number of Followers': '11.3M Followers', 'Number of Following': '696 Following', 'Birthday': 'Joined June 2010', 'Joined Time': 'No Join Date Information', 'Website': '@_Jmallen', 'L50_favorites': 'No Info', 'L50_retweets': 'No Info', 'L50_replies': 'No Info'}
{'Username': '@UnitedStandMUFC', 'Displayed': 'The United Stand', 'Description': 'Manchester United Fan Channel (Unofficial) For The Global Fanbase! http://YouTube.com/theunitedstand | Enquiries Soccerboxtv@gmail.com | Latest News \n@NewsUnitedStand', 'Location': 'United Kingdom', 'Number of Followers': '1M Followers', 'Number of Following': '674 Following', 'Birthday': 'Joined July 2014', 'Joined Time': 'No Join Date Information', 'Website': 'http://YouTube.com/theunitedstand', 'L50_favorites': 'No Info', 'L50_retweets': 'No Info', 'L50_replies': 'No Info'}
{'Username': '@RodrygoGoes', 'Displayed': 'Rodrygo Goes', 'Description': 'Atleta do \n@realmadrid\n e da \n@cbf_futebol\n , revelado pelo \n@santosfc\n.  rodrygo@letsvanquish.com', 'Location': 'Madrid, Spain', 'Number of Followers': '1.1M Followers', 'Number of Following': '369 Following', 'Birthday': 'Joined January 2017', 'Joined Time': 'No Join Date Information', 'Website': '@realmadrid', 'L50_favorites': 'No Info', 'L50_retweets': 'No Info', 'L50_replies': 'No Info'}
{'Username': '@WayneRooney', 'Displayed': 'Wayne Rooney', 'Description': '@dcfcofficial\n | http://instagram.com/WayneRooney | \n@foundationwr\n | \n@triplessports', 'Location': 'Joined April 2011', 'Number of Followers': '17.2M Followers', 'Number of Following': '530 Following', 'Birthday': 'No Birth Information', 'Joined Time': 'No Join Date Information', 'Website': '@dcfcofficial', 'L50_favorites': 'No Info', 'L50_retweets': 'No Info', 'L50_replies': 'No Info'}




