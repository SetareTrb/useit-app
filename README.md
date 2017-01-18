# useit-app
Creating the Dresden Version of the Useit map app. 
- [ ] Get Setare and Yueying to download and work with this file. 
- [ ] Set up Github accounts for them.
- [ ] Clone this to their own repositary (set up a remote to mine). 
- [ ] Set up their own branches. 
- [ ] Once they have finished push it to their own branch, and then create a pull request for my "master" branch. 

# To our future selves: 

PUSH mine to github by going on VCS-> git-> push. 

I'll be working on the database and the list and the info, Setare on the geolocation and smaller map, Yueying on the bigmap and all of us on the style. 

Which one of us will work on creating the app logo? 


 
 
3)  
1) I have  tried to tidy the code in PlaceInformationActivity a bit, so that it is extensible. getInfo gets the information out. setText, sets this information.  The problem is in this line.  

 TextView text = (TextView) findViewById(R.id.+ elementId);
 Ive commented this out. 

2) Make other textViews in the  activity_place_information.xml . 
1)  Replace the use_it.db. Import the use_it_full database into the project. 
2) See whether the other fields can be used and incoporated - probably. By replacing the text in android:id="@+id/button1" .   
3) Try and see how to incorporate the clicks into the list. Not working yet :(  

