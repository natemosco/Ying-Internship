# YING-Internship
## Overview
This is a Writeup of experiences and accomplishments during my time at YING.

During This 9 week Internship I had the pleasure of helping to build up the YING web and mobile application.

YING is a platform being built to allow people to skill share with eachother thus empowering individuals, non-profits and corporations to exchange their resources and skills for time based credits.
<div style="width:100%; height:300px; display:flex; justify-content:center; align:center">
    <div style="height:210px; width: 210px; background-color:#91e7b6; padding: 10px">
    <img id="thumbnail" src="./data/ying-logo-black3x.png" title="YING logo" alt="reset-password gif" width="200" height="200">
    </div>
</div>


## Added Features
### 1. Reset Password Flow
- GIF displaying the flow of a user required to use multifactor authentication by default in order to reset password. This is an entirely new flow that I was able to add to the project in my time with YING.
<center>
<img src="./data/ying-reset-password.gif" title="Reset password flow" alt="reset-password gif" width="800" height="400">
<br><br>
</center>

### 2. Shareable Link
- GIF displaying an added feature where a link is generated that can be shared with other users/non-users to route you to be able to join with the press of a single button and an autopopulated form. I added this feature and handled all routing and permissions for users from 3 User states:
    - Logged in --> routes to join said group
    - Logged out --> routes to join said group after logging in
    - Not yet a User --> onboards a User then routes to join said group
    <br><br>
<center>
<img src="./data/ying-shareable-link.gif" title="Shareable link feature that I coded" alt="share-link gif" width="800" height="400">
</center>

## Detailed list of tasks performed during my time with YING:
1.  Refactor of App.tsx on the Front-End
    - Identified mishandling of token placement & required token setting to be performed only during login / signup / app-initialization
    - Simplified rerouting logic
    - Limited app rerendering by changing app-initialization logic which prevents a loss of in app memory/state
    - Ensured onboarding a user includes multi-factor authorization
2. Improve Routing and Private-Route component
    - Remove token setting ability
    - Add authentication logic to simplify access permissions to any page without being logged in
    - Corrected in app flow patterns to match design specifications
3. Onboarding a User
    - Refactored forms to reflect current design needs
    - Added custom validation to forms
    - Modified GraphQL call on Front-End and changed Back-End code to return additional data to maintain symmetry between onboarding an organization vs a user
4. Refactored Mail Chimp code (for email marketing purposes)
    - Refactor of code in the Back-End to eliminate 200 lines of code by combining 2 calls to the external API
    - Refactor of code in the Front-End to reduce 150 lines of code by simplifying call functions and thoughtfully replacing the location of code within the onboarding flow
    - Designed a new function to incorporate group tagging for fine grain targeted marketing purposes
5. Implemented a shareable link feature
    - Upon creating an organziation a link is programmatically generated that is able to be read by the application to route the user and prepopulate the form so as to be able to join a group or organization with a simple button press
6. Implemented a multi-factor Reset Password flow
    - Coded several new components to authenticate and match user data using Firebase prior to sending a reset password email
7. General Refactoring
    - Thoughtfully refactored repetetive code to implement DRY software development principles
    - Maintainability improved through implementing functions that reuse pure functional components



## New and Practiced Skills
- Learned to use Ionic
- Learned to workwith Prisma Back-End
- Worked with GraphQL both Front-End and Back-End

## Acknowledgements
<center>
Thank you to Karla Ballard Williams who brought me onto the team and supported my efforts every step of the way.
She encouraged and supported me in my work, learning and took time to answer questions about YING for me personally.
I greatly appreciate the heart and passion she brings to the table which really drives and fuels those with whom she works
to strive towards the goals and vision she holds.
<h2>CEO / Hiring Manager</h2>

|                             [Karla Ballard Williams](https://www.linkedin.com/in/karlaballardforvp/)                                                                                                                                                  |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:   |
|    [<img src="https://media-exp1.licdn.com/dms/image/C4D03AQEcESCJjNCqQA/profile-displayphoto-shrink_200_200/0?e=1606348800&v=beta&t=LeM-Hl_1igbN-GZ2hBKHwmYveoeyyR1rau8z8Fs3R3M" width = "150" />](https://www.linkedin.com/in/karlaballardforvp/) |
|    [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="40"> ](https://www.linkedin.com/in/karlaballardforvp/)                                                                                                                |
<br><br>
<h2>Web Team</h2>
A big thank you to the web development team I got to work along side!
This experience was amazing because of a great team who worked really hard, believed in me and who quickly became my friends.
It was great to have a team who trusted me to refactor their code and to even add new features to the product on my own. I had a
wonderful time working with you.

|                             [PM: Nathan Argetsinger](https://www.linkedin.com/in/nateargetsinger/)                                                                                                                                                |                                                 [Gerardo Paredes](https://www.linkedin.com/in/gerardo-paredes-562474168/)                                                                                                                                   |                                               [Keenan Brownsberger](https://www.linkedin.com/in/keenanbrownsberger/)                                                                                                                                 |                                                 [Aaron Townsend](https://www.linkedin.com/in/aaronetownsend/)                                                                                                                                    |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|    [<img src="https://media-exp1.licdn.com/dms/image/C5103AQFrLJbCzSvb-Q/profile-displayphoto-shrink_200_200/0?e=1606348800&v=beta&t=xxP72P3lLYuk6REH5wBYtCIOW1FT9RRnPcULSacIDcA" width = "150" />](https://www.linkedin.com/in/nateargetsinger/) |    [<img src="https://media-exp1.licdn.com/dms/image/C5603AQFt_jfc8QLAJg/profile-displayphoto-shrink_800_800/0?e=1606348800&v=beta&t=jlKP4UWjNhVpNpqxmE819RcO3asMCKos75CGyTz5vUs" width = "150" />](https://www.linkedin.com/in/gerardo-paredes-562474168/) |    [<img src="https://media-exp1.licdn.com/dms/image/C5103AQGWL5C0zdoPKg/profile-displayphoto-shrink_200_200/0?e=1606348800&v=beta&t=YeJCANJ830aDLiqVvDZDfzo_3RS7w034npu-brUQIks" width = "150" />](https://www.linkedin.com/in/keenanbrownsberger/) |    [<img src="https://media-exp1.licdn.com/dms/image/C5603AQGSQLHNH6YVvQ/profile-displayphoto-shrink_200_200/0?e=1606348800&v=beta&t=xRWJWOjQFiygWY8Shf2RAaKwn9pYivR2F3kz_moKYiM" width = "150" />](https://www.linkedin.com/in/aaronetownsend/) |
|    [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="40"> ](https://www.linkedin.com/in/nateargetsinger/)                                                                                                                |    [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="40"> ](https://www.linkedin.com/in/gerardo-paredes-562474168/)                                                                                                                |    [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="40"> ](https://www.linkedin.com/in/keenanbrownsberger/)                                                                                                                |    [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="40"> ](https://www.linkedin.com/in/aaronetownsend/)                                                                                                                |

</center>