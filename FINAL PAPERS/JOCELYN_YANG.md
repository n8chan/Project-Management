## WaterQuality Ranker
Name: Jocelyn Yang

Semester: SPRING 2025

Link: https://huggingface.co/spaces/brenttf2/Chicago_Beach_Quality_Exploration



<img src="https://github.com/user-attachments/assets/97b34876-41af-41a7-998d-248c10a277a9" width="500"/>

### Introduction   

[Comment_1]: <> (begin your text here)

For Chicagoans, urban waterfronts like the ones lining Chicago's Lake Michigan, are treasured public spaces that give residents a place for recreation, relaxation, and enjoy the city. As valued as these beaches are however, the water quality of these beaches can fluctuate rapidly because of factors like stormwater runoff, bacterial contamination, and environmental shift, posing risks to public safety and health to residents and visitors. For this reason, timely and easily-accessible information about beach conditions and water quality is highly important and essential in order to help residents and visitor make informed decisions about where and when they want to visit these beaches and take a swim. 

The WaterQuality Ranker project is aimed at addressing this need of information by providing an interactive data dashboard that visualizes water quality trends across the city's beaches. Built using publicly available data from the Chicago city data portal, and intuitive design principles, the platform is designed to inform residents, or other users whether they are environmental researchers or public health officials, to explore historical and real-time data on E. coli levels, swim advisories, and seasonal trends. 

This project is more than just a data visualization tool. It also represents an effort to bridge open data with public engagement, promoting environmental transparency, and enhancing community awareness generally around a significant issue that impacts millions of residents and visitors during Chicago's summer months. Through the integration of data analysis, user-centered design, and accessible articles, this project will contribute to smarter urban-decision making and healthier waterfront use. 

[Comment_2]: <> (An example of a reference in paper text, cite in Reference list -- see Comment 8)

### Project Motivation & Goals
[Comment_3]: <> (begin your text here)

The motivation behind the WaterQuality Ranker project comes from the growing concern about the accessibility and transparency of environmental health data in urban spaces. One of the biggest for me when I consider someplace "clean" or not, will be the quality of the water and the clearness of the water. I want this project to address this concern. This is why as a frequent visitor to Chicago's beaches, I noticed that it is hard to find accurate and recent information on the water quality, especially during periods of heavy rain or high lake activity. While the City of Chicago does publish publicly accessible data, it is often in .csv format, making it highly unreadable for the public or those not familiar with csv formats. This gap in usability between data scientists and the general public inspired me to build a tool that could help make vital information such as this one more approachable for the general public and engaging so the community could understand as well.

Public awareness of beach safety is not only a matter of personal convenience, but it's also a public health issue. According to the EPA, elevated E. coli levels in recreational waters can lead to increased rates of illnesses, particularly among children and immunocompromised individuals. By creating this project, it becomes a platform that makes it easy to understand the potential dangers of the beach water and water safety, allowing the community to make smart choices and potentially avoid harmful exposure.

The overarching goal of this project is to transform raw environmental data into an accessible and informative experience for the user, specifically including:

 * visualizing historical E. coli data from Chicago's beaches in an intuitive dashboard
 * highlighting temporal trends, such as seasonal or weekday/weekend fluctuations in water quality
 * supporting public health advocacy and city planning by showing patterns in swim advisories
 * encouraging a broader conversation around urban environmental health and the role of open data

Ultimately, this project will aim to make environmental data actionable and use community-centered tools and designs to promote a safer, more informed use of shared public spaces. 

[Comment_4]: <> (Insert Figure with caption here)

### Technical Vision & Implementation  

The WaterQuality Ranker project was built around the idea of transforming open public health datasets into interpretable interactive visualizations that are meaningful and accessible to everyday users. It is hosted on HuggingFace using Altair, the project combines a clean front-end design with reliable data processing to deliver a responsive and informative experience.

