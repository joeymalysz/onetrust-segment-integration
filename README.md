## Introduction ## 

This repos shows an example of how to integrate Segment's Analytics.js library with OneTrust's web cookie consent manager. To view the live demo, please click [here](https://glitch.com/~plastic-teal-gasoline)

## How to Run Demo Locally ## 

1) Clone this Github reop into a local branch. 
2) Update line 1 one the script.js file with your Segment [source write key](https://segment.com/docs/connections/find-writekey/)
3) Update the OneTrust data-domain-script of the index.html file (line 11) with your [OneTrust id](https://my.onetrust.com/s/article/UUID-5394213a-70b9-c4e6-d68c-f809b55e7af6?topicId=0TO1Q000000ssJBWAY) This id is found within your OneTrust consent manager account, under Scipts -> Publish
4) Indicate whether you want to disable data being sent to Segment destinations by default on line 3 of script.js file


