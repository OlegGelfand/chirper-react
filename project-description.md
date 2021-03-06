## Project 3

### Full Stack Application Description

# Project Overview

-We propose the creation of a full stack application, Twitter clone. Using a back end with full CRUD abilities  that will populate front end with data. Styled in modern mobile first approach, then scaling up to the desktop applications. We would like our users to be able to post their content. Front end will be using React while backend will be a Express, Mongo, and Mongoose.

## Project Links

https://github.com/adgreenie/chirper-react(Front End)
https://github.com/adgreenie/chirper_backend (Backend)


## Project Description

React Architecture and WireFrame:

https://www.figma.com/file/IiP3bWLkxpFsWnNoVXqZrO/Twitter-Clone?node-id=0%3A1

Time Priority Matrix:

https://docs.google.com/drawings/d/19SkMOCgP_dLDPa8-AsPx5pVYVNHjlwo34_3wy7WbFPI/edit



## Wireframes

https://docs.google.com/drawings/d/1aXZuwEahwIJxlZ64BZlNaHR5ppL7RNES3SXHgBd_IYk/edit


### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP 
- Completeing and Deploying the Database
- Testing Communication between Front and Backend
- Front end React app
- Allow user to interact with the page
- Mobile First
- Displaying Comments
- Creating New Posts
- Getting All Posts
- Deleting A Post
- Updating A Post


#### PostMVP 

- Additional Styling
- Admin Pages
- Favoriting Posts/Comments




## Components
##### Writing out your components and its descriptions isn't a required part of the proposal but can be helpful.

Based on the initial logic defined in the previous sections try and breakdown the logic further into stateless/stateful components. 

| Component | Description | 
| --- | :---: |  
| App | This will make the initial data pull and include React Router| 
| Main | Will include the main navigation of the page | 
| Feed | This is where users and favorites will render depending on the link | 
| User| This will display a random amount of users|
| Chirp | This is an individual post |
| ChirpForm | This is the form to POST a post |
| Comment | This is the component that deals with comments |
| Footer | Component with the bottom nav bar/ links |




Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe. Also, put a gif at the top of your Readme before you pitch, and you'll get a panda prize.

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
|Research| H | 4hrs|  | |
| Create back end file structure | H | .5 | |
| Create models for User, Chirp, and Comment | H | 1 | |
| Set up GET route & controller to return all Users | H | .5 | |
| Set up connections for local testing, test with Postman | H | 1 | |
| Set up & test additional GET/POST/PUT/DELETE routes & controllers for User | H | 2 | |
| Set up & test GET/POST/PUT/DELETE routes & controllers for Chirp | H | 2 | |
| Set up & test GET/POST/PUT/DELETE routes & controllers for Comment | H | 2 | |
| Configure for deployment on Heroku | H | 1 | |
| Set up MongoDB Atlas server & and deploy db on Heroku | H | 1 | |
| Create helper file for front end | H | 1 | |
| Debugging interaction with front end | H | 4 | |
| Add additional functionality for postMVP goals | M | 4 | |
| React Front End Setup | H | 8hrs|  |  |
| React Components Organization/Creation| H | 8hrs | |
| Logic for Components| H| 8hrs| | |
| Deployment of Backend| H | 2 hrs|  | |
| Deployment of Frontend| H | 1hr| | |
| Communicate from Front to Backend | H | 4 hrs|  |  |
| Responsive | H | 4 hours |  | |
| Total | H | 60hrs |  | |

## Additional Libraries
ReactStrap/ BootStrap
Heroku

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description.  Code snippet should not be greater than 10 lines of code. 

```
 <Button id="Popover1" type="button">
          <i className="fas fa-play">
            <UncontrolledPopover
              trigger="legacy"
              placement="top"
              isOpen={popoverOpen}
              target="Popover1"
              toggle={toggle}
            >
              <PopoverBody>
                <ChirpForm />
              </PopoverBody>
            </UncontrolledPopover>
          </i>
        </Button>
```
The code above combines ReactStrap components with our own Component for a Chirp form. By nesting the ChirpForm inside of this React Component it brings up a small seperate window inside the app to let the user Post without having to send them away to a different screen.