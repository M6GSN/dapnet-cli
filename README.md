# DAPNET cli
 How to send Pager messages via the Linux command line.

For this you will need an account at [https://hampager.de/](https://hampager.de/) and a computer running Linux or at least a USB stick with a live version of Linux I would recomend Linux Mint.

The Script

the command line below is also included in the sh file attached to this project

`curl -H "Content-Type: application/json" -X POST -u yourcallsign:yourpassword -d '{ "text": "this is the message", "callSignNames": ["destinationcallsign"], "transmitterGroupNames": ["all"], "emergency": false }' http://www.hampager.de:8080/calls
`

Make sure to replace these words by your own parameters:

yourcallsign

yourpassword (this is the password used to log in to the hampager website)

this is the message

destinationcallsign.


if you download the sh file dont forget to run `chmod +x send.sh`

Pleas make sure to include you callsign in your message I personaly put my callsign at the end because when using digital mode our callsigns are our signitures and where do you sign a document

One final note you can send messgaes via the hampager website or by downloading the app which is currenlt only avaliable on Android


