# DevOpsDays Toronto 2018

May 30-31, 2018 — Toronto, Ontario, Canada

The talks:

* [John Arthorne — Black Friday: Lessons in Resiliency and Incident Response at Shopify](#arthorne) 
* [Nicole Forsgren, Jez Humble — Tools Won’t Fix Your Broken DevOps](#forsgren-humble) 
* [Emily Freeman — This IS NOT Fine: Putting Out (Code) Fires](#freeman) 
* [Jonathan Le Lous, Thibault Cohen — DevOps & Insurance Company: Create a Bridge Between Security and Change](#lelous-cohen) 
* [Steve Pereira — DevOpsDaysTO Year 5, DevOps Year 10](#pereira) 
* [Catherine Proulx — Shaky to Solid: A Test-Based Approach to Legacy Code](#proulx) 
* [Chris Short — What the Military Taught Me about DevOps](#short) 
* [Shawn Sterling, Nan Jiang — Unleashing the Gorillacorn – DevOps in Very Large Enterprises](#sterling-jiang) 
* [Heidi Waterhouse — Choose Your Own Deployment: Interactive Feature Flag Adventure](#waterhouse) 
* [Jason Yee, Elijah Andrews, Rachel Lo — DevOps: The Next Generation](#yee-andrews-lo) 

Other materials:

* [event website](https://devopsdays.org/events/2018-toronto/welcome/)
* [Michael McCliment — Transforming from Dev to DevOps: Open spaces discussion at DevOpsDays Toronto](https://medium.com/@cornazano/transforming-from-dev-to-devops-open-spaces-discussion-at-devopsdays-toronto-b5553485cb57)

# Day 1: Wednesday 2018-05-30

## <a name="pereira"></a> DevOpsDaysTO Year 5, DevOps Year 10

[Steve Pereira](https://twitter.com/SteveElsewhere)

[video](https://youtu.be/ZwYR8z-ndCk)
| [sketchnote](https://assets.devopsdays.org/events/2018/toronto/DevOpsDaysTO_May30_2018_StevePereira.jpg)

**Twitter thrads:**
[cornazno (me)](https://twitter.com/cornazano/status/1001823006530916352)

Presented a tour through the history of DevOps (coining, first DevOps Days, etc.).

Reference to follow up: CAMS – Culture Automation Measuring Sharing

Reference to follow up: The Human Side of Postmortems

Commenting on companies doing devops: "sometimes they talk about it more than they actually do it".

Topics of interest for the future:

* Small doses of AI/ML can help us sift through data.
* Scaled transformation and how to spread through organizations.
* Simulation – attack patterns and failure modes.
* Human factors for devops.


## <a name="sterling-jiang"></a> Unleashing the Gorillacorn – DevOps in Very Large Enterprises

Shawn Sterling (Sourced)
| Nan Jiang (Sourced)

[video](https://youtu.be/9kWtmmt_048)
| [sketchnote](https://assets.devopsdays.org/events/2018/toronto/DevOpsDaysTO_May30_2018_ShawnSterling_NanJiang.jpg)

**Twitter thrads:**
[wiredferret (Heidi)](https://twitter.com/wiredferret/status/1001824196085932032)

As a company, sourced is focused on security, governance, and compilance.

Title refers to the notion of the “800-lb gorilla,” something you don’t challenge – as an analogy for large corporations.

“Going viral internally” – Masthead application, does demos internally

Opinionated pipeline – implements policy across disciplines.

Change control pattern should be approved rather than individual changes. This is the notion of compliance as code.

* Gitleaks

Get security involved in pipeline as soon as possible.

Automation strategies in inconsistent environments.

Self-tainting ephemeral instances – login triggers rebuild within 24 hours.

Moving to cloud won’t fix your broken code.

Test-driven infra as code – used BDD-style Given/When/Then in examples!

Discussed blue/green environments.

Don’t log into the web console.

Gorillacorn: A large enterprise that embraces devops practices.

## <a name="proulx"></a> Shaky to Solid: A Test-Based Approach to Legacy Code

[Catherine Proulx](https://twitter.com/cproulx_softdev)

[video](https://youtu.be/HQiPAu47lD4)
| [sketchnote](https://assets.devopsdays.org/events/2018/toronto/DevOpsDaysTO_May30_2018_CatherineProuix.jpg)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1001845576152076288)

All code is doomed to decay – and some of it decays really fast!

People who pay us don’t need unit tests, they need features and bugfixes.

Reference to follow up: Michael Feathers, _Working Effectively with Legacy Code._

* Start with the latest bug you’ve been fixing.
* Beware of code coverage
  * Let’s you know where your blind spots are
  * As a metric, encourages testing the trivial stuff (rather than what you want)
* A test suite that’s always red breaks developer’s trust (when its due to test structure)

No, manual testing is not dead

* Should be in parallel with manual
* Testers should not be a computer just running a script
* Good testers should be devious about finding flaws – requires creativity
* James Whittaker wrote about exploratory testing (look this up?)
* “Frustrated users” instead of testers (where manual testing occurs)
* There are things people are good at but computers are bad at.

Legacy code contains the knowledge of what problems we’ve faced; throwing it away throws away that knowledge.

New code is an investment, legacy code is a past investment that’s paying dividends now.

## <a name="short"></a> What the Military Taught Me about DevOps

[Chris Short](https://twitter.com/ChrisShort)

[video](https://youtu.be/TIE1rKkJWyY)
| [sketchnote](https://assets.devopsdays.org/events/2018/toronto/DevOpsDaysTO_May30_2018_ChrisShort.jpg)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1001850428999520257)
| [cornazano (me)](https://twitter.com/cornazano/status/1001852412058095616)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1001847604106485761)

Senior DevOps advocate, works for John Willis

Whiteboards to visualize -> Kanban

Everything is a resource

* Break up silos
* Teaching people how to fish helped increase the bus factor

When dealing with infra as code: assumptions behind what’s in the code aren’t in the code.

Contrast:
* Hey, RTFM.
* Hey, we're being shot at.

Technology outpaced regulations.

If you think "My users will do this thing", you’re mistaken.

Disbanding Iraqi military – one day from decision to implementation, US involved for 8 years after.

Goldsboro B52 crash

Reference: Netflix documentary Command and Control covers near failures in military

Lowest bidder = build in chaos monkey

Build muscle memory for failures, it will save countless hours of downtime

Diversity is a force multiplier. Figure out how to defend it in your organization.

If someone is willing to learn, you must be willing to teach!

## Ignites

* Augusto Rosa - Azure Cloud - Good and the Ugly, how to be successful!
* Simon Woodside - Let’s Challenge Common DevOps Assumptions: Health Tech Edition
* Karen Odegaard - Ready, Set, DevOps Roadblock
* Donald Donovan - Creepy stuff with anonymous data

From Karen Odegard: People won’t remember who kept prod stable, will remember who moved from
four to ten deploys per year.

## <a name="freeman"></a> This IS NOT Fine: Putting Out (Code) Fires

[Emily Freeman](https://twitter.com/editingemily)

[sketchnote](https://assets.devopsdays.org/events/2018/toronto/DevOpsDaysTO_May30_2018_EmilyFreeman.jpg)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1001879814662483968)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1001878392197865472)

Overview of actual firefighters and how they respond. Incident Commander.

Too many funerals. This pushed firefighting to improve.

1. Organization must be flexible – different events need different responses.
2. Consistent systems – the more you use a system, the more it becomes second nature.
3. Standardize everything.
4. Keep the price down.

Standardized terminology. “Our communication is only as clear as our language permits.”

Suggests rotating incident teams

Put people where they’re uncomfortable – discomfort is where we learn and develop skills

Suggestion form audience: first person to show up is incident commander until someone else shows up.

Comment from audience: Multiple incidents, ex. Action starts electrical fire.

* Team taking action has 1 incident.
* Fire department has a second, related but separate, incident.

## Open Spaces: Dealing With Burnout
(Terrace North)

## Open Spaces: Database Tooling, CI/CD tooling
(St. Patrick North)


# Day 2: Thursday 2018-05-31

## <a name="forsgren-humble"></a> Tools Won’t Fix Your Broken DevOps

[Nicole Forsgren](https://twitter.com/nicolefv)
| [Jez Humble](https://twitter.com/jezhumble)

[video](https://youtu.be/t453Fy8wOeY)
| [sketchnote](https://assets.devopsdays.org/events/2018/toronto/DevOpsDaysTO_May31_2018_NicoleForsgren_JezHumble.jpg)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1002180029336387585)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1002177503014916096)

(This was a title / focus switchup, schedule listed The Secrets of High Performance: What the Data Says)

Waterscrumfall – anyone have a friend who has this problem?

“One definition” of devops isn’t the problem. Definitions matter when we want to measure, test, or research it.

“Anyone can be amazing, and anyone can screw this up.”

What improves performance is capabilities, not tools. A lot of this comes from XP.

Goal: “Make releases boring.”

It wasn’t amazing tools that made the difference.

What’s the perfect set of tools? Psychological safety, plus some other cultural stuff.

## <a name="arthorne"></a> Black Friday: Lessons in Resiliency and Incident Response at Shopify

[John Arthorne](https://twitter.com/jarthorne)

[video](https://youtu.be/ryCIZyHrNow)
| [sketchnote](https://assets.devopsdays.org/events/2018/toronto/DevOpsDaysTO_May31_2018_JohnArthorne.jpg)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1002186862109380609)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1002186481866244096)

Shopify. Platform for retail, over half a million retailers.

Failure != impact.

Being in a state that we’re not restarting things is pretty unusual.

“Clench all the clenchable parts.”

Redis: reads to not fail with OOM. Misconfigured health check assumed they did.

// They have an automated resiliency suite!

## <a name="yee-andrews-lo"></a> DevOps: The Next Generation

[Jason Yee](https://twitter.com/gitbisect) (Datadog)
| Elijah Andrews (Datadog)
| Rachel Lo (Datadog)

[video](https://youtu.be/oNqd3I4sjjY)
| [sketchnote](https://assets.devopsdays.org/events/2018/toronto/DevOpsDaysTO_May31_2018_JasonYee_RachelLo_ElijahAndrews.jpg)

Quick show of hands indicates ~ 1/4 of people at DevOpsDaysTO went through formal CS program.

Interns:

* Test your onboarding process
* Chaos monkey for your docs

~ 20% of full times were interns

Lessons:

* Hiring is hard! – restarting internship program: 0 hires, 1 match next time around (9 hours of interviews), 7 next time.
* Treat interns like full times – give them real work!
  * Give them real compensation
  * Real paid time off – burnout for interns is as real as burnout for full times
  * Production access (contentions, even at DataDog)
* Mentorship. Donut program – volunteer basis, every two weeks, schedules a pariing of people who should go get coffee together during the upcoming two weeks.

## <a name="waterhouse "></a> Choose Your Own Deployment: Interactive Feature Flag Adventure

[Heidi Waterhouse](https://twitter.com/wiredferret)

[video](https://youtu.be/IkiUp_fM6go)
| [sketchnote](https://assets.devopsdays.org/events/2018/toronto/DevOpsDaysTO_May31_2018_HeidiWaterhouse.jpg)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1002215308973789184)

Note: Very dynamic, choose-your-own-adventure presentation.

~ 200 ms for killswitches at LaunchDarkly

**Albatross Launch:** retain features for critical customers without supporting / visibility to everyone.

Role based access control.

Feature flag is part of shift left on security.

Reference: _The Power of Positive Dog Training_.

## Ignites

* Jason Harley - Revisiting Larry Wall's "Three Virtues" through a DevOps lens
* Christine Rohacz - Who's to Blame?
* Fawzy Manaa - Mission Impossible - Prioritizing DevOps
* Matty Stratton - Talk Selection as Mockumentary Film Editing

## <a name="lelous-cohen"></a> DevOps & Insurance Company: Create a Bridge Between Security and Change

Jonathan Le Lous
| Thibault Cohen

[sketchnote](https://assets.devopsdays.org/events/2018/toronto/DevOpsDaysTO_May31_2018_JonathanLeLous_ThibaultCohen.jpg)

## Open Spaces: Transforming Traditional Development Teams to a DevOps Model
(St. Patrick South)

## Open Spaces: Feature Toggles!
(Armoury)

## Open Spaces: Branch vs. Trunk-Based Development / Branching Strategies
(Armoury)
