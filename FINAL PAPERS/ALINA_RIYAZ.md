# Focus Garden – Final Paper  
**Alina Riyaz, IS 340: Integrative Project Management, Spring 2025**

---
## Abstract  
Focus Garden is an open-source, solo-developed mindfulness and productivity tracker designed to promote intentional living through simple daily reflection. Born from the challenges of balancing academics, work, and emotional well-being, the project offers a lightweight system for individuals to log their focus, mood, and personal thoughts. At its core, Focus Garden is both a self-care tool and a digital ecosystem rooted in the values of working open. It empowers users to record and observe trends in their emotional and cognitive patterns over time through CSV-based tracking and journal prompts. The use of GitHub not only provides version control and structure, but also demonstrates transparency, encourages community involvement, and supports sustainability. Focus Garden transforms personal wellness from a solitary endeavor into a potentially communal and participatory one. This paper explores every facet of the project—from philosophical motivations to technical design, issue scoping, contributor onboarding, and long-term project lifecycle planning—all through the lens of open-source best practices. It is a story of how simplicity, honesty, and open collaboration can turn a personal tool into a public good.

---

## Introduction and Project Motivation  
The initial spark for Focus Garden came not from a technical problem, but from an emotional one. During a particularly overwhelming semester filled with deadlines, job interviews, and family responsibilities, I realized I was functioning more like a machine than a person. I was completing tasks, attending meetings, submitting assignments—but never stopping to ask myself how I was doing. I had no space in my daily life to reflect, decompress, or even identify how my mental state was affecting my performance. I tried traditional productivity apps, but they were either too complex, too goal-oriented, or too commercialized. They offered gamified dashboards and elaborate visualizations, but they lacked the gentle humanity I was seeking. I didn’t want to be optimized—I wanted to be understood, first by myself.

In that moment, Focus Garden began as a personal remedy. What if I could build something that asked only one thing of me each day: to check in? No goals, no metrics, no social feeds—just a digital garden where I could log my focus, my mood, and a few thoughts. That’s it. If I felt amazing, great. If I felt terrible, that was okay too. Every day’s log would be a drop of water, and over time, the habit would help something grow: not just emotional resilience, but awareness, gentleness, and consistency.

As I began thinking more intentionally about the structure of this tracker, I realized that this concept—simple as it was—could benefit from being open. In fact, it needed to be open. Because Focus Garden isn’t just about me; it’s about the universal need for low-pressure reflection. It’s about reclaiming self-care from app stores and paywalls and returning it to the commons. If I could build the system to be transparent, modifiable, and welcoming, then other people—students, professionals, caregivers, and even total beginners—could use it, adapt it, or contribute to it. The idea transformed from a solo journaling experiment into a fully open-source ecosystem.

That’s why this project lives on GitHub, why every decision is documented in Markdown, and why the entire structure—from issues to features—is built around modularity and inclusiveness. Focus Garden, as I envisioned it, should grow like a real garden: slowly, with care, and in community. This paper is both a technical report and a personal reflection on how I built this project, what I learned, and how it lives as a manifestation of the working open principles we studied in IS 340.

## Project Design

From the very beginning, I wanted Focus Garden to be a quiet, thoughtful space—not just in its purpose, but in its design. This meant making decisions that prioritized simplicity, accessibility, and openness above all else. I was not building a flashy app with visualizations or rewards systems. I was building a tool that someone—myself included—could open with minimal effort and maximum trust. To achieve that, the design had to feel as natural as possible, as if it were an extension of a notebook or a quiet moment, rather than a platform demanding performance.

Focus Garden is centered around two components: a CSV file for structured, numerical tracking, and a Markdown-based journaling template for emotional and qualitative reflection. The CSV, named `focus_log.csv`, includes four simple fields: Date, Focus (1–5), Mood (1–5), and Notes. These fields are intentionally minimal. They offer just enough structure to capture patterns without becoming overwhelming. The use of numbers allows for lightweight trend analysis over time, but they’re not there to judge the user—they're just anchors for reflection. The “Notes” field, in particular, invites honesty. It can be one word or an entire paragraph. It’s flexible, forgiving, and completely optional.

The journaling component lives in `docs/journal_template.md`. It offers a more spacious format for those days when numbers aren’t enough. The prompts are gentle and introspective: “What helped you focus today?” “What drained your energy?” “What’s something you’re proud of?” These questions aren’t tied to any goals or metrics—they exist to encourage storytelling. Because sometimes, understanding our focus or mood doesn’t come from measuring it—it comes from naming it, exploring it, and letting it unfold. The Markdown format makes the journaling template portable, editable, and easy to use across devices and platforms.

