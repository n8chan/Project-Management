# OpenStudy: Leveraging Open Source for Campus Study Spaces

## Project Overview
OpenStudy is an open source project for students to easily identify available study spaces on campus. The project was inspired by a personal pain point that I found many other students related to as well. Which is the lack of readily available spaces to study between classes. Using real-time data aggregation OpenStudy simplifies students' academic experiences. This open-source project is managed and developed primarily by student volunteers.

## Project Objectives
This project encompasses several objectives designed to benefit both students and developers involved in it:


- **Real-time Study Space Tracking:** Aggregation and display of data about classroom availability.
- **Community Engagement:** Foster a vibrant community of student developers' contributions through open-source work.
- **Marketing and Adoption:** Drive student adoption through effective marketing strategies.
- **Educational Opportunities:** Provide student developers practical experience and opportunities to engage in collaborative software development.
## Project Management Approach


### Open Source Principles
The OpenStudy project fully embodies open-source principles. With an emphasis on transparency, collaboration, and community-driven development. We use Github for collaboration and versioning.


### Repository and Version Control
GitHub is the primary repository and version control system. This ensures organized project history, making it so much easier for student developers to work together.


### Agile Development Methodology
This team uses Agile practices. The Agile methodology breaks development into iterative phases where each phase has clear deliverables. Due to our personnel our sprints are structured to align with university semesters, with reasonable goals so that if we are missing a student or two for finals, we can still continue to make progress.


### Phased Development

