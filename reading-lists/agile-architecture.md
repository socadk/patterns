---
Modified: 2023-07-17
Created: 2023-07-14
Status: draft
--- 

<!-- *Reading List #2* -->
*Note and disclaimer: this is a draft page serving as PoC/MVP (work in progress)*

## Agile Architecting

Watch out for papers by Joe Yoder et al, for instance:

* ["Patterns to Develop and Evolve Architecture During an Agile Software Project"](https://www.hillside.net/plop/2015/papers/proceedings/papers/wirfs-brock.pdf)
  * "This paper presents four patterns for architectural design on agile projects: Architecture in the Backlog, Architectural Trigger, Architectural Spike, and Technical Debt Management." 

### Pattern Summaries

|Pattern|Problem|Solution|Full Pattern|
|-|-|-|-|
|**Architecture in the Backlog**|*How can the architecture adequately evolve to best meet the changing stream of software requirements?*|Add new architectural capabilities to the backlog to ensure that they are prioritized and implemented at the Most Responsible Moments.|[Paper PDF](https://www.hillside.net/plop/2015/papers/proceedings/papers/wirfs-brock.pdf)|
|**Architectural Trigger**|*How can the team know when to rework or evolve the architecture?*|Define conditions that trigger architectural investigations which may lead to adding tasks to the backlog|same paper|
|**Architectural Spike**|*How can you make architecture decisions when their impacts are not completely understood by the team?*|When you discover that the current architecture is inadequate and you do not know how to address it, add an Architecture Spike task to your backlog to perform some study, test or alternative investigation that supports architectural decisions.|same paper|
|**Technical Debt Management**|*How can you protect your architecture from the ravages of uncontrolled technical debt?*|Identify and manage the technical debt present in the project along with the respective effort to fix it.|same paper|

## From Quality Assurance (QA) to Agile Quality (AQ) 

Paper series by Joe Yoder and Rebecca Wirfs-Brock:

* Part 1 (AsianPLoP 2014) outlines 21 patterns as patlets and describes six:  Integrating Quality into your Agile Process, Agile Quality Scenarios, Quality Acceptance Stories, Fold-Out Qualities, Whole Team and Quality Focused Sprint. [PDF](https://hillside.net/asianplop/proceedings/AsianPLoP2014/papers/27.pdf)
* Part 2 (US PLoP 2014) features six patterns: Find Essential Qualities, Agile Landing Zones, Measurable System Qualities, Agree on Quality Targets, Recalibrate the Landing Zone and System Quality Dashboards. [PDF](https://hillside.net/plop/2014/papers/proceedings/papers/20-yoder.pdf)
* Part 3 (SugarLoaf PLoP 2014) has two patterns: Break Down Barriers and Pair with a Quality Advocate. [PDF (via ResearchGate)](https://www.researchgate.net/publication/267152535_QA_to_AQ_Part_Three_-_Shifting_from_Quality_Assurance_to_Agile_Quality_-_Tearing_Down_the_Walls)

|Pattern|Problem|Solution|Full Pattern|
|-|-|-|-|
|**Agile Quality Scenarios**|*How can we get a good understanding and a high level view of the important qualities that need to be addressed during the development of the system?*| "... create high-level quality scenarios that address important non-functional requirements such as performance, load, reliability, security, etc. If we know that certain qualities are an important consideration, they can be prioritized as part of the product roadmap and included during relevant sprints."|[PDF](https://hillside.net/asianplop/proceedings/AsianPLoP2014/papers/27.pdf)|
|**Quality Acceptance Stories**|*How can you define and describe agreed upon quality?*|"... create separate quality acceptance stories and add them to your backlog because in their own right there may be a need to elaborate specific conditions of the system, describing what is be measured or verified and what constitutes 'success'."|same paper|
|to be continued||||

*work in progress/PoC*


## Other Reading Lists

* [API design, evolution, management](./api-design.md)
* [Cloud-native applications and microservices](./cloud-native-microservices.md)

***Back to [reading list index](../reading-lists/index.html).***