Every file in the Focus Garden repository has a purpose, and every design decision was made with both the user and the future contributor in mind. The `README.md` acts as a welcoming front door, clearly explaining the project’s mission, how to use it, and how to get involved. The `CONTRIBUTING.md` file outlines low-barrier ways to participate—no coding required. Want to suggest a new journal prompt? Great. Want to tweak the CSV format? Let’s talk. The tone is conversational and inclusive, because if this project is truly going to embody “working open,” then it has to feel like a space where everyone’s ideas are welcome.

One of the most important lessons I carried from IS 340 into the design of this project was the idea that structure is an act of care. When we label our files clearly, when we organize our folders intuitively, when we explain our intentions in our commits and issues—we aren’t just making things easier to find. We’re creating a culture of thoughtfulness. Focus Garden’s design is simple, yes—but that simplicity is the result of deep intentionality. Every piece was crafted to invite reflection, encourage contribution, and honor the quiet complexity of daily life.

## Technical Infrastructure & GitHub Workflow

While the emotional heart of Focus Garden lies in daily reflection and self-awareness, the structural integrity of the project is built through a clean, open, and sustainable GitHub workflow. One of the most empowering things I learned in IS 340 is that infrastructure doesn't need to be flashy to be meaningful—it just needs to be intentional. In the same way that a well-laid garden bed makes space for growth, a well-organized repository makes space for collaboration, understanding, and evolution. That’s exactly what I set out to build.

The repository begins with a simple structure. At the root level, you’ll find the `README.md`, which serves as both introduction and invitation. It outlines the project’s purpose, how to get started, and where to contribute. It doesn’t assume you’re a developer or a technical expert—it just assumes you’re curious. Alongside the README sits `CONTRIBUTING.md`, which acts as a conversation starter with new collaborators. Instead of presenting a checklist of commands, it offers context: why the project matters, what kinds of contributions are welcome, and how to submit them without fear of “getting it wrong.” That tone of welcome—clear, gentle, and inclusive—was directly inspired by our discussions on contributor experience and working open philosophy in class.

The project’s primary files live in two subfolders: `/data/` and `/docs/`. The `/data/` folder holds the `focus_log.csv`, a file designed to be both functional and familiar. Whether opened in Excel, Google Sheets, or a basic text editor, the file is readable and writable. There are no complicated schemas or database dependencies—just rows of real, human entries. In `/docs/`, you’ll find the journaling template, the Open Canvas for the project, and future space for templates, community prompts, or contributor highlights. Everything is written in plain Markdown, because simplicity isn’t just a design choice here—it’s a philosophy.

The GitHub project board, meanwhile, is where the garden planning happens. Modeled after the Kanban boards we explored in our lectures, the board has three core columns: `Planned Features`, `In Progress`, and `Completed`. Each issue on the board is scoped intentionally, drawing on the Earth/Moon/Mars model we studied. I leaned heavily into Earth Shot issues—small, achievable tasks that could be tackled without context overload. Examples include “Add three new journal prompts,” “Write description for focus_log.csv,” and “Label issues by contribution type.” By keeping issues bite-sized and descriptive, I’m not just tracking tasks—I’m telling a story of what’s happening in the project and how others can participate.

Beyond just the board, I also used GitHub’s features for labeling, assignment, and pull request tracking. Every commit has a clear message tied back to an issue. This isn’t about bureaucracy—it’s about transparency. If someone wants to understand why a feature was added or how a decision was made, they can trace the conversation in the open. This kind of digital paper trail is one of the most beautiful aspects of working in the open—it transforms development into dialogue.

One of the things I’m proudest of is how this infrastructure stays true to the project's emotional roots. Even though it lives in a technical space, the repository never forgets that its purpose is to support people in understanding themselves. That’s why the infrastructure is gentle. That’s why it’s clean, well-labeled, and kind. Because infrastructure, when done right, isn’t just about efficiency—it’s about care. And in the context of Focus Garden, that care shows up in every branch, every file name, and every issue.

## Working Open Philosophy & Community Mindset

