# game-html-launcher

(this README.md may have some typo, so try to read it until i get into high school)

This tool helps you launch .html files when the file:/// prefix are blocked, and launch it in a "about:blank" page

# how does this work?

you upload a .html files to run it on the website, acting like it was part of the site, so. . . if you get this type of screen: https://blocked.goguardian.com/ when running the file itself, this tool will work just find


# what if they are blocked?

we (what i meant by "we", i mean "i") have more site tha same as this, deployed on other coding sites like vercel, github(this one), etc. but i would mostly recommemnd is the script.google.com urls, because 1. its light wighted. 2.  it uses the "google.com" as a part of the url, so it wont get blocked for some time (i dont guarantee it to not get blocked for good). and 3. since google script uses https://script.google.com/macros/s/XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX/exec its gonna be hard to type all of that into the black list page of goguardien or what ever type of filler your school uses

# how many site are deployed?

https://tinyurl.com/Da-Backup-Game

if im guessing right, theres 6 site deployed: 4 from google script, 1 from vercel, and 1 from netlify

# how does this work on script.google.com?

you add this piece of code into the code.gs

function doGet() {
  return HtmlService.createTemplateFromFile('index').evaluate();
}

#are there games included?

yea. there right here: https://tinyurl.com/an-ww2-essay, you can also use it if the file:/// prefix dont get blocked

# can i deploy my own site?

yea, you can deploy your own with vercel, https://vercel.com/new/import?repository-name=game-html-launcher&s=https%3A%2F%2Fgithub.com%2FItTommy22Toad%2Fgame-html-launcher
you gonna need a github, gitlab, or bitbucket account to deploy as your own

# does this site have an offline version?

i mean, it woulden make sense since the only purpose of this project is to run .html files as part of the website, i mean, its made using only html but would make sense because, it would be blocked it runned as an html, but yes.

thats it, i hope to make more of these, or update it

BYEEEEE

-ItTommy22Toad
