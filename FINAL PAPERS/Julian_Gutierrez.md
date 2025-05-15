# Julian Gutierrez
# IS 340 Project Management
# May 14th, 2025


## Overview
I created Chi-Town Watch as an open-source and community focused dashboard and forum that is designed to help explore and visualize crime data in Chicago neighborhoods. I used data from the Chicago Police Department provided by the Chicago Data Portal, it enables residents as well as tourists to interact and explore local crime trends. It was built using Python libraries such as Pandas, Numpy, Streamlit, and GeoPandas and the application utilizes interactive visualizations hosted on HuggingFace. By encouraging community engagement through forums and reliable data Chi-Town Watch works to promote public safety and awareness to tear down the astigmatism surrounding Chicago, and uplifts the community through investments, creating a safer, more aware Chicago. 
## Introduction
Chicago is an absolutely stunning city, which is known for its culture, strong communities, and controversial history. However, all of this is often overshadowed by headlines pertaining to crime and different concerns to public safety, issues that affect residents and tourists alike. Statistics in recent years have told this story perfectly, with a steady increase of violent incidents such as aggravated assaults, reasonable alarm has been created in communities across Chicago land. Despite the clear availability of data pertaining to this issue, many citizens lack the information to find a centralized place where they may discover issues and discuss with other residents. 

In response to this, Chi-Town was created to put citizens in front of an interactive dashboard in which they are able to make their own informed decisions based on data, allowing a platform where citizens can visualize and explore crime trends in neighborhoods. Unlike other crime mapping tools, Chi-Town Watch aims to focus on Chicago neighborhoods while also providing a space where residents can start a dialogue with other community members. This combination of dashboard and forum in one space provides a strong space where information can flow freely but also a space where citizens can connect and quell concerns.
## Project Motivation and Goals
According to IllinoisPolicy.org, during 2024 attacks and threats were up and aggravated assaults hit a 20 year high. Considering this, residents of Chicago are a tight knit community and above anything else deserve to feel safe whether it be just going to the grocery store or wanting to go for a nice stroll to enjoy the weather. Which is why I decided to create Chi-Town Watch. It is a community project where Chicago residents can come together to see crimes in their community to help keep themselves safe as well as be informed on the events happening in their own neighborhood. This project could be beneficial for tourists looking to explore the city in knowing where they are going to have a better travel experience and to break the stigma behind Chicago being an incredibly dangerous space. I aim to bring the community together through providing free, reliable information to the public as well as creating spaces in which people can discuss concerns and get to know the people who live around them. Although there are similar ideas that exist such as the citizen app, which serves as a way to see crime that happens around you and even a dashboard created by the Chicago Police Department themselves, none of these spaces create a place for community engagement but just solely serve to notify you of crimes in your area. This is where Chi-Town Watch sets itself apart, by creating a space where community members can engage about community issues, events, and concerns which all comes together to create a closer community where people can finally feel safe and meet people that live in their own communities which brings everyone closer.

Chi-Town Watch has certain goals that should be obtained through its lifespan:
- Technical Goals:
  - Develop an interactive and up-to-date dashboard using Python libraries (Geopandas, Streamlit, Pandas, Numpy)
  - Create a mobile and desktop experience for more accessibility.
  - Maintain an Open-Source policy through providing documentation and version control through GitHub.
  - Gather data regularly through the Chicago Data Portal.
- Community Goals:
  - Create a space for community members to share concerns, issues, or to connect with one another.
  - Allow tourists to engage with the community and help make informed decisions about areas they plan to visit. 
  - Provide relevant information to Chicago residents about their neighborhoods as well as other surrounding communities. 
  - Create understandable crime data.

- Growth Goals:
  - Create opportunities for community partnership and opportunities to create local policy using insights
  - Create transparency within communities, as well as connecting them with public data.
  - Create more features, with increasing complexity based on the scale of the project (Safety ratings, alerts, hot spots, etc.)

