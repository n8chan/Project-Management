Anantya Kasturi, IS 340, Spring 2025

## FitSync

---

### Background

The demand for more accessible, personalized, and inclusive fitness solutions continues to grow in today’s digital health and wellness industry. Although there are many fitness and nutrition apps constantly in the works, many fall short of fully including the individual and more nuanced differences in people, specifically women. Some of these differences include menstrual cycles, biofeedback, lifestyle routines, and medical history, which significantly alter how a woman should be training. In particular, women often encounter obstacles when using generalized fitness platforms that tend to overlook the key physiological factors that are unique to them. 
FitSync’s goal is to address this gap by offering a platform that is tailored to women’s health and nutrition. By bringing together personalized recommendations and real-time feedback, location-based gym plans, and menstrual cycle syncing, our project aims to provide women with a holistic and more scalable solution to workout and meal tracking. Unlike traditional fitness platforms, we incorporated holistic personalization and many other features that take into account women’s physiology. FitSync aims to help women who face obstacles in the lack of inclusive tools, intimidating gym culture, and inconsistent advice. Furthermore, the rise of wearable devices such as Apple watches and Fitbits connect well with our AI and create an opportunity for a smart fitness platform. Our mission is to bridge the gap by integrating biofeedback, medical conditions, and menstrual health into one unified platform.


---

### Purpose

Our purpose is to revolutionize digital fitness and nutrition by developing a full-stack application that is tailored for women. This project is designed to:

- Allow women to personalize their meals and workouts based on menstrual cycles, biofeedback, medical conditions, and dietary restrictions
- Make fitness and exercise less intimidating for beginners and more accessible overall
- Give women a supportive safe space that adapts to each individual’s goals and their progress over time
- Utilize AI and ML models to give users intelligent recommendations and display predictive analytics
- Enable real-time equipment-based workout plans via location and gym tracking
- Address gaps in long-term hormonal changes and analytics

Ultimately, our goal is to empower users to be in charge of their fitness through a more comprehensive, and user-friendly platform. Your personalized wellness experience evolves with you. 


---

#### Target Audience

Our platform is primarily designed for the following users:

- Women ages 18-140, seeking personalized nutrition and fitness plans
- People managing hormonal medical conditions such as PCOS and endometriosis
- Active individuals who use wearables like Fitbits and Apple watches
- Users with specific medical conditions or dietary restrictions that require tailored routines
- Beginners in fitness who may feel intimidated by traditional gym cultures or apps
- Technologically adept users looking for advances tracking using AI insights and data integration
- Healthcare professionals or trainers who want to recommend more personalized plans to their clients

Overall, FitSync looks to have a user-centric approach that ensures inclusivity for people from diverse backgrounds, fitness levels and health goals. 


---

### Workflow

The FitSync project will follow an agile development strategy with the following key phases:

- Gathering requirements: analyze user needs, consult with healthcare professionals, and gather data on user fitness habits
- Design & prototype: UI/UX design using Figma, workflow diagrams, and wireframe development
- Development
    - Frontend: React.js for dynamic interfaces
    - Backend: Node.js + Express for real-time API handling
    - Database: PostgreSQL for structured data, MongoDB for unstructured input data
- ML Integration: Develop and train models using PyTorch and TensorFlow for personalized fitness and meal plans
- Deployment: AWS for cloud scalability, CI/CD pipelines for more seamless integration and updates
- Testing: Conduct unit testing, integration testing, and user testing
- Iterations: Use feedback-driven improvements across all components of the application


