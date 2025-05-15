# Elective App by Fabian Martinez

## Background
The University of Illinois Urbana-Champaign is one of the largest institutions in the worlds, and like many of the large colleges, students are given a wide selection of elective courses to choose from. While this variety is obviously viewed as a strength, it can also lead to uncertainty, uncomfort, and stress. With that being said many students struggle to select electives that align with their interests, workload preferences, and academic goals. Some of the current platforms available that students like myself use are RateMyProfessor, the Course Explorer, and even the GPA disparity website. Although they are all good tools, they do fall short of delivering consistent, reliable, and student-specific insights. In addition to that, more often than not students rely on “word-of-mouth” or just chats with strangers to get real feedback about electives. This broken system creates a clear need for a better student focused system that is credible, and an easy-to-use  where UIUC students can learn from one another.

---

## Purpose
The purpose of the Elective application is to provide a more centralized student-driven web platform where only UIUC students can anonymously post and explore feedback about elective courses that they are probably going to take or are considering. This will allow students to gain a thorough peer generated content while also simplifying the process of elective discovery while giving students more confidence in their academic planning. This specific platform will be designed with a focus on “trust” from other students, relevance, and personalization because each post is verified through NetID authentication but remains anonymous if they select to do so. I think this specific feature and purpose of the app can be backed up by research. After doing some more research on user experience principles, the project will be structured around Garrett’s (2010) framework, which emphasizes the importance of usability, content quality, and interface structure in developing responsive platforms.

---

## Vision Statement
Elective envisions a future where students have all the proper control that they need which will lead to clarity over their academic journey. The platform will act as a verified service that is partnered with the university but will also remain an anonymous space(if opted in) where UIUC students can ask questions, upvote answers, and explore course threads that reflect real student experiences. Overall, by prioritizing ease of use and authenticity, Elective hopes to become the number one planning resource in every UIUC student's hand.

---

## Target Audience

- First-year students looking for Gen Eds
- Double majors balancing workloads
- Students exploring topics outside their major
- Peer advisors referencing useful electives

---

## Features

- Anonymous reviews of UIUC electives
- Tags like “GPA boost”, “writing-heavy”, etc.
- Threaded discussions per course
- Verified NetID login with privacy
- Personal dashboard
- Search and filter by department, rating, tags
- Course recommendations based on interests

---

## High-Fidelity Prototype

