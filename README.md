# App

Gympass style app.

## RFs (Functional requirements)

- [x] It must be possible to register
- [ ] It must be possible to authenticate
- [ ] It must be possible to obtain the profile of a logged in user
- [ ] It must be possible to obtain the number of check-ins performed by the logged in user
- [ ] It should be possible to obtain your check-in history
- [ ] It should be possible to get the user to search for nearby gyms
- [ ] It should be possible to get the user to search for gyms by name
- [ ] It must be possible to get the user to check-in to a gym
- [ ] It must be possible to validate a user's check-in
- [ ] It must be possible to register a gym

## RNs (Business Rules)

- [x] The user must not be able to register with a duplicate email
- [ ] The user cannot do 2 check-ins on the same day
- [ ] User cannot do check-ins if they are not close (100m) to the gym
- [ ] Check-in can only be validated up to 20 minutes after it is created
- [ ] Check-in can only be validated by administrators
- [ ] The gym can only be registered by administrators


## RNFs (Non=functional requirements)

- [x] User password must be encrypted
- [x] Application data must be persisted in a PostgreSQL database
- [ ] All data lists must be paginated with 20 items per page
- [ ] The user needs to be identified by a JWT (JSON Web Token)