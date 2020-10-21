## Landing (while logged out)
- User clicks on sign in -> goes to login page
- User clicks on sign up -> goes to sign up page

## Landing (while logged in)
- User clicks dashboard -> goes to dashboard

## Login
- User enters email and password and click submit -> goes to dashboard
- User enters invalid email and password and click submit -> error message stating email isn't registered and suggests registering
- User enters email but no password then submits -> error message to enter password
- User clicks submit -> error message to enter email 
- (While Signed In) Redirects to Dashboard

## Register
- User enters valid email and password and click submit -> success message and suggests login
- User enters valid email but password doesn't meet requirements -> error message notifying user of password requirements
- User enters an already registered email -> error message notifying user of usage of an already registered user
- User clicks submit -> error message to suggest entering information
- (While Signed In) Redirects to Dashboard

## Dashboard
- (While Not Signed In) Redirects to Login
- User clicks + -> goes to add cell modal
- User clicks stats -> goes to stats page
- User clicks cell -> goes to update cell modal
- User clicks profile -> goes to profile settings

## Stats
- (While Not Signed In) Redirects to Login
- User clicks + -> goes to add cell modal

## Profile
- (While Not Signed In) Redirects to Login
- User clicks + -> goes to add cell modal
- User enters new valid image url and clicks update profile image -> profile image updates
- User enters  imvalid image url and clicks update profile image -> error message 
- User changes name and submits -> name changes