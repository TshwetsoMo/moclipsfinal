# About The Project
For this project i was required to create a single page application that outsources data from one of the given API's.
I coded my application using Reactjs and chose an API called the movie database API.

# Getting Started with Create React App
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
## Available Scripts
In the project directory, you can run:
### `npm start`
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
The page will reload when you make changes.\
You may also see any lint errors in the console.
### `npm test`
Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.
### `npm run build`
Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.
The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
### `npm run eject`
**Note: this is a one-way operation. Once you `eject`, you can't go back!**
If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.
Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.
You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.


# Features and Functionality
I was not able to get data from API to show on my display, or to upload onto my graphs so my functionality is limited to changing pages from landing to compare and timeline. 
I have added a button at the bottom of the app where users can generate a movie overview as this was all i was able to display from my API.

# Concept Process
## Ideation:
A website where users can look up the latest, popular, and now showing movies. The site must also allow users to compare 2 movies on 3 or more different objects using graphs (Bar, Line, Pie, and Radar charts).
## Wireframes:
![Landing](https://user-images.githubusercontent.com/113917323/230880853-543dfbc0-f416-4a7f-9407-fadabee09cf7.jpg)
![Compare](https://user-images.githubusercontent.com/113917323/230880872-27714ecf-f8e2-4e7f-b034-45e9cf062709.jpg)
![Timeline](https://user-images.githubusercontent.com/113917323/230880892-ebf659d1-34d4-436d-a981-1af5d5df1b76.jpg)
## Custom UI:
colour pallete
buttons 
display grid customized for optimal viewing
easily understandable layout

# Development Process
## Implementation process:
In the beginning of the term i was struggling to get my API to work to the point where i had to ask a former classmate of mine to recommend a movie API that i could use better. The API did work better but I now had the problem of getting data from the API to display. AFter an unsuccessful contact session in the beginning of the term with Leo which left me with the same problem I went in with but on top of that a skepticism on the advantages of a contact session. 
I decided to focuse more of my efforts on the design and layout of my website. around week 6 i scheduled another contact session out of desperation, but it also proved to be unsuccessful as my follow-up emails and messages regarding my problems were not reponded to/ ignored. 
Given the situation i was in i decided to do what i can even though most of the marks for this project are regarding the main problems i am facing: pulling data from my API.
## Highlights 
I was able to get aquainted with ChatGPT and its capabilities and limitations.
I learned a new programming language called Reactjs and the importance of components, and their reusability. 
Leo telling me my problems aren't an excuse for how far behind I am even though he failed to help me solve a problem i was having with my projet in a contact session i had scheduled with him.
I was able to create the layout for my site fairly easily for a person who has only been coding for a year, though my coding skills did not allow me to make it look identical to my designs.
Handing in such a project for assessmnet can only be used as fuel going forward.
## Challenges
I had trouble getting data from my api to be displayed on my website, the most i was able to manage was creating a button at the end of my app.js page when pushed it generates a movie overview for the user.
I had trouble getting my cards to diplay in rows instead of columns at the beginning of my project. Ended up removing them and puting styled div's in their place. Later during the term i used ChatGPT to figure out how to make a row of cards instead of a row of styled div's. I just needed to put the cards into a container and style that container so that it's contents appear in a row.
I had trouble constructing components. I understood them and how to make them but i have trouble importing them in a way that will allow for my website to work. I am still working on this problem at the moment by studying the ReactJS user manual on their website.
I had trouble getting my graphs to display. Even though i have no data to feed to my graph compenents i still felt that an empty graph is better than an empty block, but whenever i tried to include my graphs in my website the page would stop responding all together or it would import without displaying the graph in the chosen fields.
When asking for help I got more critisism than actual help from the people I could ask. I am solving this problem by getting a development tutor to help me get up to speed so i can avoid falling behind.

# Future Implementation
In the future I plan on scheduling AT LEAST one contact session per week during the term. I understand that maybe it was my fault for not being adamant enough about what i needed help with so I'll do better going forward. I appologise in advance if this means more work for my lecturers but I am very consious of the money my parents are spending for me to get this qualification, and (unfortunately) I am in no position to waste it.
In the future when stuck in class I will hold up the whole class until i understand what is being said, or until I'm asked to stay behind after class for a more in depth explaination.
In the future i will make sure to read the term brief well before school starts so that i can do the work that i can and push ahead of the class so that i can use my extra contact sessions to ask lecturers to explain whatever I am stuck with or fail to understand. So staying ahead of the class basically.
In the future I will not be timid about my ignorance regarding the subject and ask whomever, whenever, and wherever I need help. And I will meet belittlement with unfazed focus.

# Final Outcome
## MOCKUPS:
![screencapture-localhost-3000-2023-04-10-13_17_20](https://user-images.githubusercontent.com/113917323/230891960-5dfb1426-2371-4bc1-a464-12b35a116df9.png)
![screencapture-localhost-3000-compare-2023-04-10-13_18_26](https://user-images.githubusercontent.com/113917323/230891971-54c1763b-ba07-46b3-82f1-861e88592124.png)
![screencapture-localhost-3000-time-2023-04-10-13_23_23](https://user-images.githubusercontent.com/113917323/230892592-db2bc419-6704-4870-8e50-c9e54d7fa023.png)

## Video Demonstartion:

# Conclusion
I failed miserably at meeting the requirements of this assignment and that's largely due to my inability to voice my struggles. So I'll have to work on being more vocal in the future. I also need to take proactive measures so as to not rely soley on one source for gaining knowledge regarding development, in this case the only source being Open Window. I'll have to make sure to get a tutor outside of school in order to expand my understanding and skill of the subject. Even though i might have failed this term i still learned a lot about Reactjs, components, and API's. I just need to practise translating my understanding into physical implementation and with practise i will grow in the skill.
