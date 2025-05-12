## Wave: Building an Open Source Skill Learning Platform
Annie Wang, Spring 2025


### Abstract
---
As an open-source learning platform, Wave was designed to enable people all over the world to learn together and share their knowledge in newly and uniquely developing subject areas. The mission of Wave is to address the missing parts of education and promote inexpensive, interactive, community-driven learning experiences on subjects that are often ignored by large mainstream educational institutions. Citing good practice recommendations in Karl Fogel’s **Producing Open Source Software, Ben Cotton’s Program Management for Open Source Projects**, and the Mozilla Foundation’s **Working Open** guide, the purpose, targets, characteristics, target audience, technical features, and operation strategies of Wave are detailed in this paper. By practicing open-source philosophy and open-source project management techniques, Wave hopes to build an ecological system of education that is sustainable and inclusive. This paper will discuss what makes the platform necessary, how it will be developed and maintained, and how both students and creators can benefit.


### Introduction
---
Online learning has come a long way in recent years. Today, we can acquire world-class education without leaving our homes--or even the country. Platforms such as Khan Academy, Skillshare, and Coursera have helped steer this much-needed institutional reform. However, there is one significant gap remaining. In a quite niche or an all-new field, or even a long-professional specialized area in between the two, students are unable to find good learning materials. Large platforms often have extremely commercially valuable content: computer programming, business management, marketing, and data science. But by contrast, they overlook areas like indie game development, rare techniques in various arts, obscure programming languages, or even one-of-a-kind crafts.

Many learners turn to YouTube videos, online articles, and blog posts. These resources can be helpful, but vary so much in quality that one is likely to find themselves left out of luck a great deal of the time. Without systems to provide the framework as well as depth and interactive feedback essential for mastery, learners may feel confused and alone. Wave was designed as a retort to this situation and also uses an open-source model. Pairing formal courses together with collaborative learning and the participatory spirit of open-source communities, Wave not only satisfies the pursuit of lifelong learning but also is new ground for education.


### Project Purpose and Goals 
---
Wave seeks to transform learning and education in those areas typically neglected by conventional education systems, thereby making all such opportunities accessible to all. The vision is to establish a friendly platform where teachers, artists, and students can interact with each other on equal terms—a genuine community for collaboration. Some of the fundamental aspects of what Wave seeks to accomplish are given below:

First, Wave is about turning learning into an interesting and interactive experience. Courses include group projects, quizzes, and tests in addition to videos and reading. Daily tasks provide consistent progress as they help students work towards bigger goals by dividing them into smaller pieces. Also, a credit system with leaderboards encourages a lighthearted, competitive attitude, making the learning experience more game-like and interactions with friends.

Second, Wave allows users not only to learn but also to teach. Unlike most learning platforms, which restrict content creation to experienced teachers, Wave allows any user to propose and develop a course. Peer review and feedback cycles ensure that content is to community standards, while clear guidelines walk first-time instructors through the process. This model is creator-focused as it recognizes that knowledge is spread across communities and that lived experience, leisure activity, and specialized interest are as significant as formal education.

Third, Wave is also about being affordable and accessible. Most classes will be free, and the ones that are pay-as-you-go will not exceed thirty dollars. With this kind of price strategy, Wave opens education to students, hobbyists, and professionals without regard to cost.

Fourth, Wave will foster a vibrant, diverse community. Discussion boards, chat rooms, mentorship activities, and collaborative projects will provide learners with opportunities to communicate with one another, share ideas, and form social connections. A sense of belonging to a community can transform motivation, persistence, and the learning experience as a whole.


### Target Audience
---
Broad lifelong learners make Wave's target audience one that has diverse groups. The people involved consist of leisure amateurs, including those who prefer to concentrate on tiny fields of research like complex origami, growing mushrooms, or classical fencing techniques. Students who want to stretch their learning beyond the curriculum of formal schooling, such as college students interested in experimental art forms and environmental activists trying to master data visualization at home. It may appeal to professionals who want to develop new skills, such as a developer who wants to learn uncommon coding languages.

Wave aims, too, at people who have talent in a particular field but no means or platform for teaching others. As a result, an independent game author could run a course on pixel art, a local musician might teach some uncommon instrument to curious novices, or a community historian might record oral histories tracing the dappled fates of different parts of this region. In both cases, Wave shall provide the necessary resources and community cooperation to take these voices far beyond their local areas, out onto the global stage.

