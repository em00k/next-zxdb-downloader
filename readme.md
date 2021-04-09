<img src="https://raw.githubusercontent.com/em00k/src-gifs/main/ZXDBNext.png">

Next ZXDB-dl search v0.12 - em00k 06/04/21
------------------------------------------

Big props to Remy for his .http, which was influenced by Nihirash's NextExplorer. 
httpfile was a modified fork of httpbank for use with NextZXDB, which is no longer 
needed.

Without Remy's work this would not be possible. https://github.com/remy/next-http

Thanks to D-Rimron Soutter for supplying backend magic and never ending support. 

Note this is an EARLY beta, it my crash, it might fail to download etc etc. Best 
results have been with a FAST SD card (class10). As time goes on things will 
improve however for now its great fun to use. 

How to use:

Copy the two folders to the root of your Next SD card : 

  zxdb-dl 
  dot 

Connect to your wifi using the wifi.bas supplied on the next distro this can 
be found in demos\esp\wifi2.bas - note you only need to configure your wifi
once, each power on the esp should automatically re-connect. 

- Using the browser, Go into the zxdb folder 

- Launch zxdbloader.bas

- If connection is successful you should see a search prompt. Enter a search term 

to find result. eg manic*miner 

You can then select a file to download or search for a new term. 

The search works with "starts with", all spaces must be replace with an
asterix, eg : "target renegade" should be entered as "target\*renengade"

zxdb-dl can than lauch your download if preffered, or you can choose to do another
seach. 

Sometimes a download will fail and zxdb-dl will attempt 4 times before giving up,
these can happen for a number of reasons and hopefully as time goes on this will
improve. 

em00k

0.12    07/04/21

- more improvements on the GUI
- better stability 
- fixed retry key input


0.10	06/04/21

- added selector bar for chosing a file to download
- now uses updated .http (Thanks Remy)
- better-ish search
