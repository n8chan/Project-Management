## SummarAIze - Note-Taking Made Intelligent
Logan Patterson, Spring 2025


### Abstract
---
SummarAIze is the world’s newest and most advanced note-taking app. Developed with completely open-source principles in mind, SummarAIze leverages Artificial Intelligence and machine learning to deliver a seamless place to organize, summarize and collaborate on the notes you take every day. 


### Introduction
---
**Background**

Everyday, around the world, people are taking notes all of the time. Whether this be in a professional setting for recording meetings or performing research, or an academic one, note-taking has been a staple of humankind for as long as we have been writing. Notes allow us to have greater recall, to share our ideas and organize our thoughts all in one place, but note-taking has not evolved as much as one would think in today’s technological world. This progression has been fairly simple, starting with pen-and-paper and ending with digital notes (either typed or written on a tablet), the only real advancement has been in the ease of storing and sharing our records. SummarAIze seeks to revolutionize this everyday activity, making it more efficient, intuitive, and most importantly, fun.

**Value of Open-Source Principles**

Working using open-source principles has shown to increase agility, flexibility, quality of code, cost-effectiveness and time-to-market when compared to more traditional practices (Zenhub). Increasing levels of transparency and making coding bases available to the public in an open-access format allows for much greater community involvement, allowing members of your community to iterate on your ideas and bring new ones to fruition. Listed below are a few specific benefits SummarAIze can take advantage of through open-source design and support:

Transparency: All developmental activities will be properly documented and available publicly on a repository such as GitHub

Community Involvement: Contributions from community members such as developers, designers and users will be not only supported, but highly encouraged

Inclusivity: SummarAIze will maintain a code of conduct regarding community involvement and provide onboarding resources to involve contributors of all skill levels to foster a collaborative and safe community

Open Access: All codebases, AI training data,  resources and project documentation will be open to the public and available on our repository (unless it contains personally identifiable information of users)

**Audience & Community**

SummarAIze will not cater to a specific group of people, but instead maintain support and features that benefit anybody who likes or needs to take notes during their day. This support could range from a parent overwhelmed with events, helping them organize and plan out their day, to a professional researcher who must take and share scrupulous notes daily, providing them with smart tagging and summarization features. The beauty of using an AI Large Language Model (LLM) is its adaptivity to specific situations. By asking members of our audience and community to allow us to use specific portions of their notes to help further train our model, we can continue to create a more robust and flexible system, benefiting all who use it. Additionally, allowing community involvement in the design and implementation of features and updates will allow our project to benefit from the knowledge and ingenuity of an entire community, far outpacing what we could have done as a small development team. As discussed previously, maintaining up-to-date community services such as onboarding features, AI training information and codebases is paramount to ensuring our project perpetuates open-source community involvement standards, benefiting in essentially every facet imaginable. To ensure these standards are met, a library of videos describing the company, goals and giving a rundown of code and previous work will be published and kept up-to-date on our repository and website to foster an inclusive environment for all skill levels.


### Strategy
---
**Tech Stack**

In regards to our AI model, creating a brand new LLM or AI model would take an enormous amount of resources, time and expertise. First, a team of AI experts would need to be hired, onboarded and given what would likely be years to create and refine an initial model, all of which could become moot during the time it took to develop. Instead, our model will be built using OpenLLaMa, an open-source LLM built using Meta’s initial Llama architecture. While many “open-source” AI models claim this title, they do not provide training data, which is arguably the most important aspect to an AI model. OpenLlama provides all data in a truly open-source format, meeting OSAID’s standards for AI to be considered truly compliant with these ideals (Maffulli, 2025). OpenLLaMa is not only open-source, but highly customizable to specific scenarios, and above all, is extremely small, meaning it does not require large computing facilities to host the pretrained model (Castelvecchi, 2023). Using a pretrained model and being allowed to slightly tweak parameters to meet our needs will save a large amount of time and overhead, not to mention reduce potential technical debt that could be accrued creating our own model. 

Both the model and backend servers will be built using Python, as Python is the most standard language for machine learning and has a multitude of libraries for LLMs, APIs and tokenization. For the API layer, FastAPI seems to be a fantastic fit for our needs, since it auto-generates docs and is extremely high performance, fitting with our theme of maintaining high efficiency across all systems. To this point, PostgreSQL would be a fantastic database option for this project, since it is open-source, free, highly scalable, and above all, efficient. Docker and Docker Compose are a great way to host applications by making use of containerization, something important when working with LLMs. Frontend interfaces will likely make use of TypeScript and React in order to create a more streamlined developer experience with our web app. If this app adds some kind of authentication, OAuth2 pairs nicely with FastAPI, removing some overhead for our team. The most important aspects to the development of this project were to maintain open-source principles, which all aspects of our tech stack abide by, and create an efficient system, capable of being run using small servers and any device, which, in theory, should be possible with these tools. 

**Licensing**

There are a few potential licenses a project like this could make use of. The BSD, MIT and GNU licenses all fall under the open-source, copyleft obligation. The Apache 2.0 license, which is used by our LLM, OpenLLaMa, is very similar to these licenses, but permits derivative works to be distributed under a different, more restrictive, license (not copyleft). Initially, the Apache 2.0 license seemed like a great fit, as OpenLLaMa, a large part of our application, already uses this, but the allowance for derivative works to not adhere to copyleft principles didn’t sit right with me. With this consideration, the MIT license seemed like the best fit, as it is extremely widely used in this sphere, only being second to the Apache 2.0 license.

