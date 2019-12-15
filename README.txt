Kate Higgins
concept Manager Application
StudentNo: 20075687
Mobile Appp Development 
Bitbucket: https://bitbucket.org/kateh101/repoo/src/master/
Youtube Link: https://youtu.be/Vd1jJlm4hQo
(Video also in folder if any issues)

DESCRIPTION
I have designed my application to function as a concept manager (ie. Trello) to organize concepts in order of urgency.
I have included an Image button as I moved on in the labs but, I wish for this to be included in the second assignment. 
You have the ability to add, save, update, and delete concepts freely in this application. Working through the labs got me as far as adding
and listing placemarks and the rest was done using tutorials and applying the knowledge I gained in the labs to make CRUD functionality.


FUNCTIONS 
Delete Button: 
1. Added delete method to the store interface 
2. Override it in the JSON store 
3. In the override, call concepts.remove(concept) then serialize()
3.remove concept from list of concepts, Save new list to JSON file
4.add delete button in activity_concept.xml
5. Set button onClickListener to call app.concepts.delete(concept), setResult(RESULT_OK) THEN FINISH()
this deletes the concept and returns to main activity

Splash Screen:
This creates a concept which runs as a fixed delay. The concept being the intent for the next screen.
It also calls finish after launching the intent so the splash screen wont show up in the back history
IE:pressing back wont bring you back to the splash screen.

Spinner:
This was done by creating an array in my concept_activity,
create a new item.view in the concept listener (concept adapter)
Declare the spinner in activity_concept
adjust layout in card_concept.xml


REFERENCES: 
youtube tutorials::

Startup Activity (which i used to assist in my making of the splash screen) : https://www.youtube.com/watch?v=DflrLDLfzsU&fbclid=IwAR0lWPt6LOEhI1S3pwp_IWRGQrgMsHblwf5oPK3J_yt0v2_tPrMK83VpVK4
Spinner: https://www.youtube.com/watch?v=IfM7Wc9iKV8&fbclid=IwAR0j7jjerqPyPZ7APcwlvlswbdt1i-LdEnXVB8bCb45FEXpe37uOMAer7WA
