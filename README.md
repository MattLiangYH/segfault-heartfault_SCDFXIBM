# 1. segfault-heartfault_SCDFXIBM

- [1. segfault-heartfault_SCDFXIBM](#1-segfault-heartfault_scdfxibm)
- [2. Group Members:](#2-group-members)
- [3. Short Description:](#3-short-description)
- [4. How can technology help?](#4-how-can-technology-help)
- [5. The idea](#5-the-idea)
- [6. Pitch Video:](#6-pitch-video)
- [7. Architecture:](#7-architecture)
- [8. Long Description:](#8-long-description)
- [9. Roadmap/Proposed timeline (not compulsory):](#9-roadmapproposed-timeline-not-compulsory)
- [10. Getting Started:](#10-getting-started)
- [11. Live Demo (not compulsory):](#11-live-demo-not-compulsory)
- [12. What we used to build the solution:](#12-what-we-used-to-build-the-solution)

# 2. Group Members:
Liang Ying Hao Matthew (NJC, JC1)
Kia Jia Han (NJC, JC1)
Cao Jialin, Marianna  (NJC, JC1)
Sim Shang En (NJC, JC1)
Allysa Tan Li Ying (NJC, JC1)

# 3. Short Description:
What’s the problem?
There has been a high rate of deaths due to cardiovascular diseases such as heart attacks. In fact, statistics show that in Singapore every day, around 17 people die from such diseases. This is a sizable amount of people. There are many people who may be at a higher risk of these diseases, such as those with pre existing heart conditions or who have high cholesterol. It may be difficult for them to be constantly monitored for signs of heart disease.

# 4. How can technology help?
There are ways to detect abnormal heart rates that could potentially arise from heart attacks. This will allow CFRs to be notified should a person experience such conditions which may indicate that the person is at risk of getting a heart attack or that a silent heart attack could have already taken place.

# 5. The idea
It is essential that when someone has a heart attack, there are people who will know and that will respond. Hence, our idea facilitates the mobilization of CFRs to the scene of someone who has had a heart attack.

# 6. Pitch Video:


# 7. Architecture:

# 8. Long Description:
(link) (i put it below for now)


# 9. Roadmap/Proposed timeline (not compulsory):

# 10. Getting Started:

1. Download the python program from Github.
2. Open telegram, and search ‘@BotFather’.
3. Send @BotFather ‘/start’.
4. Send another “/newbot” message, then follow the instructions to setup a name and a username.
5. Your bot is now ready, be sure to save a backup of your API token, and correct, this API token is your bot_token.
6. On Telegram, search your bot (by the username you just created), press the “Start” button or send a “/start” message.
Open a new tab with your browser, enter https://api.telegram.org/bot<yourtoken>/getUpdates , replace <yourtoken> with your API token, press enter and you should see something like this: 
```
{"ok":true,"result":[{"update_id":77xxxxxxx,"message":{"message_id":550,"from":{"id":34xxxxxxx,"is_bot":false,"first_name":"ManHay","last_name":"Hong","username":"manhay212","language_code":"en-HK"}
```
Look for “id”, for instance, 34xxxxxxx above is my chat id. Look for yours and put it as your bot_chatID in the code above.

7. Repeat the steps above if you want to use two chatbots, except now replace the bot_token1 and bot_chatID1 fields respectively.
8. Run the attached python code.
9. When program prompts for input, supply it with a dataset provided below. Here, Y means it is a normal ECG, and N means it is an ECG with Atrial Fibrillation.
10. If a dataset with atrial fibrillation is used, a text message should be sent to the Bot.


# 11. Live Demo (not compulsory):

# 12. What we used to build the solution:

We used AutoAI from IBM to train our AI so that it can recognise abnormal heart beats by using data sets from online. Watson Chatbot is used to notify CFRs around the area if a person is in need of emergency medical aid.
