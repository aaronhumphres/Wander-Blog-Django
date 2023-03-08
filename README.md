# Wander-Blog-Django

# Project 4 Django

## Overview

A GIRL, a JEEP, and a PASSION TO EXPLORE!

A blog to share Sydnei's love of exploring, while juggling being a full-time student. A way for her to communicate and meet other students that share the same passion.

!

![Sydnei Jeep](https://user-images.githubusercontent.com/120183363/223731849-24d7a3ed-6d07-45df-9b2f-903b9200eaaf.jpeg)


Posts will have trail subject and posts can include images about various points on trail.

example - Mojave Trail Lava Cave

![Syd lava](https://user-images.githubusercontent.com/120183363/223755399-e8c5518d-76b8-4081-9cd7-a2375f4ad0fc.jpeg)

There will be a tips/maintenance/safety section... let's face it, girls have different obstacles then many boys when exploring

![Syd maintenance](https://user-images.githubusercontent.com/120183363/223761621-413760a7-57db-491d-9da2-f9a432fa2f0c.jpeg)
![Syd handgun course2](https://user-images.githubusercontent.com/120183363/223761639-6404168d-7de9-44a1-8abc-19caa3cbd337.jpeg)




### Technologies Used

- Django
- React
- HTML5
- CSS
- Node
- Bootstrap


### Link

TBD

## Approach

## Installation Instructions

## User Stories

- As a unregistered user, I would like to sign up with email and password.
- As a registered user, I would like to sign in with email and password.
- As a signed in user, I would like to change password.
- As a signed in user, I would like to sign out.
- As a unregistered user, I would like to see all users blog posts.
- As a unregistered user, I would like to see comments on those blog posts.
- As a signed in user, I would to create blog posts.
- As a signed in user, I would to comment on other users' blog posts.
- As a signed in user, I would to update my blog posts and comments.
- As a signed in user, I would to delete my blog posts and comments.


## Wireframes

![Alt text](IMAGES/WIRE%20FRAME.png)

## ERD
![Alt text](IMAGES/ERD.png)

![Alt text](IMAGES/ERD.png)

Routes

URL	HTTP Verb	Actions
/auth/sign-up	POST	new
/auth/login	POST	create
/auth/logout	DELETE	destroy


URL	HTTP             |    Verb	        |     Actions
--------------------------------------------------

/auth/sign-up	     |    POST	        |     new
/auth/login	         |    POST	        |     create
/auth/logout	     |    DELETE	    |     destroy

/posts/	             |    GET	        |     index
/posts/mine	         |    GET	        |     index
/posts/              |    POST	        |     create
/posts/:id	         |    PATCH	        |     update
/posts/:id	         |    DELETE	    |     delete

/replies/	         |    GET	        |     index
/replies/:postId	 |    POST	        |     create
/replies/:postId/:replyId|	PATCH 	    |     update
/replies/:postId/:replyId|	DELETE	    |     delete

## Unsolved Problems / Major Hurdles
