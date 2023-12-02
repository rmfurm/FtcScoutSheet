# ScoutSheet
An Excel spreadsheet allowing for in-depth scouting during events, made for and by FTC students. 

## Installation

Simply download the .xlsm file, and open it in Microsoft Excel. 

- Press the 'Enable Content' button when first opened, or else the spreadsheet will not work

![image](https://github.com/rmfurm/FtcScoutSheet/assets/86154178/e59d9dbf-f7a6-40b0-b128-7dc5667de974)

- Press the 'Enable Editing' button to allow it to be edited

![image](https://github.com/rmfurm/FtcScoutSheet/assets/86154178/0905ec9b-8e42-4aec-bacb-9dcc882cf12f)

- If the following error occurs:

![image](https://github.com/rmfurm/FtcScoutSheet/assets/86154178/a91fb9b8-fc55-474c-b3a5-71eb9509faa4)

Find the .xlsm file in File Explorer, right click on it, press Properties, which will show you the following:

![image](https://github.com/rmfurm/FtcScoutSheet/assets/86154178/6c03debb-18cd-45d1-a061-7d7306037806)

Press the 'Unblock' checkmark, allowing you to use the spreadsheet as required.

## How to use

### Information

When opening the sheet, the first thing you should do is navigate to the 'Information' sheet. This will allow you to enter imformation, like the season, your team number, and the code of your event. 

If you do not know your event code, it is listed on the FTC events website. For example, the Australian National competition is AUCMP. 

Once this information is added, the 'Get Schedule' button can be pressed. This will take the schedule from the FTC events website. It will take a while to load the data, so be patient. 

IF THERE IS NO ONLINE SCHEDULE, YOU WILL RECIEVE NO SCHEDULE. They are usually posted in the morning of the competition. You can also type in the data manually in the 'Raw Schedule' sheet, which is hidden by default. 


### Schedule

This shows the formatted schedule, showing match number, which field, which day of the competition the match is, the time of the match in 24 hour time, and the red and blue alliances. Additionally, this is where the timestamps and scores appear when they are inputted. 

### Dashboard

This is the main page you will be using during the day, along with Team Notes. On the left is information regarding matches, such as total amount of matches for your team, the next match, your teams next match, and the time. The 'Delay of matches' box is used during the day to account for any delays during the matches. Type in how long the matchs are delayed compared to the schedule, and the sheet will delay accordingly.

On the right is the current qualification match. It shows the teams playing, and their alliances. To set a timestamp, type in the box next to Timestamp, then press the 'Set Timestamp' button. This will set the timestamp value for the corresponding match. Press on any team names to go to their Team Notes. To set the score, enter the red and blue score in each box seperately, then press the 'Set Score' button. 

### Team Notes

The Team Notes sheet shows a list of teams participating, dictated by the schedule. If a team is not playing any games, then they will not appear in the team list. In the match list, it shows every game they play, along with their alliance, and whether they won or lost (win = gold text). Click on these numbers to be sent to the match, using the timestamp specified earlier. This allows for you to instantly look at any teams matches. 

## Roadmap

I plan on adding more features, such as automatic OPR calculations (if i can figure out the maths!), and live rankings based on it. Additionally

- Better UI
- Cleaner calculations
- Possibly an application
- Ranking system for alliance picks

## Contributing

Feel free to do pull requests, and adding issues. Ill try to respond as soon as possible :)


