Christy Goon IS340 Final 
# Linker - An Open-Source Development Project 
## 1. Overview
### 1.1 Purpose of Linker
Linker is a job application platform that reimagines the hiring process by integrating the intuitive swiping and matching features of the app Tinder with the professional networking concepts of the website LinkedIn. The objective is to create an engaging and efficient way for employers and job seekers to connect, ensuring that better opportunities reach the right candidates. Linker, as a smartphone app, will result in simplifying and facilitating the job search experience for both the job seeker and employer. Linker aims to also foster more meaningful professional relationships, while reducing barriers to employment, which could be based around age, race, and gender.
Linker will operate as a mobile application available on both Android and iOS to ensure accessibility for a wide range of users.
### 1.2 Key Points of Solution in Linker’s Model
- Inclusive & Bias-Free Job Matching: Linker merges the professional utility of LinkedIn with Tinder’s intuitive swipe-to-match feature, promoting equitable access to opportunities through anonymized profiles (no names, photos, or demographic info) to reduce bias and encourage diverse hiring.
- User-Centered Design & Accessibility: Designed by university students prioritizing accessibility and inclusivity, Linker offers a minimal, intuitive interface that reduces job search overwhelm with relevant matches and a familiar swiping experience.
- Dual Audience Value: Linker benefits both employers and job seekers—employers build more innovative, diverse teams free from unconscious bias, while job seekers enjoy a fairer, faster, and more tailored application experience, accessible via mobile on both iOS and Android.
---
## 2. Project Vision
### 2.1 Overview of the Employment Landscape 

Over the years, the introduction of technology has transformed traditional employment services and procedures, through the implementation of many different website developments for networking, job-hunting, and professional development. This redefines how individuals interact with the employment market, with hiring managers seeking optimal talent and job-seekers reevaluating their market. However, the automation of A.I. in the industry has left many approaches to interpersonal relationships afloat. 
Now, industries and their job markets struggle to encapsulate the efficiency of the typical application process on both ends of the spectrum. With more applications flooding the market, it often enables hiring managers to automate their selection processes. These automation processes can be harmful in the process of hiring, as it allows exceptions to fall through the cracks of resume filtration. In addition, those looking to find new opportunities have a hard time applying towards active job applications, with little to no experience, biases in the A.I. resume filtration systems, or simply do not have enough time to apply. By streamlining the process with Linker, both the hiring managers and job-seekers will reap the benefits of an inclusive algorithm with 
matchmaking and faster processing times for an application process.

### 2.2 Significance of Opportunity
As more individuals strive to further their careers, the current  limitations of existing job platforms, especially those driven by AI filtration systems, have become increasingly apparent. These systems often introduce biases that unintentionally exclude capable candidates based on age, race, gender, or non-traditional backgrounds. 
By prioritizing interpersonal connections and anonymous, skills-first profiles, Linker promotes equity and inclusivity in the hiring process. It addresses the growing demand for tools that not only streamline job searching, but also foster meaningful professional relationships. By including the familiar design patterns from widely used apps like Tinder, Linker also reduces the learning curve and increases user adoption of a new application. 
In a market increasingly focused on diversity, fairness, and innovation, Linker will stand out as a competitor, quickly able to streamline the process and quality of candidates to suitable careers.

---
### 2.3 Overall Project Objectives
- **Develop a Cross-Platform Mobile App with Anonymized Matching Capabilities**
Objective: Build the core Linker application using open-source frameworks to support both Android and iOS, with Tinder-style swipe functionality and anonymous profile matching
- **Integrate an Open-Source Backend to Support Secure and Scalable Data Handling**
Objective: Use scalable open-source tools like to manage user data, match logic, and anonymization securely.
- **Ensure Inclusive Design and Accessibility Compliance**
Objective: Apply inclusive design principles using open-source UI libraries and ensure accessibility standards are met to accommodate a diverse user base.
---
## 3. Target Audience & Stakeholders 
### 3.1 Target Audience 
It is important to understand the target demographic of Linker. In the current state Linker aims to provide services towards:
- **Job Seekers** - Individuals from diverse and non-traditional backgrounds seeking equitable access to career opportunities, especially those frustrated with biases in conventional hiring platforms.
- **Employers & Recruiters** - Organizations and hiring managers aiming to build more inclusive, diverse, and innovative teams by reducing unconscious bias and expanding beyond traditional candidate filters.
- **Young Professionals & Students** - Tech-savvy users familiar with swipe-based apps, looking for a more intuitive, mobile-friendly way to connect with job opportunities.
### 3.2 Stakeholders 
It is important to understand the target demographic of Linker. In the current state Linker aims to provide services towards:.