- Long-Term Goals:
  - Utilize machine learning in order to predict crime hotspots and trends based on previous data and current trends. 
  - Collaborate with local organizations to create a deeper impact with the community and host local events to encourage community involvement. These are where community investments will occur. 
  - Create a specific forum space only for residents, to drive local-only conversations.
## Features & Functionality
Chi-Town Watch is an interactive but also user-friendly dashboard that will let users explore recent crime that occurs in local Chicago neighborhoods. Using GeoPandas an interactive map can be leveraged in order to visualize crimes as well as display incidents by type, date, and even location. What’s also offered is filtering based on different categories of crime such as, theft, assault, or robbery. Being able to identify patterns of each of these crimes over different time spans such as days, weeks, and months is also very important to being able to really understand the extent of these crimes. Another very important aspect of this project is that citizens are able to understand and process this information even if there is lack of technical experience, meaning that presenting these data points in a clean format is important.. 
In addition to the visualization component of this project, what Chi-Town Watch works towards is building a sense of community through forums where users can share their experiences in the community, as well as raise concerns and connect with locals. Using this space to encourage community dialogue is important as it can highlight incidents that perhaps do not get reported on a map data set rather one owns personal experience. What is being done is going beyond what raw data can represent, and one of the major long term goals of this project is to be able to represent community voices, which in turn highlights one of the major advantages of what allowing citizens to voice their opinions can do. Through combining the idea of a forum with statistical dashboards what can be accomplished is a tool to bring together the community and to bring awareness to issues in the community. 
## Target Users
Chi-Town Watch is designed with two major groups of users in mind: Residents of Chicago, as well as tourists who are planning to visit the city. For users who currently reside in Chicago, what the platform offers currently is a way to be informed about the crimes that occur at home, mainly by creating a way to visualize where crime occurs. Using this, residents can make safer decisions on a day to day basis, whether it is just deciding where to walk their dog or even their route to work, keeping citizens aware of the on-goings of the community is imperative to what Chi-Town Watch is designed for. 

The second key audience that Chi-Town Watch is designed for, is visitors to Chicago who are unfamiliar with the lay-out of the city or unaware of the safety of certain areas. Being a platform that offers a tool that can help plan smarter and informed decisions is also imperative to the mission of Chi-Town Watch. Instead of users relying solely on the stereotypes that are peddled through large media, individuals can form their own opinions based on the unbiased data displayed through our dashboard.  This helps potential visitors navigate Chicago confidently while also being aware of the issues surrounding communities at that moment in time. By providing transparency rather than fear we can work towards creating trust in our communities and by emphasizing clarity, community, and accessibility we can utilize real world data to make data driven decisions. 

## Sustainability
A major concern surrounding Chi-Town Watch is sustainability. Chi-Town watch relies on an open-source philosophy which creates accessibility. Using  libraries in Python such as Pandas, Streamlit, Numpy, and GeoPandas, as well as hosting the website on HuggingFace we can ensure that the project remains sustainable and expandable by contributors in the future. Keeping the code public creates an environment where collaboration is encouraged, individuals can engage in bug fixes, and improvements can all work towards broaders developmental goals. Another sustainability point being that relying on data that is publically available such as the Chicago Data Portal allows us to consistently pull data, relying on a data source that is dependent and doesn't require fees which allows us to be able to bypass financial barriers.
Another aspect of sustainability is we need to keep in mind that this project needs to remain relevant no matter what happens on the net. Sustaining the project in a state that keeps it dynamic rather than static is imperative seeing that this project adapts and changes depending on the different needs of its users. Sustainability depends greatly on the idea that users continue to engage with the dashboard and forums sharing their experiences and insights. We depend on users to raise questions which in result will allow the project to grow in directions that will benefit its users in the long run. Features that are to be planned such as machine learning and specific forums all represent the long term nature of this project. With this in mind Chi-Town Watch has the potential to remain a long-term valuable resource in which we not only utilize the code used for the project but also live through the community that this project is made for.
## Methodology & Workflow
During the development of Chi-Town watch, what was followed was a workflow that was grounded in open-source project management principles to make sure that this project was build upon ethical methods that allowed for its user to view the code as well as create renditions of their own using the code being hosted within GitHub. Ensuring that the data that was used within the project was clean, firstly I would have to go through the dataset and ensure that all data that was used to create this data was not missing any values and was a complete and full data set that allowed me to be able to create my visualizations.

