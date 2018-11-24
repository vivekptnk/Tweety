# Tweety
A Twitter bot that replies to users you mention you using '@&lt;your_Twitter_handle>'  and use the hashtag '#HelloJi'

## Making a Developer Account and setting up the keys
First make a [Twitter Developer](developer.twitter.com) account using your existing Twitter Main Account also make a second account to test your Bot and then go to [Twitter Developer](developer.twitter.com) ,click on your username and click on Apps and then generate the keys, make sure its in Read-Write mode.
Use the keys and make a new script (keys.py) so that you can call it in your main script. Insert the keys into the script as shown in this repo (I have used placeholder keys), without this your Twitter won't be connected to your scripts. 

## Installing Tweepy
Before installing Tweepy install python and pip3. Then use the following commands to get the Tweepy Module.
### For Python 3.6
```
pip install tweepy
```
### For Python 3.7x
```
pip3 install -U git+https://github.com/tweepy/tweepy.git@2efe385fc69385b57733f747ee62e6be12a1338b
```

### Run the Bot
You can use [PythonAnywhere](pythonanywhere.com)'s Always-on-Tasks(paid) feature or you can use the normal free bash script to run it for a while but it terminates in 7-8 hours, just use the command below to install Tweepy in PythonAnywhere too.
```
pip3 install -user git+https://github.com/tweepy/tweepy.git@2efe385fc69385b57733f747ee62e6be12a1338b
``` 
Then, make the files one by one as in this repo in the home/user directory and then run the main my_twitter_bot.py script. Keep it running and use the Bot to have the satisfaction.

## Credits
### All credits to my lord and saviour [@CSDOJO](https://github.com/ykdojo/)
#### This was my take on the Project. #HELLOJI
#### Amazing Learning Experience.
#### Happy Coding !
