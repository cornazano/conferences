# DevOpsDays New York City 2019

The talks:

* [Dominica DeGrandis — Making Connections Visible: How to Defrag your Value Stream](#degrandis)
* [Jaclyn Damiano — The X Factor: Making Women Visible](#damiano)
* [Gaurav Gargate — Steel Thread approach to building large scale architectures](#gargate)
* [Quintessence Anx — Sensory Friendly Monitoring: Keeping the Noise Down](#anx)
* [Matty Stratton — Fight, Flight, or Freeze — Releasing Organizational Trauma](#stratton)
* [Liz Fong-Jones — Organizing for Your Ethical Principles](#fong-jones)
* [Jessica Kerr — Principles of Collaborative Automation](#kerr)
* [Rob Boll — Kubernetes at Datadog: The Very Hard Way](#boll)
* [Alex Hidalgo — Developing Meaningful SLIs for Fun and Profit](#hidalgo)
* [Peter Chestna — This Lane Ends: Shifting Security Left](#chestna)

Other materials:

* [event website](https://devopsdays.org/events/2019-new-york-city/welcome/)


# Day 1: Thursday 2019-01-24

## <a name="degrandis"></a> Making Connections Visible: How to Defrag your Value Stream

[Dominica DeGrandis](https://twitter.com/dominicad)

[slides](https://speakerdeck.com/dominicad/making-connections-visible-how-to-defrag-your-value-stream-75a2fe2d-e52b-47d4-898f-e3ae4b1c505e)
| [MindsEyeCCF sketch](https://twitter.com/MindsEyeCCF/status/1088544295127302144)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1088443489082322945)
| [lizthegrey (Liz Fong-Jones)](https://twitter.com/lizthegrey/status/1088439714699460608)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1088440887003238400)


**My livetweet contents**

> "We need specialists to deal with complexity" (even though it creates related communication needs) - @dominicad #devopsdaysnyc

> "There are costs associated with disconnections in the value stream" #devopsdaysnyc

> Lots of small teams often have lots of unknown / hidden dependencies, which is a fundamental problem with disconnected value streams and causes delays in delivering results. #devopsdaysnyc

> These delays also open our organizations up to disruption by companies (like Amazon) that know how to deliver more effective flows with fewer delays. #devopsdaysnyc

> If tools aren't synced automatically, the coordination still needs to happen somehow. It will be manual and slow, and potentially lead to fights. #devopsdaysnyc

> "Things take too long is a universal problem." #devopsdaysnyc

> Value Stream Canvas Exercise - starts by looking at incidents, since this impacts business operations and customer satisfaction. #devopsdaysnyc

> Unhandled / poorly handled incidents often morph into feature requests that sit in a backlog. [with everything that implies for lead times with unbounded backlogs] #devopsdaysnyc

> Value Stream Canvas Exercise - second step is to look at business feature requests. Often the first time people see it when you draw the value stream this way. #devopsdaysnyc

> Ideally, this exercise is lighter weight than a full value stream mapping, but gets some of the benefits of it. #devopsdaysnyc

## <a name="damiano"></a> The X Factor: Making Women Visible

[Jaclyn Damiano](https://twitter.com/jaclyn_damiano)

[MindsEyeCCF sketch](https://twitter.com/MindsEyeCCF/status/1088543435840278528)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1088453768708907010)
| [lizthegrey (Liz Fong-Jones)](https://twitter.com/lizthegrey/status/1088453450763927553)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1088453525493837824)

**My livetweet contents**

> Next up at #devopsdaysnyc : @jaclyn_damiano on the need for making women visible in our workplaces / industry.

> CFP to 1000 engineers for an internal conference - 0 women applied. Researched causes, and found that there is a confidence gap between men (overestimate capabilities, apply when not meeting 100% qualifications) and women (underestimate, do not apply). #devopsdaysnyc

> Community is important, but various activities are "unpromotable tasks" - work that doesn't help people advance in their careers (often taken on by women) #devopsdaysnyc

> Once you undestand and articulate a problem like this, an important question "so now, what are you going to do about it?" #devopsdaysnyc

> HIghlighted the work of Mariana Costa Checa and the Laboratoria project as an inspiration. Her work creates resource pools where they didn't exist before. #devopsdaysnyc

> Introducing Project Athena. Plan is two cohorts of women this year, actually taking action to address the tech inbalance in a single-company context. Looking at other underserved communities as well. #devopsdaysnyc

> This require support and education in order to succeed. Mentorship and learning are central to the process and set up for success, learning by doing actual work that produces value for the company. Once through, place them within the company. #devopsdaysnyc

> Benefits: Diversity of experience (gender, race, socioeconomic classes); Investing in local community; potential for significant evolution in the tech workforce. #devopsdaysnyc

## <a name="gargate"></a> Steel Thread approach to building large scale architectures

[Gaurav Gargate](https://twitter.com/gauravgag)

[MindsEyeCCF sketch](https://twitter.com/gauravgag/status/1088898989108355072)

**Twitter thrads:**
[cornazno (me)](https://twitter.com/cornazano/status/1088473918896250882)
| [lizthegrey (Liz Fong-Jones)](https://twitter.com/lizthegrey/status/1088472733883793408)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1088473119990398976)

**My livetweet contents**

> Next up: @gauravgag on an approach to building large scale architectures #devopsdaysnyc

> Shifting to microservices requires thinking about the dependencies. Need to invest in both people and processes in order to support it. Need workflows to try the new architecture and be able to learn from the experience. #devopsdaysnyc

> "Steel threading" is an approach where you build only the really important functionality, but build it thoroughly. It is the reliable backbone for the rest of the work that comes later. Started by build a platform for operating micoroservices. #devopsdaysnyc

> Started by introducing an api gateway between the edge and the monolith, allowing them to start building other small services behind it. [Reminds me a bit of creating branch points in code when introducing feature flags] #devopsdaysnyc

> They invested in CI/CD pipelines early; they didn't want to get to a point where they were blind to issues for any microservice in their ecosystem. #devopsdaysnyc

> Need to build the muscle about how to take decisions (build / buy, what to learn from others, etc.). Requires thinking about the impacts of our choices. #devopsdaysnyc

> Architecture can be split between application services, domain services, existing monolith, etc. To make this work, requires an API-first approach with API management as a critical architectural element. #devopsdaysnyc

> The developer workflow is critical to productivity - off-the-shelf observability / monitoring tooling makes this easier and helps maintain developer happiness in a microservices world. #devopsdaysnyc

> Reflection on pipeline - change from fewer, longer steps to many, shorter steps. This is part of the shift to a "you build it, you own it" world. #devopsdaysnyc

> Proper tooling of the hardware resource abstractions are needed to facilitate fast, stable deployment processes (e.g., kubernetes, containerization). #devopsdaysnyc

> Among the lessons learned - a focus on onboarding and ability to manage the transition to development teams supporting the service they build is necessary. #devopsdaysnyc

## <a name="anx"></a> Sensory Friendly Monitoring: Keeping the Noise Down

[Quintessence Anx](https://twitter.com/quintessenceanx)

[video (DevOpsDays Vancouver, March 29 2019)](https://www.youtube.com/watch?v=IZ5SPRx2Tm4)
| [slides](https://noti.st/quintessence/KjitaX/sensory-friendly-monitoring-keeping-the-noise-down)

**Twitter thrads:**
[cornazno (me)](https://twitter.com/cornazano/status/1088550378512240640)
| [lizthegrey (Liz Fong-Jones)](https://twitter.com/lizthegrey/status/1088550382744358912)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1088550369607725056)

**My livetweet contents**

> Next up: @QuintessenceAnx on managing the noise generated by monitoring. #devopsdaysnyc

> "I need to know everything" is a trap. It becomes very loud white noise, and people start ignoring things like alerts and slack, then you start missing everything (even what's important). #devopsdaysnyc

> Time cost is a thing when we're interrupted. However, some interruptions are important, since they indicate that we need to redirect what we're doing because e.g. kubernetes is down. #devopsdaysnyc

> Multitasking also has impacts, including on error rates for basic recurring tasks. [Hint: automate what you can to reduce whatever toil-based interruptions are occuring.] #devopsdaysnyc

> Part of the way to get control of this is to determine what the sources of noise are, and determine what relevance they have. Does every feed into slack really need an "at channel" notifying them? #devopsdaysnyc

> We need to set focus time in order to establish boundaries and reduce noise. "Please don't interrupt me in this window." #devopsdaysnyc

> If you fix the source of a problem, the noise goes down. Don't alert to people who can't act on it (direction to the right people). Redundancy can also increase the noise level and needs to be managed. #devopsdaysnyc

> Spring cleaning (housekeeping) of alerts is important to manage the noise levels. We need to check the checks or we'll get false positives or checks that are no longer relevant based on the changing ecosystem. #devopsdaysnyc

## <a name="stratton"></a> Fight, Flight, or Freeze — Releasing Organizational Trauma

[Matty Stratton](https://twitter.com/mattstratton)

[video (from DevOpsDays Charlotte, February 7 2019)](https://www.youtube.com/watch?v=DJdS48vFV20)
| [slides](https://speaking.mattstratton.com/z91QcD/fight-flight-or-freeze-releasing-organizational-trauma)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1088560247034310656)
| [lizthegrey (Liz Fong-Jones)](https://twitter.com/lizthegrey/status/1088557133526953984)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1088560587708219397)

**My livetweet contents**

> Last talk for the day: @mattstratton Fight, Flight, or Freeze. #devopsdaysnyc

> Threats introduced into a zebra's environment (such as a lion showing up) have physiological effects on a zebra - fight or flight response. (Note: humans are not Zebras, we have a prefrontal cortex which replay traumatic scenarios). #devopsdaysnyc

> Humans have a reponse to trauma that can move us out of the healthy zone for our nervous system. (So do organizations.) #devopsdaysnyc

> The nervous system response will be activated by imagined threats in addition to real ones. But the solutions to the real threats don't work for the imagined ones. #devopsdaysnyc

> Constant vigilance - being always aware of threats - prevents moving forward. Wartime metaphors and the existence of production support teams are symptoms of this. #devopsdaysnyc

> Similar signals seem the same as previous examples through the lens of human experience. This is true even if they are *not* the same cause (typical of complex systems). #devopsdaysnyc

> We need to understand our organization's window of tolerance in order to understand when we become disregulated, when we're creating a trauma response rather than a healthy response. #devopsdaysnyc

> To get back to healthy responses, we want to take the traumatic signal and associate non-traumatic experiences with it. Game days are an example of this - it's a safe environment to have incident response be just a thing we do. #devopsdaysnyc

> To do this, we need guidance (don't reinforce fight/flight reactions), and we need them to follow normal process (use incident commanders - in fact, use the game days to *train* them). #devopsdaysnyc

> Incident resoultion needs closure, not just ending a meeting or just writing a report. We need to process and integrate the lessons into our way of working. #devopsdaysnyc

> "Write-only post mortems don't help anybody." - @mattstratton #devopsdaysnyc

> Cognitive distortions - all-or-nothing thinking, overgeneralization, fortune telling, illusion of control, ... - interfere with effective processing to return to learn and re-establish healthy responses. #devopsdaysnyc

# Day 2: Friday 2019-01-25

## <a name="fong-jones"></a> Organizing for Your Ethical Principles

[Liz Fong-Jones](https://twitter.com/lizthegrey)

[MindsEyeCCF sketch](https://twitter.com/charlieroffe/status/1088889637014249473)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1088798285484253185)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1088798687445372928)

**My livetweet contents**

> First talk of the day: @lizthegrey speaking about on Organizing for Your Ethical Principles. #DevOpsDaysNYC

> Anonymous poll: about half of us have seen something unjust in our workplace; about 15% have seen unjust things that disproportionately impact customers. #devopsdaysnyc

> We need to think about the impact of our work on our communities. Accessibility and bias need to be considered. Example: Redlining was a practice where lenders would refuse to lend to historically black communities, meaning they were systematically left out. #devopsdaysnyc

> When the heads of our companies are lobbying against our rights as human beings, it becomes really dangerous. Ethics codes are not enough to solve this - the overall effect it is a tradeoff between profits and people. #devopsdaysnyc

> Dealing with harrassment, social inequality, facism, needs organization and requires the same skills that we use for incident management. #devopsdaysnyc

> As part of ethical action, we need to consider the threat models to ourselves, our colleagues, and our communities. Industry ethics codes can help with establishing norms, but we still need to organize and hold our organizations accountable to their stated values. #devopsdaysnyc

> If we're organizing and holding our organizations accountable for their behaviors, we need to think about the worst case and disaster preparedness. #devopsdaysnyc

> Change is, ultimately, worth the cost. We need to quit tolerating discrimination. It is easier to address issues earlier in the process rather than after it is embedded in our products and business models. [We need diverse teams for this!] #devopsdaysnyc

> We need to build relationships with people in positions of power over decisions in order to effectively change things. They may have different/missing information, and sometimes they need to hear other elements to improve decisions. #devopsdaysnyc

> If it is possible to enact change within a company, do that first. Stronger measures (strikes, whistleblowing, ...) should only be considered after that isn't possible. #devopsdaysnyc

> To fix these issues, we need not just continuous integration and continuous deployment, but continuous ethics. It needs to become an integral part of our job. #devopsdaysnyc

> [This was one of the emotionally harder talks I've listened to, and also one of the more important ones.] #devopsdaysnyc

## <a name="kerr"></a> Principles of Collaborative Automation

[Jessica Kerr](https://twitter.com/jessitron)

[slides](https://www.dropbox.com/s/5si2tfq75xsbtnj/poca.pdf?dl=0)
| [MindsEyeCCF sketch](https://twitter.com/MindsEyeCCF/status/1088913765838524416)
| [blog post version](https://blog.atomist.com/principles-of-collaborative-automation/)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1088815335497781250)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1088815488824676353)

**My livetweet contents**

> Next up: @jessitron on Principles of Collaborative Automation. #devopsdaysnyc

> DevOps isn't automation (although automation contributes to it). It is a situation involving people. The principles in this talk come out of the resilience community, who have done a lot of study of collaboration. #devopsdaysnyc

> Symathesy - a system that learns made up of parts that are also learning. In DevOps situations, this is a _sociotechnical_ system. We learn from our systems as we experience their behaviors; since we can change our automation, it can also learn from us. #devopsdaysnyc

> Joint activities are things we do where we have shared objectives and interdependencies. There are known principles for navigating collaboration when engaged in joint activities.  #devopsdaysnyc

> The _basic compact_ involves a commitment to noticing failure, communicate them, and correct them. We work this way inside the system, so that the external experience is reliable. #devopsdaysnyc

> Being _mutually predictable_ means we need to understand how our collaborators will react to specific signals / events / conditions, and to communicate when we won't meet that expectation. We need to be more precise than "hire people like me." #devopsdaysnyc

> As humans, we need to discover _why_ things occur. "The algorithm said so" isn't a valid why. We need to be able to explain and understand, at least in retrospect. Part of this is developing the ability to bring people into context. #devopsdaysnyc

> _Mutual directability_ is the ability to influence our collaborators (whether human or technical components of the system). Presenting and explaining choices is better than forcing single options. #devopsdaysnyc

> The more flexible actor in an interaction has more power. We need to keep our software directable, keeping the power in the hands of the humans. #devopsdaysnyc

> _Common ground_ is the shared context and mental models that form the basis of communication. [I'm reminded of the Gricean maxims for communication.] #devopsdaysnyc

> Layers between tech components serve to establish common ground between the actors, including making elements interpretable to humans. #devopsdaysnyc

> Key point: Let the human decide things, and let the human see what's going on. #devopsdaysnyc

## <a name="boll"></a> Kubernetes at Datadog: The Very Hard Way

Rob Boll

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1088836404946391042)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1088836105947017216)

**My livetweet contents**

> Next up: Rob Boll talking about Kubernetes at DataDog. #devopsdaysnyc

> Organizational challenge - how to replicate the datadog platform to multiple cloud providers? They needed to provide a proper platform. Scary, but also an opportunity. #devopsdaysnyc

> What works? Toolbox pattern - a toolbox pod that does nothing but provides operational tools. Supports transition from existing tooling to more cloud-native tooling. #devopsdaysnyc

> CNI for network performance (avoid overlays); containerd instead of docker; control plane topology is really flexible (large clusters can have performance issues). #devopsdaysnyc

> With new technologies, we need to be prepared to have a deep, low-level understanding of the tech to address issues that arise. #devopsdaysnyc

> The default loadbalancing setup creates some complexity and performance issues. They're pursuing pod-native ingress and automating with cloud-based loadbalancers in order to address this. #devopsdaysnyc

> One challenge with the ecosystem is that many components lack production use and testing at scale (autoscaling, metrics, external dns). #devopsdaysnyc

> Need to invest in training and practices for people. New developers don't have the depth of understanding to really make good usage decisions, they will need guidance. #devopsdaysnyc

> The "early adopter tax" is really expensive. You need to communicate effectively, since there will be some slowdowns in development and delivery of solutions. #devopsdaysnyc

## <a name="hidalgo"></a> Developing Meaningful SLIs for Fun and Profit

[Alex Hidalgo](https://twitter.com/ahidalgosre)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1088915684833267713)
| [lizthegrey (Liz Fong-Jones)](https://twitter.com/lizthegrey/status/1088915428699713537)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1088915796837978114)

**My livetweet contents**

> Next up: @SometimesAlex on developing meaningful SLIs. #devopsdaysnyc

> The term "service level agreement" goes back to at least the time of the patent for the first punch card machine; associated job descriptions included the term. #devopsdaysnyc

> We have a proliferation of services. XaaS frame with lots of values for X, and moving into microservices. Framework for reliability: SLI (indicator) / SLO (objective) + error budget / SLA (agreement) + error budget. #devopsdaysnyc

> SLIs are the building block on which the reliability stack is built. The stack on top of it crumbles if the SLI isn't well defined / meaningful. #devopsdaysnyc

> SLIs measure the _reliability_ of your service. Users define it - are they getting what they need it to do? (uptime, error counts, etc. don't matter). [Reminds me of @mipsytipsy's "9s don't matter if your users aren't happy" comments.] #devopsdaysnyc

> When we care about a _lot_ of things, there's lots to measure. But some of them (e.g., fresh data) implies that others are good (e.g., didn't error). This lets us reduce the number of things we need to measure and how we express good SLIs. #devopsdaysnyc

> Good SLIs should focus on the user's needs. Results in happier users and in fewer pages because the other aspects aren't critical (handle them, but without crisis / incident management that wakes people up). #devopsdaysnyc

> In particular, they need to focus on the entire user journey - the full round trip - because that's what the users experience. Its more work, but you'll be able to measure your service in a way that actually matters. #devopsdaysnyc

> Building meaningful SLIs is useful because we end up with happier users, engineers, and product teams. #devopsdaysnyc

## <a name="chestna"></a> This Lane Ends: Shifting Security Left

[Peter Chestna](https://twitter.com/petechestna)

[MindsEyeCCF sketch](https://twitter.com/MindsEyeCCF/status/1090285456762257411)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1088922101044703233)
| [wiredferret (Heidi)](https://twitter.com/wiredferret/status/1088922445757796353)

**My livetweet contents**

> Closing talk: @PeteChestna on shifting security left. #devopsdaysnyc

> Applications are risky. It's easy to make mistakes. A major reason to shift security into the application layer is that most breaches come through the application layer, and we need to work on dealing with that risk and those mistakes. #devopsdaysnyc

> Companies today are *still* organized around the old waterfall model. It is a remnant of how we *used to* work. #devopsdaysnyc

> Waterfall --> Agile --> DevOps. As we move through this sequence, we bring more people into the same room in order to facilitate getting the right information applied at the right time in the application lifecycle and get everyone working towards the same goal. #devopsdaysnyc

> Testing at the end of the software pipeline is expensive. Not so much fixing the thing we find (it isn't too hard once we know it's there), but undoing / redoing all of the things we did between the point of introduction and the point of detection are costly. #devopsdaysnyc

> Some classes of errors can be eliminated. We introduce them not because we don't care, it's because we don't know. The goal of an application security program should be _education_ in order to reduce risk by eliminating issues at the source. #devopsdaysnyc

> Security needs to be all the way through the pipeline, not just during one step in it. #devopsdaysnyc

> The three ways apply to security considerations, not just to dev and ops interactions. Systems thinking (flow / relationships / mutual accountability), feedback (measurement / training / awareness), and experimentation and learning (introspection). #devopsdaysnyc

> Shift from "us and them" to "us and we". We are working for the same organization, trying to achieve the same goals. We are not adversaries. #devopsdaysnyc
