# App

GymPass style app.

## FRs (Functional Requirements)

> These are the functionalities that the system must have, i.e., what the user can do in the system.

- [ ] Can be possible to user register
- [ ] Can be possible to user login
- [ ] Can be possible render the logged user profile
- [ ] Can be possible get the number of check-ins of the logged user
- [ ] Can be possible to user get the history of check-ins
- [ ] Can be possible to user search for nearby gyms
- [ ] Can be possible to user search for gyms by name
- [ ] Can be possible to user create a check-in in a gym
- [ ] Can be possible to user validate the user check-in
- [ ] Can be possible to register a gym

## BRs (Business Rules)

> These are rules that the system must follow to ensure data integrity and consistency.

- [ ] The user can't be able to register with the same email more than once
- [ ] The user can't check-in in more than once within a 24-hour period
- [ ] The user can't check-in in a gym that is more than 100 meters away from their current location
- [ ] The check-in must be validated by the gym until 20 minutes after the check-in is created
- [ ] The check-in must be validated by administrators
- [ ] The gym only can be registered by administrators

## NFRs (Non-functional Requirements)

> These are requirements that define criteria for judging the operation of a system, rather than specific behaviors.

- [ ] The user's password must be stored encrypted
- [ ] The data must be stored in a database
- [ ] All API data must be paginated with a limit of 20 items per page
- [ ] The user must be indentified by a JWT token (JSON Web Token)