![Workflow](https://github.com/OREL-group/Project-Management/blob/1c3ec5842090bb13e3e5ccdcba5e5a7b50c96738/FINAL%20PAPERS/FitSync.jpg)


---

### Strategy

Our core strategy revolves around the ability to personalize, scalability measures, and accessibility:

- Technology selection: We chose community, supported tools such as React.js, Node.js, and PostgreSQL
- Data handling: By splitting structured and unstructured data between PostgreSQL and MongoDB, we can achieve more efficient processing
- ML strategy: Utilizing PyTorch for prototype modeling and TensorFlow for production-grade deployment will allow for more scalability
- Cloud Infrastructure: We are using AWS for flexible scaling, computer power, and storage
- User engagement: Included features like equipment base exercise filters, smart notifications, and cycle-tracking calendars

This approach allows us to ensure long-term maintenance of the app, the ability to adapt to user feedback, and a higher degree of technical flexibility.

Proposed Timeline

| Phase | Duration    | Milestones    |
| :-----: | :---: | :---: |
| Planning & Research  | Month 1   | Finalize tech stack   |
| App Development | Months 2-3   | Core web app development   |
| Integration & Testing | Month 4   | Wearables, menstrual tracking, gym API   |
| User Feedback | Month 5   | Pilot test with initial users   |
| Final Adjustments | Month 6   | Bug fixes, UX refinements   |
| Launch | Month 7   | Public release & marketing rollout   |


---

#### Addressing Technical Debt

Although technical debt may be inevitable for any software project, specifically one with the complexity of FitSync, our goal is to try and minimize it from the beginning. The following strategies have been put in place to to minimize the impact of technical debt:

- Tool selection: All core tools (React, Node, PostgreSQL) are used extensively and have long-term support
- Code practices: By employing clean code principles and conducting code reviews, modular development can be tracked
- CI/CD pipelines: Testing is automated and deployment catches regressions early
- Documentation: Maintaining a comprehensive internal documentation to make onboarding and future chances easier
- Architecture: Backend is microservice-style where components like workout planning and nutrition recommendations are can be scaled independently
- Following community guidelines from the beginning
- Scheduled audits and refactor sprints
- Cloud optimization and cost forecasting
- Third-party API setup as a backup

These decisions can help us reduce refactoring costs while improving development and ensuring resilience as our platform eveloves and transforms. 


---

### Challenges

We anticipate some challenges during the growth and development of FitSync:
- Fast Technology Evolution: Libraries like React and TensorFlow frequently update: Continuous integration is crucial to avoid mismatches in versions and deprecated functionality
- Scalability Concerns: As our user numbers grow, PostgreSQL queries may slow down, requiring optimization or migration to more distributed systems
- Data Privacy & Security: Handling sensitive health data demands compliance with regulations like HIPAA and GDPR, which we plan to be mindful of from the get-go
- AI Model Retraining: Fitness recommendations that are based on dynamic inputs will require ongoing model retraining and evaluation
- Third-party API Dependencies: External APIs for gym locations and wearables could change or be discontinued
- User Diversity: Designing for a wide range of body types, goals, and fitness levels introduces UX complexity

Addressing these challenges will allow us to be proactive of our resource allocation, robust infrastructure planning, and user-centered testing.


---

### Conclusion

FitSync’s ambition is a crucial step forward towards transforming the fitness industry for women through technological innovations. By bringing together biofeedback, AI, and a scalable cloud infrastructure, our platform aims to create a more supportive, personalized, and data-driven experience for all users. Throughout the careful planning, strategic tool choices, and ongoing adaptability measures, we have kept in mind addressing real user’s needs, minimizing our technical debt, and remaining competitive in the years to come. Our user-first approach and philosophy for the integration of menstrual health into fitness planning marks it as a pioneering platform in digital wellness. 

---

### References

Author links open overlay panel Michelle Segar MS, et al. “Fitting Fitness into Women’s Lives: Effects of a Gender-Tailored Physical Activity Intervention.” Women’s Health Issues, Elsevier, 20 Nov. 2002, www.sciencedirect.com/science/article/abs/pii/S1049386702001561. 

Heitz, N A, et al. “Hormonal Changes throughout the Menstrual Cycle and Increased Anterior Cruciate Ligament Laxity in Females.” Journal of Athletic Training, U.S. National Library of Medicine, Apr. 1999, pmc.ncbi.nlm.nih.gov/articles/PMC1322903/. 

Jonge, Xanne A.K. Janse de, and Belinda M. Thompson. “Adapting Training to the Menstrual Cycle.” Human Kinetics, Human Kinetics, 6 July 2023, journals.humankinetics.com/view/journals/ijspp/18/8/article-p793.xml. 

Scientist, *Principal. “Physiological Changes Associated with the Menstrual Cycle:... : Obstetrical & Gynecological Survey.” LWW, journals.lww.com/obgynsurvey/abstract/2009/01000/physiological_changes_associated_with_the.23.aspx. Accessed 8 May 2025. 

