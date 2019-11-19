# DevOpsDays Hartford 2019

October 2-3, 2019 — Hartford, Connecticut, United States

The talks:

* [Anthony Barbieri — Moving Fast and Staying Compliant: The Path to Everything-as-Code](#barbieri)
* [Serhat Can — How to Build a Healthy On-Call Culture](#can)
* [Emily Freeman — Drafting Success](#freeman)
* [Taq Karim — Building PlaceExchange: Scaling Our Platform to Handle Over 10,000 Digital Street-Side Screens](#karim)
* [Matt Stratton — Fight, Flight, or Freeze — Releasing Organizational Trauma](#stratton)
* [Jason Yee — Chaos: Breaking Your Systems to Make Them Unbreakable](#yee)

Other materials:

* [event website](https://devopsdays.org/events/2019-hartford/welcome/)

# Day 1: Wednesday 2019-10-02

## <a name="freeman"></a> Drafting Success

[Emily Freeman](https://twitter.com/editingemily)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1179385695590342656?s=20)

**My livetweet contents**

> First talk of the day: @editingemily on Drafting Success. #DevOpsDaysHFD

> Her book (DevOps for Dummies) is out now. She's going to talk about the _process_ of writing it (and what we learn from it). #DevOpsDaysHFD

> Ancient idea of creativity was that it came from a muse; later, we discovered science and moved to a view where the artists were the special people who were creative. #DevOpsDaysHFD

> Modern engineering is also creative - we all do this, shaping the code to help our systems emerge. #DevOpsDaysHFD

> The Gartner hype cycle mirrors the process of writing a book. #DevOpsDaysHFD

> We compare our experience to the visible highlight reels of others - this pushes us from the peak of excitement into the Trough of Disillusionment. #DevOpsDaysHFD

> Working through this forces you to confront self doubt and the voice in your head that tries to tell you you're not good enough. #DevOpsDaysHFD

> Being in a busy space (a bar) helped with making progress - right up until she read what she wrote, then hated it. Then - after a break - re-reading it discovered it was great... only to get other feedback about where it truly was (yay, editors!). #DevOpsDaysHFD

## <a name="barbieri"></a> Moving Fast and Staying Compliant: The Path to Everything-as-Code

[Anthony Barbieri](https://twitter.com/prince_of_pasta)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1179393862541991944?s=20)

**My livetweet contents**

> Next up: @prince_of_pasta on Moving Fast and Staying Compliant. #devopsdays  #DevOpsDaysHFD

> The modern technology landscape is complex. It is impossible to master and be an expert in all of the tools and services. #devopsdays #DevOpsDaysHFD

> What is good enough depends on who answers the question. Individuals get overloaded. These factors impact consistency and compliance. #devopsdays #DevOpsDaysHFD

> Documentation is important for scaling to large companies. It should be centralized, not separated by team - separation leads to a lack of consistency and difficulty finding it. One-stop-shop does a better job of helping people. #devopsdays #DevOpsDaysHFD

> Detection of policy violation is important - it should be integrated into the infrastructure and applications. #devopsdays #DevOpsDaysHFD

> Prevention is even better. We should use the platform policies (IAM in AWS, pod security in Kubernetes), and look at integrating policy-as-code into our delivery pipelines. #devopsdays #DevOpsDaysHFD

> Remediation needs to be considered for things that get past the controls. APIs can be leveraged to automate this on modern platforms - for example, automatically undoing switching things to public access. Make it noisy when you do this! #devopsdays #DevOpsDaysHFD

> Innersourcing can help with consistency in large organizations. It helps us work with each other, and keeps us from starting from zero every time. #devopsdays #DevOpsDaysHFD

> Documentation is the foundation for all of the others; centralize it and link it from everywhere. Move DM questions into Slack channels for visibility, and look for recurring patterns - they will tell you what you're missing in the docs! [fin] #devopsdays #DevOpsDaysHFD

## <a name="yee"></a> Chaos: Breaking Your Systems to Make Them Unbreakable

[Jason Yee](https://twitter.com/gitbisect)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1179408106402529280?s=20)

**My livetweet contents**

> Next up: @gitbisect talking about Chaos! Breaking Your Systems To Make Them Unbreakable. #devopsdays #DevOpsDaysHFD

> If there is a failure, it doesn't define you. But you should learn from them. (Obama)
>
> Hope is not a strategy. (Bertram?)
>
> Observation from netflix: A great way to learn is to constantly fail.
>
> #devopsdays #DevOpsDaysHFD

> Chaos monkey is a tool for learning, not just random. It was run during business hours, in a monitored environment, with engineers present. #devopsdays #DevOpsDaysHFD

> @datadoghq runs Game Days. They are limited-duration events for a chaos experiment (90 mins), run in pairs (1 subject matter expert and 1 SRE). Sometimes they add a junior developer. #devopsdays #DevOpsDaysHFD

> Planning (30 mins): schedule it (not end of day); pick the tests (start easy, document steps); write a hypothesis (what you expect to happen - likely not "systems stay up"); write a plan for if things go wrong; share the doc. #devopsdays #DevOpsDaysHFD

> During the event (50 mins): Staging before prod; announce in group chat (and maintain it!); monitor for unexpected impacts / incidents (and be able to abort); run the experiment and take notes. #devopsdays #DevOpsDaysHFD

> After (10 mins): cards for identified issues; write summary and lessons; email to all of engineering team; and CELEBRATE what you learned (and fixed)! #devopsdays #DevOpsDaysHFD

> There can be multipe game levels. Start simply, for example by blocking access to one dependency. Hopefully, the service should behave the way we expect it to (alerts, for example). #devopsdays #DevOpsDaysHFD

> Harder levels: block *all* dependencies; terminate hosts; degrading environments (latency, resouce saturation, etc). #devopsdays #DevOpsDaysHFD

> Hardest levels involve traffic spikes and regions failures (or even outages of entire cloud providers!). #devopsdays #DevOpsDaysHFD

> [This is pretty neat - he's running a live demo of a gameday exercise, killing a database out from under a wordpress site.] #devopsdays #DevOpsDaysHFD

> The key takeaway: experiments in chaos are not that hard.
>
> Share! Plan! Have fun!
>
> [fin] #devopsdays #DevOpsDaysHFD

## <a name="can"></a> How to Build a Healthy On-Call Culture

[Serhat Can](https://twitter.com/srhtcn)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1179417896688275459?s=20)

**My livetweet contents**

> Next up: @srhtcn talking about how to build a healthy on-call culture. #devopsdays #DevOpsDaysHFD

> Why have on call? In 2014, 911 calls through a particular telecom provider would not go through. There were wider disruptions to the 911 support in 2018. These are important services. #devopsdays #DevOpsDaysHFD

> On call is not free time, even when there are no alerts. It is part of your work, and has effects on people's experience. #devopsdays #DevOpsDaysHFD

> The notion of developers on call has changed our industry: helps us meet increasing reliability demands; reduces conflicting incentives between developers and operators; gives managers clear reasons to properly prioritize reliability work. #devopsdays #DevOpsDaysHFD

> "You haven't learned anything until you change your behavior" - @littleidea quote here at #devopsdays #DevOpsDaysHFD

> Don't put people on call for over a week at a time. Heroism is not sustainable - we need better processes to make it easy to call for help, arrange development load based on the pager call load. #devopsdays #DevOpsDaysHFD

> We need to proactively fight against alert fatigue. Some techniques: If it can be a ticket, do that instead of alerting; automatically add *context* to alerts to help people understand them. #devopsdays #DevOpsDaysHFD

> "People are not the root causes of incidents" [This is fundamental. People are how we get out of incidents, and are the source of organizational resilience.] #devopsdays #DevOpsDaysHFD

> Practice for on call boosts confidence. Use shadowing, game days, team playbooks, listen to podcasts about cases. #devopsdays #DevOpsDaysHFD

> On call (outside of office hours) needs to be compensated. Note: don't do this based on alerts, since it can incent people to have more alerts! #devopsdays #DevOpsDaysHFD

> Put people first, the rest will follow. [fin] #devopsdays #DevOpsDaysHFD

# Day 2: Thursday 2019-10-03

## <a name="stratton"></a> Fight, Flight, or Freeze — Releasing Organizational Trauma

[Matt Stratton](https://twitter.com/mattstratton)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1179745491619332096?s=20)

**My livetweet contents**

> Kicking off day 2, we have @mattstratton presenting Fight, Flight, or Freeze: Releasing Organizational Trauma. #devopsdays #DevOpsDaysHFD

> Starting off describing the physiological changes in a Zebra between at rest and when threated, with the fight / flight / freeze response. But...
>
> Humans are not Zebras.
>
> #devopsdays #DevOpsDaysHFD

> Among the differences, we have a prefrontal cortex that can replay traumatic events. #devopsdays #DevOpsDaysHFD

> Healthy nervous response operates in a window of tolerance, moving between the sympathetic and paraysmpathetic responses. When we get outside that range, we can get stuck "on" (fight or flight) or "off" (freeze). #devopsdays #DevOpsDaysHFD

> Organizations display similar behaviors. Getting stuck on - a hyperarousal state - are super vigilant about everything, and not able to move forward effectively. Getting stuck off - hypoarousal - is also a problem because we can't make changes. #devopsdays #DevOpsDaysHFD

> Both of these are inappropriate responses, and prevent us from getting back into the healthy region of the window of tolerance. #devopsdays #DevOpsDaysHFD

> Part of what we need to do is to identify our organization's window of tolerance (can vary from org to org), so that we can identify when we're deregulated. Resilient organizations are _not_ traumatized by routine threats. #devopsdays #DevOpsDaysHFD

> Somatic experiencing is a technique for training ourselves to have healthy responses to trauma; we can adapt this to our organizations as well in order to get back to a regulated state. #devopsdays #DevOpsDaysHFD

> We need to normalize the experience of incident response to keep from getting overwhelmed and deregulated; game days should be a safer context, but need to actually practice our real incident response processes. #devopsdays #DevOpsDaysHFD

> This doesn't eliminate the stress of the 2 am call, but keeps us from getting wound up about the process. More practice helps make it _just part of our job_. #devopsdays #DevOpsDaysHFD

> We need to process our failures to work through trauma events - to integrate them into a coherent whole. Talking it through helps the entire organization. The larger the organization, the more important it is to share our postmortems. #devopsdays #DevOpsDaysHFD

> But the process has to _have a conclusion_. #devopsdays #DevOpsDaysHFD

> We need to be aware of and deal with cognitive distortions - for example, polarized thinking (all or nothing thinking), overgeneralization, fortune telling (assuming data can predict the future, analysis paralysis)... #devopsays #DevOpsDaysHFD

> ... control fallacies (no control / total control illusions). These are all causing us to see the world _differently_ than it actually is. #devopsdays #DevOpsDaysHFD

> We can improve the on call experience. One way to help with this is to create rituals for context switching between going on call and coming off call. Some people have an on-call hoodie, so that they can take it off when they're done. #devopsdays #DevOpsDaysHFD

> Preparing for on call is important - allocate the mental bandwidth (reschedule fewer high-focus efforts); treat yourself (shedule things you enjoy to counteract the stress of on call). [fin] #devopsdays #DevOpsDaysHFD

## <a name="karim"></a> Building PlaceExchange: Scaling Our Platform to Handle Over 10,000 Digital Street-Side Screens

[Taq Karim](https://twitter.com/taqkarim)

**Twitter thrads:**
[cornazano (me)](https://twitter.com/cornazano/status/1179757419322335232?s=20)

**My livetweet contents**

> Next up: @taqkarim talking about scaling PlaceExchanges platform for streetside screens. #devopsdays #DevOpsDaysHFD

> One of the challenges is to programatically control the content that appears in a particular location. Not all ads can appear in all locations (possible legal issues, usefulness, etc.). #devopsdays #DevOpsDaysHFD

> The billboards themselves request ads when they have slots, and it produces a real-time bidding process to select which ad will be returned to the billboard. #devopsdays #DevOpsDaysHFD

> They're doing most of this using AWS lambda, and needed to deal with various issues as they scaled out from nothing to 10,000 screens all requesting ads. #devopsdays #DevOpsDaysHFD

> Collecting data from lambda functions and ingesting it into datadog needed some creativity - lambdas live for a maximum of 15s, while datadog worked by host. They hit rate limits, and used lambdas on cloudwatch subscriptions in order to get past this. #devopsdays #DevOpsDaysHFD

> Takeaways: spikes were easy to manage in a serverless environment; observability is important to undertand what is happening (invocation times, etc); not everything needs to be serverless. [fin] #devopsdays #DevOpsDaysHFD
