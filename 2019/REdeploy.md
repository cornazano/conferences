# REdeploy 2019

October 16-17, 2019 — San Francisco, California, United States

The talks:

* [Jabe Bloom — Collaboration, Coordination, Co-Design CoEvolution: Challenges to Resilience in Concurrent SocioTechnical System Design](#bloom)
* [Michelle Brenner — Document Yourself: A Framework for Career Advancement](#brenner)
* [Ronnie Chen — Getting Comfortable With Being Underwater](#chen)
* [Dr. Richard Cook — A Few Observations on the Marvelous Resilience of Bone and Resilience Engineering](#cook)
* [Matt Davis — The Practice of Practice: Teamwork in Complexity](#davis)
* [Will Gallego — Resilience Engineering Mythbusting](#gallego)
* [Marisa Grayson — Approaching Overload: Automation as Fellow Responders](#grayson)
* [Rein Henrichs — Beyond Blameless](#henrichs)
* [Adrian Hornsby — The Art of Embracing Failure at Scale](#hornsby)
* [Ryan Kitchens — The Meat of It](#kitchens)
* [George Kobar — Rule #2: Double Tap. An Elasticsearch Journey of Resiliency and Eliminating Zombies and Split Brain](#kobar)
* [Michael McCliment — Cognitive Linguistics at the Sharp End: Prototypes, Metaphors, and Resilience](#mccliment)
* [Kate Pond — A Talk For Right Now: Resilience in the Face of Change](#pond)
* [Casey Rosenthal — Trajectory of Chaos](#rosenthal)

Other materials:

* [event website](https://re-deploy.io/)


# Day 1: Wednesday 2019-10-16

## <a name="cook"></a> A Few Observations on the Marvelous Resilience of Bone and Resilience Engineering

[Dr. Richard Cook](https://twitter.com/ri_cook)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184503563201859585?s=20)

**My livetweet contents**

> Kicking things off is @ri_cook with A Few Observations on the Marvelous Resilience of Bone and Resilience Engineering. #REdeployConf

> Your skeleton is continuously replaced every 10 years; there is a dynamic balance between destroying old and making new. #REdeployConf

> There is no controller for this process. It responds to signals from mechanical strain to achieve a result. #REdeployConf

> Bone has a complex structure at different scales. The exact pattern of bone structure is not programmed, but emerges from the strains placed on the bones. #REdeployConf

> Calcium is a scarce resource; bones are a store of it in the body. 99% of calcium in the body is stored in bone. #REdeployConf

> Fractures can occur, and will gradually recover. In this recovery, over time, there is a sequence that re-establishes the bone post-fracture. The process proceeds through stages:  "reactive", "reparative", and "remodeling". #REdeployConf

> Mechanical stabilization is important to the long-term result of remodeling as new bone gets laid down (think casts). The stabilization allows the natural, resilient healing processes to lead to a desirable result. #REdeployConf

> Resilience Engineering, like bone setting, is the process of understanding the resilience of a system, and creating conditions where it leads to an intended / desirable result. #REdeployConf

> Altering the underlying resilience mechanism is also a form of resilience engineering, adjusting the signaling, and may have other effects on the system; example is the use of the PTHrP signal in cases of osteoperosis. #REdeployConf

> We've been exploiting existing resilience for 3500 years, but only started modulating the resilience mechanisms for about 5 years. #REdeployConf

> Modulating the mechanisms requires a much deeper understanding of them than exploiting existing mechanisms. #REdeployConf

> Turnover of people in our organizations is _also_ an example of destruction and creation, like bone. We can think of bone as an _archetype_ for resilience. [fin] #REdeployConf

## <a name="hornsby"></a> The Art of Embracing Failure at Scale

[Adrian Hornsby](https://twitter.com/adhorn)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184513546480021504?s=20)

**My livetweet contents**

> Next up: @adhorn talking about The Art of Embracing Failure at Scale. #REdeployConf

> AWS, as a publicly-available thing, has been around since 2006 - as an experiment. The original endpoint was http://s3.amazonaws.com/bucket/, a decision made early on that has implications for the future - questions of region, version, etc. - and still has impacts today. #REdeployConf

> Latest iteration has the bucket at the beginning of the domain name for access, which has the effect of making clients first-class citizens in the addressing. #REdeployConf

> Personal dashboards are also new - it provides a view adapted to the customer. #REdeployConf

> Regions and availability zones are central to the AWS approach to resilience. AZs are designed for low latency replication within a region, providing multiple-AZ approaches to redundancy. This pattern is used for by-region services. #REdeployConf

> The blast radius of an AZ is fairly large. They further subdivide the multi-AZ architecture and replicate it as _cells_; this just requires a thin routing later, and is the unit that gets horizontally scaled. Some services have > 10K cells. #REdeployConf

> With cascades, the blast radius can be all customers. Scoping customers to cells provides isolation that reduces the blast radius. With the cusomer as part of the subdomain, there is better isolation and the service status can be personalized to what affects them. #REdeployConf

> Shuffle sharding is another technique to reduce the blast radius, so that an issue with one problematic request cannot take down an entire customer; a retry can generally succeed under those circumstances. #REdeployConf

> Client retry behavior is critical to the stability of large distributed systems; we need both backoff and jitter to avoid retry storms. This depends on the client implementation; throttling is a way for the system to protect itself against bursts and bad actors. #REdeployConf

> Understanding concurrency is a good foundation for understanding and reasoning about the capacity of a system. #REdeployConf

> The approach described here is to think in terms of blast-radius reduction in the technical architecture. This is founded on culture, processes, and tools, which all contribute to operational excellence. [fin] #REdeployConf

## <a name="chen"></a> Getting Comfortable With Being Underwater

[Ronnie Chen](https://twitter.com/rondoftw)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184528147309572096?s=20)

**My livetweet contents**

> Next up: @rondoftw telling us about Getting Comfortable with Being Underwater. #REdeployConf

> Technical dives can be at depths with 10 atmospheres of pressure, with divers there for several hours. These are team based activities, with both high risk and high consequence. #REdeployConf

> We don't always prioritize safety. For example, we may have diving as a hobby.We choose our risks - we could snorkel instead of diving. This raises a question of _why_ do people do this? It is in exchange for pursuing goals. #REdeployConf

> Choosing to NOT stop the world to change things (e.g., pay down tech debt) is rational. It allows us to pursue goals that we would not be capable of pursuing without increasing our tolerance for risk - provided we do it in responsible ways. #REdeployConf

> A lack of psychological safety creates barriers to responding to risk. It compromises information flows, and undermines our ability to make responsible choices. #REdeployConf

> Prioritization of goals, especially if it becomes a goal in itself, is hazardous when dealing with complex systems; while working on it, the evolving system may have drifted into a different state. #REdeployConf

> Normalization of deviance also becomes self-sustaining. As we drift, we compromise our ability to evaluate risk. Experience is no longer a suitable gauge. #REdeployConf

> A foundational element of a strong dive team is strong communication and psychological safety. We need to prioritize other people's safety over the dive; terminating it is normal, shaming is not tolerated. #REdeployConf

> Strong dive teams also need to be sensitive to the environment. We need a way to update our knowledge of the conditions, and redefine what success looks like based on the changing situation. Fallback goal: everyone survives the dive. #REdeployConf

> We need alignment of risk tolerance. With alignment, lack of information means no change; without it, lack of information becomes uninterpretable where people's filters make decisions for you. The team needs a shared understanding of levels of risk tolerance. #REdeployConf

> To adapt to differing skill levels, it is the person with the least skill that leads the dive. It facilitates psychological safety, and It helps identify weaknesses in the system. #REdeployConf

> Number of dives doesn't build expertise. We need to build intuition. Start by practicing for failures. This is a foundation for being able to apply skills at appropriate times during a dive. #REdeployConf

> Prepping a dive (pre-mortems) give us a chance to align on risk tolerance, and be ready to navigate the change of priorities in response to changing conditions. #REdeployConf

> Good dive stories produce a lot of context - and no JIRA tickets! They talk about contributing factors, near misses, why did we make the choices we did. Among other things, this lessens the bias on negative outcomes and facilitates the development of good judgment. #REdeployConf

## <a name="davis"></a> The Practice of Practice: Teamwork in Complexity

[Matt Davis](https://twitter.com/dtauvdiodr)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184537072230715393?s=20)

**My livetweet contents**

> Next up: @dtauvdiodr on The Practice of Practice: Teamwork of Complexity. #REdeployConf

> Improvisation is about making something not planned ahead of time, from the materials available. Some composers use improvisation to build scores. #REdeployConf

> What distinguishes some of these composers - it is not the performance technique, but the method of composition [loving the John Cage reference here!] #REdeployConf

> A second style of improvisiation is "adaptation in a changing environment". Free jazz is an example of this. [Laurie Anderson ref. :D].
>
> Improvisation is also the development of group interaction. Improvisation in performance shows up (idiomatic improvisation). #REdeployConf

> Interesting point about idiomatic improvisers: they spend time building mental maps of their styles, so that they will be able to apply it in performance. #REdeployConf

> Different styles require different mental models. Understanding these is part of how we construct our basic compact. We combine this with a knowledge of what has transpired, what has changed since we started. This is part of building our intuition. #REdeployConf

> Joint activity involves parties working together, not in parallel [and the example given looks alot like the situational idealized cognitive models that show up in cognitive linguistics.] #REdeployConf

> Common ground breakdowns affect our ability to work together, and are tied to the progression of time. Example of a string breaking, and during the repair misses the band leader changing a key. But now the key change occurs... coordination surprise! #REdeployConf

> This happens in tech as well. "Aren't you using the push button deploy?"
>
> Time doesn't stop while we deal with the surprise. #REdeployConf

> We need to study success to understand failure. The same things are there at both times. This leads us to "the practice of practice" - the activity of doing things in a recurring way so that we get the ability to deal with those things while time doesn't stop. #REdeployConf

> "Improvisation has no existence outside of it's practice." #REdeployConf

> Chaos engineering experiments (game days) should use the same tools as you would use during an actual incident. This helps build intuition, and provides practice for how to repair common ground during actual performance surprises during an incident. #REdeployConf

> Four notions of resilience: rebound / robustness / graceful extensibility / sustained adaptive capacity. The practice of practice allows us to support people's abiltiy to achieve this. #REdeployConf

## <a name="brenner"></a> Document Yourself: A Framework for Career Advancement

[Michelle Brenner](https://twitter.com/michellelynneb)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184568316083359744?s=20)

**My livetweet contents**

> First post-lunch talk is @MichelleLynneB, Document Yourself. #REdeployConf

> We should think in terms of the ROI of ourselves as an individual. We need evidence in order to do this. A starting point is to create success statements: "I improved this thing by this measurable amount using this method." #REdeployConf

> [There's a workshop element to this, we're doing audience exercises on actually writing success statements.] #REdeployConf

> One thing you can do for this is to ask teams that are impacted how your work helps them. #REdeployConf

> A brag sheet is another part of using documentation to help ourselves. Sections: record of achievement (summary of success statements), career goals (next steps), readiness for goals. #REdeployConf

> Creating an elevator pitch about yourself is about telling the right story for your audience. What do you want them to learn? What is your pattern of growth and your transferrable skills? Your skills are more important than how you used them. #REdeployConf

## <a name="gallego"></a> Resilience Engineering Mythbusting

[Will Gallego](https://twitter.com/wcgallego)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184578899432398849?s=20)

**My livetweet contents**

> Next up, Resilience Engineering Mythbusting with @wcgallego! #REdeployConf

> As software practicioners, resilience engineering is something we're borrowing from other fields. We don't need to reinvent all of this as we explore and adopt it. #REdeployConf

> Myth: We're building resilience into system arch. We need to distinguish robustness (performance within predetermined expected boundaries), reliability (trust the system to perform within the boundary), and resilience (adapt when it goes past the boundary). #REdeployConf

> Our servers can't display resilience, but our systems can (they have people in them). Resilience is looking for deeper insights. #REdeployConf

> Myth: Complexity is the enemy of a well-maintained system.
>
> We can see this by removing logging and error handling - they're less complex, but less reliable. #REdeployConf

> People can self monitor, anticipate and learn rather than collapsing. We won't have certainty, but without the learning and expertise we will experience recurring system collapse. #REdeployConf

> Myth: We need chaos engineering to find the bugs.
>
> We actually need it to develop intuition and update our mental model, chaos engineering helps with this. #REdeployConf

> Myth: Need to follow best practices to ensure availability.
>
> Best practices do not guarantee safe actions. We fail to use our expertise. They are "best" in hindsight, but can't adapt to context. If the site is down, maybe don't require tests to complete. #REdeployConf

> Myth: Retrospectives require actionable items.
>
> How do we know they are worth the expended effort? The goal is learning and understanding of our systems. #REdeployConf

> Myth: root cause.
>
> We need to understand _why_ this is a fallacy, not just repeat the idea that it doesn't exist. When we seek it, we seek easy answers and only get shallow understanding of our systems. #REdeployConf

> Myth: Frequency and severity of incidents are good indicators of safeness.
>
> These are just the failures we acknowledge. It ignores the ones we don't see or admit.
>
> If there are (acknowledged or unconscious) incentives, these numbers are also easily gamed. #REdeployConf

> Meltdown and Spectre: these vulnerabilities existed in code that was created before people in this room were born. How long do we need code to be live before we accept that it is safe? #REdeployConf

> Myth: Our worst incidents produce the greatest learning experiences.
>
> This is simple outcome bias. Severity is not correlated with learning. #REdeployConf

> Why did the expert pause in that near miss? #REdeployConf

> Myth: error budgets can be used to control risk.
>
> Story: css file deleted, site came down. It was used as a static artifact, used as part of the 404 page, which cascaded into locked children processes as each 404 created another attempt to render a 404 page. #REdeployConf

> Myth: Field of resilience engineering is representative for the study of human factors.
>
> We need to bring in voices from underrepresented communities. #REdeployConf

> Deploys are not mass produced - every one of them is different in it's content. They are not repetition of the same change. #REdeployConf

> How do we _really_ learn? Should be more than just writing retrospective documents and having then having them sit in an archive. #REdeployConf

> We can't plan for everything. We need to understand what we're going to do when we encounter the unexpected. [fin] #REdeployConf


## <a name="kitchens"></a> The Meat of It

[Ryan Kitchens](https://twitter.com/this_hits_home)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184594523919409155?s=20)

**My livetweet contents**

> Final talk of the day, @this_hits_home sharing The Meat of It. #REdeployConf

> Contemporary incident reviews and analyses relies on satisfying but misleading oversimplifications. #REdeployConf

> (Over)simplification is inherent in learning and development of expertise. The trick is to recognize when it is more harmful than helpful. #REdeployConf

> Through reification, we associate error with people. We treat it as a single thing rather than a complex reality, and as a result take ineffective actions. #REdeployConf

> "In dynamic worlds, there is no single well-formulated diagnosis of the situation." A failure to recognize this results in fixation. #REdeployConf

> Story of 100% tracing data getting enabled. Performance impact went undetected during canarying because downstream systems gracefully terminated overload - so the canary went to full prod. Tracing resulted in _reduced_ observability. #REdeployConf

> A commit intended for local testing made it to production.
>
> "Does anyone else have some bones to pick with the ergonomics of git?" #REdeployConf

> [This talk is really funny, and really hard for me to livetweet well. You should catch this when the video makes it to the web.] #REdeployConf

> During an incident resulting from a config change, remediation efforts went via an older configuration tool. "If the engineer just used the right tool, this never would have happened." But how did we end up using that tool in the first place? #REdeployConf

> New solutions come with new hazards. What new failure modes might we be introducing? #REdeployConf

> Simply saying you're a learning organization doesn't make you one. Learning is hard, and requires deliberate effort. #REdeployConf


# Day 2: Thursday 2019-10-17

## <a name="rosenthal"></a> Trajectory of Chaos

[Casey Rosenthal](https://twitter.com/caseyrosenthal)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184865304901373952?s=20)

**My livetweet contents**

> Kicking off day 2, we have @caseyrosenthal talking about Trajectory of Chaos. #REdeployConf

> Talking about ship captains in the past. Captains who took more risk got more reward. They also had better safety records. Captains who didn't go out didn't develop skills to deal with surprising weather. #REdeployConf

> Economic pillars of complexity: states, relationships, environment, reversibility. Ability to navigate depends on our ability to control these. #REdeployConf

> [More affect or influence than control.] The more we can influence these, the easier it gets. The one place where software has an advantage over other fields is in terms of reversibility. The other three are growing or out of our ability to influence (environment). #REdeployConf

> Anything that lets you change your mind is going to help you navigate complexity. Feature flags, containers, feature flags. #REdeployConf

> Taylorist bureaucracies are not the right model for knowledge work. "Software engineering: doing it WRONG since 1913." #REdeployConf

> With software, we contend with an increasing ability for very small localized changes can have wide, global effects. #REdeployConf

> Contrast in ways of thinking about resilience: systems thinking viewpoint of finding small points where we can effect changes vs. thinking about the system as an irreducible whole. #REdeployConf

> Chaos is a tooling discipline to reveal system weaknesses through experimentation. It supports the evolution of how we manage complex software systems: shift through CI, through CD, towards CV (continuous verification). #REdeployConf

> We cannot crack open and verify the internals of neural net models; we can only verify the outputs. #REdeployConf

> Resilience engineering, to the degree it is successful, will likely have an outcome of effecting organizational change. #REdeployConf

> Disalignment from management can cause a lot of wasted effort. Alternative: work as an "invisible college" that shares and evolves the knowledge, and has an influence on how we work in order to change the world. #REdeployConf

> Tools don't create reliability.
>
> Humans do.
>
> (But tools can help.)
>
> #REdeployConf

## <a name="bloom"></a> Collaboration, Coordination, Co-Design CoEvolution: Challenges to Resilience in Concurrent SocioTechnical System Design

[Jabe Bloom](https://twitter.com/cyetain)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184874176235966470?s=20)

**My livetweet contents**

> Next up, @cyetain sharing ideas about Collaboration, Coordination, Co-design and Co-evolution. #REdeployConf

> Three main themes of this talk:
>
> * Sensemaking is a sensual activity.
> * Things matter in relation to other things.
> * Design rhymes with resilience engineering.
>
> #REdeployConf

> We think with things, not about things. [This has a bit of an extended mind feel to it.] #REdeployConf

> When we are present and think _with_ things, we don't need representations; when we are at a distance, we are more dependent on representations. We can't just look. Our representations are lower fidelity than direct experience. #REdeployConf

> Depending on what we experience, we may deal with a physical stance, design stance, or intentional stance (this comes from Dennet). #REdeployConf

> As we diverge from the present, we get distance that is either experiental and descriptive (past) or expectational and propositional (future). #REdeployConf

> Expertise comes from experience, so there is a limit to it - there is only so much time for gaining experience. How we make sense of things depends on the timeframe in which we are trying to make sense of them. #REdeployConf

> Coming from a philosophical perspective, phenomenology deals with how experience works. Retention deals with the (near) past, related to the immediate present, which exists in anticipation of the near future (protention). #REdeployConf

> A thing in use disappears until it doesn't meet our expectations. We don't (consciously) have awareness of a tool we're using until it doesn't work, when it becomes present for us. #REdeployConf

> Interpredictability works like this as well. We tacitly expect behaviors from other people, and are unaware of them until it is broken. #REdeployConf

> There are multiple (conceptual) models for how we comprehend truth. Two approaches are the correspondence theory of truth and the coherence theory of truth. #REdeployConf

> [Lots of philosophy in here that I at least partially understand, but don't know well enough to type it at speed for livetweeting.] #REdeployConf

> There is too much information for us to comprehend it all. We have to decide [consciously or not] what we pay attention to. #REdeployConf

> "The whole is more than (other than) the sum of its parts." #REdeployConf

> There are a set of problems about "future knowledge". The one we most often confront in resilience discussions is: We cannot know now what we will need to know in the future. #REdeployConf

> Our ability to cope with current situations inherently produces a limit on change. #REdeployConf

> Three things to pay attention to as we strive to navigate the behaviors of our systems: retrospective coherence, sense making, and prospective coherence.
>
> In our assessments, we need to keep in mind that observations underdetermine explanations. #REdeployConf

> The frame of a problem / solution dichotomy eliminates our ability to sustain the inherent "ongoingness" of design work. #REdeployConf

> [I'm going to need to rewatch this talk later. Also, how do I follow this when I speak later today?!?] #REdeployConf

## <a name="henrichs"></a> Beyond Blameless

[Rein Henrichs](https://twitter.com/reinh)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184891581028978689?s=20)

**My livetweet contents**

> Next talk is @ReinH, Beyond Blameless. #REdeployConf

> Claim: current blameless postmortem approaches reduce resilience. #REdeployConf

> Blamelessness is sometimes interpreted as stopping attribution. Unfortunately, attribution is also fundamental to learning from the people who were there and their experience. We need a different way to avoid sanctions as an outcome. #REdeployConf

> Blame is the link from attribution to sanction. We need to rehabilitate the link in order to avoid destructive sanctioning while retaining our ability to learn. #REdeployConf

> Moral cognition is constructed by living in a society, it is not inherent. Learning norms generates our ability to make moral judgments and, consequently, moral decisions. #REdeployConf

> We perceive negative events, and we can then ask questions about the path of norm violoation / causality / intention / reasons that produce a warrant for sanctions. It is analytic... and brains don't work the way that the path model presupposes. #REdeployConf

> Evaluations of events arise in our brain fully formed in milliseconds; we do not have the ability to introspect about how they arise. [It is inaccessible, the same way that subliminal images are imperceptible but have effects on us]. #REdeployConf

> Magritte's pipe, an example of the treachery of images, is a first interpretation of the issues. There is a deeper question - what even is a pipe? We need to consider prototypicality and gestalt perception to approach this. #REdeployConf

> Once we acquire a frame of victim / villain, we will automatically experience dyadic completion when we identify a victim. Our brain will seek to find who the villain is - even if there isn't one [hurricane victims, for example]. #REdeployConf

> Blame often shows up as an incongruent coping stance.
>
> We sometimes need to transgress social rules (implicit) in order to discover that they are there. #REdeployConf

> Blame is often accompanied by anger, and frequently erupts. It is preconscious, and can't be eliminated. Given that, what do you do with the mad that you feel? #REdeployConf

> Our mental state prior to a blaming judgment condition the resulting emotions, assessment, and sanctioning. We can create an environment where people are able to apply more deliberate processes in order to get better blaming judgments. #REdeployConf

> While the path model doesn't match what the brain does, we can use it as a facilitation cheat sheet to get better results. Use it to generate reflective questions. We want to not over-sanction. #REdeployConf

> What we choose to sanction constructs the social norms that will be used in making value judgments. #REdeployConf

> Attribution is a source of resilience and necessary for learning. Blame (some forms) are also a source of resilience for society, shaping and constructing the social norms. #REdeployConf

## <a name="grayson"></a> Approaching Overload: Automation as Fellow Responders

[Marisa Grayson](https://twitter.com/MarisaGrayson)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1184901704468156416?s=20)

**My livetweet contents**

> Last talk before lunch is @MarisaGrayson, Approaching Overload. #REdeployConf

> Sofware systems are not physical. All our interactions with them are mediated through representations. #REdeployConf

> When dealing with our systems behaviors, we need to pursue hypothesis generation, anomalies, questions, interventions (diagnostic or therapeutic), and model updating. #REdeployConf

> [She's using the the above the line / below the line model. If you haven't seen it, look up the STELLA report.] #REdeployConf

> Automated processes can be viewed as (pseudo) "cognitive agents" that function as responders to certain classes of risk. #REdeployConf

> Responses to overload: shed load, redce thoroughness (ETTO), recruit resources, shifting work in time. These are the four general types of responses for all joint cognitive activities. #REdeployConf

> [She's stepping through a case study... and I feel like I'm essentially reliving an incident resolution I was involved in a couple weeks ago.] #REdeployConf

> We need to reflect on the assumptions we make in specific situations. Our actions will be conditioned by those assumptions - we may not have all relevant context in our mental model of the system. #REdeployConf

> We can, drawing from chat, diagram a collective hypothesis space that was explored during an incident. [She's showing a diagram of having done this, drawn from her master's thesis.] #REdeployConf

> The four responses to overload can be applied in the analysis of the incident, and mapped to the above / below the line representations. #REdeployConf

> Automation tends to be brittle in it's responses. It can't adapt dynamically to unexpected evolving contexts. #REdeployConf

> Automation as a team player requires observability, directability, mutual predictabiliy, shared intent, and goal negotiation. Challenges to this include strange loops, masking, concurrent issues, and measure limitations. #REdeployConf

> The burden is ultimately on the human responders to integrate all of the information about the situation. This raises design questions about how we can adapt to our human needs. #REdeployConf

> How can we get different representations to track our hypotheses? How can we get different perspectives on the same phenomenon? #REdeployConf

> Automation's response to overload displays similar patterns to ours, but is brittle in the face of a changing world around it. #REdeployConf

## <a name="kobar"></a> Rule #2: Double Tap. An Elasticsearch Journey of Resiliency and Eliminating Zombies and Split Brain

[George Kobar](https://twitter.com/GeorgeKobar)

## <a name="mccliment"></a> Cognitive Linguistics at the Sharp End: Prototypes, Metaphors, and Resilience

[Michael McCliment](https://twitter.com/cornazano)

**Twitter thrads:**
[crayzeigh (Aaron)](https://twitter.com/crayzeigh/status/1184941444106088448?s=20)

## <a name="pond"></a> A Talk For Right Now: Resilience in the Face of Change

[Kate Pond](https://twitter.com/OhKPond)
