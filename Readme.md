! run app.py to test (flask) get photo recognition logic (and some more stuff i forgot, check it out !
! if you wanna try the app, run app.py flask app and go to the local url (some https://some_local_ip/upload2) it gives, and yeah... test it out !

for now, i have done the backend and main logic

whats remaining is, -
*creating a flask hosting application
*creating a web/admission portal similar to government one
*linking the application
*checking and testing trials, and record accuracy
*find beter solution
*optimize
\*and other crap, we will see ...

So what will the final design look like ?

Basically, we make a website similar to government admission portals & have the user fill in details,
but when the user uploads a passport size photo & their signature, we verify whether it has been uploaded under the correct place holders (signature under upload your signaure plcaeholder & photo under upload your passport size photo placeholder),
so once the user hits submit or after uploading the photo, we have a method that firtsly check if the photo has a face in it & the signature photo has a sign in it, if this case passes then we ignore and continue, but if the photos are wrong and does not have a face or sign, then we notify the user, i thought of another case where, if the signature and passport photo are uploaded, but they are uploaded under the worng placeholder, we could give them a prompt and swap it automatically from our side.. (thats exactly why i have added a config file in this project, just so that we can enable/disable experimental features and display them if required)
and in the end presentation is important for our project,
so i thought of hosting it for a week before presentation of our project,
the user, does not have to see the back end, we just have to send them the website/demo link and let them use it (or) we make a pre recorded video of our project which would be great..

the back end is done as of now, I want Bharath & Arun to replicate the government portal (css & html stuff only) meanwhile i have to create a flask application to get data & return/process the result

lets goo...

TRY TO COMPLETE AS SOON AS POSSIBLE !

update :
i have added flask application to get photos and signature from our web and store them in resources folder (also added a logging feature to manage ppl who view the webpage), all thats there is to link the main logic to rename the files to the user id of user and to add a logic to respond with when the user submits the form, and in the end add ui (bharath & arun you guys r on it, immma also do somethin abt it in the end) &... &... &... &... boom thats it !

Bye,
Regards Team Sepher


SIH UI has been created -- FRONT_END-----bharath_rajiv
