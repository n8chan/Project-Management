## ConnectForACause
Harshitha Vetrivel, Spring 2025
### Background
Oftentimes, in college towns like Urbana-Champaign, community is one of the most foundational pillars. One of the most important ways that communities grow is by establishing connections between local entities. The community here is a hub for various nonprofit organizations, from student-led social work to volunteer-run groups. However, several of these groups face challenges with organizing fundraising channels. Similarly, small businesses in the area struggle to efficiently find methods to engage with the community and boost their exposure. 
	
While conducting interviews with several small business owners as part of undergraduate research, I found that many of them echoed that they feel a lack of a centralized platform to connect local businesses and non-profit organizations. Most of their collaborative ventures heavily depend on word-of-mouth, cold calls, or email correspondence. These methods require manual coordination on both ends which can lead to inefficient communication and missed opportunities. Small businesses may feel hesitant to agree to partnerships with a loose structure or visibility and nonprofit organizers—often made up of volunteers or students—may not be able to allocate enough resources to initiate and manage external partnerships on top of handling internal affairs. This is further supported by research conducted by Zatepilina-Monacell which found that locally owned businesses are eager to deepen their relationships with nonprofit organizations but often lack the infrastructure to do so effectively (Zatepilina-Monacell, 2015). 

The idea for ConnectForACause emerged from this gap and aims to provide a centralized platform for nonprofit organizations and small businesses in Urbana-Champaign to establish connections, plan, and execute fundraising initiatives. Through the usage of dynamic app development tools to incorporate features like real-time event planning and direct messaging, this project hopes to serve as a sustainable and efficient way for fundraising partnerships between nonprofit organizations and local businesses to be created and maintained over time. 
### Purpose
The purpose behind this project has two main components. First, to assist nonprofits with finding and coordinating fundraising events with local businesses. Many local nonprofits—including student groups, community organizations, and service clubs—often have a difficult time arranging fundraising events with local business partners. When communication happens mainly through email or phone, plans can easily become disorganized, delayed, or fall through entirely especially when these are the same modes of communication that are used to manage other logistics for the organization. The same applies to small businesses, who may already be juggling limited staff, tight schedules, and day-to-day operations, making it difficult to consistently engage with outside partnerships or respond to scattered outreach efforts. 

Second, the app intends to give small businesses an opportunity to gain exposure within the campus community by partnering with these nonprofit initiatives. For many local restaurants, cafes, and small retail shops, these partnerships can open the doors to more than just a way to give back to the community. As Little explains, “giving back to the community directly correlates with increased customer loyalty and brand visibility,” making fundraisers a smart investment for small businesses looking to grow their reach (Little, 2023). They can also serve as a way to help these businesses attract new customers outside of their current reach and attract the student population, especially if nonprofit partnerships come in the form of student-run organizations. Getting involved in fundraisers can help these businesses mold strong bonds between local residents and students and increase foot traffic during these events to show support for causes that matter to their community. Through the app, small businesses can further promote their mission and support their community. 

By serving as a platform to facilitate these mutually beneficial partnerships, ConnectForACause hopes to support both social impact and local business engagement to ensure that community fundraising is efficient and valuable for all parties involved.

### Target Audience
**1. Nonprofits**
   
This includes student-run organizations, university-affiliated causes, and local charities. Several of these groups have to work with limited resources and face obstacles when coordinating events. ConnectForACause can give them access to a database of interested local businesses and strategies to facilitate partnerships in a more effective manner.

**2. Local Businesses**

Small businesses often look for methods to increase campus visibility. The app provides these businesses with an easier way to participate in giving back to the community while also giving them the opportunity to increase their foot traffic and customer engagement. With features like performance analytics and partnership browsing, the app provides transparency into the business’s return on investment when commiting to these fundraising opportunities. 

**3. The University of Illinois Campus Community**

