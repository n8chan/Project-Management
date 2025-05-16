## MuseMap - Final Paper
**Noam Gomez**
IS340: Project Management, Spring 2025


### Abstract
MuseMap is a mobile app designed to transform the way that people explore, interact and experience with museums. By integrating location-based services and personalize recommendation, MuseMap aims to modernize the cultural institution experience. The platform empowers users to discover nearby museums, receive curated tour suggestions, and engage with museum content both in the real world and remotely. This paper outlines the motivations behind MuseMap, it’s design and technical framework, the open-source philosophy behind it and short as well as long-term plans for implementation.


### Introduction
Museums often serve as a sort of gateway to culture, history and knowledge, and yet they are often underutilized or inaccessible to the general public, particularly younger generation and underserved communities. In an age dominated by digital experiences, the traditional museum model often fails to capture the attention of an audience accustomed to tailored and interactive content. Musemap is motivated by the desire to spread access to cultural institutions by harnessing what makes digital experiences so attractive, through the use of technology such as geolocation and machine learning algorithms to provide a more individual experience. Muse map aims to answer several core questions:
-	How can we make museums more engaging for modern audiences?
-	What role can technology play in enriching the museum experience?
-	How can we encourage learning through these discoveries?


### Project Motivation
I’ve always been fascinated by museums and technology, even from a young age. I always found museums to be spaces filled with so much knowledge and creativity, often a hub from which to base my own ideas, fantasies or lessons. As someone who has often been quite passionate by history and innovation, as well as naturally the intersection between history and innovation, I’ve often wondered why the experience of a museum varies so differently depending on the institution.
Over the years, I’ve visited a lot of museums. Sometimes of my own choice and often at the behest of my parents, I’m not a very big fan of art museums but they sometimes surprise me. One trend that has continued to stand out to me is the gap in how effectively different types of museums integrate interactivity into their exhibitions. Science and technology museums often lead the way in creating immersive and memorable experiences. One of my favorite all around experiences was the the Natural History Museum in London, which I often frequented when I lived in the United Kingdom. I thought they found the perfect way of blending physical exhibits with digital technology that enhanced the experience. Particularly with their use of a sort of card that you could use to go from terminal to terminal and collect the various specimens you looked at. 
However this level of interactivity is not universal. I’ve found that art and history museums, while rich in content and fantastic physical exhibits, often lag behind in adopting digital tools to enhance the experience. A visit to the Art Institute in Chicago, while impressing me with the skill of the artists, left me feeling a bit dissatisfied. The lack of interaction made the experience feel very rigid and passive. The static labels and absence of guided exploration tools failed to really spark that curiosity in me. I will however concede that my parents returned at a later date for an immersive experience related to Van Gogh that they very much enjoyed, so perhaps some steps being taken in the right direction.
These contrasting experiences are what inspire the idea of MuseMap, I want to create e platform that bridges this engagement gap, an app that makes art and history just as interactive and accessible as the buzzing science exhibits. My goal is to empwer users to explore museums on their own terms, guided by their own interests but supported by technology that enhances the experience. I believe that every museum, no matter the subject, has the potential to be a place of wonder and learning, and that understanding what the modern visitor is used too is paramount to this.
MuseMap is my attempt to combine my love for technology and museums into something meaningful. It’s a personal response to a problem I’ve seen and felt firsthand, as it reflects my belief that cultural spaces should evolve alongside the tools we have at our disposal.
To go with this are the following project objectives of MuseMap:

### Project Objectives

1.	Enhance Museum Discovery through Location-Based Technology
Utilize GPS to help users effortlessly locate nearby museums and cultural institutions based on their location.

2.	Provide Personalized Museum and Exhibit Recommendations
Implement self learning preference algorithms that offer tailored suggestions for not only museums but also individual art pieces, encouraging deeper engagement with content.

3.	Develop Real-Time Interactive Navigation Tools
Create an in-app nav system that helps users find specific exhibits they are looking for, plan routes through museums and avoid missing important parts of their tour.

