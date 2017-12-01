# QA Testing

## Login Page
- [ ] There is a giant text logo at the top of the page that says "simplif.ai".
- [ ] Beneath the logo, there is text that says "Login".
- [ ] Beneath the "Login" text, there is a box that requires login credentials.

### Email text box
- [ ] A text box is located in the center Login box region labeled "email".
- [ ] When selected, text can be entered into this text box.

### Password text box
- [ ] A text box is located below the Email text box labeled "password".
- [ ] When selected, text can be entered into this text box.
- [ ] Text entered into this box is censored.

### Submit button
- [ ] A button is located below the Password text box labeled "submit".
- [ ] If pushed, and the Email text box is empty, a small text blurb will instruct the user to fill in their email.
- [ ] If pushed, and the Email text box is filled without an '@' symbol, a small text blurb will instruct the user to fill in a proper email.
- [ ] If pushed, and the Email text box is filled but the Password text box is empty, a small text blurb will instruct the user to fill in their password.
- [ ] If pushed, and both email and password are filled but do not correspond to a true account, an error message will appear on the top of the box.
- [ ] If pushed, and both email and password are filled out correctly, the user will be redirected to the Profile Page.

### Forget Password Link
- [ ] A link is located below the Submit button labeled "Forgot your password?".
- [ ] When clicked, the user will be redirected to the Request Password Reset Page.

### Create Account Link
- [ ] A link is located below the Forget Password Link labeled "Create an Account".
- [ ] When clicked, the user will be redirected to the Create Account Page.

## Create Account Page
- [ ] There is a giant text logo at the top of the page that says "simplif.ai".
- [ ] Beneath the logo, there is text that says "Create an account".
- [ ] Beneath the "Create an account" text, there is a box that contains text fields for account creation purposes.
    
### First Name text box
- [ ] A text box is located in the center box region labeled "First Name".
- [ ] When selected, text can be entered into this text box.

### Email text box
- [ ] A text box is located below the First Name text box labeled "Email".
- [ ] When selected, text can be entered into this text box.

### Phone Number text box
- [ ] A text box is located below the Email text box labeled "Phone Number".
- [ ] When selected, text can be entered into this text box.

### Prefer email updates checkbox
- [ ] A checkbox is located below the Phone Number text box labeled "Prefer Email Updates".
- [ ] Box starts out unchecked and can be checked and unchecked.

### Password text box
- [ ] A text box is located below the Prefer email updates checkbox labeled "Password".
- [ ] When selected, text can be entered into this text box.
- [ ] Text entered into this box is censored.

### Submit button
- [ ] A button is located below the Password text box labeled "Submit".
- [ ] If pushed, and not all text boxes are filled, then the first occurrence of an empty text box gets a popup instructing user to fill the field.
- [ ] If pushed, and all text boxes are filled, then an account is created and the user is redirected to the Login page.

### Sign in Link
- [ ] A link is located below the Submit button labeled "Already have an account? Sign in".
- [ ] When clicked, the user will be redirected to the Login page.

## Request Password Reset Page
- [ ] At the top of the page, there is text that says "Requesst Password Reset".
- [ ] Beneath the "Request Password Reset" text, there is a box that contains information for password resetting instructions.

### Email address text box
- [ ] A text box is located in the center box region labeled "Enter your email address to reset your password".
- [ ] When selected, text can be entered into this text box.

### Submit button
- [ ] A button is located below the Email address text box labeled "Submit".
- [ ] If pushed, and the Email text box is empty, a small text blurb will instruct the user to fill in their email.
- [ ] If pushed, and the Email text box is filled without an '@' symbol, a small text blurb will instruct the user to fill in a proper email.
- [ ] If pushed, and the Email text box is filled out correctly, the user will receive a password reset email to their email inbox.

### Sign in Link
- [ ] A link is located below the Submit button labeled "Already have an account? Sign in".
- [ ] When clicked, the user will be redirected to the Login page.

### Register Link
- [ ] A link is located below the Sign in Link labeled "Or register for an account.".
- [ ] When clicked, the user will be redirected to the Create Account page.

## Profile Page
- [ ] At the top, there is text that says "Upload a Picture".
- [ ] Beneath the "Upload a Picture" text, there are various buttons to tweak user settings.

### Profile Section
- [ ] On the left side, there is a boxed region containing profile information.
- [ ] At the top, the user's profile picture is displayed, using a placeholder if one is not provided.
- [ ] Below the profile picture, the user's first name is displayed.
- [ ] Below the name, the user's email address is displayed.

### Upload Image button
- [ ] A file browsing button and upload button are located below the "Upload a Picture" text.
- [ ] If the file browsing button is clicked, a file explorer of the user's local files is opened.
- [ ] If the Upload Image is pushed without a chosen file, a small text blurb will instruct the user to choose a file.
- [ ] If the Upload Image is pushed with a chosen file, the user's profile picture will update accordingly to the new picture.

### Edit Profile button
- [ ] A button is located below the Upload Image button.
- [ ] When pushed, the Edit Profile section will appear.

### Toggle Scheme button
- [ ] A button is located below the Edit Profile button.
- [ ] When pushed, the color scheme will change.

### Delete Account button
- [ ] A button is located below the Toggle Scheme button.
- [ ] When pushed, the user's account will be deleted.

### Authorize Google Account button
- [ ] A button is located below the Delete Account button.
- [ ] If pushed, and user is not authenticated, the user will be redirected to login to their gmail, and then the text "Your Google account has successfully been linked" will appear for a few seconds.
- [ ] If pushed, and user is already authenticated, the text "You are already successfully linked to a google account!!" will appear.

### Update Password button

### Edit Profile Section

#### Name text box
- [ ] At the top of the section, there is a text box labeled "Name".
- [ ] When selected, text can be entered into this text box.

#### Email text box
- [ ] Below the Name text box, there is a text box labeled "Email".
- [ ] When selected, text can be entered into this text box.

#### Save button
- [ ] Below the Email text box, there is a button labeled "Save".
- [ ] If pushed, the text entered into the Name text box will replace the user's name and the text entered into the Email text box will replace the user's email.

#### Cancel button
- [ ] Below the Email text box, there is a button labeled "Save".
- [ ] If pushed, Edit Profile section will disappear.

### Edit Password Section

#### Current Password text box

#### New Password text box

#### Save button

## My Notes Page

### Create new note button

### Existing notes section

### New Folder text box

### New Folder Submit button

### Collaborator Email text box

### Collaborator Submit button

## Note Editing Page

### Title Area

### Note Area

### Save Button

### Summarize Button

### Brevity Slider

### Edit Summary Menu button

### Edit Summary Title button

### Options button

### Sentence Editor

## Drop Down Menu

### Profile Link

### Logout Link

### My Notes Link