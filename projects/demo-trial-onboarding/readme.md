*Notes from @jglovier and @tangollama's onboarding brainstorming session on 1/22*

## Transcribed notes

#### Onboarding from three perspectives

There are three ways we can look at the onboarding experience.

1. The experience for new contributors
2. The experience for sysadmins deploying a new instance
3. The experience for new end users

#### An example use case

 Jean Francois Negrini, a surgeon in Niger, wants to find a better software system for his hospital.
**Wants**
- Features
  - Track patient records better
  - Reports
  - Share patient data
- To get past his current limitations (need for IT support, etc, etc)
- **To be able to easily evaluate the system to see if it is the right solution for him**

#### Ideas

- Make a **demo mode** in the software that can be flipped on, which is a type of sandbox for demoing the app
  - Contains a feature tour of the UI for new users to learn the app
  - Users can switch between roles to view the UI as different roles.
  - Comes with preloaded demo data set
  - From here, users can initiate a trial (new instance) of the software on their own machine
<img width="217" alt="screen shot 2016-01-23 at 8 26 04 am" src="https://cloud.githubusercontent.com/assets/1319791/12530361/079b0f22-c1ab-11e5-8bcd-1b77f8110ade.png">

- Make a **trial mode** that can be initiated from demo mode, which installs a new instance of the app on the users machine
  - Can ultimately be deployed to production/the cloud
  - Comes up as a blank instance to be populated with your own test data or live data
  - Lives only locally on users machine

#### Questions to explore

- How do we do email?
  - **A:** We get their email when they login to their instance/trial and use in-app analytics to track behavior
- How do we handle local/trial-mode setup WRT back end setup? (e.g. couch/pouch stuff, etc)
- How do we handle deploy to cloud?
  - UX of setting up (AWS, Heroku, etc)?

#### Onboarding flow diagram

<img width="1025" alt="screen shot 2016-01-23 at 9 27 48 am" src="https://cloud.githubusercontent.com/assets/1319791/12530658/9f60745c-c1b3-11e5-92a2-d1bdc1275d46.png">

## Actual notes from markerboard session

<img width="490" alt="screen shot 2016-01-22 at 11 12 54 pm" src="https://cloud.githubusercontent.com/assets/1319791/12528266/b8baf554-c15d-11e5-8866-2a1ca454258a.png">