![Alt text](https://github.com/OREL-group/Project-Management/blob/main/FINAL%20PAPERS/OpenStudyProcessDIagram.jpg)
- **Phase 1 (Week 1-2): Research Needs, Understanding Student Study Patterns**
 We plan to start with a short survey promoted through residence‑hall group chats, and Instagram stories. We'll ask students how often they hunt for space and when that is the most diffcult. At least is 100 responses would be enough for so they we can feel confident in our decisions for our target audience.

- **Phase 2 (Week 3-4): Campus Data Collection, API Exploration**
Once we understand our users. We can turn our attention the schedule data. We will make a formal request to the university for a read‑only API tokens or even nightly CSV exports from campus IT. Another option could be to use lightweight Python web scrapers. It will be nessacry to  publish a Room Availability Schema that normalises fields such as start_time, end_time, building_code, and capacity. Then we will need to test our api calls making sure it meets a minimum success rate of least 70% of buildings. Throughout all this we will document each integration for open source.

- **Phase 3 (Week 5-6): UI/UX Design, Cloud Provider Choice**
Phase three we will focuse on the design and look of Openstudy. The main goals of the diesign is for it to feel responsive and clean overall. At this point we should understand the scale and needs of our project enough to decide on an appropriate cloud provider. By the end of this sprint the team has both a polished mock‑up and an agreed hosting strategy. 

- **Phase 4 (Week 7-8): Core Development (Authentication, Map Interface, Database Connections) AKA MVP**
These sprints turn prototypes into a minimum viable product.
On the front end, we will use React/TypeScript to renders a Leaflet campus map. Integration of a live room moniter on the back end will connect to pins that will fade from red to green when there's an open room. Students will be able to using their already existing ILlinois credentials through further implementation of shibboleth sso. Hopefully by the end we will have demo showing MVP answering *“Where can I study right now?”* in under ten seconds.

 
- **Phase 5 (Week 9):** Testing
Before launch we will begin testing. Every defect will be publicily shared on a public Kanban board with labels *blocker*, *annoyance*, or *nice‑to‑have*.

- **Phase 6 (Week 10):** Launch & Bug Reporting
We will start our launch by spreading the word about OpenStudy through Flyers with QR codes in lecture halls and student centers. Video demos on social media pages as well.
We'll set up analytics to manage and moniter our weekly users.


## Community and Stakeholder Engagement

### Campus Organizations
Collaboration with campus organizations (such as BUILT, NSBE, and ACME) is crucial. These organizations not only promote adoption but also recruit motivated students who already possess the skills we will need to start development and testing.


### User Community
Through open forums, surveys, and social media interactions, OpenStudy will look to gather user feedback.


## Tools and Technologies


### Cloud Hosting
The choice of cloud provider is not an immediate need as data on classes rarely change requiring only 1-2 API calls a week. As we scale we plan to reassess and with cost-effectiveness, scalability, and real-time data handling capabilities as our primary considerations in this decision-making process.


### Development Stack


- **Frontend:** React.js for dynamic, responsive interfaces.
- **Backend:** Node.js and Express.js for scalable API development.
- **Database:** MongoDB or PostgreSQL for flexible, efficient data storage.
- **Authentication:** Integrated login using university credentials via Shibboleth or OAuth2.

### UI Development 

When designing my app, I initially started from scratch. I built the initial home screen and some of the corresponding pages that would appear once clicked. I found this tedious, to say the least. As I started looking into icons and layouts for my app, I started asking if there was a better way. It was at this time I remembered an important lesson I learned from my internship over this past summer. I was working on this fix to correct time-zone issues and spent hours looking through the software documentation. I was trying to come up with an original solution for a problem that had already been solved extensively and quickly realized this was not the way. Utilizing someone’s work (with credit, of course) has been a catalyst for success for decades, so trying to build this template from scratch was inefficient in hindsight. I was then able to work through a template that had the core functions I needed. From here, I could make the most important choices that would fit the needs of my audience.

<image src="https://github.com/OREL-group/Project-Management/blob/main/FINAL%20PAPERS/400%20(1).png" width="125"> <image src="https://github.com/OREL-group/Project-Management/blob/main/FINAL%20PAPERS/400.png" width="125"> <image src="https://github.com/OREL-group/Project-Management/blob/main/FINAL%20PAPERS/950.png" width="125">


Here I chose a neon green on a dark background. The vibrant green gave a  tech-savvy vibe that worked with my idea of quickly finding study spaces in a fast-paced college environment. I personally have all my devices on dark mode and I know many other students are the same. I found this is easier on the eyes  and dark interfaces can feel modern and sleek. The color palette was one of the most important choices; it would help my interface stand out and establish a visual identity.

 I wanted my app to feel familiar and secure. From the sign on page it showcases that students must sign in through their UIUC credentials. I want to imply seamless integration with existing campus systems which is a strong convenience factor. This builds trust within the user. Providing quick info on location, distance (“3 Min away”), and building details (e.g., “Armory,” “ECE Building”) allows students to quickly see how far away a room is and if it’s available. Short text snippets would allow students to take a quick glance and know where to go. 

<image src="https://github.com/OREL-group/Project-Management/blob/main/FINAL%20PAPERS/Stations%20Tab%20_%20Page%20LoFi%20(2).png" width = "200"> <image src="https://github.com/OREL-group/Project-Management/blob/main/FINAL%20PAPERS/Apple%20Login%20_%20Page%20LoFi.png" width= "200">


## Marketing and Adoption Strategy
- **Social Media:** Regular updates, features showcases, and interactive sessions on platforms such as Instagram, Twitter, and TikTok.
- **Physical Flyers:** Placed throughout campus buildings to reach the student body.


## Governance & Decision‑Making  

OpenStudy will adopt a **merit‑ocratic committee model** that mirrors the “build the project, then the community” progression that we discuessed in week 4. Those lectures warn against single points of failure as well as distributing authority and knowledge across several people.

### Roles & Structure

| Role | How elected | Powers |
|------|-----------------------|--------|
| **Maintainer Committee** (3 people) | Should be the founding leads | Strategic roadmap as well final conflict‑resolution authority |
| **Contributor** | Will be by seniority  | Repository triage; issue assignment; PR review |
| **Newcomer** | Default role | Paired with a Contributor mentor|

### Decision Flow

1. **Discussion → Proposal → Lazy Consensus**  
   Routine changes stay open **72hours**; silence=approval.  
2. **Request for Decision(RfD)** for architectural or governance shifts  
   *   Label `decision‑required`  
   *   Maintainers must publish a written rationale. I'm taking this suggestion from our discission during **Week5** and *centralising information and transparent updates* 
3. **When consensus fails**  
   The decsion will be up to the Maintainers where simple majority will decide.



## Funding & Sustainability  

**"[Although] Open‑source lowers barriers to innovation it still requires reinvestment to stay healthy**.In week 14 we are reminded that a *diversified funding strategy* outperforms any single revenue stream so for OpenStudy we will pursue a **three‑tier financial model**:

| Stream | Year 1 Target |
|--------|--------------|
| **Campus Seed Grant** | $3k |
| **GitHub Sponsors** |$150/mo recurring |

### Fiscal Oversight & Transparency  
We learned this semester about **“lifecycle and sustainability”** and how it is  imperative to keep finances visible so future contributors can trust the project. 

* We will host funds on **Open Collective**, publishing quarterly budget posts.  
* All expenses over \$100 require two Maintainer signatures so we have a sense of *checks‑and‑balances*

### Grant & Sponsorship Pipeline  
Week 14 taught use about the *three grant types* framework, therefore, we'll have:  
1. **Operating‑support grants** for hosting & CI/CD.  
2. **Program‑development grants** (Google Summer of Code for example) to fund contributor stipends.  
3. **Capital grants**  if we outgrow our cloud hosting.

### Long‑term Vision  
By Year 3 we aim to qualify for **NumFOCUS Affiliated Project** status (small‑scale fellowships) and transition the OpenStudy treasury to a 501(c)(3) (nonprofit), mirroring the *foundation pathway* showcased in the Mozilla & Linux case studies. 

## Automation & CI/CD Pipeline  

Automation is a double‑edged sword. While it reduces rote effort it raises the stakes when humans are not involved. This is the paradox of automation. With this in mind  OpenStudy will implement automation through a **two‑stage GitHub Actions pipeline**  while still giving humans the final say.

1. **`pull‑request.yml` (quality checks before code is merged)**  
   - **Code‑style sweep:** Automatically looks for formatting or style issues (with ESLint and Prettier).  
   - **Run the tests:** Makes sure that least 85% of the codebase is covered.
   - **Quick security scan:** Compares our third‑party libraries against a public list of known security flaws.  
   - **Instant feedback:** If anything fails, the bot leaves a friendly note right in the pull request. As we learned this semester good automation should "surface problems, don’t hide them*.
   - 
2. **`main‑deploy.yml` (automatic releases after code is approved)**  
   - **Pack & ship:**  Wraps change in Docker Image and stores it in the project’s registry.  
   - **Half‑step rollout:** Does half server rollout so if there's an issue it's atleast not the whole server. If all looks good after 15 minutes, the rest follow.  
   - **Heads‑up message:** Bot posts a quick update in Slack to let everyone know of the release.


## Managing Technical Debt

Technical debt management is crucial for sustaining OpenStudy. This will make sure that our code is still maintainable, scalable, and responsive to needs from our student body as well as the ever changing technological landscape.

All technical debt must be transparently identified, documented, and prioritized. This includes regular code reviews and detailed documentation within project management tools.

Technical debt items prioritized based on:
- **Impact:** Performance, maintainability, or scalability.
- **Urgency:** Immediate resolution needs.
- **Effort Required:** Effort to resolve the debt.

Some concerns with my current tech stack:
- **Multiple Langauges:** With managing multiple languages comes with keeping up with evolving frameworks, security patches, and potential breaking changes. 
- **Database Restriction:** MySQL's structured nature could require careful schema migrations as my application evolves, this is additional maintenance. 
- **Cloud Providers:** AWS Lambda’s vendor locks me within AWS’s ecosystem so if I need to change providers down the line, it’ll be very painful.

## Risk & Mitigation Matrix  

| Risk  | Likelihood | Impact | Mitigation |
|----------------------|------------|--------|--------------------------------|
| **Automation tool failure** (*“Seven Deadly Sins of Automation Mismanagement”#4: maintenance costs*) | Med | High | Keep workflow files under version control
| **Contributor churn after graduation** | High | Med | Annual “Good‑First‑Issue Hackathon” |
| **Data‑privacy incident** | Low | High | OAuth 2‑only auth; weekly GitHub Advanced Security scans |
| **Budget shortfall** | Med | Low | Auto‑scale to zero in summer|
## References

- Fogel, K. (2005). *Producing Open Source Software: How to Run a Successful Free Software Project.* O'Reilly Media.
- Raymond, E. S. (1999). *The Cathedral and the Bazaar: Musings on Linux and Open Source by an Accidental Revolutionary.* O'Reilly Media.
- GitHub Open Source Guides. (2024). Retrieved from [https://opensource.guide](https://opensource.guide).
- Google Cloud vs AWS in 2024: A detailed comparison. (2024). Retrieved from [https://cloud-comparison.io/google-cloud-vs-aws-2024](https://cloud-comparison.io/google-cloud-vs-aws-2024).

## Conclusion
  OpenStudy is just an idea that I saw a local student need. Because it is open source, has potential to be implemented on other college campuses. I think this is a common frustration for students at universities everywhere. Looking forward, the path to broader adoption we envision creating an online resource of detailed setup instructions on setting this up. This way they can move quicker to adopt this and not be burdened by issues we already solved. 
  
 Ultimately,  I think OpenStudy represents the kind of digital public good that higher education sorely needs. With continued development, and support OpenStudy can grow into a vital infrastructure for universities everywhere.


