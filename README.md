# game-html-launcher

(this README.md may have some typo, so try to read it until i get into middle school)

This tool helps you launch .html files when the file:/// prefix are blocked

how does this work?

you upload a .html files to run it on the website, acting like it was part of the site, so. . . if you get this typa screen: https://blocked.goguardian.com/ when running the file itself, this tool will work just find


what if they are blocked?

welp, youre cooked. . . . just kidding, we (what i meant by "we", i mean "i") have more site tha same as this, deployed on other coding sites like vercel, github(this one), etc. but i would mostly recommemnd is the script.google.com urls, because 1. its light wighted. 2.  it uses the "google.com" as a part of the url, so it wont get blocked for some time (i dont guarantee it to not get blocked for good). and 3. since google script uses https://script.google.com/macros/s/XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX/exec its gonna be hard to type all of that into the black list page of goguardien or what ever type of filler your school uses

how many site are deployed?

https://tinyurl.com/Da-Backup-Game

im not counting all of that

how does this work on script.google.com?

you add this piece of code into the code.gs

function doGet() {
  return HtmlService.createTemplateFromFile('index').evaluate();
}

are there games included?

yup. there right here: https://tinyurl.com/an-ww2-essay, and best part, it wont get blocked, BECAUSE YOU NEED GOOGLE DRIVE TO DO YOUR WORK!! you can also use it if the file:/// prefix dont get blocked

can i deploy my own site?

yea, you can deploy your own with vercel or netlify or whatever

does this site have an offline version?

what type of monster are you? EWWWWWW!! but yea because it made using html, no css or js exept for google script for code.gs in which you need the code to make the .html render.

thats it, i hope to make more or these

BYEEEEE

-ItTommy22Toad