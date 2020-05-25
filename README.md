# Playbook

What you'll find here are samples of content I've written that is not published on my blog. I'm using the term "Playbook" because it's one way of referring to a set of guidelines that can be helpful in many different organizational contexts, and what you'll find here are examples of such content that I've written. 

The content is organized based on the following categories:

+ Quick Start Guides
+ (more categoreis to follow)

## Quick Start Guides

The Quick Start Guides consist of brief summaries of what I've found to be effective when working with teams, and which are likely to be particularly helpful to anyone who would like some general guidelines, which are not intended to be prescriptive, but which can serve as a baseline for any team to work from. Most of the Quick Start Guides focus on Scrum-related topics (Scrum Events). The rest of them cover other areas that we often encounter as facilitators.

**Scrum Topics:**

+ [Backlog Refinement Quick Start Guide](#backlog-refinement-quick-start-guide)
+ [Daily Scrum Quick Start Guide](#daily-scrum-quick-start-guide)
+ [Sprint Planning Quick Start Guide](#sprint-planning-quick-start-guide)
+ [Sprint Review Quick Start Guide](#sprint-review-quick-start-guide)
+ [Sprint Retrospective Quick Start Guide](#sprint-retrospective-quick-start-guide)

**Additional Topics:**

+ Story Splitting Quick Start Guide (to be added in a later commmit)
+ Writing Well-Articulated User Stories Quick Start Guide (to be added in a later commit)

### Backlog Refinement Quick Start Guide

Introductory Note: Backlog Refinement (also known as Backlog Grooming) is an activity that is not part of the [Scrum Guide](https://www.scrumguides.org/scrum-guide.html). However, the practice of Backlog Refinement is so common among Scrum teams that some practitioners consider it a Generally Accepted Scrum Practice (GASP). 

#### Definition
Backlog Refinement is an ongoing process of readying user stories for upcoming iterations (Sprints). There are two main aspects of Backlog Refinement: 
+ Ongoing definition, refinement, clarification, and reprioritization of functionality, often led by Product Managers and Product Owners;
+ A collaborative meeting prior to the start of a Sprint to evaluate new information, ensure the next set of stories is ready for development, and reach early consensus on a set of stories to be included in the upcoming Sprint Backlog. 

#### Frequency
+ Once per Sprint (typically mid-Sprint)

Note: Some teams choose to have Backlog Refinement sessions more than once per Sprint. 

#### Duration 

Teams should strive to complete Backlog Refinement for a two-week Sprint in an hour or less. It is more likely for teams to be able to complete Backlog Refinement in a reasonably short amount of time when stories are well-articulated well before the Backlog Refinement session starts. (See also the Writing Well-Articulated User Stories Quick Start Guide.)

#### Participants, Inputs, Outputs 

+ Participants - Product Owner, Scrum Master, Development Team
+ Inputs – Primary inputs are the user stories forecasted for the upcoming Sprint, and also some additional stories that might be a good choice for a subsequent Sprint. It is helpful to have more user stories in a ready state than are likely to fit in the next Sprint, so that there is flexibility in case the team identifies a dependency, has new information that could impact priority or effort of one or more stories, or when questions surface that might need to be answered before working on a particular story.
+ Outputs - Consensus on a set of prioritized, clearly-defined, independent, small user stories that are framed to generate valuable and demonstrable functionality during an upcoming Sprint. 

#### Activities

Activities during Backlog Refinement typically include: 
+ Review new information learned from the current Sprint
+ Discuss Best, Probable, and Worst case Velocities
+ Do a checkpoint on current Sprint progress - do we feel we will complete all the work during the Sprint that we thought we would? 
  + When answering this question, keep sustainable pace in mind
  + It is better for the team to realistically assess how things are looking mid-Sprint than it is to wait until the end of the Sprint to make any course corrections that might be needed 
+ Review and clarify upcoming user stories
+ Discuss and agree to Acceptance Criteria to confirm shared understanding Confirm size estimates and slice stories that are too big 
  + Reminder: Any story that a team thinks will take more than half of a Sprint to complete is too big 
+ Agree on the plan for the next Sprint 
  + Based on our velocity prediction and sizing, is this a realistic plan?
  + If the answer to the previous question is "no," work to slice stories, and/or swap in smaller stories of similar priority, until the team feels confident in the plan 

Note: See also [Backlog Refinement and Sprint Planning: Similarities and Differences](https://medium.com/agile-outside-the-box/backlog-refinement-and-sprint-planning-similarities-and-differences-d08761aca3ae)

### Daily Scrum Quick Start Guide

#### Definition 

The Daily Scrum (aka Daily Standup) is the opportunity for a Development Team to make sure they are in alignment every day via a short, focused conversation. The main things that happen during the Daily Scrum: 

+ Share knowledge
+ Identify opportunities to help another team member  
+ Identify dependencies/risks
+ Agree on next steps for removing roadblocks 

#### Frequency

Once every day (generally with the exception of the first day of the Sprint) 

#### Duration

The duration of a Daily Scrum is intended to be no longer than 15 minutes. 

#### Participants, Inputs, Outputs 

+ Participants - Development Team, Scrum Master (or other facilitator), Product Owner +
+ Inputs – Primary input is any work for which the workflow state has changed since the last Daily Scrum. Other potential inputs include any anomalies that might have surfaced during testing, changes in priority, or anything else that could impact the work that is planned for the Sprint 
+ Outputs – Agreement among team members about what to do to address any impediments that have surfaced, and how they can most effectively work together during the next 24 hours to move any in-progress work items to done 

(+) *Participants are listed in order of importance: The Daily Scrum is for the Development Team, and thus, the meeting belongs to them. A Scrum Master is often present as a facilitator. However, it is also common for different members of the team to take turns acting as the facilitator. It can also be helpful for the Product Owner to be present, to clarify any product-related questions that might arise.* 

Activities
An example of a “Daily Standup Routine” is as follows: 
+	Start the Call 
+ Walk the Wall (take a quick look at where things are in the workflow, where the wall can be a physical card wall, or a virtual wall, in Jira, or both) 
+ Headlines (is there anything particularly urgent that needs to be discussed?)
+ Updates (blockers or other information team members would like to mention)
+ High Five (just like it sounds, whether physical or virtual ...  ;)
+ After Party (synonymous with a Parking Lot – a time to have a follow-up conversation, if necessary; in some cases, only a subset of team members may be needed for an After Party).
+ Update the board (if the workflow state of any work item was updated during the conversation) 

Note: H/T to Jimmy Janlén for the "Daily Standup Routine" idea, in his book [Toolbox for the Agile Coach: Visualization Examples](https://visualizationexamples.com/).

Note 2: See also [Daily Standup Patterns](https://medium.com/agile-outside-the-box/daily-standup-patterns-d69ff48e1087) 

### Sprint Planning Quick Start Guide 

#### Definition 

Sprint Planning is a meeting that focuses on making sure there is complete clarity on what the team plans to work on during a Sprint that is about to start. There are several key aspects of Sprint Planning: 
+ Formulation of/refinement of Sprint Goal(s)
+ Discussion about/confirmation of functionality (stories) to be worked on during the Sprint, based on their relative priority
+ A deeper dive conversation that can, on some teams, include task decomposition, where the team identifies specific tasks that need to be completed for any given story they are planning to work on 

#### Frequency

Once per sprint (the first day of the Sprint) 

#### Duration 

Provided that Backlog Refinement has been done before Sprint Planning begins, many teams are able to complete Sprint Planning in an hour or less. The higher the degree of uncertainty about the work that is to be done during the Sprint, the greater the likelihood that Sprint Planning could take more than one hour. 

#### Participants, Inputs, Outputs 

+ Participants - Development Team, Product Owner, Scrum Master
+ Inputs – Primary input is a set of well-defined (clearly written, sized, prioritized, with Acceptance Criteria) stories from the previous Backlog Refinement session. Other potential inputs include any changes to priority since the Backlog Refinement session, or unfinished stories from the Sprint that just ended
+ Outputs – Sprint Goal(s) and a well-articulated Sprint Backlog 

#### Activities 

+ Start with one or more Sprint Goals (to be revisited at the end of the session)
+ Capture any business or technical assumptions that the team is making about the work they plan to do (which can also be a helpful way to make sure no important information was missed during Backlog Refinement)
+ Review any other new information which may have surfaced since the previous Backlog Refinement: 
  + Any changes to prioritization of stories to be worked on next
  + Any stories not completed during the Sprint that just ended, which *could* be worked on during the Sprint that is about to start, depending on their priority 
+ Review who (if anyone) is going to be out of the office, and for how long
+ Surface any dependencies or risks, including who might be the owner(s) for mitigating those dependencies or risks, and what the expected impact could be
+ Review and clarify user stories: 
  + Confirm story wording for clarity Confirm Acceptance Criteria Confirm relative size 
  + (optional) Task decomposition: Some teams choose to further break each story down into a set of tasks during Sprint Planning, some teams do task decomposition individually (after Sprint Planning is over), and some teams do no task decomposition at all 
  + The newer the team is to working with each other, the higher the likelihood that task decomposition could be helpful to them 
  + Many teams that have been working together for a while find that task decomposition is not necessary, especially when those teams are consistent about breaking stories down into reasonably small pieces 
+ Agree on the plan for the Sprint:
  + Based on team capacity, is this a realistic plan?
  + Are all dependencies or risks identified, along with any Action Items needed to ensure the dependencies or risks do not become impediments?
    + If the answer to either of the previous questions is "no," look for ways to allocate work more evenly among team members, and/or account for what needs to happen to address dependencies or risks
+ When the team reaches agreement on the plan, ensure that the physical board (if the team is using one) and Jira are updated accordingly
+ Revisit the Sprint Goal(s) and make sure they align with the team's plan for the Sprint 
 
### Sprint Retrospective Quick Start Guide 

#### Definition
The Sprint Retrospective is an opportunity for a team to have an open and honest conversation, which typically focuses on the work the team did during a Sprint that is coming to a close. The Sprint Retrospective is the team-level enabler of Kaizen, or Continuous Improvement. 

#### Frequency
Once per sprint (the last day of the Sprint) 

#### Duration 
Team context plays a significant role in the duration of a Sprint Retrospective. For teams that are relatively new to working with each other, or that find themselves in a situation where they need to surface and overcome significant challenges, a miminum of one hour is likely to be neeed. Other teams may find that 30 minutes is sufficient for their Sprint Retrospective. 

#### Participants, Inputs, Outputs 
+ Participants - Scrum Master, Product Owner,+, Development Team++
+ Input – Primary input is the sum total of the interactions the team had during the Sprint
+ Outputs – Clarity about potential changes to the team’s way of working, articulated as one or more actionable steps that the team agrees to which can help them work together as effectively as possible +++ 

(+) *Some Agile practitioners suggest that it is unnecessary (or even undesirable) for a Product Owner to attend a Sprint Retrospective. Given the importance of the relationship between and among the Product Owner, the Scrum Master, and the Development Team, as a general practice, enabling the Product Owner to be part of the Retrospective conversation is likely to help that team continuously improve.*

(++) *In the interest of psychological safety, it is a standard practice that ONLY the members of the Development Team, the Scrum Master, and the Product Owner attend Sprint Retrospectives.*

(+++) *Teams often discuss a great many things during the Sprint Retrospective, however, what the team talks about during the Sprint Retrospective is considered confidential, and is not shared with anyone who was not present during the conversation, unless all members of the team agree to share one or more parts of the conversation. The chief exception: any actionable steps that the team identifies to help them improve, which typically are made visible to others.* 

#### Activities 
+ The facilitator (who is most often a Scrum Master) sets the stage for the conversation
+ The Sprint Retrospective is more likely to be a productive use of time if and when the facilitator has prepared in advance for what activities and what types of conversations are most likely to help the team, based on its particular context
+ To establish psychological safety, it is helpful to always keep the “retrospective prime directive,” as articulated by Norm Kerth, in mind: 

> Regardless of what we discover, we understand and truly believe that everyone did the best job they could, given what they knew at the time, their skills and abilities, the resources available, and the situation at hand.

+ With the help of the facilitator, the team reflects back on the Sprint that has just ended. A common set of three areas to talk about are:+ 
  + What went well during the Sprint
  + What did not go so well during the Sprint
  + What actionable steps can the team potentially take to improve going forward 
+ It is important to never lose sight of the positive. A good way to help ensure that positive observations are included can be as simple as asking something like “who would like to thank another team member” (or someone external to the team) for something they helped with during the Sprint?”
+ The actionable steps that the team agrees to are made available in a visible place, which helps ensure that the team remembers to work together to address those areas of potential improvement 

(+) *The universe of potential approaches for retrospective facilitation is vast. Teams are far more likely to get value out of Sprint Retrospectives over time if and when the questions that are asked and the way in which they are framed and answered varies from one Sprint to another.*
 
### Sprint Review Quick Start Guide

#### Definition 
The Sprint Review is a meeting that focuses on making sure there is complete clarity on what a team finished during a Sprint, and what they expect to work on next. There are several key aspects of the Sprint Review: 
+ An overview of what has changed in the product since the last Sprint Review 
+ A demonstration of current product functionality
+ A preview of what’s coming up next for the team 

#### Frequency
+ Once per sprint (the last day of the Sprint) 

#### Duration 
Because there is the potential for significant variation in format, e.g., single-team Sprint Review, or multiple team Sprint Review, the length of such sessions can vary significantly, from as little as 30 minutes for a single team, to one or more hours for multiple teams. 

#### Participants, Inputs, Outputs 
+ Participants - Product Managers, Product Owners, Scrum Masters, Development Teams, stakeholders
+ Inputs – Primary input is the set of work items that a team completes during a Sprint. Other inputs include any changes to overall vision or priority at the strategic/product level since the last Sprint Review
+ Outputs – Clarity about the work the team completed; feedback from stakeholders about the work the team completed; clarity about what the team plans to work on next, taking into account any stakeholder feedback, along with business priorities in general 

#### Activities 
+ Set the stage by painting a general picture about what is different in the product since the last Sprint Review 
+ Discuss the Sprint Goal(s) and the extent to which the team met the goal(s)
+ Demonstrate work that the team completed 
  + Try to refrain from depicting the work in terms of user story x, user story y (a level of detail which may not be meaningful to some stakeholders)
  + Instead, focus on telling a coherent narrative about the current behavior of the product 
  + Ensure that stakeholders have an opportunity to provide feedback
+ (optional) Touch on any challenges the team may have encountered during the Sprint, what the impact of those challenges was, and how the team may have overcome one or more of those challenges
+ Recognize the team for the work they did (and also anyone else who might have played a role in helping the team during the Sprint)
+ Provide a preview of what’s coming up during the next Sprint 
+ Be sure to account for any feedback that could affect those plans 
+ It’s okay to also provide insight into what they team will be focusing on beyond the next Sprint; however, the focus is on what is coming up next 
 