The technical implementation began with retrieving and cleaning historical beach water data from the City of Chicago's public dataset, specifically focusing on two datasets, Beach Water Quality and E.coli measurements and swim advisory records for multiple beach sites in Chicago. Using Python and Pandas, the data was then preprocessed to handle missing values, standardized, and cleaned for further analysis. 

For the front end aspect, we are using Altair for its simplicity and it is easy to quickly develop interactive applications. The interface allows users to select which beach they want to check and view the various trends for the season. These plots, created using Matplotlib and Seaborn, showcase key metrics like E. coli levels and distribution comparisons between beaches. To ensure clarity and usability, there was particular attention given to the design of the dashboard, we tried to make it as user friendly as possible while also keeping the simplicity. Interactive dropdown menus and graphs were used to guide users through the exploration process, and labeling was used to make it easy to interpret the results. The layout was designed to support both casual users interested in beach water quality and researchers or policymakers looking for general trends over time.

### Workflow Process & Project Management    

As for the development of the WaterQuality Ranker project, I tried to follow a flexible workflow, balancing flexibility with clear goals to keep me on track across all stages of design, data processing, and interface development. Because this was a solo project, managing time and scope was highly important to delivering a functional and high quality product within the deadline.

The initial planning phase focused on identifying the right data sources and setting a clear goal: enabling the community to explore and understand patterns in Chicago beach water quality. This early research period also included assessing which visualization tools I should use which resulted in selecting HuggingFace and Altair for their simplicity and accessibility, taking technical debt into mind as these are relatively popular spaces and methods.

