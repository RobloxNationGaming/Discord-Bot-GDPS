# Discord Bot GDPS
A Discord Bot GDPS for your geometry dash private server

# How to Setup Your Bot
Download this Repository. And then Extract the Files Zip.
After you Extract the zip files. Upload the bot folder/directory into your database geometry dash private
server to read files by the bot. Before you upload the bot folder please setup botConfig.php for emoji set
<br>

# Make Bot Discord 
First, we need to create a new application on the discord development portal.
We can do so by visiting the portal and clicking on new application.
<br><br>
![...](http://famrygd.5v.pl/totur/image1.png)
<br><br>

Make your own bot name. For example:
<br><br>
![...](http://famrygd.5v.pl/totur/image2.png)
<br><br>

Goto Bots Tab at the left option.
<br><br>
![...](http://famrygd.5v.pl/totur/image3.png)
<br><br>

Copy your token bot and set bot permission to admin
<br><br>
![...](http://famrygd.5v.pl/totur/image4.png)
<br><br>
After that, You must edit setup.json at folder botfiles and put your token. Make your prefix at the setup.json. And also put your host of gdps must be included with database folder. Like this <b>[ Not need slash at behind url ]</b>
<br>
<b>http://www.boomlings.com/database </b>

# For Hosting the bot using two devices
<h3>For run/host the bot using android</h3>
Please download termux at Google Play Store
After you downloaded, Open the app and type..
<br>
<code>pkg install nodejs </code>
<br>
where did you put the botfiles is your path storage..
<br>
<code>cd /sdcard/your-path-folder/botfiles </code>
<br>
And then install all the dependecies in package.json using this code
<br>
<code>npm i</code>
<br>
Last Step to host the bot..
<br>
<code>node index.js </code>

