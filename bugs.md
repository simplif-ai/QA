Problems
1. When there are no collabs /getcollabs returns false and a weird sql error (from: Audrey)
2. /resetPassword has an auth failure and it has the domain as localhost:3000 and needs to be changed to the frontend domain in file password.js (from: Ian and Kevin) 
3. endpoint update note does not save text correctly (from: Audrey)
4. delete collabs always returns success equals true, if the email doesn’t exist in the db it returns 502 (from: Audrey)
5. In the edit profile section of the profile page the email is not validated as an email (from: Ian and Kevin)
6. In the profile page there are two buttons for delete account and two buttons for authorize google account. (from: Ian and Kevin)
7. On create account page phone number is not validated as a phone number (from: Ian and Kevin)
8. update password may still need their old password (from: Audrey) endpoint /changePassword sends 502 always (from: Ian and Kevin)
9. When creating a note the body of the note is not saved in the db (from: Audrey and Ian)
10. There is a 504 error on long summarizations (from: Kevin, Sawyer and Ian)


Fixed
1. On create account page email is not validated as an email