![High Fidelity](https://github.com/fabianmartinez6/fabian_martinez/blob/main/UI_High_Fi.png?raw=true)

---

## Project Planning
The planning phase is focused on locking in the core features for the first version of the app and then building a timeline that actually works. The main features or the “Must Haves”, include anonymous posts, course tags, discussion threads, and NetID login. I also mapped out how user testing would be run, how the backend should be set up, and what the front-end structure needs to look like. The full build is split across 27 weeks, and is broken into sprints for onboarding, research, design, development, and testing. What counts as success here is simple in my opinion. If we see that students use it, it’s easy to navigate, and the content feels useful then that translates to success. 


---

## Workflow & TimeLine

![Workflow](https://github.com/fabianmartinez6/fabian_martinez/blob/main/Workflow.png?raw=true)

### Project Timeline

| Phase                      | Weeks      | Description                                                            |
|---------------------------|------------|------------------------------------------------------------------------|
| Project Planning          | Weeks 1–2  | Outline goals, define scope, and map out development roadmap          |
| Onboarding                | Weeks 3–6  | Hire team members, assign roles, and set up necessary tools           |
| User Research             | Weeks 6–10 | Conduct interviews, analyze responses, and validate core app ideas    |
| Low-Fidelity Prototypes   | Weeks 10–18| Create wireframes and draft core layouts using feedback from research |
| High-Fidelity + Dev Build | Weeks 18–24| Build out full designs and begin front/back-end implementation        |
| Beta Testing & Launch     | Weeks 24–27| Test with real users, collect feedback, and officially launch         |


---

## Onboarding
As far as the onboarding process goes, it will involve assembling a team of developers and designers, and then being able to equip them with the tools and infrastructure needed to execute the project. Some infrastructure that will be needed includes around 2 front-end developers and 2 back-end developers supported by 2 designers. The team will use GitHub for version control and that will also help with automation. They will use Figma for prototyping, Slack for team communication, and Firebase for authentication and data storage. Clear documentation will outline workflows, design systems, and API structures to promote alignment across contributors. As far as students go, we will be able to recruit students off random samples needed. I think for this project it would be good to give a student an incentive to be researched such as a gift card. At the same time it is important to maintain the random sample of our demographic to keep results consistent. 

---

## 🧪 User Research
Research will begin with surveys and interviews targeting a diverse group of UIUC students across majors and years from freshmen to seniors and from information science majors to industrial engineers. The focus will be understanding where students currently go for elective advice. We also want to know what information they value most, and their willingness to contribute to a platform like Elective. In addition to this I want to be able to ask students to also evaluate different tag types and UI mockups to determine what structure feels most intuitive. The user research phase will directly inform interface decisions, filter categories, and onboarding experience. At least 30 interviews will be conducted, with summaries turned into user personas and journey maps. 

---

## Design
As far as the design phase goes, it will be built upon from research insights to create intuitive and scalable UI components. We want to be able to take information we gained such as “the search feature felt really useful” or “the profile section could be more personalized” and use it to improve our models to ensure a user centric platform. Low-fidelity models are going to be the core flows: searching for a class, reading threads, posting a question, and bookmarking responses. The interface will be designed mobile-first using Figma, with emphasis on minimalism and readability. I want the designers to be able to develop a full design system including color themes, interaction patterns, and accessibility standards. Final high-fidelity prototypes will be tested with a small group of students and passed to front-end developers for implementation.

---

## Front-End Development

Front-end development will use React for modularity and Tailwind CSS for styling. First off I want to use React because React’s component based system will enable efficient development of features like course cards, upvote buttons, filters, and post modals. Next I think it would be a good idea to add Tailwind as it allows for rapid prototyping and ensures responsive design across mobile, tablet, and desktop. The team of developers will follow all ethics and also accessibility guidelines and use fallback states for slow connections or empty results. Updates from the backend will be reflected in real-time using React hooks and Firestore listeners which will also improve automation for our platform.

---

## Back-End Development

On the other hand, the back-end will use Firebase Auth for secure login and Firestore as the primary NoSQL database. Real time syncing will allow users to see updates to posts and replies without needing to constantly refresh which will allow for a overall better user experience. Firestore’s scalability is ideal for all the student generated content and fast filtering. The back end will take care of storing course info, creating threads, tracking user activity, and handling moderation. Only current UIUC students will be able to post or comment using their NetID, but their names won’t be shown if they choose not to. Later on, I plan to add features like course recommendations and a dashboard to track user activity. I also want to be able to expand it to other universities. 

---

## User & Beta Testing

For user testing and usability testing will be conducted with 10–15 students who will be asked to complete tasks such as searching for an elective, posting a review, and reacting to a comment. I want to implement a “think aloud” like experience which will be observed, timed, and followed up with a short debrief interview. Feedback will be sorted by priority and used to refine labels, navigation, and interactions. For user testing we want to make sure that they ask any questions and just talk through the process of them using the application. Alongside that, accessibility testing with screen readers and keyboard navigation will be included. Lastly, we want to have a usability score at the end of the testing to set our priorities straight. The overall goal of this is to make sure that we will release a bug free and accessible platform that supports a wide range of user styles and even tech skills.  

I think beta testing will involve releasing the first version of the app Elective to a certain amount of UIUC students. I think its good to include students like student leaders, RSO members, and peer advisors. The testing phase will be live for several weeks to monitor real usage patterns, interaction rates, and performance under moderate traffic. I also want to be able to look at if any students spam problems about the application and also how long they are on the app for. Alongside that, feedback will be gathered on onboarding flow, tag clarity, and any content moderation gaps. From this specific part of the project adjustments will be made before the actual public launch, and severe bugs will be logged and prioritized by severity.

---

## Launch Strategy

After all the testing protocols, the first launch of the platform will be Launch 1. The launch will be promoted through campus-specific channels, including Instagram pages, Discord groups, and email newsletters like the Daily Illini. The app will go live to all UIUC students using NetID verification. IN addition to that, launch features include course threads, tags, filters, anonymous posting, and a feedback form. Metrics like active users, post frequency, and bounce rate will be tracked using Firebase Analytics. Post Launch it will be important to be able to make sure that the development team will continue releasing small patches post-launch and begin roadmap planning for Version 2. As time goes on we will continuously keep updating the application to make sure that we don't run into any errors or glitches to ensure the security and user experience of our students/users.

---

## Open-Source Collaboration

Elective will be hosted on GitHub as an open-source project. What GitHun allows us to do is that it means other developers can fork it, fix bugs, or suggest new features which will help automation. Its important to include a full contributor guide, API documentation, and setup steps to assure that everything is stored neatly. Also, to keep quality high, all code will go through reviews, use Prettier and ESLint for formatting, and require unit testing on major features. I think it's important to use Github because after looking into more about open source I found that Open source will also help other schools adapt Elective for their own campuses. 


---

## Community

Since Elective is open-source, the goal isn’t just to build an app. I think that it’s to create a community of students and developers who want to make course planning better for everyone because many of students have struggled with it in the past. 
First off, It starts with making sure everything is easy to understand. That means a clear  instructions for the students that actually work, and contribution guidelines that explain how to get involved. If it takes too long to get started, most people will probably just close the app and we dont want that. For communication, I plan to use GitHub Discussions and possibly a campus discord server so contributors and users can ask questions, report bugs, or share ideas. Whether you’re a developer fixing bugs or a student suggesting a feature that you want I think that there should be an easy way to be heard. 
One priority is keeping Elective modular so that if someone wants to add a new type of tag, build a recommendation tool, or adapt the app for another school, they should be able to do that without breaking everything. 
Lastly, to stay organized, I’ll use GitHub Projects for tracking issues and a public roadmap so people know what’s coming next. Ill also use social media to announce all changes to keep the users up to date. 


---

## Challenges

A key challenge will be driving initial engagement for sure. I think that students wil definitely be hesitant to post reviews or trust an emerging platform because it can be intimidating at first. I also think that students will be scared to try the app because of the affiliated log in but I believe that the way we approach this problem is to allow for them to remain anonymous. I also think that this can be mitigated by seeding content, creating partnerships with orgs, and offering incentives like gift cards and anything students might want for being a first-time contributors. 
Technical challenges include preventing spam, scaling search queries, and moderating sensitive content. I also believe that long term, another challenge will be maintaining consistency across user-contributed data. Tag use and post formatting will need to be guided with helpful defaults and tooltips.
Lastly, keeping up with the course catalog will be something that can create problems but I think that our developers will be able to use UIUC Apis to scrape that information before the new classes are implemented. 


---

## Conclusion

Overall, I think that Elective is built from the ground up to solve a real and recurring issue in student academic life. By combining UIUC-specific insights, anonymous but verified contributions, and a clean user experience, Elective has the potential to become the next greatest tool for students who are looking for information about electives and course planning in general. For thousands of students choosing the right class is a stressful process and with Elective we will fight to solve that problem.

## References

Brusilovsky, P., & Millán, E. (2007). User Models for Adaptive Hypermedia and Adaptive Educational Systems. In P. Brusilovsky, A. Kobsa, & W. Nejdl (Eds.), The Adaptive Web (pp. 3–53). Springer. https://doi.org/10.1007/978-3-540-72079-9_1 
Garrett, J. J. (2010). The Elements of User Experience: User-Centered Design for the Web and Beyond. New Riders. 
- [Firebase Documentation](https://firebase.google.com/docs)  
- [Firestore Real-time Database](https://firebase.google.com/docs/firestore)  
- [ReactJS](https://reactjs.org/)  
- [Tailwind CSS](https://tailwindcss.com/docs)  
- [GitHub Docs - Contributing](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)  
- [MDN - Web Accessibility](https://developer.mozilla.org/en-US/docs/Web/Accessibility)  