This the workflow I wrote up:
![Image](https://github.com/user-attachments/assets/2da89281-d87c-4d39-b9fd-ef02cf0403dd)

The development timeline was organized into four key stages:

- **Dataset Selection & Acquisition (Weeks 1–2)**  
  Tasks: Identify and collect relevant datasets  
  Participants: Students, project supervisors

- **Data Cleaning & Preprocessing (Weeks 3-4)**  
  Tasks: Remove inconsistencies, handle missing data, prepare data for analysis  
  Participants: Students  

- **Variable Selection & Visualization Design (Week 5)**  
  Tasks: Choose meaningful variables, sketch visualization plans  
  Participants: Students  

- **Data Analysis & Visualization Creation (Weeks 6-7)**  
  Tasks: Analyze data, generate visualizations based on prior designs  
  Participants: Students, supervisors

- **Webpage Development & Presentation (Weeks 8-9)**  
  Tasks: Build and design webpage to display visualizations, prepare presentation materials  
  Participants: Students

- **Review & Final Submission (Week 10)**  
  Tasks: Submit final project, present findings  
  Participants: Students, supervisors

- **Post-Submission Review:**  
  Question: Do results warrant follow-up?  
    Yes: Schedule follow-up with supervisor  
    No: Project is considered finalized and closed

Risk management played a critical role here, especially in terms of data limitations (missing data or abnormal data). To address this, we handled the missing values by dropping them or replacing them (depending on the situation) to avoid errors in the interface. Additionally, I ensured all visualizations would adapt to handle things according to user inputs without crashing. This project was managed using a personal vision board to track tasks, issues, and new feature ideas. This helped maintain a clear goal to focus both on immediate deliverables and long-term improvements. While the project was an individual effort, the framework makes it easy to allow collaboration or community contributions in the future, especially if published as an open-source project on GitHub.

#### Managing Technical Debt

Throughout the development of WaterQuality Ranker, there was careful attention paid to avoiding unnecessary complexity in terms of both the codebase and tool selection. Like many solo projects, there have to be certain trade-offs that are made that can be considered forms of technical debt short-term decisions that might need to be improved upon in the future, in order to support scalability, collaboration, and maintainability. For example, while using Hugging Face Spaces and Altair did allow for an easier and more accessible platform, these tools also have their limitations. Altair, though it is easy and intuitive to use, has constraints when handling large datasets or interactivity that is highly customized. As user demands increase, the existing visualization may not be enough to support more advanced use cases without having improvements made on it in the future. Similarly, the current project structure lacks a modular design, meaning that updating one part of the code, like adding a new data source, may require changes to be made throughout the entire script rather than just in certain methods or adding it to a database without changing the rest of the code. This would be a bigger technical debt that is added up as future improvements would take more time to update. These choices that I made were from a conscious decision to prioritize delivery and usability over long-term scalability, but I realize that in future iterations, this project could benefit from adopting better practices such as modular scripting, API-driven design, or structured testing. Additionally, technical documentation and version control via GitHub would be essential in the next steps as it would heavily reduce technical debt and allow outside contributors to add to this project. Finally, by identifying and acknowledging technical debt early on, this project is in a better position to be maintained and have continuous improvement without compromising the current functionality. This awareness is critical in maintaining projects beyond the initial launch results and ensures that these projects are not short-term decisions, but have the potential to be a long-term project, one that others can build off on.

#### Gamification and Community-Building
While WaterQuality Ranker is primarily a technical and community engagement project, it has the potential to benefit from gamification strategies to enhance community interaction, especially if I plan to expand it to include collaborative contribution, educational components, or other elements. Gamification is when the application of game-like elements, like points, badges, progress tracking, or public recognition, is used to motivate users and contributors. One example of this is Reddit, which awards users with badges and achievements to encourage more engagement within the community and interactivity. In the context of open-source or community-driven platforms, successful gamification can significantly help motivation, guiding people to want to feel like their participation matters in this community based project. For example, adding a badge or contributor profile system could heavily encourage users to contribute to gathering localized data reports, flag unusual water quality patterns, or even participate in data cleaning efforts. Similarly, environmental science researchers or independent journalists could earn recognition for contributing to public dashboards or writing blog posts about the findings.

Another important thing to note is that gamification does not need to be competitive. Instead, it can be used to garner a feeling of fellowship and a shared common goal, for instance, a “community contributor” label on GitHub or a running leaderboard for those who are the most active beach monitors. These small incentives build a sense of ownership and reinforce consistent engagement, which is especially valuable to projects like these focused on sustainability. And though this feature is not yet implemented in the current version of WaterQuality Ranker, it is a promising goal that we can aim for for the next steps of this project. Gamification could be a game changer and turn passive users into highly active participants, strengthening not only educational partnerships, but also deepening the platform’s community roots.

#### Release and Support Cycles

One key lesson from open-source project management is the importance in defining a release and support cycle, which is essentially a timeline that outlines how often features are added, updates are made, and bugs are fixed. Although WaterQuality Ranker was originally developed to be a semester-long project, it is essential to plan for the future if I want to maintain this project as one that is useful and trusted by the public, specifically its future development and maintenance. A calendar-based release model could align with the beach season, perhaps launching new features each spring as more people visit the beach for the warmer seasons. This would include updating the dataset, checking visualization performance, and ensuring that the interface remains accessible to all users, whether on a computer or a mobile. Additionally, a feature-based release model could also be developed, prioritizing enhancements like adding a map that overlays with weather so that users could see where the beach is and what the weather would be like that day, which could be released once it is ready, regardless of the calendar updates. 

In terms of support, WaterQuality Ranker would benefit a lot from a lightweight system for tracking bugs and feature requests, possibly using GitHub Issues. There could be a Kanban board of issues, relying on users to participate in finding bugs or reporting any abnormalities they encounter. Even without a formal customer support model, this open-source style feedback mechanism could allow for a more transparent and trusted project for the community. It would also allow contributors, whether they are technical volunteers or students, to engage with the project more meaningfully. By acknowledging the need for a structured release and community-facing support, this project can transition from a one-time demo into an actual tool that can serve the community with long-term civic and educational value. Managing this project lifecycle this way promotes stability, reliability, and user trust over time as this project continues to engage with the community.

By applying structured yet flexible project management principles, the development of WaterQuality Ranker was able to be completed in a timely manner, and accomplish both technical and user-experience goals.

### Community Building and Engagement      
[Comment_7]: <> (begin your text here)

A key part of the WaterQuality Ranker project is its potential to serve as a bridge between the publicly available data and the interpretability of that data to the community. While it began as a solo initiative, it is designed with community awareness and public health impact in mind, prioritizing usability, transparency, and educational value. 

The primary users of this platform would be residents of Chicago, tourists, policymakers, researchers, or anyone who is simply interested in understanding beach water quality. By transforming dense, static datasets into visual, interactive visualizations, this platform helps monitor water safety and encourages data-informed decision making among everyday users. To support engagement, the project is hosted on HuggingFace, making it easy to share via social media, community forums, or other channels of news. This interface is made to be lightweight and mobile-friendly, enabling quick access for users, making it a flexible application, useful for those who want a quick check before heading to the beach.

Beyond general users, this platform also invites collaboration from educators, data journalists, and researchers. It can be used in the classroom to teach about urban water quality or by journalists investigating trends in public health policies. One future goal is to expand this platform to beaches or other water sources beyond the city of Chicago, so that it can be useful everywhere. Looking ahad, this project was not just about technical enhancements, but also about cultivating public trust and shared use of public data. Ideas for expanding this engagement could include partnering with local environmental nonprofits, creating blog posts about patterns found in the data, or making predictive models to extend the platform functionally. 

### Conclusion
The WaterQuality Ranker project demonstrates how open data, when thoughtfully presented, can become a powerful tool for public awareness in terms of health safety. By transforming raw data into accessible, easy to visualize graphs and patterns, this project addresses a clear need for the community to access local water quality information.

Through its interactive dashboard and user-friendly design, this project helps individuals make informed decisions about going to the beach while also highlighting urban environmental health patterns. The technical foundation was built in Python, using Altair and HuggingFace. This ensures that the project does not accumulate too much technical debt and that the platform is scalable, adaptable, and ready for future improvements. 

Beyond the technical aspects, this project also opens up a conversation around data-driven decision-making and invites collaboration from local organizations, educators, researchers, or other developers. This project contributes to the broader vision of environmental justice and shared responsibility we all have in public health.

As cities face increasing challenges around climate, pollution, and urban infrastructure, projects like this one gives us the reminder that we all need the power of accessible information. From making information readable to everyday users, we can spread awareness and help others understand what they are privy to. With continued refinement and community engagement, WaterQuality Ranker has the potential to become a trusted resource for residents and a model for similar initiatives in other cities or other areas of need.

### References     

[Comment_8]: <> (begin your reference list here. Cite as author, year in main text. Reference link should correpond with link in Comment 2  Use any format you wish -- MLA, APA, etc.)

Alicea, B. (2025). Lecture 9: Community Building [Lecture slides]. IS 340: Project Management, University of Illinois Urbana-Champaign.

Alicea, B. (2025). Lecture 20: Project Lifecycle and Sustainability [Lecture slides]. IS 340: Project Management, University of Illinois Urbana-Champaign.

City of Chicago. (n.d.). Beach water quality - Automated sensors. Chicago Data Portal. https://data.cityofchicago.org/Parks-Recreation/Beach-Water-Quality-Automated-Sensors/qmqz-2xku/about_data

Chicago Park District. (n.d.). Beaches. https://www.chicagoparkdistrict.com/parks-facilities/beaches

Fondriest Environmental. (2014, July 24). Protecting Chicago’s lakefront: Freshwater beach monitoring. https://www.fondriest.com/news/protecting-chicagos-lakefront-freshwater-beach-monitoring.htm

Pratap, P. L., Redman, S., Fagen, M. C., & Dorevitch, S. (2013). Improving water quality communications at beaches: input from stakeholders. Journal of water and health, 11(4), 647–658. https://doi.org/10.2166/wh.2013.077
