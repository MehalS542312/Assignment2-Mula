# Assignment2-Mula
# Mehal Reddy Mula
###### Pizza
Pizza is a savory dish of **Italian** origin and it  is the epitome of a perfect snack. It combines a crispy crust that's drenched in savory sauce and concealed underneath a mountain of melty, mozzarella cheese.


--------------------------------------

### Cricket
1. Cricket is my favorite Game.
2. Each team has 11 members.
3. There will be different formats:
     1. Test matches
     2. T20 matches
     3. ODI matches

#### Important Facts About Cricket
* Cricket is a bat-and-ball game played between two teams of eleven players on a field.
* They must follow the rules strictly.
* Cricket is a multi-faceted sport with multiple formats that can effectively be divided into 
       first-class cricket, limited overs cricket.
* Most international matches are played as parts of 'tours'.
* The game's governing body is the International Cricket Council (ICC).

[About Me](https://github.com/MehalS542312/Assignment2-Mula/blob/main/AboutMe.md)

---------------------------------------

### Interesting places
  
  There are so my places to visit in the World.Some of those locations are:

  | Location | Hours | Money |
  | -------  | ----- | ----- |
  | Bali     | 12    | $1000 |
  | Kerry    | 8     | $800  |
  | Taj Mahal | 4    | $150  |
  | Maldives | 24    | $1500 |

--------------------------------------

###  Quotes
“ The purpose of our lives is to be happy.” - *Dalai Lama* <br>
“You only live once, but if you do it right, once is enough.” - *Mae West*

--------------------------------------

### Google Apps Script
  
  Apps Script is a scripting platform developed by Google for light-weight application development in the Google Workspace platform. Google Apps Script was initially developed by Mike Harm as a side project whilst working as a developer on Google Sheets.
  [About Google Apps Script](https://en.wikipedia.org/wiki/Google_Apps_Script)

  ```
   Sample Code Of Google Apps Script

   /**
 * Creates a Google Doc and sends an email to the current user with a link to the doc.
 */
function createAndSendDocument() {
  // Create a new Google Doc named 'Hello, world!'
  var doc = DocumentApp.create('Hello, world!');

  // Access the body of the document, then add a paragraph.
  doc.getBody().appendParagraph('This document was created by Google Apps Script.');

  // Get the URL of the document.
  var url = doc.getUrl();

  // Get the email address of the active user - that's you.
  var email = Session.getActiveUser().getEmail();

  // Get the name of the document to use as an email subject line.
  var subject = doc.getName();

  // Append a new string to the "url" variable to use as an email body.
  var body = 'Link to your doc: ' + url;

  // Send yourself an email with a link to the document.
  GmailApp.sendEmail(email, subject, body);
}

```
[About Code](https://developers.google.com/apps-script/overview#your_first_script)
