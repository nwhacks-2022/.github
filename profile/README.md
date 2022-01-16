# talko

<img src="https://github.com/nwhacks-2022/.github/blob/main/assets/logo.png?raw=true" alt="drawing" width="180"/>

Hello! talko is a project for nwHacks 2022.

Interviews can be scary, but they don't have to be! We believe that practice and experience is what gives you the
confidence you need to show interviewers what you're made of. talko is made for students and new graduates who want to
learn to fully express their skills in interviews. With everything online, it's even more important now that you can
get your thoughts across clearly virtually.

As students who have been and will be looking for co-ops, we know very well how stressful interview season can be;
we took this as our source of inspiration for talko.

talko is an app that helps you practice for interviews. Record and time your answers to interview questions to get
feedback on how fast you're talking and view previous answers.

## Features
- View answer history for previous answers- playback recordings, words per minute, standard deviation of talking speed and overall answer quality.
- Integrated question bank with a variety of topics.
- Skip answers you aren't ready to answer.
- Adorable robots!!

## Technical Overview
For Talko’s front-end, we used React to create a web app that can be used on both desktop and mobile devices.

We used Figma for the wireframing and Adobe Fresco for some of the aesthetic touches and character designs.

We created the backend using Nodejs and Express. The api handles uploading, saving and retrieving recordings, as well as
fetching random questions from our question bank. We used Google Cloud Firestore to save data about past answers, and Microsoft
Azure to store audio files and use speech-to-text on our clips. In our api, we calculate the average words per minute over
the entire answer, as well as the variance in the rate of speech.

## Challenges & Accomplishments
Creating this project in just 24 hours was quite the challenge! While we have worked with some of these tools before,
it was our first time working with Microsoft Azure. We're really proud of what we managed to put together over this weekend.

Another issue we had is that it can take a while to get speech-to-text results from Azure. We wanted to send
a response back to the frontend quickly, so we decided to calculate the rate of speech variance afterwards and
patch our data in Firestore.

## What's next for talko?
- Tagged questions: get questions most relevant to your industry
- Better answer analysis: use different NLP APIs and assess the text to give better stats and pointers
  - Are there lots of pauses and filler words in the answer?
  - Is the answer related to the question?
  - Given a job description selected or supplied by the user, does the answer cover the keywords?
  - Is the tone of the answer formal, assertive?
- View answer history in more detail: option to show transcript and play back audio recordings
- Settings to personalize your practice experience: customize number of questions and answer time limit.

## Built using
![image](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![image](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![image](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![image](https://img.shields.io/badge/microsoft%20azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![image](https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black)

<img src="https://github.com/nwhacks-2022/.github/blob/main/assets/rainbow.png?raw=true" alt="drawing" width="180"/>

### Thanks for visiting!
