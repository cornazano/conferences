# Day 1: Wednesday 2019-05-29

## Drafting Success

[Emily Freeman](https://twitter.com/editingemily)

[twitter thread](https://twitter.com/cornazano/status/1133725021526999040)

**Livetweet contents**

> First up: @editingemily talking about the experience of writing DevOps for Dummies, and how the creative process parallels our engineering efforts. #DevOpsDaysTO

> Engineering software is a creative process. Maybe we are sculptors, coaxing machine to do what we want. #DevOpsDaysTO

> Writing a book was hard, lonely, daunting. It is a struggle. We see the highlight reels of other people, and compare it to our experience. It is a false comparison, though. #DevOpsDaysTO

> Our brain sees opportunity as risk. As a consequence, when working through a creative process, we pass through a trough of disillusionment and a great deal of self-doubt. #DevOpsDaysTO

> Following the trough, there is a _slope of enlightenment_ where things stabilize, and a _plateau of productivity_. Things get better. #DevOpsDaysTO

> The first time we do something is the hardest. It takes a plan - but at some point we need to throw it away. Tossing the plan isn't failure, but rather adaptation. #DevOpsDaysTO

> We start with the book as imagined, and at some point we need to understand what the book needs to be. This is like coding. #DevOpsDaysTO

> A plan should be a guide, not a prison. We need to grow and adapt. Growth is painful, but also part of the process. Working through it as a team can build trust. #DevOpsDaysTO

> Procrastination is usually seen as avoiding work. However, it is part of the creative process, but just doesn't feel like work. It is where we reflect and figure out how to proceed. #DevOpsDaysTO

> We need to recognize that we are not geniuses, and not simply inspired by a muse. All creators are humans just like us. We need to create environments were we support one another. We are never alone. #DevOpsDaysTO

> It is not actually tech at the heart of DevOps. It is humans. It is you. #DevOpsDaysTO

## How to Have an Operational Incident (A Crash Course)

[Courtney Eckhardt](https://twitter.com/hashoctothorpe)

[twitter thread](https://twitter.com/cornazano/status/1133734628299350016)

**Livetweet contents**

> Next up: Courtney Eckhardt @hashoctothorpe talking about How to Have an Operational Incident. #DevOpsDaysTO

> Do you know what you would do if you woke up to a message telling you your AWS account was compromised? We're going to talk about emergencies. #DevOpsDaysTO

> There is a difference between urgency and importance. Urgency is about timeline; handle quickly or no longer relevant. Importance is about needs or consequences; it can be about danger. Emergencies are both _urgent_ and _important_.

> Emergencies need to be observed before we can respond. #DevOpsDaysTO

> When emergencies occur, we need to respond quickly. We don't have time to think and consider because the situation is urgent. So, we need to remove the need for responders to think; they need to already know what the next step is. #DevOpsDaysTO

> Frameworks are about organization and planning. We need an emergency response framework to help us with effective, timely response. #DevOpsDaysTO

> We need a way to know that something is going wrong; and what we consider to be an emergency in our context.

> We then need to know how to get help; single point of contact that is easier to remember. Heroku has a slackbot to do this. #DevOpsDaysTO

> Incident commander coordinates response to the emergency.
>
> Coordination requires assembling the responders, and how they will communicate. This needs to be defined and known - and have a backup plan in case the communication channel is also down. #DevOpsDaysTO

> Essence of success in coordination is delegation. Incident commander decides what to do, because it is worse to have conflict than to not taking action. The incident commander is the one paying attention to the progress of the incident. #DevOpsDaysTO

> We need to know how the incident can end, and allow the responders to disperse. How do we know when we're done? #DevOpsDaysTO

> Training needs to be offered to all engineers. Even if they won't be an incident commander, it will help them understand what to expect from the commander and why they are asking the questions they do. #DevOpsDaysTO

## Shortcuts and Scenic Routes: Deconstructing DevOps

Matthew Chum

Monti Ghai

[twitter thread](https://twitter.com/cornazano/status/1133748028710490112)

**Livetweet contents**

> Next up: Matthew Chum and Monti Ghai, Shortcuts and Scenic Routes #DevOpsDaysTO

> Gartner indicates 75% of all DevOps initiatives will fail by 2022. They will cover some pitfalls to help us not be in that stat, oriented around three catchphrases: Automate everything. You build it, you run it. One size fits all. #DevOpsDaysTO

> An early challenge: automate the deployment into a staging environment. This was needed to have repeatability and to reduce time. This was complex, and not a quick fix, because components were not designed for it. #DevOpsDaysTO

> Autonomy of teams can produce deeper silos, and can increase lead time if other people's work interacts with the deployment process. Continuous deployment is needed to mitigate these risks. #DevOpsDaysTO

> Services should be immutable and self-contained. Configuration should be minimized so that we can have a high degree of confidence that production will behave like what we've seen in staging. #DevOpsDaysTO

> Some resistance points when pursuing devops: impact on the perceived effectiveness of devs; diffs between test and prod environments; impact on developer's traditional roles; why not have a "devops" team?
>
> Among the risks: perpetuate culture that blames dev teams. #DevOpsDaysTO

> "We were told what tools to use, but not how to use them." This resulted in a lot of redundant work across teams. #DevOpsDaysTO

> When trying to move to consistent approaches, legacy components are a challenge. Rewriting them is a cost, especially when they are satisfying the current needs. At least in the short term, hybridized approaches can be used to get some benefits. #DevOpsDaysTO

> We cannot just ignore the value of our legacy systems; we also can't use it as an excuse for avoiding the use of modern practices. We need balance: festina lente (make haste slowly). #DevOpsDaysTO

## Just in Time Cloud Infrastructure: Redefining the Relationship Between Applications and Cloud Infrastructure

Austen Novis

[twitter thread](https://twitter.com/cornazano/status/1133757105889062912)

**Livetweet contents**

> Next up: Austen Novis talking about Just In Time Infrastructure. #DevOpsDaysTO

> The context in which the approach evolved was building a platform, where the needs included having dynamic infrastructure, achieving as close to no ops as possible, and delivering a multitenant shareable platform. #DevOpsDaysTO

> Just in time infrastructure is an infra-as-code approach, but where the infrastructure definitions share the same lifecycle as the application; the code for the infrastructure is in the same repo as the application. Helps people see the interactions between the two. #DevOpsDaysTO

> The approach can be used with various technical stacks; it can be enabled by Capital One's particle cloud framework. #DevOpsDaysTO

> Among the benefits of JiTI: every piece of infrastructure is clearly tied to an application, making cleanup of orphan resources easier. #DevOpsDaysTO

> We can also see lower coordination costs for rollbacks, since the application and infrastructure versions are tied together. #DevOpsDaysTO

> Governance and permissions management need to be adapted to this context. They need to be more application centric rather than traditional models. #DevOpsDaysTO

> The approach also facilitates developer's ability to work, since they can more easily spin up properly configured environments to experiment with their work. #DevOpsDaysTO

## My Favourite Errors

[Hany Fahim](https://twitter.com/iHandroid)

[twitter thread](https://twitter.com/cornazano/status/1133789014618726401)

**Livetweet contents**

> Last session before open spaces: Hany Fahim @iHandroid presenting on My Favourite Errors. #DevOpsDaysTO

> In operational work, errors are part of the job; they usually indicate where the immediate problem is. When getting paged, a useful first question is to asking what the error is. #DevOpsDaysTO

> Some useful initial tests to diagnose things that are before the application gets involved:
>
> - ping failing also tests dns and registration issues
> - no route to host tells you it is a routing issue before ever getting to the site.
>
> #DevOpsDaysTO

> More things:
>
> - Connection reset by peer errors point to a proxy as a likely culprit.
> - Connecction refused also frequently points to a proxy.
>
> Timeout is terrible as an error, though, because this could be anywhere.
>
> #DevOpsDaysTO

> [The neat thing about this talk is that illustrates how we could catalog error conditions and what the typical causes are, helping minimize the amount of thinking we need to do when managing incidents.] #DevOpsDaysTO

> We've seen an increasing number of HTTP 408 errors in recent years, due to browsers (Chrome) implementing predictors that issue tcp connections on startup; it speeds up access to your most used websites, but causes a 408 if you delay acccessing it. #DevOpsDaysTO

> An interesting case: app can return 200, nginx return 499, and the proxy return 504. To avoid this, it can help to set increasing timeouts: app timeout < nginx timeout < proxy timeout. #DevOpsDaysTO

> Least favorite error? No error, while something is obviously wrong.
>
> #DevOpsDaysTO

> Lesson from a wonderful story: getting a late page is better than no page at all, and make sure you get notified for all maintenances (even "non impacting" ones). #DevOpsDaysTO
