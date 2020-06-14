# 1. SCDFXIBM HeartFault by Team Segfault

## 1.1. Table of Contents
- [1. SCDFXIBM HeartFault by Team Segfault](#1-scdfxibm-heartfault-by-team-segfault)
  - [1.1. Table of Contents](#11-table-of-contents)
- [2. Group Members](#2-group-members)
- [3. Summary](#3-summary)
  - [3.1. What’s the problem?](#31-whats-the-problem)
  - [3.2. The idea](#32-the-idea)
- [4. How can technology help?](#4-how-can-technology-help)
- [5. Architecture](#5-architecture)
- [6. About the Project](#6-about-the-project)
- [7. Getting Started:](#7-getting-started)
- [8. Videos](#8-videos)
  - [8.1. Pitch Video](#81-pitch-video)
- [9. What we used to build our solution](#9-what-we-used-to-build-our-solution)
- [10. Contributing](#10-contributing)
- [11. License](#11-license)


# 2. Group Members
- [Liang Ying Hao Matthew (NJC, JC1)](https://github.com/MattLiangYH/)
- Kia Jia Han (NJC, JC1)
- Cao Jialin, Marianna  (NJC, JC1)
- [Sim Shang En (NJC, JC1)](https://github.com/12458)
- Allysa Tan Li Ying (NJC, JC1)

# 3. Summary
## 3.1. What’s the problem?
There has been a high rate of deaths due to cardiovascular diseases such as heart attacks. In fact, statistics show that in Singapore every day, around 17 people die from such diseases. This is a sizable amount of people. There are many people who may be at a higher risk of these diseases, such as those with pre existing heart conditions or who have high cholesterol. It may be difficult for them to be constantly monitored for signs of heart disease.
## 3.2. The idea
It is essential that when someone has a heart attack, there are people who will know and that will respond. Hence, our idea facilitates the mobilization of CFRs to the scene of someone who has had a heart attack.

# 4. How can technology help?
There are ways to detect abnormal heart rates that could potentially arise from heart attacks. This will allow CFRs to be notified should a person experience such conditions which may indicate that the person is at risk of getting a heart attack or that a silent heart attack could have already taken place.

# 5. Architecture
![Architecture](/assets/architecture.png "Architecture")

# 6. About the Project
[DESCRIPTION.md](/DESCRIPTION.md)

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
   If you don't see this, you might need to send the "/start" message again. Look for “id”, for instance, 34xxxxxxx above is my chat id. Look for yours and put it as your bot_chatID in the code above.

7. Repeat the steps above if you want to use two chatbots, except now replace the bot_token1 and bot_chatID1 fields respectively.
8. Run the attached python code.
9. When program prompts for input, copy and paste data found in the Sample Input Data folder into the interface. 
10. If a dataset with atrial fibrillation is used, a text message should be sent to the Bot.

# 8. Videos
## 8.1. Pitch Video
[![Pitch Video](http://img.youtube.com/vi/f-Pk9XnI1C4/0.jpg)](http://www.youtube.com/watch?v=f-Pk9XnI1C4 "Segfault: Heartfault SCDFXIBM")

# 9. What we used to build our solution

We used Auto AI Experiment from Watson Studio from IBM to train the Watson machine learning service so that it can recognise abnormal heart beats by using data sets from online. Telegram Chatbot is used to notify CFRs around the area if a person is in need of emergency medical aid.

# 10. Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

# 11. License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
- **[GNU GPL V3 license](https://www.gnu.org/licenses/gpl-3.0.en.html)**
- Copyright 2020 © [Sim Shang En](https://github.com/12458), [Cao Jialin, Marianna](https://github.com/mariannacao), [Liang Ying Hao Matthew](https://github.com/12458), [Kia Jia Han](https://github.com/12458), [Allysa Tan Li Ying](https://github.com/12458) 
