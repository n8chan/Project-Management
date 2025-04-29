Shivam Patel, IS 340 Spring 2025, Link to personal website: https://www.linkedin.com/in/shivam-patel-13622b238/


## Introduction - CartSync

---

### Background

College students living together often struggle to coordinate grocery shopping, leading to overbuying some items and forgetting others, resulting in frustration and extra costs. Students are juggling numerous responsibilities, from academics to extracurricular commitments, leaving them little time to worry about splitting expenses. There are apps that allow students to split expenses, but some features are either behind a paywall, require an ad to proceed further, or the features are too basic. As a student myself, I have personally tried out these apps but I find myself switching between apps to be able to manage my expenses. I forget about expenses that I am supposed to pay for and I have a hard time managing my budget due to the lack of understanding of my personal expenses. This has led to conflicts with my roommates and has strained our relationships at times. Therefore, I am proposing a college expense splitter app called CartSync that is free and leverages AI with a user-centric design made for college students. 

---

### Purpose
The purpose of CartSync is to provide an intuitive and satisfying solution for collaborative expense management. Students can easily create a group with others and be able to log expenses within their respective group. CartSync allows students to view their fair share of expenses quickly with pay these expenses with the tap of a button. CartSync also bridges the gap between budget and expense management. Students can view real time changes to their budget as expenses are posted.  Real-time notifications are enabled to notify students when they are paid or when an expense is posted by someone. By automating mundane tasks such as pantry inventory management, grocery shopping list creation, and expense management, CartSync helps students focus their time and energy on tasks that are more important. CartSync takes the hassle out of collaborative expense management while helping students stay on top of their budget, preventing unnecessary frustration between roommates. Some core features include:

- Expense Logging: Add expenses either through photos or the add expense button
- Pantry Inventory Management: Students can take photos of their pantry or log the items manually to save time while grocery shopping.
- AI Recipe Generator: Based on the items in the pantry, AI can create a list of potential recipes that students can create, which takes the grunt work out of deciding what to cook.
- Shopping List: Students can view an entire group's shopping list. It is easy to see who has paid and who hasn’t. Students can also pay any pending expenses here as well. 
- Grocery List: Students can view a history of all of their past expenses, who has paid them, and any remaining expenses all in one place. 


---
#### Vision Statement: In essence, the vision for this project is to create a straightforward collaborative budgeting and expense tracking system designed for college students. ####
---

### Target Audience
<b> College Students: </b> This app will cater to students between the ages of 18-24. These students will also have at least 2-3 roommates and are looking for a more hassle free, intuitive way to manage collaborative expenses.  

---

