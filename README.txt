Ashley Jarman
Concept Manager App
StudentNo: 20076649
Mobile App Development 

DESCRIPTION
This app is a place to temporarily record Ideas, the fiery colour scheme is in order to induce a sense of passion within the user. there is also the option to add an image for better commincation of the concept or inspiration.

FUNCTIONS 
Splash Screen:
A simple delay of a few seconds, like a loading screen, upon opening which gives the user information on the app.

"Placemark" storage
1. Using JSON store the cards are now kept even when the app is closed.

Delete Button: 
1. Added delete option for the cards/ideas the user records.
2. Override-JSON store 
3. override call concepts.remove(concept) then serialize()
3.remove the card from the array, and save the new list to JSON file, to make it perminent.
4.add delete button in the .xml for user interface
5. Set button onClickListener to call app.concepts.delete(concept), setResult(RESULT_OK) THEN FINISH()
this deletes the concept and returns to main activity



Spinner:
simple drop down to say how the progress is going on the idea.


REFERENCES: 
youtube tutorials::

https://firebase.google.com/products#develop-products
https://code.luasoftware.com/tutorials/android/android-spinner-tutorial/
https://kotlinlang.org/docs/tutorials/native/basic-kotlin-native-app.html
https://developer.android.com/kotlin/?gclid=Cj0KCQiA0NfvBRCVARIsAO4930nrH-bSJJr-D2vDITiTV_4XUAxmnkMci6kSj_Qw64n6RmWYfLNApd8aAkFqEALw_wcB