Using the built in libraries I would be able to create an interface that would allow me to create an interactive map, libraries such as GeoPandas and Pandas would allow me to clean data and prepare it for display. While libraries such as Streamlit I would be able to distribute the interface and eventually I would be able to host the dashboard on HuggingFace free of charge which would dig into the technical debt aspect of this project. 
## Technical Debt
One aspect to consider when thinking about a project of this scale is certainly the extent of technical debt to be incurred within the project. A majority of the time the aspect to make or break a project of this caliber would be the technical debt component, as a majority of the time what kill project of this size is the fact that they cannot be maintained properly by their creators, harboring a project that is already destined to fail through events that should have been considered in the first place. In a project such as this, there are a plethora of expenses to be considered. 

One of the first aspects of this project that is to be considered is where the dashboard will be hosted, which would be HuggingFace. What would be beneficial about this project is that HuggingFace is a commonly used platform and is largely free of use, meaning that this will not be a major expense. Nevertheless what else will be used to GitHub, which is also perfect seeing that the use of this platform is also free of charge and will serve as an excellent platform to keep this idea open-source which will help keep costs down altogether. 

Being able to prioritize free-to-use libraries within the scope of this project creates an environment which makes maintaining this project affordable, but also sustainable over a longer period of time. Minimizing technical debt over a longer period of time I believe will serve will to keep a sustainable project.
## Project Timeline
Phase 1: Planning and Data Collection (Week 1 - 3)
Research similar tools that already exist (Citizen and CPD Dashboard)
Identify the scope of this project (Community and technical scope)
Obtain the datasets from the Chicago Data Portal
Clean data using Pandas, as well as utilizing EDA to engage more with the dataset. 

Phase 2: Dashboard Development (Week 4 - 5)
Build visualizations in Python using Geopandas
Integrate interactions within visualizations
Create a working prototype that will work in HuggingFace. 

Phase 3: Testing and Launch (Week 7 - 8)
Create a discussion board system 
General bug fixes and refining the UI for a better user experience
Open the project to collaboration within the community

Phase 4: Enhancements (Present day)
Ensure that users are engaging through the forum.
Keep an out for bugs and continue to monitor support tickets to ensure that there are no major issues.
Work on future updates and features.
## Conclusion
What Chi-Town Watch does goes much more further than just creating a dashboard of crime data for citizens to explore. What it really does is give the community an opportunity to empower itself and create awareness. Allowing individuals to come together to explore data and interact with other individuals in the community is integral to rebuilding the sense of community that has been lost in decent years. 

Throughout development of this project, we see not only hurdles but also challenges posed by this data, we must work to dismantle the astigmatisms presenting by this data, ensuring that people understand that Chicago is not defined by the data that is presented to us but rather should be defined by the wonderful members of its community. 

Chi-Town Watch was built to grow alongside the community it serves and above all else was built to evolve and change, helping the residents of Chicago reclaim the safe feeling that has been fleeting and allowing them to become aware and connect with other members of the community. 
## Citations
Patrick Andriesen. Chicago Policy Center, by Patrick Andriesen, January 29, et al. “Chicago Violent Crime Trends up as Arrests Trend Down.” Illinois Policy, 10 Mar. 2025, www.illinoispolicy.org/chicago-violent-crime-trends-up-as-arrests-trend-down/. 