Working open is not just a strategy—it’s a mindset, a culture, and, in many ways, a quiet act of resistance. In a digital world dominated by closed systems, opaque algorithms, and hyper-optimized products, Focus Garden stands as a gentle rejection of all that. It doesn’t track your clicks or optimize your attention span. It doesn’t sell your data or gamify your mental health. It simply says: here’s a place to slow down, reflect, and grow—and if you want to be part of that, you’re welcome to join. That, in essence, is what working open means to me.

I was deeply influenced by the Mozilla Foundation’s definition of working open, which emphasizes radical transparency, modular contribution, shared ownership, and inclusive governance. From the beginning, I knew that if Focus Garden was going to live up to these ideals, it couldn’t just be a tool—it had to be a community. That doesn’t mean it needed thousands of users or weekly contributor meetings. It just meant that every decision, every file, every interaction had to be made with people in mind—real people, with different skills, comfort levels, and emotional needs.

That’s why I designed every aspect of the project to be welcoming. The issues are not just technical—they’re human. Many of them invite reflection, creativity, and feedback. For example, one issue simply asks: “What would you want a journaling prompt to ask you on a tough day?” That’s not a bug to fix or a feature to add. That’s a doorway. A moment of connection. And if someone responds—even once—that’s success. Because the value of working open isn’t measured in stars or forks—it’s measured in invitations, in voices, in trust.

The contributor pathway was another key component of this philosophy. Inspired by our class’s discussions on community building and contributor onboarding, I created a `CONTRIBUTING.md` file that doesn’t read like legalese. It reads like a conversation. It explains what the project is, how it works, and what kinds of contributions are welcome—whether you’re submitting a new journal prompt, translating a Markdown file, or suggesting a change to the mood scale. There’s no hierarchy, no gatekeeping, no “rockstar developers.” There’s just a garden. And in this garden, everyone has a place.

I also created issues labeled as “Good First Issue” with extra guidance and context, so that even someone new to GitHub could get involved without feeling overwhelmed. These small gestures—labeling, context, warmth—go a long way. They signal that the project isn’t just technically open-source, but emotionally open-source too. And that distinction matters.

Another key pillar of working open is visibility. That’s why I’ve kept every idea, change, and roadmap entry in the open. Even if no one sees it today, it’s there. Documented. Visible. Traceable. Because someone might discover this project a year from now and want to know how it came to be. And they’ll see that it was built not in secret, but in sunlight. That’s working open.

Ultimately, working open is about generosity. It’s about building not just for yourself, but for others—without assumptions or expectations. Focus Garden lives that value in every line of text, every issue, and every interaction. It’s not perfect. It’s not finished. But it’s open. And in that openness, it offers a quiet but powerful invitation: let’s grow something together.

## Sustainability & Long-Term Growth

Sustainability in open-source isn’t just about technical uptime—it’s about emotional endurance, thoughtful planning, and preparing for the quiet moments between contributions. One of the most resonant lessons I took from IS 340 is that sustainability must be designed from the beginning. Not bolted on. Not reactive. It’s a value, not a feature. With Focus Garden, I knew from the outset that I wasn’t just creating a tool for today—I was planting something I hoped could last.

The first pillar of that sustainability plan is simplicity. Focus Garden intentionally avoids complex infrastructure. It doesn’t require dependencies, packages, or third-party services. It doesn’t rely on APIs or servers or external libraries that could change or vanish. Everything lives in plain text. That means the barrier to long-term maintenance is low. Anyone can fork it, edit it, or use it without needing to spin up a dev environment. In the same way that a good journal should work offline, this project works in the quietest, simplest technical contexts.

The second pillar is documentation. Every element of the project is labeled, explained, and commented. Each folder has a purpose. Each file has a name that tells a story. The `README.md` doesn’t assume prior knowledge. The `CONTRIBUTING.md` doesn’t assume confidence. Even the `focus_log.csv` file is seeded with examples that show—not just tell—how it’s meant to be used. I wrote the documentation not for “power users,” but for someone who might stumble on this project at 2 a.m. during a moment of burnout, looking for a gentle way back to themselves. That’s who I wrote for. That’s who I want to sustain.

The third pillar is modularity. One of the common causes of project collapse in open-source is overreach—trying to do too much in one place, or depending on interlocked systems that become fragile over time. Focus Garden avoids that trap by staying flexible. Want to use just the journal prompts? You can. Want to extend the CSV with new metrics like sleep or energy? Easy. Want to fork the project and build a web interface on top of it? Go for it. Nothing breaks. Because each piece—each file, each feature—can stand alone or be recombined. That’s intentional. That’s resilient.

