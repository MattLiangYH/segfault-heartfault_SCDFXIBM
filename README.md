# 1. SCDFXIBM HeartFault by Team Segfault

- [1. SCDFXIBM HeartFault by Team Segfault](#1-scdfxibm-heartfault-by-team-segfault)
- [2. Group Members:](#2-group-members)
- [3. Summary:](#3-summary)
  - [3.1. The idea](#31-the-idea)
- [4. How can technology help?](#4-how-can-technology-help)
- [5. Architecture:](#5-architecture)
- [6. Long Description:](#6-long-description)
  - [6.1. Introduction to the Problem:](#61-introduction-to-the-problem)
  - [6.2. Introduction to the project:](#62-introduction-to-the-project)
  - [6.3. What we used to build the solution:](#63-what-we-used-to-build-the-solution)
- [7. Getting Started:](#7-getting-started)
- [8. Videos](#8-videos)
  - [8.1. Pitch Video:](#81-pitch-video)
  - [8.2. Live Demo:](#82-live-demo)
- [9. Contributing](#9-contributing)
- [10. License](#10-license)

# 2. Group Members:
- [Liang Ying Hao Matthew (NJC, JC1)](https://github.com/MattLiangYH/)
- Kia Jia Han (NJC, JC1)
- Cao Jialin, Marianna  (NJC, JC1)
- [Sim Shang En (NJC, JC1)](https://github.com/12458)
- Allysa Tan Li Ying (NJC, JC1)

# 3. Summary:
What’s the problem?
There has been a high rate of deaths due to cardiovascular diseases such as heart attacks. In fact, statistics show that in Singapore every day, around 17 people die from such diseases. This is a sizable amount of people. There are many people who may be at a higher risk of these diseases, such as those with pre existing heart conditions or who have high cholesterol. It may be difficult for them to be constantly monitored for signs of heart disease.
## 3.1. The idea
It is essential that when someone has a heart attack, there are people who will know and that will respond. Hence, our idea facilitates the mobilization of CFRs to the scene of someone who has had a heart attack.

# 4. How can technology help?
There are ways to detect abnormal heart rates that could potentially arise from heart attacks. This will allow CFRs to be notified should a person experience such conditions which may indicate that the person is at risk of getting a heart attack or that a silent heart attack could have already taken place.

# 5. Architecture:
![Architecture](/assets/architecture.png "Architecture")

# 6. Long Description:

## 6.1. Introduction to the Problem:

Our project is tasked to tackle the problem of the high number of deaths due to heart attacks. In fact, according to the American Heart Association, it is estimated that every 40 seconds an American will have a heart attack. There are approximately 720,000 new attacks and 335,000 recurrent attacks in the United States every year. Around 14 percent of people who have a heart attack will die from it. That is a lot of people! In Singapore, while the situation may not be so bad due to the lower population and good healthcare facilities, there should still be something done about these heart attacks which still lead to numerous deaths. There are many people who may be at a higher risk of these diseases, such as those with pre existing heart conditions or who have high cholesterol. It may be difficult for them to be constantly monitored for signs of heart disease, due to them living alone or other factors. 

## 6.2. Introduction to the project:

Our proposed project is a electronic wearable that can track and monitor the heart rate of the wearer. This wearable detects the electrocardiogram (ECG) signals from the wearer. Then, the wearable will compare the ECG signals received and the ECG signals from a normal heart. This will allow it to spot any differences and infer if these differences could amount to Atrial Fibrillation (AF), which is a sign of heart attack. In the event that there is AF, the device will vibrate and if the wearer is able to respond, he or she should press a button to stop the vibrating. Since AF may not necessarily mean that a heart attack has taken place, this is to avoid having too many false alarms. The wearer can then seek treatment for the AF at his or her own time as long as it is not an emergency. However, if the wearer does not press the button, attempts will be made to contact the wearer, though means such as calling. If after a certain period of time, the attempts have been unsuccessful, then the device will track the user’s location and notify the Community First Responders (CRFs) who are in the area or on duty to attend to the wearer as soon as possible as it is very likely that the wearer has had a heart attack. This will allow early intervention for people who experienced heart attacks, which would result in lesser lives being lost from heart attacks through mobilization of CFRs. Also, this would greatly benefit people who live alone as often if they do have a heart attack, there is no one for them to turn to for help and no one who would know what is going on. With this wearable, the CFRs would be able to track down the person and provide them the needed help to increase their survival rates. 

## 6.3. What we used to build the solution:

We used AutoAI experiment from IBM to train our AI so that it can recognise abnormal heart beats by using data sets from online. Telegram Chatbot is used to notify CFRs around the area if a person is in need of emergency medical aid.

# 7. Getting Started:

1. Download the python program from Github.
2. Open telegram, and search ‘`@BotFather`’.
3. Send @BotFather ‘`/start`’.
4. Send another '`/newbot`' message, then follow the instructions to setup a name and a username.
5. Your bot is now ready, be sure to save a backup of your API token, and correct, this API token is your bot_token.
6. On Telegram, search your bot (by the username you just created), press the “Start” button or send a “/start” message.
   Open a new tab with your browser, enter `https://api.telegram.org/bot<yourtoken>/getUpdates` , replace `<yourtoken>` with your API token, press enter and you should see something like this: 
   ```
   {"ok":true,"result":[{"update_id":77xxxxxxx,"message":{"message_id":550,"from":{"id":34xxxxxxx,"is_bot":false,"first_name":"ManHay","last_name":"Hong","username":"manhay212","language_code":"en-HK"}
   ```
   Look for “id”, for instance, 34xxxxxxx above is my chat id. Look for yours and put it as your bot_chatID in the code above.

7. Repeat the steps above if you want to use two chatbots, except now replace the bot_token1 and bot_chatID1 fields respectively.
8. Run the attached python code.
9. When program prompts for input, copy and paste data found in the Sample Input Data folder into the interface. 
10. If a dataset with atrial fibrillation is used, a text message should be sent to the Bot.

# 8. Videos
## 8.1. Pitch Video:
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
## 8.2. Live Demo:
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

# 9. Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

# 10. License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
- **[GNU GPL V3 license](https://www.gnu.org/licenses/gpl-3.0.en.html)**
- Copyright 2020 © [Sim Shang En](https://github.com/12458), [Cao Jialin, Marianna](https://github.com/mariannacao), [Liang Ying Hao Matthew](https://github.com/12458), [Kia Jia Han](https://github.com/12458), [Allysa Tan Li Ying](https://github.com/12458) 