Most importantly, Wave is dedicated to extending learning opportunities to those who are not currently served by the system. In many parts of the world, education at institutions is either expensive, limited, or simply not available. Wave hopes that by providing relatively low-cost and wide-ranging educational possibilities, it will serve as an instrument for possibility in cities as well as rural areas. Multilingual support, mobile first design, and the ability to access content offline should help ensure Wave's range is as large as possible.


### Platform Features
---    
Wave’s features aim to create sustained learning opportunities alongside social connections and community involvement. The platform features daily tasks that divide courses into manageable goals to help learners maintain continuous advancement. Users will earn points through the completion of lessons, quiz success, and collaborative project participation. The weekly leaderboards will establish friendly competition that boosts motivation among users. Students can ask for new educational content about subjects that interest them. The community can view these requests until enough users express interest, which triggers their addition to the development roadmap. The platform will provide creators with simple tools to develop multimedia educational content, including lessons, quizzes, and exercises. First-time creators can use templates and guides to develop effective materials that engage their audience.

Wav’s recommendation system examines user interests and learning history alongside progress to recommend appropriate courses and materials. The personalized approach will guide learners toward discovering fresh topics while sustaining their ongoing interest. The platform will provide community features through discussion forums, live chat rooms, peer mentoring programs, and collaborative projects. The designated spaces enable learners to interact with each other through question-and-answer sessions, experience sharing, and collaborative work on practical skill applications.


### Technical Architecture
---
Wave's technical architecture will rely on Firebase as its back-end platform. Firebase offers a suite of tools especially suited for open-source educational platforms, including a real-time NoSQL database, user authentication, cloud storage, and serverless computing. Firebase's scalable infrastructure means that Wave can handle surges in traffic, real-time but secure user interaction, such as live chat and collaborative editing, and secure user management without the overhead costs of physical servers (Firebase Documentation).

Wave will use the popular JavaScript library React.js on the frontend. React makes it easy to reuse across different parts of the platform with block-based building technology. Also helping is the modular, responsive nature of components that React fosters, making development faster and easier to maintain. To design user interface (UI) and user experience (UX), Figma can be used. Designers and developer teams are better off designing new projects at Figma. Once those are completed, they can be tested and refined within the app without affecting running work; it's like having an editing room on set.

Communication between the frontend and backend will be managed through RESTful APIs, while real-time updates will be supported using Firebase’s native capabilities. All code, documentation, and project management will be hosted on GitHub in order to be transparent and encourage the entire community’s participation. Git will be used for version control, so a clear and traceable development history can be maintained.


### Applying Open-Source and Working Open Principles
---
Open-source software is software whose source code is made available to anyone for inspection, modification, and distribution (OpenSource.com). Open source, however, the Mozilla Foundation says, is far more than a license; it is a pattern of working that is characterized by transparency, inclusion, and collective problem-solving (Mozilla Foundation). Wave will have these values embedded within it at every level.

Every single piece of Wave's code, documentation, and design files will be made public on GitHub. Detailed guides for contributions, codes of conduct, and issue trackers will enable newcomers to find ways to help out. They may write code or fix bugs; maybe they are good at translating material, might have design ideas about how things should look, or maybe there is something that needs creating, and then everyone will benefit from it. Major decisions will be taken through public consultation, with the community encouraged to submit proposals, vote on priorities, and take part in discussions about governance.

Drawing on the best practices of Fogel and Cotton, Wave will implement a decentralized but connected management style. GitHub Projects and Kanban boards can be used to organize tasks, while tools will include messaging apps, such as Slack or Discord, for cross-timezone collaboration. Occasional hackathons and sprint events will provide opportunities for both striving toward ambitious goals and attracting new contributors. Regular sprints and hackathons will allow the kind of concurrent cooperation and concentrated effort that is needed for modern software projects. The intended result of building architectural inclusivity into the product is not just to create software but to build a movement itself. 


### Project Management Strategy
---
The development of Wave will implement agile and lean practices to enable fast adaptation of project features based on user feedback and changing requirements. The development process will organize itself into two-week sections, which focus on delivering distinct features and improvements. The first minimum viable product (MVP) will contain daily tasks alongside a point system and fundamental course delivery capabilities. The next development sprints will add user-generated content tools, collaborative project features, and personalized recommendation capabilities to the platform.

