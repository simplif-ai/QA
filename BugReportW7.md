# Bug Report Week 7

## Login Page
- [x] There is a giant text logo at the top of the page that says "simplif.ai".
- [x] Beneath the logo, there is text that says "Login".
- [x] Beneath the "Login" text, there is a box that requires login credentials.

### Email text box
- [x] A text box is located in the center Login box region labeled "email".
- [x] When selected, text can be entered into this text box.

### Password text box
- [x] A text box is located below the Email text box labeled "password".
- [x] When selected, text can be entered into this text box.
- [x] Text entered into this box is censored.

### Submit button
- [x] A button is located below the Password text box labeled "submit".
- [x] If pushed, and the Email text box is empty, a small text blurb will instruct the user to fill in their email.
- [x] If pushed, and the Email text box is filled without an '@' symbol, a small text blurb will instruct the user to fill in a proper email.
- [x] If pushed, and the Email text box is filled but the Password text box is empty, a small text blurb will instruct the user to fill in their password.
- [x] If pushed, and both email and password are filled but do not correspond to a true account, an error message will appear on the top of the box.
- [x] If pushed, and both email and password are filled out correctly, the user will be redirected to the Profile Page.

### Forget Password Link
- [x] A link is located below the Submit button labeled "Forgot your password?".
- [x] When clicked, the user will be redirected to the Request Password Reset Page.

### Create Account Link
- [x] A link is located below the Forget Password Link labeled "Create an Account".
- [x] When clicked, the user will be redirected to the Create Account Page.

## Create Account Page
- [x] There is a giant text logo at the top of the page that says "simplif.ai".
- [x] Beneath the logo, there is text that says "Create an account".
- [x] Beneath the "Create an account" text, there is a box that contains text fields for account creation purposes.
    
### First Name text box
- [x] A text box is located in the center box region labeled "First Name".
- [x] When selected, text can be entered into this text box.

### Email text box
- [x] A text box is located below the First Name text box labeled "Email".
- [x] When selected, text can be entered into this text box.

### Phone Number text box
- [x] A text box is located below the Email text box labeled "Phone Number".
- [x] When selected, text can be entered into this text box.

### Prefer email updates checkbox
- [x] A checkbox is located below the Phone Number text box labeled "Prefer Email Updates".
- [x] Box starts out unchecked and can be checked and unchecked.

### Password text box
- [x] A text box is located below the Prefer email updates checkbox labeled "Password".
- [x] When selected, text can be entered into this text box.
- [x] Text entered into this box is censored.

### Submit button
- [x] A button is located below the Password text box labeled "Submit".
- [x] If pushed, and not all text boxes are filled, then the first occurrence of an empty text box gets a popup instructing user to fill the field.
- [x] If pushed, and all text boxes are filled, then an account is created and the user is redirected to the Login page.

### Sign in Link
- [x] A link is located below the Submit button labeled "Already have an account? Sign in".
- [x] When clicked, the user will be redirected to the Login page.

## Request Password Reset Page
- [x] At the top of the page, there is text that says "Request Password Reset".
- [x] Beneath the "Request Password Reset" text, there is a box that contains information for password resetting instructions.

### Email address text box
- [x] A text box is located in the center box region labeled "Enter your email address to reset your password".
- [x] When selected, text can be entered into this text box.

### Submit button
- [x] A button is located below the Email address text box labeled "Submit".
- [x] If pushed, and the Email text box is empty, a small text blurb will instruct the user to fill in their email.
- [x] If pushed, and the Email text box is filled without an '@' symbol, a small text blurb will instruct the user to fill in a proper email.
- [x] If pushed, and the Email text box is filled out correctly, the user will receive a password reset email to their email inbox.

### Sign in Link
- [x] A link is located below the Submit button labeled "Already have an account? Sign in".
- [x] When clicked, the user will be redirected to the Login page.

### Register Link
- [x] A link is located below the Sign in Link labeled "Or register for an account.".
- [x] When clicked, the user will be redirected to the Create Account page.

## Profile Page
- [x] At the top, there is text that says "Upload a Picture".
- [x] Beneath the "Upload a Picture" text, there are various buttons to tweak user settings.

### Profile Section
- [x] On the left side, there is a boxed region containing profile information.
- [x] At the top, the user's profile picture is displayed, using a placeholder if one is not provided.
- [x] Below the profile picture, the user's first name is displayed.
- [x] Below the name, the user's email address is displayed.

### Upload Image button
- [x] A file browsing button and upload button are located below the "Upload a Picture" text.
- [x] If the file browsing button is clicked, a file explorer of the user's local files is opened.
- [x] If the Upload Image is pushed without a chosen file, a small text blurb will instruct the user to choose a file.
- [x] If the Upload Image is pushed with a chosen file, the user's profile picture will update accordingly to the new picture.

### Edit Profile button
- [x] A button is located below the Upload Image button.
- [x] When pushed, the Edit Profile section will appear.

### Toggle Scheme button
- [x] A button is located below the Edit Profile button.
- [x] When pushed, the color scheme will change.

### Delete Account button
- [x] A button is located below the Toggle Scheme button.
- [x] When pushed, the user's account will be deleted.

### Authorize Google Account button
- [x] A button is located below the Delete Account button.
- [x] If pushed, and user is not authenticated, the user will be redirected to login to their gmail, and then the text "Your Google account has successfully been linked" will appear for a few seconds.
- [x] If pushed, and user is already authenticated, the text "You are already successfully linked to a google account!!" will appear.