But sustainability also means preparing for the human lifecycle of a project. There may be periods of growth and interest—and there may be long, quiet stretches where nothing changes. That’s okay. In fact, I expect it. Focus Garden isn’t chasing hype. It’s not a startup. It’s a slow project, a living thing, and its value isn’t tied to stars or downloads. It exists because it’s useful. If even one person uses it to reconnect with themselves, it has done its job. That’s a radically different definition of success—but it’s the one that sustains me.

I’ve also built in space for future evolution. In the project’s `/docs` folder, I maintain an `ideas.md` file—a kind of open garden bed for new features and dreams. Maybe one day someone will add visualization tools, build a mobile client, or integrate audio journaling. Maybe someone will translate the prompts into other languages or use the format for community workshops. Maybe none of that will happen. But the ideas are there. They’re open. And more importantly, the path to implement them is clear, documented, and unobstructed.

Finally, sustainability means designing for succession. I may not always be the maintainer of Focus Garden. Life moves. People grow. But the project can outlast me if it’s open enough, documented enough, and inviting enough. That’s the goal. To create something that isn’t just personally meaningful—but that could be carried forward by others, adapted for new needs, and kept alive through care, not coercion.

In this way, Focus Garden is an act of stewardship. I’m not the owner—I’m the first caretaker. And everything I’ve done, from the folder structure to the tone of the writing, has been in service of that future caretaker. Because open-source isn’t just about building things—it’s about building them so they can live.

## Reflection & Personal Learning

When I started Focus Garden, I was trying to fix something I didn’t have a name for. I didn’t set out to build an open-source project, or to demonstrate version control best practices, or to write a 20,000-word paper. I was just trying to build something small and soft—a space to breathe, to check in with myself, and to slowly, gently come back to a sense of center. But somewhere in the process, that intention grew roots. And it sprouted into something that lives in the world now. Something open. Something others can touch.

This project taught me more than any textbook or tutorial ever could. It taught me how to take a vision and translate it into structure. It taught me how to organize not just code, but care. Every commit message, every issue label, every sentence in a Markdown file became a small act of communication. A signal to the future that said, “Here’s what I’m trying to do. You’re welcome to help.”

There were moments of doubt, of course. Times when I questioned whether the project was too simple, too personal, or too niche. But IS 340 reminded me that simplicity is not a flaw—it’s a feature. And personal does not mean private. Personal can still be shared. In fact, some of the most impactful open-source projects in the world started with one person trying to solve a problem for themselves. That’s where clarity comes from. That’s where empathy begins.

I also learned to see GitHub differently—not just as a technical platform, but as a canvas for collaboration. I used to be intimidated by issues and pull requests. Now I see them as storytelling tools. Each one captures a moment in the project’s evolution. Together, they form a narrative. And that narrative is open to anyone who wants to join.

Perhaps most importantly, I now understand what it means to work open—not just as a method, but as a way of being. It means writing documentation like you’re speaking to a friend. It means leaving comments for the person who might come next. It means being okay with imperfection, because perfection was never the point. The point is to grow. Together.

Focus Garden is still small. It always might be. But that’s okay. Gardens aren’t built to scale—they’re built to nourish. And if this project nourishes even one person, for even one moment, then it has already succeeded.

---

## Conclusion

Focus Garden began as a personal coping mechanism. It became a digital space for reflection. Then it evolved into a community-centered, values-driven, working open project. Through the design of its files, the flow of its issues, the tone of its documentation, and the care in its structure, it embodies everything I’ve learned in IS 340—and everything I hope to carry forward.

I built this project not just as a final assignment, but as a lasting contribution to a more mindful, more generous way of building software and systems. It’s not a product. It’s not a portfolio piece. It’s a quiet offering. A small, open invitation to slow down, breathe, and grow—together.

Thank you.

---

## References
- Mozilla Working Open Guide: https://mozillascience.github.io/open-science-leadership-workshop/01.2-working_open.html  
- Fogel, K. (2005). *Producing Open Source Software*. https://producingoss.com  
- GitHub Docs: https://docs.github.com/en  
- IS 340 Lecture Slides, Lectures 1–22  
- Bainbridge, L. (1983). *Ironies of Automation*  
- Cotton, B. (2021). *Program Management for Open Source Projects*  
- Jhangiani, R. & Biswas-Diener, R. (2017). *Open: The Philosophy and Practices That Are Revolutionizing Education and Science*
