# ForACause

Live Web Demo (Do expect a slight delay due to Heroku loading): https://for-a-cause.herokuapp.com/
Youtube Short Preview: https://www.youtube.com/watch?v=oPuDCCGTqlo

## Inspiration
Ever thought of volunteering but not sure how to go about finding a suitable opportunity for you to do so? Although there are some websites which lists out available volunteering opportunities, these platforms often lack sufficient information such as feedback by fellow volunteers on the scope of work. Due to differing natures and preferences, it is essential that we are provided with such information to make an informed decision. Hence, we have recognised that there is a lack of avenue that provide such services.

Additionally, we realised that organisations and self-initiated community projects often lack a proper avenue to find potential volunteers. Many of these organisations and groups would then often have to turn to social media to reach out to more people but to little avail. Hence, there is a need for the development of a platform where they are more likely to be able to reach out to their target audience.

Hence, we have decided to develop "For A Cause" which is a website that connects volunteering organisations and groups to volunteers on this platform. Our hack aims to foster the spirit of volunteering amongst users so that they can give back to the community by making volunteering opportunities accessible to every individual. We decided to name our project "ForACause" as we believe that voluntary work for the community benefits both the volunteer and the other party that they are working with. It is meaningful collaboration and experience so as to enrich the lives of others.

## What it does
ForACause is our web app that we have pieced together so as to encourage volunteering to give back to the community. ForACause has 4 main features :
1. View available opportunities nearby (with interactive map) together with feedback provided by others to find suitable opportunities to give back to the community 
2. List volunteering opportunities and search for potential volunteers by encouraging others to participate together
3. Feedback about the volunteering experience so that others will have a better grasp of the workload and job scope
4. Simple and reliable account registration and authentication for users

## How does our hack answer the problem statement
ForACause helps to make volunteering more accessible as it displays details of various volunteering opportunities all over Singapore. The centralised interactive map is able to give an overview of the various opportunities to give back to the community. With a few clicks, users are able to quickly find out what different opportunities entail. 

ForACause also enables more widespread opportunities for volunteering as we have a feature to allow users to create their own opportunity for volunteer work. Users can upload their volunteer projects and appeal to other like-minded volunteers to join them. This promotes self-initiated volunteering projects that individuals may have as they can use ForACause to find other fellow volunteers. Since ForACause is a platform that specialises in volunteering, volunteering organisations and groups are more likely to be able to reach their target audience too.

Moreover, users can leave their feedback and thoughts about each volunteer opportunity to let other users have a better idea of what the experience at the particular opportunity was like. Such a feature can enable other users to better find opportunities that appeal to their area of interest.

## How we built it
Listed below are what we used to build ForACause.
- Express
- Node.js
- EJS
- MongoDB
- BootStrap5
- HTML5
- CSS3

For the front-end development, we utilised EJS (NPM package), HTML5, CSS3 mainly to create the main interface of the website. We have also used BootStrap5 as it simplifies the process of designing and beautifying the webpage. For the backend development, we utilised NodeJS with Express to manage API requests sent and received. Last but not least, we used MongoDB as our database. 

## Challenges we ran into
The biggest challenge we ran into while creating this application was with the collaboration of our work within the team. We initially decided on one team member to take charge of the backend features with NodeJS while the other two would focus mainly on the UI design and the frontend of the website so as to provide a great experience for users. However, we ran into some problems merging both the frontend and the backend due to differing syntax used and realized that the workload was unevenly distributed. Although we spent a lot of time debugging the program, we learnt to standardise the syntax used for this project despite our differing coding styles and managed to complete the project together successfully.

Another challenge we ran into was with time constraints. Due to the fact that we did not have much time to complete the project and develop a full-stack website with a frontend and backend, we had to effectively allocate our time within the stipulated period. Hence, we learnt to distribute the workload evenly by taking the initiative to work on untouched parts of the program so that we are able to contribute our work while not interfering with the code that others are working on. We managed to make progress steadily and working with minimal rest through the day and night, thus managing to complete this project in time.

## Accomplishments that we're proud of
We are most proud of the fact that we have managed to develop a functional full-stack website within 24 hours for LifeHack 2022! Although some of us had some experience in full-stack and front-end web development in the past, we were not bounded to such a tight timeline as compared to during this hackathon. By working with minimal rest and overcoming our difficulties such as time constraint and with collaboration, we managed to gain much knowledge about full-stack web development and complete our project in time while working under time pressure.

## What we learned
Our biggest learning point was the ability to collaborate on a fairly elaborate project such as a full-stack website like "For A Cause". Due to the complexity associated with working with a functional server database like MongoDB as well as with both a frontend and backend with NodeJS, it was difficult to collaborate on this project by working on individual portions of the code as most of the code are intrinsically inter-linked with each other. Hence, we learnt to standardise the basic syntax used for this project despite our differing coding styles as well as the importance of writing code that is as clean as and as readable as possible. Although the code we had written was messy at first, we gradually improved and learnt to collaborate effectively to successfully complete this project together.

Next, we have also gained much knowledge in the development of a full-stack website. Not all of us had experience in full-stack development before and had only worked with the front-end in the past before. Through LifeHack 2022, we managed to learn more about working with a backend framework like NodeJS as well as utilise our existing knowledge to supplement our learning for a full-stack website. Other learning points would include soft skills such as time management and efficient division of workload based on our strengths during development. We believe that we have definitely improved learning the relevant knowledge required for building “For A Cause” for LifeHack 22.

## What's next for InfinityCoders
Given more time, we plan to include more advanced features that could help volunteers to a greater extent. For example, we hope to include an interactive feature that would provide up-to-date information on the availability of slots for that particular volunteering opportunity. This allows volunteers to effectively find available volunteering opportunities as well as facilitates the volunteer searching process for organisations.

Additionally, "For A Cause" relies on organisers to actively update the website with their available volunteering opportunities currently as it functions as a platform that connects both volunteer organisations and volunteers. However, this process may be a hassle in the long run if organisations do not have the manpower to frequently update this page. Hence, we have also planned for the utilisation of external web-scrapping tools such as the BeautifulSoup library in Python to parse through existing websites in a fast and efficient way on the web to update available volunteering opportunities for "For A Cause". This would automate process of listing the available volunteering opportunities for "For A Cause" and ensure that the information provided would always be up to date.
