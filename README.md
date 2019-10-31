# Yale-Hackathon
My project for YHack. I did this Hackathon alone. 

# Description 
I created Sentimetica, Artificially Intelligent Parenting, during the 2019 Yale Hackathon, YHack. My motivation for this project stems from seeing first hand the influence YouTubers have on our society. I made Sentimetica to help parents understand what type of influence these YouTuber's channels have on our children. I mined 6 years of top trending YouTube videos in the United States with all their comments. Next, I ran natural language processing algorithms to find the sentimental value of every comment on every post for every YouTube video. We then assign the overall sentiment value to the associated channel. I then stored all the sentiment values in a database with corresponding channel names. From this database Sentimetica can give you feedback to your children's YouTube influence environment. I set up a UI to take in channel name input to give results on the sentimental influence the channel has. The next step is setting up a baysiean filter to filter out channels that have over a said amount negative influence. This filter value is set by the parent.
