Reimagine: Reducing the cost of education with reuse! 

Taylor Chan, IS 340, Section B, Spring 2025

**Introduction**

*Background:*

In the United States, many K-12 schools are underfunded. This phenomenon places strain on educators, leaving many teachers paying out of pocket for additional classroom supplies. In fact, they spend $673 on average each year outside of what the school provides (Association of American Educators, 2023). Moreover, the average one-child family spends almost $600 every year on class materials (Capital One Shopping, 2024). When families cannot afford these supplies, there is a potential for low student self-esteem and diminished learning outcomes. For this reason, schools would benefit from more accessible, budget-friendly resources.
In order to combat this issue, we can leverage creative reuse stores. Creative reuse stores collect donations for reconsumption of items that would otherwise end up in the landfill. Many of these stores offer educator discounts, selling these donations for little or even no price for teachers. Although some of these items are practical within a classroom environment, like pens, paints, and markers, the majority require more imaginative and clever repurposing. Examples include film canisters, bottle tabs, and cassette tapes. Therefore, it can be challenging for instructors to figure out how to utilize these supplies within their classrooms. This issue contributes to a problem faced by creative reuse centers as well. Similar to thrift stores where “only between 10 and 30 percent of second-hand donations to charity shops are actually resold in store” (Franklin-Wallis, 2024), many donations end up going to waste. Although donors and nonprofits have good intentions, their impact can be hindered if considering the inventory actually resold and redistributed. This provides the grounds for a possible solution: Reimagine. 


*Project Vision:*

Reimagine is an open-source project meant to address issues within the current educational and environmental landscape. By working with **local reuse nonprofits**, the developed platform aims to help **K-12 educators** discover and gather resources for creative classroom activities and projects. Reimagine is different from other online instructional resources due to direct collaboration with creative reuse nonprofits. With this set-up, schools will receive access to resources from these organizations. The exchange of materials will help lower the financial strain of education in communities, while promoting and inspiring sustainable behaviors. 

*Core Features:*

Reimagine will have four main features within its interface.

1) **Project Library:** This area of the interface will house a database of projects and activities for teachers to incorporate into their classroom. Each project will have tags for subject, grade level, and used materials to allow for greater efficiency of use. As such, educators can more easily find ideas that more closely align with their goals and curriculum. 
2) **Inventory Checker:**  Within this feature, educators will be able to search for specific resources and see if nearby organizations have them in stock for purchase and/or pick-up. 
3) **Messaging Center:** The messaging center will act as a built-in way of correspondence between educators and nonprofit organizations. Within this feature, educators can request holds or reservations for select items. 
4) **Customized Interface:** Reimagine has two main user groups: one from education space and one from the nonprofit space.As such, designers will create a more tailored user experience to the type of account made with Reimagine. During the onboarding and sign-up process, users will be able to make an education or a nonprofit account because the intentions behind the interface’s use are different for them. For instance, there will be a way for nonprofit members to connect their stock to Reimagine. They will have editing privileges to the inventory, while educators and administrators would not have these capabilities.


*Technology Stack:*

The Reimagine technology stack will encompass programs across software development, design, and marketing teams within the project. The product manager will work with each team to research and determine the most effective tools for the intended project. This careful consideration from the get-go will help minimize the amount of technical debt accrued. I acknowledge that it is impossible to figure out the best possible collection of programs, as technology trends and standards rapidly change. There are updates to existing platforms and releases of new platforms. However, I would like to prioritize perceived longevity and scalability when creating the technology stack, reducing the need for technology migration. It will take money and time resources away from other developments if the platform will need to switch over to other methods. The complexity of the swap only grows as the complexity of the project grows (Alicea, 2025).

Reimagine will not only need to navigate technical services and products but also collaboration channels. This will act as another proactive measure against technical debt, as contributors often make mistakes and errors when they do not communicate within or across teams. I will prioritize longevity and scalability in this area as well. I envision this project to live for many years to come. Over the course of Reimagine’s development and growth, its community will increase in size. Therefore, the team will need to agree on communication platforms that will survive both time and growth. Again, this will avoid the need to transfer methods later.

<img width="2696" alt="Proposed_Technology_Stack" src="https://github.com/user-attachments/assets/1f8ef74a-96d7-4f46-a6f0-27b46919e817" />
Figure 1: Proposed Technology Stack


**Reimagine v1**

*Initial Scoping*

Reimagine’s initial release will be narrow in scope with a focus on implementation in the Chicagoland area. The first partner for the Reimagine team will be the WasteShed. By concentrating efforts on only one nonprofit, the team can create an optimal user flow of processes. If the Reimagine team collaborated with multiple reuse centers at once, it would be difficult to manage conflicting needs and operations. This could cause the team to miss issues that would be hard to correct later on, since the team might prioritize the bigger picture. In other words, overly large-scale projects tend to lose out on quality given time constraints. Moreover, the WasteShed would be an ideal first partner because they have two locations: Chicago and Evanston, IL. As such, the Reimagine team would gain access to consultants with knowledge of the scalability of features. To exemplify, managers from the WasteShed could give insights on how the database of the inventory checker could work to support different locations.