### Organization Workflow
| ![](https://github.com/spatel54/Project-Management-340/blob/main/FINAL%20PAPERS/IS_340.jpg) | 
| :--: |
| <b>Figure 1.</b> Image of a product workflow from research to production. |   

### Organization Workflow with timeline
[Comment_3]: <> (begin your text here)

| ![](https://github.com/spatel54/Project-Management-340/blob/main/FINAL%20PAPERS/IS_340.jpeg) | 
| :--: |
| <b>Figure 1.</b> Image of a product workflow from research to production with timeline. |   

---

#### Phase 1:
##### Software + Onboarding <b> (Weeks 0-4) </b>
--Help the team install the necessary software and create the appropriate accounts to perform their duties. This applies to technical(Figma, Python, Java, etc.) and workflow software (e.g. Slack, Jira).
--Explaining the scope of the project to the team to align effort and vision. 
Answer any questions regarding the scope of the project and being receptive to changes to the scope.

---

#### Phase 2:
##### User Research<b> (Weeks 4-9) </b>
Conduct surveys and user interviews to gather feedback about potential features and interactions within the app. 
Perform a competitive analysis and gap analysis to understand the current market and how our app can stand out.

---

#### Phase 3:
##### Design<b> (Weeks 9-12) </b>
- Ideate and narrow down potential solutions based on user feedback.
- Create an information architecture diagram that combines the brainstormed features into a cohesive user flow.
- Start sketching screens to provide a visual representation of the design.
- Work on designing low-fidelity wireframes to understand placement, sizing, and positioning of design elements. 
    - No color or stylistic elements are needed at this stage. 
    - Sole purpose is to maintain clarity in user flow and allow ability to easily change designs without undertaking intensive revisions.

---

#### Phase 4:
##### User Testing<b> (Weeks 12-15) </b>
- Conduct user tests with at least 10-15 users to gain user behavior and attitude insights. 
- Depending on testing results, revisit the design or research phase and make necessary changes. A/B Testing is another option.

---

#### Phase 5:
##### Front-End Development<b> (Weeks 15-19) </b>
- Review functional requirements with designers to ensure cohesiveness in app functionality and alignment in expectations.
- Using mobile UI components and frameworks, user interfaces will be developed alongside functionality between screens.
- Conduct testing on a regular basis.

---

#### Phase 6:
##### Back-End Development<b> (Weeks 19-25) </b>
- Review functional requirements with designers and front-end developers to ensure cohesiveness in app functionality and alignment in expectations.
- Set up MongoDB to handle user account information and functionality.
- Set up pantry inventory scanning feature.
- Set up easy sign-in (prevent signing in every time) using OAUTH.
- Configure AI for recipe tracker.
- Deploy AWS cloud to host app.
- Review app with the team and release.

---

#### Phase 7:
##### Beta Testing<b> (Weeks 25-28) </b>
- Release the app to a small group of users (~15 users) and receive quick feedback that can be implemented before launch.
- Create social media account and promotional material to gain traction and reach.

---

#### Phase 8:
##### Back-End Development<b> (Weeks 28-29) </b>
- Create a launch strategy 
- Release app on the app store.

---

#### Phase 9:
##### Back-End Development<b> (Weeks 19-25) </b>
- Monitor app KPIS (Key Performance Metrics).
- Monitor user feedback
- Continue to update the app or/and create new features based on feedback and latest trends in the market using PostHog.

---

### Strategy
#### Open-Source
Open source is a vital aspect to this project. Starting an open-source community can be intimidating due to the multiple requirements and extensive management required. To initiate this, I would propose a minimum viable community. A minimum viable community would allow me to start an open-source community with a minimal number of members. To start, commsor.com recommends I create a community member persona, which allows me to understand who my audience is so that I understand the ‘why’ behind my community (HigherLogic). I would aim for around 15-25 members to begin with. I would release a small feature to this community such as expense logging in order to seek feedback. This could be translated to beta-testing. Relying on this core community to gather feedback would be pertinent to gaining insight and making data-driven decisions. This helps me and the team understand customer needs on a deeper level and helps us guide the direction of the project accordingly. Once we start to see success with this community, I would try to scale the community and try to create a "developer community" (Stürmer, 2013). I would still retain a MVC despite creating a developer community. 

Later, I would first establish community guidelines and establish a vision for the open-source community through a readme file. After communicating with my team, I would create developer docs to inform developers about key details such as API specific information, database architecture, and the data model. I would also set up a Slack or Discord channel with assigned contributor roles so developers can discuss ideas and problems in different channels. Gauging a developer’s interest and experience will determine what contribution role they receive. On GitHub, example issues will be posted to demonstrate an example of a “good first issue”. This sets clear expectations for issue management and streamlines how issues will be addressed. Developers on my team will be monitoring the Slack channel and any Github updates to ensure cohesiveness and a safe environment. 

Nowadays, vibe coding has become an internet phenomenon and I would like to incorporate this concept in my open-source community. I would license tools such as Cursor.AI or OpenAI codex to get started. Not only would developers be interested in using these softwares, but this is another way to introduce automation to my project. Coding will become more flexible, cost-effective and accessible. An idea to incentivize developers to continue to contribute is through Github Badges. I would also have my developers live coding sessions where my developers would teach the open-source community new skills or technologies. Depending on the badge level, they would have access to these channels to learn new skills. Brainstorming new perks as individuals acquire badges would also be a next step.


#### Feedback Loop
Engaging in sprints and setting milestones is an important part of the work culture for my team. Leveraging both methods would be useful to this project. Sprints can be organized in an arbitrary amount of time. I would choose around "2-3 weeks" (Confeur, 2019). Since I have already defined time periods for each phase of my workflow map, I would integrate sprints within each phase. For example, in the design phase, the entire phase is 4 weeks. I would split this up into 2 weeks for brainstorming and ideation and 2 weeks for designing and refining. This would be a great way to visualize my team’s "WIP (Work in Progress)", an indicator of high performing teams (Confeur, 2019). Issues would be created accordingly so the team stays on track and is notified of any potential blockers. In alignment to my workflow, I would define certain tasks that need to be completed and any other task that appears during the sprint is backlogged. 

By the end of the sprint, there should be a progress update (not necessarily a demo) to show. That may be a Kanban board, a demo (if feasible), slideshow, Github issues, etc.  Forcing my team to produce a working demo at the end of each sprint may lead to technical debt. This can backlog future development cycles, especially towards front end and back end implementation, which results in wasted time, energy, and capital. Another important aspect of the feedback loop are milestones. The article talks about implementing fixed-date milestones, which I would implement to sync work between research and design, design and front-end, and front-end and back-end. Milestones help reduce risk by allocating resources in advance, and setting clear expectations from the beginning. Milestones are a great way to keep sub-teams accountable since work from one team may rely on work from another team. By staying accountable, "last minute issues are more likely to be avoided and can be addressed sooner" (Confeur, 2019). It is also important to keep milestones and sprints flexible based on urgency and size. Perhaps integrating a buffer period for a sprint or milestone is a potential option to account for any mishaps. I believe that successful milestone planning leads to more productive sprints and successful sprints reinforces optimal milestones. Utilizing sprints and milestones simultaneously but not abusing both helps focus on product over dates and deadlines (Confeur, 2019). 

Demos are imperative for our team to continue to innovate. A huge chunk of our workflow map is design and research, so the result of those phases culminates into a demo. Demos are important for this project because it allows the team to understand what works and does not work. Whether it be a Figma prototype or a simple implementation, the degree of complexity for a demo is not important. Being able to translate ideas, design, and code into a visual representation allows users to provide valuable feedback to the team. Through quasi-functioning code, alternatives can be created for different target groups. These different alternatives (a form of A/B testing), helps refine future demos and impacts the product development lifecycle. According to Joi’s notion of ‘Demo or Die’ from the MIT Media Lab, demos are the main focus ((mstem, 2014). Intense pressure and stress can arise from creating demos. For our team, when we reach out to investors or users, calls may be scheduled at any time. It is important for my team to realize the true value and significance of demos so they are not overworked and demoralized. 

As mentioned in the Joi’s 9 Principles of the Media Lab, the ‘Compass over maps’ is one of 9 principles I can use to help the team understand why demos should be created frequently (mstem, 2014). Rather than over-planning and creating different theories for how certain features of a product may behave, spending time and resources towards trying different solutions is more effective. In the long run, building is cheaper than planning and reduces the guesswork towards a better solution. As Danah mentions in this article, the point of ‘Demo or Die’ is to help “it was to help the visitor change their perspective of the world through the lens of the demo” (mstem, 2014). Demos are a way of expressing the team’s ideas, attitudes, and perspectives. Demos are not supposed to fit the world view for a user, rather challenge those assumptions and compel them to consider a new avenue. Creating ‘impact’, as Dana mentions is one of the most important outcomes from producing demos (Boyd, 2017). I would encourage my team to change their mindset towards demos. Demos do not lead to success or failure, they lead to perspective and impact. Demos lead to a greater product and shows qualities of an even greater team. 

#### Scalability
Being able to scale this app to accommodate for future user needs and increasing technical and nontechnical requirements is an essential part of this project. A prerequisite to scaling is planning. Great planning will allow the project to scale further. However, setting goals is not enough. OKRs, or objectives and key results is an effective method. According to Jira, OKRs can help push agile teams to ‘peak performance’ and ‘keep a track record of achievements’ (Atlassian, 2022). This defined method boosts team morale and keeps them motivated to maintain their standard of work. The three pillars are ‘commitment’, ‘accountability’, and ‘regular updates’ (Atlassian, 2022). One way to keep my team committed and accountable for their personal goals or team goals is by writing them down and sharing them with other members, even if they are not in their team. Sharing goals promotes transparency and trust as well as creating a sense of urgency to meet a deadline. Most importantly, feedback is given upon goal completion which is why learning is the main priority over performance. Receiving this feedback will help my team measure their progress over time and allow the team to achieve higher metrics which translates to scaling. An example of an OKR can be increasing customer acquisition by decreasing customer acquisition cost by 10% through gap analysis between our system and other competitors. Once an OKR has been set, at the end of the deadline, I can score the OKR from a scale of 0.0 to 1.0 (Atlassian, 2022). According to Jira, 0.7 means that a team has succeeded (Atlassian, 2022). 0.0 means ‘we didn’t make any progress’, and 1.0 means ‘we delivered’ (Atlassian, 2022). I realize that a score of 1.0 is not necessary for every OKR because I prioritize progress over perfection. Every OKR is a step in the learning process and the goal is to always strive for more. 

To help define OKRs, the MoSCoW prioritization method can be implemented. For each OKR, I need to define 'Must Haves', 'Should Haves', 'Could Haves', 'Will not Haves' (Brush, 2023). I want my team to mainly focus on the Must Haves in order for successful completion of a task. Maybe a Must Have is generating insights from gap analysis from at least 10 organizations. In order to increase customer acquisition, strategies from other companies must be examined to increase this metric. Without it, this OKR is not achievable. A Will not Have can maybe be building a new feature (or improving an already existing feature) to directly increase customer acquisition. Utilizing the MoSCoW method increases the granularity of my OKRs and provides more accurate estimates. My team is more focused and understands what are the main priorities for the project. 

Now in order to start the project, resource allocation needs to be defined. I may want to allocate 60% of my resources towards Must Haves, 30% towards Should Haves, and 5% towards Could Haves, and 5% towards Will not Haves. These proportions can change mid-project due to the iterative process and the agile nature of our team. According to Adriene Watt’s project management textbook, looking at ‘published estimated data’ is a way to estimate how many resources are needed (Barron et al., 2014). I may even use some project management software such as Microsoft Project to help estimate resources and constraints best fit for specific parts of my project. After analyzing published data, I would get a general baseline for how resources are typically allocated which I can use as a starting point for how I allocate resources. I would proceed to engage in ‘three-point estimating’, where I would come up with three different estimates (Barron et al., 2014). A ‘realistic estimate that is most likely to occur’, an ‘optimistic one that represents the best-case scenario’, and a ‘pessimistic one that represents the worst-case scenario’ (Barron et al., 2014). I would then take the average of the three to calculate my final estimate. I can then incorporate this estimate into my OKRs and incorporate my resource planning strategies to allocate resources towards an OKR that will make that OKR successful. To help determine the direction of the OKR, the MoSCoW method will be implemented to pre-determine team priorities. Utilizing these three methods will help scale my project to the next level. 

---

### Addressing Technical Debt
Throughout this project, technical debt is minimized throughout this project. The tools that I decided to use are industry standard and are popular for being used for app development. For design, Figma is one of the best design tools on the market. Most companies such as Spotify, Universal Studios, and AirBnB use Figma. Figma is far above its competitors and will continue to remain relevant in the industry for a long period of time with little chances of becoming replaced, therefore using Figma reduces technical debt. React is another framework that is popular for developers to use for coding the front-end interface of an application. It is one of the most popular Javascript libaries to use and has numerous UI components to choose from. React is used by companies such as Facebook and Netflix. However, React can be hard to learn without any previous JS experience. Assuming the developers I hire have JS experience, this additional learning curve may decrease productivity, lower code quality, and hence lead to higher technical debt. However, technical debt cannot be completely eliminated. 

---

### Challenges
Over time, certain coding practices and documentation will become outdated. For design, design systems and components will need to be updated to support newer versions. Existing design processes will need to be revisited and edited to create a new design playbook. Refactoring code and reevaluating design processes are timely and potentially costly. To prevent this, my team will optimize code with AI and hold meetings to review outdated code that needs to be refactored. Documenting these practices will help us to rebuild our codebase and create a more efficient and secure process to address outdated code. For design, considering different design frameworks or incorporating elements from different design systems keeps the design process flexible and agile. Reevaluating and redesigning design systems in phases will reduce the burden on the team to maintain the current designs while slowly migrating to a new design system. 

Another challenge is payment integration. Multiple payment vendors have different priorities for security features. Fraudulent activities are therefore prevalent which is why understanding security features for a specific vendor are important before sharing sensitive data. Documenting these features and validating security measures is essential beforehand. Not only is fraud important to detect, but the ability to report fraud is also a functionality that must be properly supported. While building a payment integration method, choosing the right API integration method that can handle different payment methods is key (Tranzzo, 2024). Deciding a payment method requires business context and payment infrastructure support. For CartSync, Stripe will be the preferred payment method due to its popularity, user-friendly interface, advanced security features, and wide support for global payments. According to Tranzzo, this increases system interoperability and decreases the likelihood of compatibility issues. Not being able to track incoming and outgoing data from various sources can lead to data fragmentation. Fragmented data opens up the database to vulnerabilities and hacking attacks. Another challenge regarding payment integration is currency. To position CartSync on the global market, global currency support is needed. Transactions may occur across different currencies which leads to different regulations and barriers. One solution suggested by Tranzzo is to “collect, normalize, and merge payment data in a single area” (Tranzzo, 2024). This data can be stored in a data warehouse or a cloud platform so that data can be queried independently and accessed seamlessly, regardless of currency. 

CartSync also incorporates AI to generate recipes for users based on items in their pantry. It is possible for the AI to hallucinate and generate recipes that are inaccurate or create recipes with items that are not present in a user’s fridge. To account for this, preprocessed training data needs to be present. The data needs to be validated and checked for stray values. To prevent overfitting to training data, feature selection is a simple technique that allows control over features being inputted into the system. I would implement the conventional 80/20 train-test split to maintain model accuracy and control for overfitting of data values. Using the OpenAI Generative AI model, establishing consistent results over time while ensuring these results are statistically significant will be a key marker of success. More importantly, collecting troubleshooting reports from users is key to train the AI model and help it handle edge cases. On the interface, we would make it clear users should always be aware that AI can generate inaccurate results because CartSync seeks to be transparent and build trust with its users. 

---

### Conclusion      
CartSync offers a unique value proposition to help college students manage collaborative expenses while tracking their budget simultaneously and seamlessly. Being able to view and split expenses removes unnecessary confrontation and tension between individuals. This allows users to take ownership of their finances and teaches them how to manage their personal wealth. At the same time, CartSync also promotes sustainable decision making and encourages users to learn how to cook. Through open-source contributions and feedback from the community, CarySync can continue to scale and improve its services to help users manage their expenses while being financially independent. 

---

### References     

“Distinguishing Your Online Community Personas.” Higher Logic, 7 Mar. 2024, www.higherlogic.com/blog/online-community-personas/#:~:text=Community%20personas%20are%20archetypal%20representations,meet%20each%20persona’s%20distinct%20needs. 

Stürmer, Matthias. “Four Types of Open Source Communities.” Opensource.Com, 10 June 2013, opensource.com/business/13/6/four-types-organizational-structures-within-open-source-communities.

Confeur. “Sprints vs Milestones.” Medium, Medium, 22 Oct. 2019, medium.com/@confeurhq/sprints-vs-milestones-6fe700d101f9. 

mstem. “Joi Ito’s ‘9 Principles’ of the Media Lab.” MIT Center for Civic Media, Civic Media, 24 June 2014, civic.mit.edu/index.html%3Fp=1677.html. 

Boyd, Danah. “How ‘Demo-or-Die’ Helped My Career.” Medium, Data & Society: Points, 1 Aug. 2017, medium.com/datasociety-points/how-demo-or-die-helped-my-career-89feaa5773e7. 

“Atlassian.” Jira-Align-Definitive-Guide-to OKRs, Atlassian, 2022, pages.eml.atlassian.com/rs/594-ATC-127/images/Jira-Align-Definitive-Guide-to%20OKRs.pdf?leadid=%7B%7Blead.ID:default%3DError%7D%7D&programid=%7B%7Bprogram.id%7D%7D. 

Brush, Kate. “What Is the Moscow Method?” Search Software Quality, TechTarget, Mar. 2023, www.techtarget.com/searchsoftwarequality/definition/MoSCoW-method#:~:text=The%20MoSCoW%20method%20is%20a,make%20the%20acronym%20more%20pronounceable. 

Barron, Merrie, et al. “11. Resource Planning.” Project Management 2nd Edition, BCcampus, 2014, opentextbc.ca/projectmanagement/chapter/chapter-11-resource-planning-project-management/. 

Tranzzo. “Integrating Multiple Payment Methods: Challenges and Solutions.” Tranzzo, 22 Apr. 2024, tranzzo.com/blog/integrating-multiple-payment-methods-challenges-and-solutions. 
