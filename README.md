
<img src="https://github.com/dermitdemk/bundestagsabgeordnete_socialmedia_accounts/assets/60017842/c49d15fb-0a39-4eff-8d53-bb0d6155147f" width="800" />



# bundestagsabgeordnete_socialmedia_accounts.


Analyzing the social media accounts of all the bundestagsabgeordneten

On the website of The Bundestag every current member has an own page. On this page most of them have listet there social media accounts. Ive build a scraper that first generates a link list of all members and than saves the social media accounts of each one.

With this data i created a list of each party and on which platform they have how many accounts.

The members could probably  them selves name how there social media accounts are displayed on the website and thats why there where a lot of misspelling. For instance  the datastet containt 'Instgram', 'Instagram' and 'Insatgram'.
to clean up the data i compard all the words with 'fuzzywuzzy' and grouped similar words. Then i cleand tha dataset to only have one version of spelling. There where some cases in which no the title was just 'http://' or the hole link to a site 'https://www.markus-kurth.de' this where categorized under nicht zuzuordnen. 
|                           | afd         | cdu  | linke       | grüne       | fdp         | spd         | frakitonslos |
| ------------------------- | ----------- | ---- | ----------- | ----------- | ----------- | ----------- | ------------ |
| hompage                   | 65          | 193  | 38          | 114         | 89          | 201         | 5            |
| instagram                 | 43          | 148  | 28          | 107         | 86          | 181         | 3            |
| facbook                   | 74          | 175  | 36          | 105         | 88          | 195         | 6            |
| twitter                   | 55          | 103  | 31          | 107         | 80          | 141         | 5            |
| tiktok                    | 4           |      |             |             | 1           | 5           |              |
| youtube                   | 21          | 14   | 6           | 8           | 8           | 11          |              |
| linkdin                   | 6           | 39   | 3           |             | 41          |             | 1            |
| nicht zuzuordnen          | 1           | 1    |             | 4           | 1           |             | 1            |
| telegram                  | 10          |      |             |             |             |             |              |
| gettr                     | 5           |      |             |             |             |             |              |
| xing                      |             | 2    |             | 1           |             | 2           |              |
| flickr                    |             | 1    |             |             |             |             |              |
| twitch                    |             |      |             |             | 1           |             |              |
|                           |             |      |             |             |             | 1           |              |
| Gesamte accounts          | 284         | 676  | 142         | 446         | 395         | 736         | 21           |
| Anzahl abgeordneter       | 79          | 200  | 41          | 120         | 93          | 208         | 6            |
| Accounts pro abgeordneter | 3,594936709 | 3,38 | 3,463414634 | 3,716666667 | 4,247311828 | 3,538461538 | 3,5          |

![image](https://github.com/dermitdemk/bundestagsabgeordnete_socialmedia_accounts/assets/60017842/f1cb3a92-5774-4c4a-a571-68c03949d6c2)

![image](https://github.com/dermitdemk/bundestagsabgeordnete_socialmedia_accounts/assets/60017842/c5bf59e0-05cf-4ae1-a5df-7f5f5e4734ed)