*Workflow Overview*

The projected release of Reimagine will happen within the timeframe of three quarters. 

**Q1- Proof of Concept (January - March)**
1) Consultations and Research (Weeks 1-3): The project will kick off with interviews with key stakeholders, including curriculum developers, administration boards, and nonprofit managers. The goal of this phase is to gather requirements, concerns, and information to ensure the interface will accommodate current systems in place. Team members will document data points gathered for future reference. Team members will also decide upon a technology stack.
2) UI/UX Design (Weeks 4-6): Based on the qualitative research from the weeks prior, the focus will shift to designing the platform. The design team will create user flows and architectures to organize the interface. They will also sketch out possible layouts and formats for the proposed features. By the end of this stage, the designers should have high-fidelity prototypes for the software team to reference, highlighting possible interactions between the screens.
3) Front-End, Back-End, and Database Development (Weeks 7-11): The engineering team will build out the front-end interface based on the UI/UX prototypes. Simultaneously, back-end developers will figure out the database architecture as well as create an API that pulls the information from the database. There will be databases for each of the features: Project Library, Inventory Checker, and Messaging Center). In this portion, it will be important to reference information from the consultations on how inventory is maintained at the WasteShed.
4) Front-End and Back-End Integration (Week 12): The software engineering team will fully integrate the front-end and the back-end to create a fully functional prototype.
<img width="540" alt="Q1 - Workflow" src="https://github.com/user-attachments/assets/93c0c71f-b720-41c3-8e8f-a51e872837ee" />

Figure 2: Q1-Focused Workflow Diagram of Reimagine v1

**Q2 - Testing and Iteration (April - June)**
1) User Testing (Weeks 13-17): During these weeks, the Reimagine team will carry out usability testing of the platform. To do this, the team will use a mixed-methods approach to gather more qualitative and quantitative feedback. There will be talk-aloud sessions as well as use of the UserTesting software.
2) Documentation and Decision-Making (Weeks 18): The team will analyze the findings of the user testing and create key insights to work with moving forward. The team will also document why decisions were made, so the rationale will be there to look back on.
3) Brainstorming and UI/UX Design (Weeks 19-20): The design team will make corresponding screens based on the findings from user testing.
4) Software Development (Weeks 21-24): The software team will implement changes suggested from the UI/UX team. During this phase of software development, the team will also focus on refactoring and cleaning prior code. Team members can also add documentation to explain how certain lines of code function.
5) Project Library (Week 13-24): While an additional iteration of development, other team members will focus on building out the project library. They will brainstorm classroom activities, while working with curriculum developers to ensure needs of the educational community are met.
<img width="3216" alt="Q2- Workflow" src="https://github.com/user-attachments/assets/4ab223f4-6d33-4b97-8fe4-b8237fef7ad6" />
Figure 3: Q2-Focused Workflow Diagram of Reimagine v1

**Q3 - Launch (July - September)**
1) Marketing (Weeks 25-30): The Reimagine team will create a marketing campaign and strategy to draw attention to the platform. The design team will create marketing materials on Canva to release on different social media accounts. Since the primary audience upon initial release will be those in the Chicagoland area, the team will reach out to corresponding interest groups and unions, such as the Chicago Teachers Union. The goal will be to connect the project with its target audience: K-12 educators.
2) Launch (Week 31): Reimagine is released to the public!
3) Release Analysis (Week 32-36): The team will determine whether the application is meeting key performance indicators, such as account sign-ups and materials picked up. From there, the team will look into strengths and weaknesses to develop a strategy for improvement.
4) Community Building (Weeks 32-36): At the same time, the team will move on to community building efforts (see below).
<img width="3040" alt="Q3 - Workflow" src="https://github.com/user-attachments/assets/4520d4f2-f787-488a-98b1-992c53c101ca" />

Figure 4: Q3-Focused Workflow Diagram of Reimagine v1

**Technical Debt**

In the development of the first version of Reimagine, I would like to shed light on potential sources of technical debt. First, the project timeline imposes time constraints on the team. Although my vision for the initial release is smaller in scope, it can still be challenging to complete the work as outlined by the workflow diagram. To keep up with deadlines and expectations, team members may rush their work which can negatively impact the quality of what they complete. This can be exhibited in sloppy scripts, missed documentation, or careless errors, which someone will need to spend their time fixing later on. As such, one strategy to avoid this is rescoping by extending the timeline or descoping by removing features. To figure out which is better for the project moving forward, a product manager will need to reflect on what the MVP truly is.

In addition, team members might only associate progress with novel contributions to the project. As such, they might spend less time on correcting and optimizing previous work. This can lead to code smells, which describe unrefined and inefficient programs. To address this source of technical debt, I propose task delegation during Q2. While some members of the team focus on new features, others will focus on improving existing ones. For instance, software developers could be assigned to refactoring tasks to short the run-time.
Generally, it is important to be prepared for unforeseeable circumstances. For instance, founding team members may not be able to stay onboard for the entire length of development due to changes in commitments and priorities. If a well-versed contributor is no longer available, the rest of the team might be in hot water because they can lose out on knowledge of the system. In order to minimize losses within this scenario, it is important to keep documentation. By keeping thorough notes, it will be easier for new and existing members to fill the gaps of the contributor lost.   