4.	Promote Cultural Accessibility and Inclusion
Design a platform that can be accessible to a wide range of users, including those with disabilities or limited familiarity with museums, those of younger and older ages and any other limiting factors.

5.	Support Museums with Data-Driven Insights
Provide museums with anonymized user data and analytics to help them better understand what interests visitors so they may improve exhibit planning and overall drive up visitor engagement.

### Design
MuseMap is designed with both functionality and aesthetic appeal in mind. The app will feature a clean and intuitive user interface that allows users to locate nearby museums, explore current exhibitions and receive personalize recommendations based on their interests and behavior.
Core features include:
•	Location-Based Discovery: Using GPS and location data, users can find museums near them. This includes directions, hours, ticket information, and accessibility options.
•	Personalized Recommendations: A recommendation engine that considers past visits, user preferences, reviews, and trending exhibitions.
•	Interactive Tours: Users can follow guided audio or AR-enhanced tours that lead them through specific exhibits or themes.
•	Map Integration: Museums are integrated into a dynamic map view that highlights notable collections, art pieces, and special installations.
•	User Profiles: A login-based system to save preferences, track visited museums, and bookmark exhibits.
•	Social Features: Users can share their museum experiences, leave reviews, and connect with friends with similar interests.

### Technical Decisions
MuseMap is built with a modern full-stack architecture for scalability and performance. The major components include:
•	Frontend: React Native for cross-platform mobile development.
•	Backend: Node.js with Express for the server-side application, connecting to a simple SQL database hosted by a third party such as Microsoft Azure.
•	Mapping & Location Services: Google Maps API for real-time navigation and location features.
•	Recommendation Engine: A machine learning model using collaborative filtering and content-based filtering written in Python with scikit-learn.
•	Authentication: Firebase Authentication for secure login, account management, and analytics.
•	Content Management: Integration with museum APIs, and internal data structure for non-supported museums.
•	Cloud Infrastructure: Deployed on AWS using GitHub version control.

### Open Source Philosophy
MuseMap will be committed to an open-source development model to encourage collabartion and community driven innovation. All core repositories will be hosted on GitHub, enabling developers worldwide to contribute code, report issues and suggest changes.
The choice to make MuseMap opensource was an easy one, particularly considering the material we are dealing with. Throughout history, we have worked together to make projects happen, and museums are a proof of that. I am no expert in what makes a museum experience enjoyable, I just have my own point of view, other developer’s feedback is paramount to the success of this project. 
This model ensures that MuseMap remains adaptable to emerging technologies and diverse user needs.