The project will use Git version control to enable developers to work in separate feature branches before submitting their pull requests for review. Core maintainers will lead code quality assessments and handle software releases while guiding new contributors through the development process. Team alignment will be maintained through asynchronous updates on Slack or Discord, and regular meetings will provide space for progress sharing and challenge resolution.

Technical debt management stands as a fundamental project management priority for Wave. Technical debt describes the expenses that result from development choices that sacrifice quality for fast feature delivery (Fogel). Technical debt becomes unavoidable in early-stage projects, yet unchecked debt slows development, creates bugs, and increases system complexity. Wave plans to conduct periodic debt sprints, which focus on code refactoring alongside dependency updates, documentation enhancement, and code quality improvement. All known debt items will be tracked through GitHub's issue system, where they will remain visible for appropriate prioritization. Code reviews will focus on functional correctness alongside maintainability to stop the buildup of unnecessary technical debt.


### Sustainability
---
Maintaining an open-source initiative like Wave requires more than technical expertise; it depends heavily on establishing strong relationships, earning recognition, gaining support, and enacting diligent planning. To encourage commitment and a sense of ownership among contributors, Wave will have in place a reward system comprised of badges, public recognition, leadership roles, and pathways to mentorship. Major development projects will gain support through monetary incentives funded from grants, donations, and sponsorships, all administered by a nonprofit organization to guarantee transparency and accountability. Activities directed at outreach to the community, such as social media campaigns, conference presentations, and outreach to academia, nongovernmental organizations, and other open-source communities, will raise the visibility of the platform while facilitating outreach to a broad global base. Together, these approaches are intended to establish a sustainable environment to support continuous growth and development.

### Outcomes and Impact
---
Wave's goals are ambitious yet realistic. Within its first two-year cycle, the platform hopes to involve at least fifty thousand students from at least fifty countries. In addition, it aims to enable the development of more than one thousand user-generated courses on a wide range of specialized and cutting-edge topics, some of which are poorly covered by traditional educational platforms. At the same time, Wave hopes to build a contributor community of at least five hundred active members, including developers, designers, educators, translators, and community organizers.

Along with its quantitative goals, Wave seeks to fundamentally shift people's attitudes toward learning, pedagogy, and the sharing of knowledge. By bringing specialist education within reach and within budget and focusing on community engagement, Wave allows people to study what they want, gain relevant skills, and connect meaningfully with others from all over the world. The impact of this project reaches beyond the individuals participating as Wave has the potential to make large-scale impacts within numerous communities by facilitating the sharing of local knowledge, cross-cultural collaboration, and grassroots innovation. Of particular significance, the site's emphasis on inclusivity, multilingual support, and efforts to make the platform affordable can work towards reducing educational disparities and introducing new possibilities for marginalized communities.

The Wave platform, which is released under the auspices of an open-source protocol, offers a model of the practice of educational technology beyond the limitations set by profit-motive commercial interests. In creating a learning context centered in the principles of openness, collaborative practice, and accountability to the users, Wave demonstrates the viability of designing learning sites in which users take roles beyond simple consumption, actively acting as participants and co-producers. In the long term, Wave's lasting influence will not be measured by quantitative indicators, but by the developmental pathways, alliances, and possibilities it makes available to learners and teachers worldwide.


### Conclusion
---
Wave offers a new model for digital learning, with transparency, inclusiveness, and collaborative learning at its core. Informed by the guiding principles espoused by OpenSource.com, Mozilla, Fogel, and Cotton, Wave is designed to foster not just a platform but a thriving community. With its fusion of technological innovation and deep commitment to the social nature of learning, Wave is poised to transform the very nature of education in the digital age. Whether one wants to explore a new topic, a creator wants to share knowledge, or a contributor wants to contribute to beneficial development, Wave is designed to support success.


### References
---
Ben Cotton. (2022). Program management for open source projects: How to guide your community-driven, open source project. Pragmatic Bookshelf. https://pragprog.com/titles/bcosp/program-management-for-open-source-projects/ 

Fogel, K. (2017). Producing open source software: How to run a successful free software project. O’Reilly Media. https://producingoss.com/

Mozilla Foundation. (n.d.). Working open: Mozilla open leadership training series. https://mozillascience.github.io/open-science-leadership-workshop/01.2-working_open.html

OpenSource.com. (n.d.). What is open source? https://opensource.com/resources/what-open-source

Google. (n.d.). Firebase for web. Firebase Documentation. https://firebase.google.com/docs/web/setup
