# Capstone

This is the API that enables the capstone-api.

## Important Links

- [Other Repo](https://github.com/ruizdotcom/capstone-client)
- [Deployed API](https://obscure-bayou-34723.herokuapp.com/)
- [Deployed Client](https://ruizdotcom.github.io/capstone-client/)

## Planning Story

Planning for this project, I chose what the user would be able to do once the signed up such as creating editing or deleting a post.I decided to make an application were people were able to sign up create a profile and use it as a place to write down thoughts or ideas.

### Technologies Used

- Node.js
- Express.js
- jQuery
- javaScript

### Unsolved Problems

- Would like to eventually be able to create chatrooms
- Would like to be able to add a profile section
- Would like to be able to have users pick a profile picture

### Routes

| Verb   | URI Pattern            | Controller#Action      |
|--------|------------------------|------------------------|
| POST   | `/sign-up`             | `#sign-up-email`         |
| POST   | `/sign-in`             | `#sign-in-email`         |
| PATCH  | `/change-password/`    | `#change-password-email`       |
| DELETE | `/sign-out/`           | `#sign-out-email`        |
| POST   | `/posts`             | `#create-posts-form`         |
| GET   | `/posts`             | `#show-posts-form`         |
| PATCH  | `/posts/`   | `#update-post-form`       |
| DELETE | `/posts/`           | `#delete-post-form`        |

## Images

---

#### ERD:
![ERD](https://git.generalassemb.ly/ga-wdi-boston/capstone-project/files/3729/ERD.project.4.1.pdf)
