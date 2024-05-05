# LEARNABLE KIDS BACKEND DOCUMENTATION


## Introduction
Learnable Kids is an LMS platform meant for kids between the ages of 5-12 years old to be able to learn in a more fun and interactive way doing away with the traditional way of learning. 

## _Routes_

#### SIGNUP

## Endpoint: /api/v1/user/sign-up

---

--
`   POST /api/v1/user/sign-up
  `

- The user uses the above url to sign-up



--
`   POST /api/v1/user/sign-in
  `

- The User uses the above url to sign in 

#### PROFILE

## Endpoint: /api/v1/profile

---


--
`   POST /api/v1/profile/create
  `

- Creates profile for all the users




#### COURSE
## Endpoint: /api/v1/course


--
`   POST /api/v1/course/create
  `

- create a course for students to learn

--
`   DELETE /api/v1/course/:id
  `

- deletes particular course using id this operation can only be done by the teachers with admin access

--
`   GET /api/v1/course/
  `

- get all courses for display for easy access for students

--
`   PATCH /api/v1/course/:id
  `
- handles all the editing or updating of the by a teacher with admin access




### Curriculum
## Endpoint: /api/v1/curriculum

--
`   POST /api/v1/curriculum/create
  `

- handles crating of the curriculum by the teachers with admin access.

--
`   GET /api/v1/curriculum
  `
- handles the displaying of the curriculum for every student

--
`   PATCH /api/v1/curriculum/:id
  `
- handles editing or updating of the curriculum this can only be done by the teachers with admin access 



## License

MIT