**GitHub**

GitHub is one of the most used developer platforms when it comes to open-source projects, and it’s obvious why this is the case. GitHub offers tons of features both for developmental teams and their community alike, such as access control, bug tracking, task management and wikis, all within their platform. Most importantly for this project, Git itself is a fantastic tool to be used through the GitHub platform for version control, an extremely important aspect to any project, but most importantly an open-source one which may be constantly updated and edited by the community. Using Git’s version control software, our team will be able to track any changes made on our project and its branches as well as revert certain changes if we need to rescope our project or they don’t fit with our vision of the product. Another important trait of GitHub is its easy-to-use task management features. With low startup effort, a stable, long-term documentation system and its ease of integration with other tools, it makes managing a team and community much easier, especially for a smaller developer group. Kanban boards are a fantastic example of organizational features available on GitHub, allowing a team to visualize goals and issues and make all aspects of the project more efficient. Behind our AI model, GitHub is likely the second most important software for this project. 

**Technical Debt**

With any software development project, there will always be an accrual of technical debt, no matter how hard the developmental team tries to avoid it. Technical debt refers to “the cost of maintaining source code that was caused by a deviation from the main branch where joint development happens” (Haddad & Bail, 2020). When working open-source, there is a large likelihood that this debt can build up, and it is important to watch out for it and understand how it forms and can impact a project. Some possible forms of technical debt in a project such as this could accumulate from code only some of the team understands, especially if they leave the team, repeated rescopes, lack of documentation and lack of organization within the team and broader community. To combat these possibilities, a large amount of emphasis will be put into open communication, proper documentation on GitHub through FastAPI so members of the team and community can be kept up-to-date, and widely adopted use of GitHub’s organizational features such as Kanban boards so there is no confusion on the direction of the project or what work is being done/needs to be done. Hopefully, with a team and community dedicated to these practices, we can avoid a large amount of technical debt, allowing our project more time to look toward the future. 


### Features
---
SummarAIze will launch with several integral features, and will constantly be updated with more features, some pre-planned and others coming from community involvement and suggestions. Here is a brief list of currently planned features for the project, in order of release:

Available At Release:
* Context-Aware Summaries - Allowing quick summaries to be made of notes, emphasizing important topics
* Smart Tagging System - Suggest and auto-assign tags based on content, allowing searching to be much more streamlined
* Collaboration Features - Allow multiple users to work in the same notebook with live updates, useful for team projects
* Version History & Change Tracking - Allows users to track edits of notes, who made them and when, and the possibility to roll notes back to a previous state if needed
* Task Integration - Allow notes to be linked to many widely used task management tools, allowing a seamless experience for users to track tasks they must complete, either themselves or as a part of a larger team

Planned For Post-Launch:
* Cross-Platform Integration - Sync notes across devices and integrate with services like OneNote and GoogleDrive
* Mind Map Generation - Create visual mind maps on notes in a separate tab to visualize important relationships and key topics
* Audio-to-Text Conversion - Convert audio from meetings or lectures into notes with AI-driven contextual understanding, allowing for far greater accuracy of words
* Personalized Note Summaries - After a user has used the app for some time, the AI model will be able to understand their preferred method of summary and deliver this when prompted
* Gamified Learning - Turn notes into quizzes and flashcards automatically, allowing for easier and more exciting study habits to be formed


### Conclusion
---    
With the recent excitement over Artificial Intelligence spawned out of OpenAI’s ChatGPT, the world now knows the power of AI and how it will shape the future of technology. SummarAIze seeks to expand upon these new ideas, offering a more helpful, streamlined AI solution to note-taking. From students to professionals, every demographic will benefit from the features, both available at launch and developed as the app ages, creating a more enjoyable and effective note-taking environment for all. SummarAIze will take advantage of the many benefits offered through open-source development, including increased agility, flexibility and a significant decrease in developmental overhead and time. We will create an inclusive and welcoming community, which will be our most important resource, spawning new ideas, features and support for our small developmental team. Using existing open-source architecture such as OpenLLaMa and FastAPI and adhering to consistent documentation and transparency as a company should help reduce potential technical debt, allowing our project greater speed of delivery and reduced refactoring time. GitHub will act as our main repository and workspace, allowing for greater community involvement and organization, increasing efficiency and ultimately leading to more innovation into the future. We look forward to the future and crafting a truly open-source solution to an extremely stagnant everyday activity.


### References
---
Castelvecchi, D. (2023). Open-source AI chatbots are booming — what does this mean for researchers? Nature, 618(7967), 891–892. https://doi.org/10.1038/d41586-023-01970-6  

Maffulli, S. (2025). ‘open source’ ai isn’t truly open — here’s how researchers can reclaim the term. Nature, 640(8057), 9–9. https://doi.org/10.1038/d41586-025-00930-6  

Haddad, I., & Bail, C. (2020). Technical Debt and Open Source Development. Linux Foundation.  

Zenhub. (n.d.). Open source project management: A complete guide. https://www.zenhub.com/guides/open-source-project-management  