### Weekly Plan and Workflow.
| ![](https://github.com/OREL-group/Project-Management/blob/main/FINAL%20PAPERS/Noam-Workflow.png) | 
| :--: |
| <b>Figure 1.</b> Caption test. Workflow: follow below weekly plan for better explanation |  

Week 1: Ideation and Creation
The first week of development will be completely dedicated to brainstorming and laying the foundation vision of MuseMap. This is where core goals will be defined and refined. Key features of the app will be discussed and a clear roadmap will be sketched outlining each development milestone. If the project is undertaken as a team then roles will be worked out and the technical requirements necessary to bring MuseMap to life will be ironed out.

Week 2: Market Research
During the second week, the main focus will be on market research. Figuring out what competitors or similar apps do and brainstorm what makes them successful as well as how we can implement similar features will be very important. Things such as Spotify’s recommendation algorithm or Map’s pathfinding algorithm are important things to consider as they are close to what we are trying to create.

Week 3: User Experience
Week 3 will be all about figuring out what the user can expect of MuseMap. Creating user personas and what we expect a user to look for in MuseMap is the main focus of this week. Combined with researching who is most likely to use the app and catering it to them whilst also maintaining that inclusivity, figuring out all of that is one of the most important steps.

Week 4: Identify Issues
During the fourth week, we will focus on anticipating the biggest challenges and attempting to find solutions for them. Issues such as how we should handle data and user privacy should be solved at this stage. Figuring out exactly what services we want to use to implement various technical aspects of our project are also important. 

Week 5: User stories
Creating specific examples of user that we can use to exemplify consumer needs. Now that we have an idea of what user’s should expect and who should be our primary users, we can be a little more specific. Ideas like “Tommy is a college art student who needs to easily find museums” will be useful when asking “How would Tommy feel about this feature?” and making decisions.

Week 6: User Interface
Creating a map of the expected UI flow and beginning to sketch the App so that we can begin implementation at soon. At this point technical designs should all be figured out and we should be moving on to actual implementation.

Week 7: Design
Starting with a low fidelity protype, we want to create a version of the App that can be tested. In reality this make take longer than a week but is treated as a single section of time. The idea is to implement high priority features and important parts of the app to receive direct feedback from users similar to our user stories. Using user testing and feedback we can refine the app.

Week 8: Refinement
Week 8 will be where a large portion of the technical work is done, as we have received initial feedback and created a prototype, we must now get to work on refining the app as close as possible to our vision. Implementing feedback is key whilst also maintaining our original vision.

Week 9: High Fidelity Prototype
Week 9 should be finalizing the app and preparing it for an initial release or beta. The idea is to have an app polished enough to show to the public, investors and potential collaborators. The app should be as close as possible to our goals and almost launch ready, with further stages determined by the reaction of the people we present to.

### Note on Technical Debt
As MuseMap grows in complexity and users, managing technical debt becomes critical to maintain the stability of the project. Technical debt will be incurred no matter what as we make design choices that are made for short term development (Dai 2017). In MuseMap’s case, the use of third-party support or libraries that make algorithms work better in the short term may hinder scalability and innovation. To manage this debt, it’ll be important to strike a good balance between delivering new features and maintaining the quality of the code. Regular updates to the app to keep it up to date on device compatibility as well as migrations if necessary to different third parties will need to be done as the app scales to larger audiences. Finding ways to track technical debt through issue trackers and allowing collaborators to bring up issues as well as fix them is an important part of the open-source philosophy that we can use to help mitigate some of the problems relating to technical debt. While it is inevitable that we will incur technical debt, being able to find ways to track and mitigate it is what will decide the success of the project more so than anything else.

### Long-Term Plan
Following its initial release, MuseMap’s long term vision focuses on expanding it’s features and continuous innovation. A key priority will be internationalization in adding multilingual support, localized recommendation and access to regional museum content to make the platform feel more inclusive and global. Strategic partnership with renowned museums such as the London Natural History Museum or the Chicago Art Institutions will be important to offer users exclusive experiences and other opportunities. MuseMap also aims to enhance it’s recommendation engine through the use of continuous deep learning, enhance it’s ability to provide accurate recommendations. To stay ahead of emerging technologies, MuseMap wants to integrate AR and smartwatches, and migrate from just a solely smartphone app to a multiplatform experience. On the educational front, collaboration with schools to support museum field trips and curriculum integration would be a great way to generate support in the younger generation. Furthermore by continuing our open-source philosophy, we will be able to keep up on new changes and required fixes to make sure that the user experience on MuseMap remains positive for the user.
Conclusion
MuseMap is meant to be more than an app, it is supposed to be the tool that museums can use to engage visitors in ways they have never done before. By leveraging the technologies mentioned in this report, MuseMap hopes to rekindle public interest in these cultural institutions and provide meaningful and educational opportunities to journey into science, history and art. With thoughtful design and a user-first design approach, we hope to redefine how we interact with the world’s cultural treasure. 




### References     
AlMarzouq, M., Zheng, L., Rong, G., & Grover, V. (n.d.). Open source: Concepts, benefits, and challenges. AIS Electronic Library (AISeL). https://aisel.aisnet.org/cais/vol16/iss1/37/ 

Dai, K. (n.d.). [PDF] detecting technical debt through issue trackers | semantic scholar. https://www.semanticscholar.org/paper/Detecting-Technical-Debt-through-Issue-Trackers-Dai-Kruchten/cb74305e75cda31d8838d36bbeb2aeca29ef9f32 
