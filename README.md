# bundestagsabgeordnete_socialmedia_accounts
Analyze the social media accounts of all the bundestagsabgeordneten
On the website of The Bundestag every current member has an own page. On this page most of them have listet there social media accounts. Ive build a scraper that first generates a link list of all members and than saves the social media accounts of each one.

With this data i created a list of each party and on which platform they have how many accounts.

The members could probably  them selves name how there social media accounts are displayed on the website and thats why there where a lot of misspelling. For instance  the datastet containt 'Instgram', 'Instagram' and 'Insatgram'.
to clean up the data i compard all the words with 'fuzzywuzzy' and grouped similar words. Then i cleand tha dataset to only have one version of spelling. There where some cases in which no the title was just 'http://' or the hole link to a site 'https://www.markus-kurth.de' this where categorized under nicht zuzuordnen. 