This community includes students, faculty, and staff who want to support causes that are meaningful to them through their purchases or participation. While this app is mainly targeted towards helping nonprofits and small businesses coordinate their events, our calendar feature can also be a tool for the general public to see when and where events are occurring, what causes they can choose to donate to, and how to engage.

### Timeline

This project has been designed to fall under a 15-week (1-1.5 year) timeline and an ongoing feedback loop after that. Here is the scheduled timeline:

- Weeks 1–2: Project Planning
- Weeks 3–5: Design and Prototyping
- Weeks 6–11: Development
- Weeks 12–13: Testing
- Weeks 14–15: Launch

### Organization Workflow
<img width="885" alt="Screenshot 2025-05-15 at 6 48 19 PM" src="https://github.com/user-attachments/assets/667acefa-17aa-4b44-9ca8-89090949a673" />

#### Project Planning
The initial step for this project is to set a clear direction for the overall goals and scope. This involves addressing key questions like: Who are the primary users of the app? What specific problems are they facing when it comes to organizing or participating in fundraisers? What features are essential to solve those problems effectively? And how can the app balance simplicity with functionality to serve both nonprofits and local businesses without overwhelming either group?

After clarifying the goals and scope, conducting market research to investigate these questions and how they relate to existing platforms that are used for fundraising events, nonprofit outreach, or small business partnerships. This will help identify gaps to fill in terms of features, limitations, and user engagement strategies that can inform how ConnectForACause is built. 

Finally, the most important part of this step in the workflow is to ensure that we are addressing the needs and priorities of the local community. Since one of the main attractions of the app is that it is curated for the Urbana-Champaign area, coordinating in-depth interviews with local nonprofit and small business organizers to gain insight into the challenges they face and how this project can best serve them will be integrated heavily into this part of the planning process.

#### Design and Prototyping

In this step, UI/UX research will be conducted to make sure that the app meets user needs. This involves assessing design principles like compatibility across devices, usability, and simplicity. The overall goal is to create an app that makes communication between users direct and efficient to organize and plan events in a timely manner, which means less focus on being tech-savvy and more on accessibility. 

After deciding on a design strategy, there will be a transition to bring the vision into a prototype format. Mockups of various pages will be created using Figma. These pages include the nonprofit and business profile pages, event planning features, and a direct messaging interface. In addition to the visual component, we will also work on creating an interaction flow. This will give us a complete map of how different types of users (nonprofits, small businesses, vs general community members) will interact with the app and with each other. Establishing variation between different types of log-in methods and user permissions will be a key part of this phase. We will also focus on the steps that are needed to create an event, respond to event requests, and track fundraising analytics. 

#### Development

The back-end development will involve setting up the database and servers to store nonprofit profiles, small business listings, event information, and messages. The server algorithm will be implemented to handle functions like saving, updating, and organizing information related to users, events, and partnerships. Node.js will be utilized to configure real-time data and interactive features like bookings and direct communication tools.  

On the front-end, React Native will be the main tool used in order to make the app accessible and compatible with both Android and iOS platforms. A 2023 case study on Novus Bank found that React Native enabled their team to “deliver consistent user experiences across platforms while reducing development time” making it a strong fit for this project (Pagepro, 2023). The main goal here is to take the design objectives established in the UI/UX research phase and implement them in the form of features like event planning interfaces and a responsive calendar view for each nonprofit and small business. This will also cover setting up push notifications, event RSVPs, and calendar integration to elevate the user experience and reduce the need for external coordination efforts outside of the app.

#### Testing

When the working prototype is complete, it will be released to a sample group of nonprofits and local businesses who will be recruited through outreach efforts in the planning phase. The participants will simulate real-world scenarios like creating events, connecting with potential event partners, viewing fundraiser statistics, and direct messaging in the app. Qualitative and quantitative data will be collected during this phase to inform improvements and implementation going forward. The qualitative data will be in the form of survey feedback on usability, navigation, and clarity while the quantitative data could be bug or issue reports with the underlying algorithms.  

