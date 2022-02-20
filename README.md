# Webcrawler Twitter
**General objective:** design an intelligent agent that uses twitter environment to extract data, and it has in mind pattern matching for collect info from the data.
## Talking about the agent:
To create this inteligent agent, I recommend to use Tweepy that it's an API that gives us access from Twitter data, having in mind some limits in time for recollect data.
## System context diagram:
To create the agent, I elaborated a main design to having in mind how it going to works. So, in this way our agent going to uses twitter to collect data an create a data base from it. Then the data from the data base will be proceesed, having in mind some paremeter like: follow tweets and pattern matching. One time finished this proceess, the data going to be extracted and returned to the user to visualization mode.

Now, I'm going to show you the diagram for a better understanding:
![System context diagram](/Diagrams/WebcrawlerTwitter_SCD.jpg)

## Component diagram:
I'm conscient that the last diagram was a little basic, and it just had in mind the superfitial working of the agent. So, for the next diagram I'm going to show you the agent deeply working. For that, I will mention some methods and paremeters from Tweepy.

There is the diagram, with the same works from last diagram, but the new is more descriptive:
![Component diagram](/Diagrams/WebcrawlerTwitter_CD.jpg)