**Community Building**

Successful projects need to be built from the ground up; they need to have a solid foundation before expansion and extension. As mentioned in Lecture 8, “to have an open-source community, you must first build an open project, then community” (Alicea, 2025). Therefore, the Reimagine team will shift to growing the community after the initial launch. The Reimagine community will be hosted on Github where it will be easy to track changes and contributions.


*Community Onboarding*

In order to accommodate new members into the community, contributors will develop a streamlined onboarding process. It will make it easier for newcomers to find their place within the community. The goal for this onboarding process is for it to be clear and straightforward, so new members feel caught up with project developments. Contributors will create README files and discussion forums for commonly asked questions (Alicea, 2025). In addition, there will be a code of conduct that communicates expectations within the community.

*Role Hierarchy*
	
Members can join different roles based on their skillset, such as design and software development. Within these categories, team members have the potential to hold different roles, which  might include “leader, maintainer, committer, contributor, and user” (Peters & Ruff, n.d.). This structure portrays a tiered responsibility structure where more experienced members have more privileges. This also allows new members to learn the ropes from mentor figures.

*Kanban Boards*

Kanban boards will already be in use during the development of Reimagine v1. However, contributors will continue to use this tool to help manage a larger community. The Kanban board will use tags to indicate what type of member can take on a given task. This will help new users jump right in as well.

**Sustainability**

*Altruistic Focus*

Reimagine’s impact touches on two widely held societal values: education and the environment. If the Reimagine team can convince prospective and current community members that this project makes a positive contribution to both of these spaces, I believe that we can avoid project decay. When members resonate with a project’s impact and mission, they have a greater sense of purpose and motivation towards the work. This can help sustain the project, as more people will want to help the greater good.

*Continuous Improvement*

Moreover, I believe that the Reimagine community should uphold a growth mentality towards the project. In other projects, leaders might push their team towards excellence and perfection. Although this is not an inherently bad culture, it can be demoralizing for members (Alicea, 2025). Friction and pressure from this work model might manifest in contributor burn-out, which can be detrimental to the progression of the project. For this reason, the Reimagine community will be built upon a continuous improvement model instead. This type of atmosphere will also inspire creativity within feature development, as the community will be more open-minded to different approaches and avenues. 

*Regular Support*

Finally, regular support within Reimagine’s community is essential to combating project decay. Project decay can stem from disengagement from contributors and users, so addressing the needs of both parties is important. On one hand, contributors will need to have access to readily available help and documentation. This can come in the form of messaging, forums, or bots. If contributors cannot receive assistance in a timely manner, their frustration will fester. This could potentially lead some contributors to leave the community. On the other hand, users will need to be provided with regular support if Reimagine wants to continue to grow. Reimagine cannot shut down operations because it will worsen the user experience and interactions with the platform. For example, if contributors do not fix bugs in the website, users will be left with a bad impression.

**Conclusion**

Overall, Reimagine is an open source project which intends to improve educational quality and outcomes in underfunded school districts through an environmentally-friendly approach. Reimagine will be built upon trust and collaboration, pillars of open source models. By standing by these principles, Reimagine becomes a space where voices are heard and supported. Through careful planning, coordination, and management, this project has the potential to unite communities across the United States. 

**Works Referenced**

Alicea, B. (2025). Lecture 5 [PowerPoint Slides]. Canvas. www.canvas.illinois.edu  
Alicea, B. (2025). Lecture 8 [PowerPoint Slides]. Canvas. www.canvas.illinois.edu  
Alicea, B. (2025). Lecture 9 [PowerPoint Slides]. Canvas. www.canvas.illinois.edu  
Alicea, B. (2025). Lecture 10 [PowerPoint Slides]. Canvas. www.canvas.illinois.edu  
Alicea, B. (2025). Lecture 18 [PowerPoint Slides]. Canvas. www.canvas.illinois.edu  
Alicea, B. (2025). Lecture 20 [PowerPoint Slides]. Canvas. www.canvas.illinois.edu  
Alicea, B. (2025). Lecture 23 [PowerPoint Slides]. Canvas. www.canvas.illinois.edu  
Capital One Shopping. (2024, July 14). Back-to-school shopping statistics (2024): Yearly Sales Data. Capital One Shopping. https://capitaloneshopping.com/research/back-to-school-shopping-statistics/#:~:text=The%20average%20household%20budgeted%20%24890.07,back%2Dto%2Dcollege%20shopping.
Franklin-Wallis, O. (2023, July 20). What really happens to the clothes you donate. GQ.   https://www.gq.com/story/oliver-franklin-wallis-wasteland-excerpt
Peters, S., & Ruff, N. (n.d.). Participating in open source communities. Participating in Open Source Communities. https://www.linuxfoundation.org/resources/open-source-guides/participating-in-open-source-communities