#### Launch

When preparing the app for public launch, we will publish it to mobile app stores like Google Play and the Apple App Store to make sure that all of the requirements and standards are adequately met. We will also develop marketing materials to promote the app’s mission and how it can serve local nonprofits and small businesses in the area. These could include flyers, social media, word-of-mouth, and promotion through campus community events. It would also be beneficial to begin forming partnerships with interested nonprofits and businesses who can begin to pilot their fundraising events using our app. Having applied examples through these partners can display the app’s effectiveness and further encourage other users to try the app. 

#### Feedback

After launching the app, there will be an extended focus on gathering ongoing feedback. User engagement data and direct feedback loops will inform how the app evolves over time with its future iterations. The development team will work to incorporate in-app feedback tools like quick surveys, rating prompts, and bug reports to gather data from our users. By identifying issues in real-time, we can fix bugs and refine our app to better fit our audience’s needs in an efficient manner. Feedback cycles will be incorporated as a part of our open-source strategy with users being encouraged to contribute ideas or even code as part of our open-source roadmap. This phase ensures that ConnectForACause remains adaptable, user-centered, and aligned with Urbana-Champaign’s fundraising and partnership needs.

### Strategy
The underlying strategy behind ConnectForACause is focused on addressing the crux of this local issue with accessible tools, a clear design, and space to improve. The approach is rooted in three main ideas: community impact, simplicity, and scalability.

- **Community Impact:** The app is built for the Champaign-Urbana community, where student orgs and local businesses are active but often face a disconnect in terms of fundraising. By targeting a community that is centered around a university, this app starts with a concentrated audience that regularly holds events and supports local causes.
- **Simplicity:** Tools like React Native help us build quickly for both iOS and Android, and features are designed to be intuitive with minimal clutter and efficient event planning, messaging, and partnership matching.
- **Scalability:** The long-term goals for this app involve many evolutions and iterations over time which requires scalability. While this app is launching at UIUC, we hope that this model can work at other universities or small towns. Future updates could include flexible analytics or location-specific features, as long as future iterations maintain the same goal: making it easier for nonprofits and businesses to team up on fundraising.
### Open Source Model
ConnectForACause is designed to be an open-source project to maintain transparency, collaboration within the community, and continuous growth. In order to reach these goals, we follow an open source model to define how the project is developed, maintained, and improved over time.

Firstly, the project’s main source of code will be made publicly available on a code workflow like GitHub, allowing contributors to view, suggest, and incorporate necessary changes. GitHub Projects and Issues can be used for more than task management, but to also provide exposure on real-time development, upcoming feature integration, and any issues. This allows any contributors, from developers to designers to community members, to openly participate in constructing the project’s future.

Modular design is also a key component of this project which gives different contributors to zone in on specific aspects of this app rather than feeling the need to assess the entire system. This results in more efficient collaboration because there is less of a technical barrier for interested contributors to get involved in the project.

For any successful open-source project, documentation has to be treated as a top priority. This can come in the form of upholding standards for code comments, setup manuals, onboarding resources, and community guidelines. These resources will allow contributors to get  a clear understanding of how they can get started, how key decisions are made, and the process for reviewing contributions. 

By keeping the development process transparent, ConnectForACause invites collaboration not just from other developers, but from nonprofits, businesses, and students who can offer insight into what features and improvements are truly valuable to their priorities and needs. This open source model promotes sustainability, adaptability, and long-term impact to align with the very values of the communities the app is built to support.
### Technical Debt
**1. Use of Free or Temporary Tools**

In the initial phase, the project may utilize free tools and services to keep costs low. While this is practical for prototyping, these tools may not scale well or offer enough customization for long-term use. In order to address this, these tools will be flagged early, and long-term replacements will be thoroughly researched and integrated into the final project before launch.

**2. Inflexible Algorithms**

