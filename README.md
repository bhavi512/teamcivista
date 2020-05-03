# teamcivista
Technical aspects to Team Civista's project
Hi there!
Please refer to the demo to see the protoype of our app and website. 

We have created a sample database to show how the data would be stored securely on the cloud. 
A screenshot of this is included in this repository. 

We also wrote a short algorithm for the system to recognise whether the user is calling a 'known' user or not and alert them of the same before deciding if the call should be placed in the interest of privacy. 

Below is the basic algorithm: 
for i: 1 to 10 do 
  if calleduserid not in friends[i] then 
    print ('This person may be unknown - you can only place a call with them if you ddd them to your friends list. Reply Y to add them to your friends list')
  endif
  if reply == input('Y') then 
    print ('This person has been added to your friends list')
    friends[i+1] = calleduserid
  else
    print ('Hi, I'm CIVI. How can I help you today?')
  endif 
    
NOTE: I TRIED TO CREATE A USER INTERFACE USING REACT.JS TO DISPLAY THE DATA STORED IN THE DATABASE HOWEVER SOME FILES WERE NOT INSTALLED CORRECTLY MEANING THE CODE DID NOT WORK AND THE DESIRED RESULT COULDN'T BE ACHIEVED. I HAVE ATTACHED SOME PICTURES OF THE PROCESS. 
