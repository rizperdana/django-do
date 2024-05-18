# Simple Backend Todo App
## Create a backend service for a Todo App with the following specifications:
- user can login/signup using Linkedin SSO and Google SSO
- user can login/signup using an email and password combination
- user can list,add,update and delete their todos
- If a user is logged in with the same credentials on two or more browsers, when they add, update, or delete a todo in one browser, it should sync to all browsers via socket (push mechanism
- Except for login/signup, other APIs and socket connections must be protected.

## Result
### First time access on url
![home](1-screenshoot-home.png)

### Login page on `base_url/auths/`
![login](2-screenshoot-login.png)

### Websocket on `base_url/websocket/`
![websocket](3-screenshoot-websocket.png)

### Configure google and linkedin url via django admin
![admin](4-screenshoot-admin.png)

### Final home
![homecontent](5-screenshoot-homecontent.png)

NOTE: Coverage report included