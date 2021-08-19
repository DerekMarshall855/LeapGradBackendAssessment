# Leap Grad Backend Assessment Submission Doc
## Instructions to run:
- Task1:
    - Go to t1 folder on terminal or IDE
    - Run command: npm install
    - Run command: node server.js || npm start
        - Should be running on port 5000
    - Open new terminal at same location to init mocha
    - Run command: npm install –save-dev mocha supertest should
    - Run command: mocha tests/test.js
        - Should run through ~52 tests
        - May not work if mocha isn’t installed
- Task2:
    - Same as task1 but the root folder is t2

### Sections I’m Proud of

I am proud of the entire assessment, but I specifically enjoyed making the threading feature. It took a bit to figure out how to do it properly (I’ve made a failed attempt before for my blog) but this time around I got it to work. Other wise I’m proud of implementing extra features such as followers, following, and chat rooms.

In t2 I wouldn’t say I’m “proud” of anything as I have done similar tasks before, but I am proud of the tests I wrote for both t1 and t2 as I am relatively unfamiliar with writing unit tests with mocha.

There are two things I could do to easily improve this application: 1) Adding redis or another backend cache to speed up subsequent fetch requests (And allow for the app to work at scale) and 2) Adding socket to the app so the chat feature is live.

The project I am the most proud of outside this assessment is my amazon webstore clone (https://github.com/DerekMarshall855/AmazonClone || https://webstore-clone.netlify.app/)  although there are improvements I could make on it. It was my first full stack project I felt confident about the whole way through. It lacks a cache so subsequent load times are not very good, but I learned a lot from it and it inspired me to learn how to cache for subsequent projects. I am reading more into it currently and can to basic fetch caching with node-fetch-cache module.