- **Job Seekers** - Individuals from diverse and non-traditional backgrounds seeking equitable access to career opportunities, especially those frustrated with biases in conventional hiring platforms.
- **Employers & Recruiters** - Organizations and hiring managers aiming to build more inclusive, diverse, and innovative teams by reducing unconscious bias and expanding beyond traditional candidate filters.
- **Young Professionals & Students** - Tech-savvy users familiar with swipe-based apps, looking for a more intuitive, mobile-friendly way to connect with job opportunities.

---
## 4. Open-Sourcing Strategy 
### 4.1 Leverage Open-Source Frameworks for Development
**Figma – Front-End Development and Prototyping**
Figma serves as a collaborative, cloud-based UI/UX design tool, allowing designers and developers to prototype, share, and iterate on user interfaces in real time—ensuring consistency and faster front-end implementation.
**React Native – Back-End App Development**
React Native allows us to build a single codebase that works on both iOS and Android, saving time and resources. As an open-source framework backed by strong communities (like Facebook) it ensures ongoing support, performance optimization, and access to reusable UI components.
### 4.2 Incorporating Open-Sorce Libraries for Core Features 
Libraries like react-swipeable (for swipe gestures), Passport.js (for authentication), and Tailwind CSS (for responsive and accessible UI) accelerate development by providing tested, reliable solutions for essential features—helping us focus on app logic and user experience instead of building from scratch.
### 4.3 Fostering Community Collaboration 
**Discord – Open-Communication Platform**
Use Discord as a centralized communication hub for the development team and contributors, facilitating real-time collaboration, support, and community engagement.

**Github – Project Hosting Platform**
Use Github to host the project enabling open collaboration, where developers can contribute code, report issues, and suggest features. This increases development speed, improves code quality through peer review, and aligns with Linker’s values of openness, accessibility, and inclusivity.

---
## 5. Technical Debts to Consider
One of the technical debts that is to be considered in the development of an app like Linker would be the optimization of the technical stack used for frontend and backend development. For frontend development, there is an initial decision to make with what platform the developers would work on, such as a cross-platform development that includes both Android and Swift properties, like React Native, but this might create debt with handling platform specific optimization. On the other hand, the development team could start by choosing either Swift(iOS) or Kotlin (Android) for native development, but this could propose higher initial development costs, but less debt relating to performance issue maintenance.

For the backend development, using something like Firebase or Supabase may introduce vendor lock-in, making it harder to migrate later or change setup later for the developing app. Another option would be opting for Node.js, Python (Django/FastAPI), or Ruby on Rails with a relational database like PostgreSQL ensures flexibility, but might require more setup, and therefore more people to upkeep the applications.

To minimize these problems, the team could opt for a more flexible tech stack by choosing something like React Native to minimize development time while ensuring a solid performance foundation and also adopt Node.js or Django with PostgreSQL to maintain long-term backend flexibility, which doesn't lock the realm of expansion for an app that is aimed to exponentially grow with time.

In future development, more factors to consider for the team involve platform optimizations and library framework maintenance.

React Native is great for shared code but often struggles with platform-specific features (e.g., animations, camera access, and deep OS integrations), which affects the U.I/U.X aspect of the application. This means that over time, the need to implement native modules in Swift/Kotlin could lead to fragmentation. In addition, React Native relies on many third-party libraries, which may become outdated or unsupported. This could pose a debt overtime, as major updates to React Native (e.g., architectural changes like Fabric and TurboModules) often break compatibility, requiring extensive refactoring for the upkeep of the app.

For the backend development, Node.js is single-threaded, which might struggle under high concurrency loads unless architected properly with worker threads or microservices. If Django is chosen, scaling beyond a certain threshold (especially real-time features) may require additional infrastructure (e.g., Celery workers, caching with Redis). In addition, database scaling limitations can occur within PostgreSQL. Overtime as data volume grows, indexing and read-heavy operations may require replication, sharding, or migration to a distributed database, which can cut into costs to transfer for newer versions, or a newer program all-together.

