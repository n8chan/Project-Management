## FitFocus – Real-Time Fitness Recommendations Through Biofeedback and AI
Tarun Bathini, Spring 2025, [link to personal website](https://tbath18.github.io/personal-site1/).


### Abstract  

FitFocus is an open-source digital fitness platform designed to personalize workout and nutrition plans through real-time biofeedback and AI-driven recommendations. Addressing the common struggle of generic fitness advice, FitFocus tailors routines based on each user’s biometric data, workout patterns, and personal goals. The project was born from the need for an adaptive fitness solution that evolves with the user, providing smarter recommendations and reducing workout burnout. By integrating wearable data, location-based gym plans, and predictive analytics, FitFocus empowers users to make informed fitness decisions. This paper explores the journey of building FitFocus—from initial motivation and technical design to community engagement and long-term sustainability—showcasing how open-source collaboration can drive meaningful innovation in personal wellness technology.


### Introduction & Project Motivation
FitFocus started because I got tired of fitness apps that just throw generic workout plans at you without really understanding what you need. Most apps are good at tracking steps or logging meals, but they miss the point when it comes to personalizing your fitness journey. Every day is different. Sometimes you are sore, stressed, or just not feeling it, but the app still tells you to hit legs for an hour. That never made sense to me.

I wanted something smarter. Something that could look at my actual data like heart rate, recovery, sleep, and say, “Hey, maybe today is a good day for a light workout” or “You are ready to push harder today.” That is where FitFocus comes in. It uses real-time biofeedback to give you recommendations that make sense for you, not just some preset program.

But this is not just a solo project for me. I think fitness should be accessible and flexible for everyone. By making FitFocus open-source, other people can contribute their ideas, improve features, and make it better for all kinds of users. This way, it is not just another fitness app. It becomes a growing platform built by the people who actually use it.

### Project Design     

The main idea behind FitFocus is simple. Take real-time data from your body and use it to give you workout advice that actually makes sense. The app connects with wearables like Apple Watches, Fitbits, or even basic heart rate monitors. It pulls in data like heart rate variability, sleep quality, and step count. From there, it uses that info to recommend what type of workout you should do today.

For example, if you had a rough night of sleep and your heart rate variability is low, FitFocus might suggest active recovery like stretching or a light walk. On good days when your body is recovered, it will recommend more intense workouts. It is like having a coach that pays attention to how you are actually feeling.

The design is also super focused on keeping it easy to use. No complicated dashboards or data dumps. The app shows a simple “Today’s Recommendation” with a quick explanation of why it is suggesting that. Behind the scenes, it is crunching data, but for the user, it stays clean and stress-free.

I am also keeping the project modular. This means features like nutrition tracking, mood logging, or community workouts can be added over time without breaking the app. This way, other developers can contribute and expand FitFocus based on what people want.

### Technical Infrastructure & Workflow
To build FitFocus, I’m keeping the tech stack simple but effective. The front end will be done in React because it’s easy to build clean user interfaces and has a ton of community support. For the back end, I’ll use Node.js with Express, handling user accounts, API requests, and managing data. The database will be PostgreSQL to store user profiles, workout history, and biofeedback logs.

For the AI part, I’ll start with open-source models like MediaPipe for body pose estimation. This will let the app analyze workout form from videos or live camera feeds. Over time, as more users join, the model can be improved with community contributions.

The development process will follow a simple agile workflow. I’m planning short two-week sprints, where each sprint focuses on one core feature. After each sprint, I’ll do testing, get feedback, and make improvements. This keeps the project moving without overwhelming myself or any future contributors.

Here’s a rough timeline for the first version of FitFocus:

| **Phase**                | **Timeframe**   | **Goals**                             |
|--------------------------|-----------------|----------------------------------------|
| Research & Planning       | Weeks 1-2       | Define user needs, finalize features   |
| Frontend Development      | Weeks 3-5       | Build main UI, connect wearable APIs   |
| Backend Setup             | Weeks 6-7       | User authentication, data storage     |
| AI Integration            | Weeks 8-10      | Add form feedback & biofeedback logic  |
| Testing & Feedback        | Weeks 11-12     | User testing, fix bugs, polish UX      |
| Launch MVP                | Week 13         | Release first version to the public    |

All project tasks will be tracked using GitHub Projects for visibility and organization. Communication will happen on Discord for easy collaboration if more people join.

![FitFocus Workflow]([./FINALPAPERS/focusfit.jpg](https://github.com/OREL-group/Project-Management/blob/main/FINAL%20PAPERS/focusfit.jpg))

### Community Building & Sustainability

Since FitFocus is open-source, the goal is to build a community that actually wants to improve it, not just use it. The first step is making sure everything is well-documented. This means having a clean README, simple setup guides, and clear contribution rules. If people cannot figure out how to get started, they won’t bother contributing.

For communication, I’ll use a GitHub Discussions page and a Discord server for real-time chat. This makes it easier for developers, fitness enthusiasts, and even casual users to give feedback, suggest features, or report bugs.

One big focus is making FitFocus flexible. Developers should be able to add new workouts, new metrics, or even connect new devices without messing up the core app. To keep things organized, I’ll use GitHub Projects for task tracking and have a simple roadmap showing what features are planned next.

On the sustainability side, I’m not planning to monetize FitFocus in the beginning. Instead, I’ll explore GitHub Sponsors and OpenCollective to cover basic costs like hosting and domain names. Long-term, if there’s enough interest, partnerships with small gyms or fitness influencers could help keep the project alive while still keeping it free and open-source.

The key to sustainability is community ownership. FitFocus should not be a one-person project forever. By setting up a merit-based system where active contributors can become maintainers, the project can keep growing even if I’m not the only one working on it.



### Technical Debt & Risk Management  

Building FitFocus comes with several anticipated challenges that need to be addressed to ensure the project’s success.

One of the main concerns is data accuracy. Wearable devices often provide estimates rather than precise measurements, especially for metrics like heart rate variability or sleep quality. To mitigate this, FitFocus will present its recommendations as guidance rather than strict instructions. Users will always have the ability to adjust or override suggestions based on how they feel, keeping the experience flexible and user-driven.

Another challenge is community engagement. As an open-source project, FitFocus relies on contributors for growth and improvement. Attracting and retaining contributors requires clear documentation, beginner-friendly tasks, and active communication channels like GitHub Discussions and Discord. Building a welcoming and collaborative environment will be a priority from the start.

There is also the risk of feature bloat. Fitness apps often try to do too much, which can overwhelm users and complicate development. FitFocus will avoid this by maintaining a focused scope for the initial release, concentrating on form feedback, habit tracking, and adaptive workout recommendations. Future features will be added based on user feedback and community input, ensuring the project stays aligned with its core purpose.

From a technical standpoint, managing technical debt is essential. The development process will follow best practices such as modular code structure, version control, code reviews, and automated testing using GitHub Actions. This approach will help maintain code quality and ease future updates.

Finally, there is the challenge of sustainability and avoiding burnout. To address this, FitFocus will adopt a community-driven governance model, encouraging active contributors to take on maintainer roles. This shared ownership will help distribute responsibilities and keep the project evolving over time.

### Reflection & Learning
Working on FitFocus made me realize how much harder it is to build a useful project than it looks. It is easy to come up with cool ideas, but staying focused on what actually helps people is where the real work happens. I learned that trying to add too much at once can slow everything down. Keeping it simple and doing one thing well is more important.

One of the biggest things I learned is how much open-source depends on clear communication. Good code is not enough. You need to have solid documentation, clear instructions, and simple ways for people to get involved. If someone wants to help but cannot figure out how, they will just leave. That is on the project owner to fix.

I also learned that managing technical work is not just about writing code. Keeping things organized with version control and small, manageable updates makes life easier for everyone. If the project is clean and well-structured, it becomes easier for new people to contribute without getting lost.

Most of all, I learned that open-source is really about sharing the process. It is not about building something perfect by yourself. It is about creating something that other people can build with you. That mindset is what I want to take with me going forward.

### Conclusion

FitFocus started as a simple idea to make fitness advice more personal and actually useful. Over time, it grew into a project that taught me a lot about planning, building, and managing something real. This project is not just about workouts or tracking data. It is about creating a tool that respects how different everyone’s fitness journey is.

Through working on FitFocus, I learned how important it is to stay focused on solving one problem well. I also learned that open-source projects only grow when you make it easy for people to get involved. The best part of this process was seeing how open-source is not just about code. It is about community, learning, and building together.

Going forward, I hope FitFocus can become a platform that helps more people take control of their fitness in a way that works for them. With the help of contributors and users, this project can keep improving and growing beyond just my original vision.

Cite as the form (Lastname, 2023) in the body of your text. List reference citation in this section. 

## References

- [OpenPose: Real-time multi-person keypoint detection library by Carnegie Mellon University](https://github.com/CMU-Perceptual-Computing-Lab/openpose)

- [MediaPipe: Cross-platform machine learning solutions for live and streaming media (Google Developers)](https://mediapipe.dev/)

- [GitHub Open Source Guides: Best practices for open source project management](https://opensource.guide/)

- [The Open Source Way: Community-focused guide on open source principles](https://www.theopensourceway.org/)

- Csikszentmihalyi, M. *Flow: The Psychology of Optimal Experience*. Harper & Row, 1990.

- Lally, P., van Jaarsveld, C.H., Potts, H.W. et al. "How are habits formed: Modelling habit formation in the real world." *European Journal of Social Psychology*, 40, 998–1009 (2010).

