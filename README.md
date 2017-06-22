# MUIPRT
Multi URL IP Rotator Tool, Ad bot / traffic generator. Mostly automatic. 



You will need 7zip as I had to archive a few folders to lower the folder count. 

1. Inside the MUIPRT folder there is a Firefox.7z that needs to be unpacked, so there is a folder inside MUIPRT called Firefox.
2. Inside MUIPRT > Bin > Debug there is a Firefox.7z and a Xulrunner.7z, same deal.


It should look like:

.git              Bin ===========> Debug =======> Firefox 
.vs               Firefox          Release        Xulrunner
MUIPRT =========> obj                             Useragents.txt       
.gitattributes    Properties
.gitignore        Resources 
MUIPRT.sln        App.config
                  JsLintNet.json
                  Main.cs
                  Main.designer.cs
                  main.js
                  main.resx
                  MUIPRT.csproj
                  MUIPRT.csproj.user
                  packages.config
                  Progam.cs
                  Useragents.txt
                  
What is shown is where all the 7z archives are and how the folders should look when unpacked.


Now you should be able to load the solution and compile with no problems. I;ve included a Useragents.txt for the useragents section.
You will need to scrape your own proxies. It should be self explanitory, but for those who can't think for themselves...


Start by entering the URL into the textbox under ther first listbox. Once entered click add or hit enter. Next load useragents.txt into
the second listbox. Then load your proxy list you scraped up. Add a URL to the dropdown box for the referral HTTP header. click set.
If you want to automate a click in the browser on DocumentComplete click set and put the cursor where you are wanting it to click. If 
you are wanting it to scroll a HTML element into view and then click, look in the code for the browser automation part and edit the 
CSS tag from what I have set "aads". This will automatically scroll said element into view so you can set the coordinates to click.
Now set how many views you wish to generate, usually the number of proxies there are * the number of urls you are generating traffic to.
And set the interval between refreshes. This number is in milliseconds. so 1000 = 1 second. When you think everything is ready, click
start and let the program do its magic. You should be able to let it run in the background, but I am unsure if the click function will
work without the Form being in focus.


Any questions feel free to message me or shoot me an email at nickisghosty@gmail.com.




Also feel free to edit, manipulate, redistribute as you please, just be kind enough to leave a little credit where due. Enjoy.



Screenshot:

<a href="http://tinypic.com?ref=sops1g" target="_blank"><img src="http://i64.tinypic.com/sops1g.png" border="0" alt="Image and video hosting by TinyPic"></a>