Early versions of the app may include hard coded algorithms or workflows that only serve a narrow scope. When code is not written modularly, it tends to be challenging to scale or adapt when expanding to other campuses or cities. To prevent this issue from arising, development teams will be given heavy training to ensure modular and reusable coding practices from the get go to keep the workflow as clean and dynamic as possible.

**3. Shortcuts in Implementation**

Oftentimes, in order to speed up the timeline of the project, teams tend to overlook complex designs or skip critical features like advanced error handling, form validation, and/or accessibility standards. This may result in a quicker implementation process but can lead to drastic effects in the long-term lifecycle of the project. Flagging these shortcuts through GitHub issues with various labels to indicate technical debt will allow them to be reviewed in a regular manner. 

**4. Incomplete Testing Methods**

Beginning stages of the testing process may limit their scope to only a few edge cases, which can cause reviewers to overlook bugs as the project continues to grow. A testing process that is comprehensive and holistic in nature with manual intervention and continuous review can result in a project that is more successful and feasible in the long run. 

### Challenges
**1. Engaging Users**
   
Nonprofits and small businesses tend to operate with limited time and resources. Convincing them to adopt a new platform, especially if they’re used to phone calls, email, or in-person planning. For users to be engaged the app will require clear communication, onboarding support, and immediate perceived value. 

**2. Accessibility vs Functionality**

One of the project’s goals is to be easy to use, especially for users who may not well versed with technology. However, we also want to ensure that the needs of both nonprofits and businesses are met (profile customization, analytics, scheduling tools). The app must work hard to preserve a balance between maintaining a simplistic interface and still having valuable functionality. 

**3. Long-term engagement**

We may run into challenges getting our users to continue using the app. In order to combat this, features like event success tracking, automated matching systems, and analytics tracking will be fundamental to sustaining user engagement over longer periods of time.

**4. Funding**

Since the app’s main goal is to be a community-centric tool, we must find a way to make revenue from our efforts in a way that does not hinder our accessibility. This can come in the form of ads, premium features, or sponsorships which will need to be tested in developmental phases to assess alignment with user needs.

### Conclusion

In summary, the plan for the development of ConnectForACause was formed to help nonprofits and local businesses connect and coordinate fundraising events without the hindrance of scattered communication and excessive manual efforts. Streamlining communication and planning in one central location addresses these common issues and promotes collaboration and exposure for both parties. Using open source principles allows our project to grow via user feedback, intentional feature design, and long-term flexibility. 

### References

Infographic: Small Business Charitable Giving - Big Impact on Local Communities | SCORE. (n.d.). Www.score.org. https://www.score.org/resource/infographic/infographic-small-business-charitable-giving-big-impact-local-communities

Little, B. (2023, April 30). The Influence and Impact of Small Businesses on Community - Greater Phoenix In Business Magazine. Greater Phoenix in Business Magazine. https://inbusinessphx.com/philanthropy/the-influence-and-impact-of-small-businesses-on-community

payroll@paysmartpa.com. (2024, August 16). The Positive Impact of Giving Back: How Community Involvement Builds a Positive Reputation for Small Businesses - PaySmart Payroll Services. PaySmart Payroll Services. https://paysmartpa.com/blog/the-positive-impact-of-giving-back-how-community-involvement-builds-a-positive-reputation-for-small-businesses/

React Native Development for Novus Bank | Case Study by Pagepro. (2023). Pagepro.co. https://pagepro.co/case-studies/novus-world

Zatepilina-Monacell, O. (2015). Small Business–Nonprofit Collaboration: Locally Owned Businesses Want to Take Their Relationships With Community-Based NPOs to the Next Level. Journal of Nonprofit & Public Sector Marketing, 27(2), 216–237. https://doi.org/10.1080/10495142.2015.1011511

Zavazava, T. (2022). Project Management Methodologies for Software Development in Startups. DIVA. https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1800600&dswid=1865