### Edit Profile Section

#### Name text box
- [x] At the top of the section, there is a text box labeled "Name".
- [x] When selected, text can be entered into this text box.

#### Email text box
- [x] Below the Name text box, there is a text box labeled "Email".
- [x] When selected, text can be entered into this text box.

#### Save button
- [x] Below the Email text box, there is a button labeled "Save".
- [x] If pushed, the text entered into the Name text box will replace the user's name and the text entered into the Email text box will replace the user's email.

#### Cancel button
- [x] Below the Email text box, there is a button labeled "Save".
- [x] If pushed, Edit Profile section will disappear.

## My Notes Page
- [x] At the top of the page, there is text that says "My Notes".

### Create new note button
- [x] Next to the "My Notes" text, there is a button shaped like a plus in a circle.
- [x] If pushed, the user is redirected to the Note Editing Page.

### Existing notes section
- [x] Below the Create new note button, there is a list of existing notes.
- [x] Each note contains in the list contains a title and an ID.

### New Folder text box
- [x] Below the Existing notes section, there is a text box labeled "new folder name".
- [x] When selected, text can be entered into this text box.

### New Folder Submit button
- [x] Below the New Folder text box, there is a button labeled "submit".
- [x] If pushed, and user is Google authenticated, a new folder will be created in their Google drive with the name provided in the text box.

### Collaborator Email text box
- [x] Below the New Folder section, there is a text box labeled "Collaborator email".
- [x] When selected, text can be entered into this text box.

### Collaborator Submit button
- [x] Below the Collaborator Email text box, there is a button labeled "submit".
- [x] If pushed, and user is Google authenticated, a collaborator with the email provided in the text box will be added to the drive folder.

## Note Editing Page

### Title Area
- [x] At the top of the page there is a text box with initial text "Enter a Title..."
- [x] When selected, text can be entered into this text box to replace the initial text.

### Note Area
- [x] Below the Title area, there is a large text box.
- [x] When selected, text can be entered into this text box.

### Save Button
- [x] At the bottom, there is a button labeled "Save".
- [x] If pushed, the text "Your summary has successfully been saved." will briefly appear at the top, and the note will appear in the note list later.

### Summarize Button
- [x] At the bottom next to the Save Button, there is a button labeled "Summarize".
- [x] If pushed, the text in the Note Area will be sent to the summarizer API, and an airplane loading icon will appear. Once the text is finished being summarized, the summarized text will replace the text in the Note Area.

### Brevity Slider
- [x] At the bottom right corner, there is a slider labeled "Brevity" set to 50% by default.
- [x] The slider can be moved from left to right in the range between 0% and 100%.
- [x] When the text in the Note Area is summarized, the size proportion of the summarized text corresponds with the setting on the slider.
- [x] When the slider is moved after the text in the Note Area is summarized, the size of the summary will update dynamically.

### Edit Summary Menu button
- [x] In the bottom right corner, there is a round button with an icon of a pencil.
- [x] If pushed, and text in the Note Area has not been summarized, the text "You can only edit summarized text!" will briefly appear at the top.
- [x] If pushed, and text in the Note Area has been summarized, a list of all the original sentences will appear. Sentences not in the summary are greyed out.
- [x] Existing sentences have an X button next to the sentence.
- [x] If the X button is pushed, the sentence will be removed from the summary.
- [x] Removed sentences have a plus button next to the sentence.
- [x] If the plus button is pushed, the sentence will be added into the summary.
- [x] If edit mode is engaged, and the button is pushed, the user will be returned to the original Note Area interface.

### Edit Summary Title button
- [x] Next to the Title Area, there is a round button with an icon of a pencil.
- [x] If pushed, and text in the Note Area has not been summarized, the text "You can only edit summarized text!" will briefly appear at the top.
- [x] If pushed, and text in the Note Area has been summarized, a list of all the original sentences will appear (Sentence Editor). Sentences not in the summary are greyed out.
- [x] If edit mode is engaged, and the button is pushed, the user will be returned to the original Note Area interface.

### Options button
- [x] In the bottom right corner, there is a round button with a question mark icon.
- [x] If pushed, a drop down menu of different options will appear.

### Sentence Editor
- [x] Existing sentences have an X button next to the sentence.
- [x] If the X button is pushed, the sentence will be removed from the summary.
- [x] Removed sentences have a plus button next to the sentence.
- [x] If the plus button is pushed, the sentence will be added into the summary.

## Drop Down Menu
- [x] At all times, there is a hamburger menu in the top left corner.
- [x] When clicked, and user is not logged in, nothing will happen.
- [x] When clicked, and user is logged in, a drop down directory menu will appear.

### Profile Link
- [x] First link in the drop down menu says "Profile".
- [x] When clicked, the user is redirected to the Profile Page.

### Logout Link
- [x] Last link in the drop down menu says "Logout".
- [x] When clicked, the user is unauthenticated and redirected to the Login Page.

### My Notes Link
- [x] Second link in the drop down menu says "My Notes".
- [x] When clicked, the user is redirected to the My Notes Page.

## Bugs found
- On create account page email is not validated as an email.
- There is a 504 error on long summarizations
- In the edit profile section of the profile page the email is not validated as an email