---
## 6.1 Timeline Projections
### 6.1 Mindmap + Workflow Mapping
![Mindmapping](https://github.com/user-attachments/assets/138830aa-c320-42d4-b14b-e0eb8196da72)
![Linker App Development Workflow](https://github.com/user-attachments/assets/49bc1a4c-ba86-4bef-9cd2-42c7ec939ec7)
![diagram-export-5-6-2025-1_49_59-AM](https://github.com/user-attachments/assets/aa23d21b-2a37-4566-9e3e-eb1b8477121d)

Phase 1: Planning & Research (Weeks 1–2)

- Define product goals & core values (inclusivity, bias-free)
- Competitor analysis (LinkedIn, Tinder)
- Create user personas (Job Seekers, Employers)
- Finalize feature list (swipe match, anonymous profiles, etc.)

Phase 2: Design & Prototyping (Weeks 3–4)

- Build wireframes and user flows in Figma
- Conduct feedback sessions with test users
- Create high-fidelity mockups
- Define accessibility requirements 

Phase 3: Frontend & Backend Setup (Weeks 5–7)

- Frontend: Set up Figma project, implement navigation, onboarding, and swiping UI
- Backend: Configure Node.js and React Native , user auth, and anonymized profile handling
- Integrate Figma design assets
  
Phase 4: MVP Development (Weeks 8–10)

- Connect frontend to backend APIs
- Implement match logic and profile reveal triggers
- Basic chat or connection request feature
- QA testing, bug fixes
  
Phase 5: Community & Collaboration (Weeks 11–12)

- Launch GitHub repo (with contribution guide & issue templates)
- Set up Discord server for contributors & testers
- Begin collecting open-source feedback
  
Phase 6: Testing & Launch Prep (Weeks 13–14)

- Conduct user testing (accessibility, usability)
- Optimize for performance and platform-specific issues
- Prepare launch materials (store listings, screenshots)
- Launch on Android & iOS (Beta or limited release)

---
## 7. Conclusion 
This process not only aims to aid students and individuals with unconventional backgrounds in career searching, but also gives advantageous benefits towards recruiters, streamlining interview processes by implementing an intuitive swipe-to-match foundation. This can keep both parties engaged in their job search, lessening the cognitive load that traditional screen usage and resume reading already take. 

Overall I believe that the project offers a well-defined, phased approach ensures steady progress, accountability, and adaptability throughout the 14-week timeline. Including a balanced tech stack that was planned considering technical debts such as maintenance and practical inclusion practices. Choices like React Native and Node.JS/PostgreSQL can help minimize this debt while supporting long-term scalability and maintainability. Figma and Discord enable real-time collaboration, while open-sourcing invites community engagement and iterative improvements.

Linker, as an open-source project, proves to go beyond the current established norms of industry standards in the job application process. By foregoing the process of current A.I. resume readers that implicitly instill biases within the application process, Linker aims to mitigate the potential losses of great connections that can happen among people. With most of the focus being on open-sourcing for the project, there is no better community to help share their expertise from any field in diversifying the pool for creating an A.I. framework that channels biased factors in resumes outside of skill-matching preferences of recruiters and hiring managers. 

---
## 8. References and Citations 
The Collaborative Interface Design Tool. Figma. (n.d.). https://www.figma.com/

Gilbert, R. M. (n.d.). Inclusive Design for a Digital World. SpringerLink. https://link.springer.com/book/10.1007/978-1-4842-5016-7

Introduction · REACT NATIVE. React Native RSS. (2025, April 14). https://reactnative.dev/docs/getting-started

Milne, S. (n.d.). AI tools show biases in ranking job applicants’ names according to perceived race and gender. UW News. 
https://www.washington.edu/news/2024/10/31/ai-bias-resume-screening-race-gender/

The Open Source Firebase Alternative. Supabase. (n.d.). https://supabase.com/

Open tech advocacy for a new era. Mozilla Foundation. (2024, November 15). https://www.mozillafoundation.org/en/blog/open-tech-advocacy-for-a-new-era/ 

*ChatGPT was also referenced and aided in grammar checks and helped me develop the imaginary timelines and figureheads for workflows. 
