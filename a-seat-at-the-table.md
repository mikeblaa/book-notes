# A Seat at the Table – IT Leadership in the Age of Agility

by Mark Schwartz

"Mark Schwartz is a rare combination: a deep thinker who has also applied lean, Agile, and DevOps principles at the highest level, leading an extraordinary Agile transformation in the US Federal Government at USCIS. In this book, he shows how modern IT leaders succeed by driving business outcomes rather than operating an order-taking function. This shift in organizational mindset is critical to any successful technology transformation but requires substantial changes in behavior at every level, and Mark's thorough analysis will prove invaluable to leaders who must execute it."
 – **Jez Humble** , CTO, DevOps Research & Assessment, LLC

## A Few Themes

**Getting in Our Own Way:** First, that we have locked ourselves into a frame of reference that is getting in our way as we try to become Agile. This frame of reference includes the notions of project, systems, application, investment, architecture, skill set, and accountability. We have, to be honest, made a jumble of these concepts.

**IT as an Asset:** Second, that the business value of IT is more like the value of an intangible asset, which I will call – despite some disconcerting connotations of the term – the Enterprise Architecture. The asset view of IT will substitute for the outdated project view in my vision for what IT leadership must become.

**Uncertainty and Risk:** Third, underlying all of these changes – all of the problems with plan-drive approaches, all of the advantages of Agile approaches – is a confusion about how to deal with uncertainty and risk. What I call the "contractor-control paradigm" – is really about trying to make risk go away, when risk really the essence of what we do.

**Complex Adaptive Systems:** Fourth and last, that the business should be thought of as a community, or perhaps as a Complex Adaptive System, which needs to be led and managed through an inspect-and-adapt, feedback-and-vision-oriented approach because of its complexity.

### A Nimble Approach to The Table

**Agile in One Paragraph:** Agile thinking simply says that we should empower small teams to inspect and adapt rather than stick to a plan. Lean thinking gives that small team ways to speed up its inspecting and adapting process to maximize its impact. Continuous Delivery and DevOps place the entire value stream in the hands of that small team so that it can optimize the whole – a term of art in lean thinking – and be empowered as a team to own the entire value delivery process. \<Bow/\>\<Applause/\>

**Brining Lean Principles to Software Development:** Kanban is David Anderson's approach to bringing Lean principles into software development while driving fear out of the transformation process through incremental change. Anderson provides four rules for implementing Kanban:

1. Start with existing processes
2. Pursue incremental, evolutionary change
3. Respect the current process, roles, responsibilities, and titles
4. Encourage leadership at all levels

## Planning

**Espousing the Wrong Values:** The real reason we should reject the plan-driven approach to IT is that it espouses all the wrong values.

- What is the value of rigidity and executing according to plan if you could be improving on the plan or responding to changing circumstances instead?
- What is the value of hitting your spending target if you could be spending less, or if a marginal dollar of unplanned spend will bring a return of much more than a dollar?
- What is the value of telling knowledge workers to follow a plan when you are hiring them to use their brains to figure out how to do things best?
- What is the value of adhering to a plan that was made at the beginning of a project, when uncertainty was greatest?

Business value is destroyed only when we substitute extensive planning for execution and when we substitute execution according to plan for thinking and adapting.

**A Better Way to Plan:** Nevertheless, planning is important. In my role, I need to decide whether to allow an initiative to begin, which of course depends on whether I am satisfied with its plan. I might ask these questions when I review a team's plans:

- What are the business outcomes the team is trying to achieve? What kinds of activities do they think will achieve them? Why are those outcomes valuable to the business? I want to make sure that the team has a clear vision, that they understand the business's intent, and that they will make decisions within the context of that intent.
- How will the team determine the specific requirements—that is, determine what work they will do? Note that I am not asking what the requirements are, but rather how the team will discover them. I want to make sure the team has a good basis for making value decisions.
- How is the team planning to work together? What skills are on the team? How will the team communicate? How do they plan to retrospect and continually improve their process? I want to make sure they can operate as a team and learn together, and that they are committed to continuous improvement.
- How will the team seek feedback on its work? How will it solicit feedback and guidance from management? How frequently will it engage management? I want to make sure that we have an understanding on how my input and feedback will enter into their process.
- What are the key risks to delivery? What assumptions are contained in the plans? How will the team move quickly to test those assumptions and gain information to manage the risks? I want to understand their plan for learning.

## Requirements

**Requirements simply don't exist:** A requirement is a constraint. It is a way of saying "create value this way, rather than other ways." Really, a requirement is a constraint masquerading as a decision.

- What we have traditionally called a requirement may better be thought of as a hypothesis.
- We can think of the project team and its sponsors and stakeholders as embarking on a voyage of discovery and innovation, during which they begin with a goal in mind and empirically find and test hypotheses.

**A Better Way – Desired Outcomes:** We must replace the notion of requirement with that of a desired outcome. What gets tossed over the wall for the team to solve should not be a set of requirements: it should be an objective, an envisioned outcome that would add business value.

- The best framework I have found for working with desired outcomes as requirements is Gojko Adzic's _Impact Mapping: Making a Big Impact with Software Products and Projects_.
- The age of IT organizations hiding behind requirements—"just tell me what you need"— is gone. IT leaders must instead take ownership, responsibility, and accountability for accomplishing the business's objectives. The IT leader must have the courage to own outcomes.

## Transformation

**Mistakes have been made:** Transformational projects are evidence that a mistake has been made.

- The worst of these transformational projects are so-called "modernization projects"—transformational projects undertaken to bring technology platforms up to date.
- There is a deeper problem at the root of this dysfunctional transformation cycle. It lies, I believe, in our distinction between the development of a system and its operation and maintenance.
- Dividing our IT spending into development and maintenance buckets leads to some ineffective ways of making decisions. A nod to the ancient Greeks and the tale of Theseus's ship.

**A Better Way – The Strangler Pattern:** Theseus's activities fall into what the software world now calls the strangler pattern: a way to incrementally modernize a legacy system as defined by Martin Fowler.

- Instead of building an entirely new system, we take a small piece of the legacy system and rebuild it in a way that lets it interoperate with the rest of the legacy system. We launch that piece into production and have users use it seamlessly as if it is part of the legacy system.
- Then we take another piece out of the legacy system and do the same thing. And another. And another. Until eventually there is nothing left of the legacy system—it has vanished, piece by piece, like Alice in Wonderland's Cheshire Cat.
- The strangler pattern overcomes a critical problem many of us have faced in applying Agile techniques to modernizations. In the absence of the strangler pattern, we would develop a new system on the modernized architecture and then move the users over to it. The problem is that the users cannot begin using the new system until its capabilities at least match those of the legacy system. Because this usually takes a while, the first release of the new system doesn't come for quite some time, which works against the Agile principle of delivering value quickly and frequently. Legacy modernizations cannot be done in an Agile way without the strangler pattern.

## Enterprise Architecture

Enterprise Architecture, the domain of the IT bureaucrats, is the place we must look for the solution to our Agile challenges. We shall journey to the land of the template zombies to retrieve our golden asset, careful to carry mirrors to avoid petrification. Good luck, Agile fellows.

**In the past:** We viewed EA as primarily concerned with standardization, consistency, planning, and cost reduction. It documented as-is and to-be architectures, demonstrated alignment of systems with business needs, and did the "rigorous" up-front analysis and centralized planning that could then be used to set boundaries for developers when they began a project. In other words, a vehicle for control. But standardization also imposes costs by:

- limiting agility and adding bureaucratic waste: exceptions must be put through an approval process
- standardization limits the space of possible solutions to a problem.
- if we mandate that projects reuse code whenever possible, each project may have to spend time searching archives of available code to find something that is a near fit, and then deal with the question of whether it is a near enough fit.

I don't mean that standards are bad. Let's just agree that they might be overrated.

**A Better Way – Treat IT as an Enterprise Asset (EA):** When we add all of our current IT capabilities together, we arrive at an asset that enables the enterprise to earn future revenues and reduce future costs—that is, an asset in the classic economic sense. This asset I will refer to as the EA, which could just as well stand for Economic Asset.

- The EA has intangible, latent capabilities—potential that is, for the moment, hidden.
- The EA asset evolves over time through incremental investments.
- Managing the EA asset is an art, just as all strategic management is an art. Just as the CMO must sense market opportunities, weigh tactics for communicating with that market and encouraging it to purchase, and manage creative talent to present the message compellingly, the CIO must similarly steward the EA.

Imagine the EA asset as a ball that we mold and polish.

- If it is built as a collection of individual products, it is lumpy rather than smooth. The products don't quite fit together; they have excess capabilities that we don't really need; the ball has strange gaps where it is unexpectedly hollow and missing needed capabilities.
- We want a smooth ball of EA, an EA shaped to facilitate change and reuse, something you can easily roll in any direction you choose. That is its latent value; the inverse of the cost of implementing changes in the future.

What does such an EA, brimming with latent value, look like?

- It has little technical debt.
- It is built according to good, extensible design patterns and uses well-accepted standards.
- It is loosely coupled—pieces of it can be easily exchanged for newer pieces without requiring changes to the whole ball of EA.
- It has a robust, automated regression test suite, so that new development does not cause expensive break-fix activity.
- It has good monitoring tools in place.
- It is coded in a way that resists hard-to-find defects like concurrency errors.

## Build Versus Buy

Everyone knows that in every case under the sun, in any example one can imagine, when rational human beings are making decisions, if an IT product can be acquired "off the shelf," it is better to do so than to build it. This obvious fact is neat, plausible, and in most cases, wrong.

**The economics of software development have changed:** Changed in a way that now favors "building" over "buying." There are now ways of custom-developing systems that preserve many of the advantages of buying off the shelf.

- The risk of developing a system incrementally and altering it based on user feedback is often lower than that of buying a finished product that is hard to change.
- The advantages of the agility that can be gained through a flexible, changeable, custom system—a smooth rather than a lumpy EA, as we put it in the last chapter—are becoming more compelling, and the disadvantages of proprietary products, always evident, are becoming harder to accept.

**We make this mistake a lot:** We organize our business around a product rather than creating IT capabilities to fit our business.

- We acquire a product that does not fit our business and customize it until it does.
- We offer our business users a user interface that is clunky because it was designed for users in the abstract across many possible companies and usage situations, rather than being designed for the particular needs of our employees.
- Off-the-shelf systems are more expensive than we expect, and take longer to roll out. We pay for features that we don't actually use.
- It resists change—we can't even change it ourselves, but have to get the vendor to change it.
- Our IT Skills Asset also becomes less flexible when we acquire an off-the-shelf product, since we will have to employ people with skills in that product.

**The cost of custom development is falling:** More and more logic is abstracted away by frameworks and design patterns. Incremental delivery and staged investments reduce cost and risk.

- Custom code is almost not custom these days. A developer incorporates open source frameworks, uses standardized design patterns, and orchestrates services that are already available.
- There are "cookbooks" available with templates for deploying systems, code snippets that handle common tasks, and well-known and well-studied algorithms for solving typical problems.
- Development takes place on automated pipelines that help the developer move frictionlessly and quickly from requirements to deployment.
- The developer uses a powerful integrated development environment (IDE) that centralizes the tools that help him or her do the job.
- The code is built automatically using Continuous Integration, and it is tested automatically through scripted tests.
- It is deployed automatically with automated deployment tools onto infrastructure that can be automatically provisioned.

**The choice we have to make:**

- Option 1: These techniques, if we use them correctly, enable a fast try-and-learn cycle in which developers can produce something, get feedback, and then adjust what they have produced. As a result, the code can be developed in a user-centric way and match the enterprise's needs precisely. Risk is low, because the team is constantly adjusting.
- Option 2: Compare that to the risk of buying a vendor's product, where the investment is one large lump sum—and a commitment to future maintenance payments. Then, of course, there is the risk of the vendor going out of business or discontinuing the product. It seems strange that back in the Stone Age (yesterday) we believed that it was riskier to develop custom code.
- So, today's choice is no longer really between build and buy. It is between quickly assembling best-practice frameworks with continuous user feedback and then continuing to adapt the system over time as the business changes versus buying an undefined stream of future services from a vendor who doesn't know your business and doesn't have financial incentives to support you. Text "1" to @obvious if you like the first option, or "2" to @/dev/null if you prefer the second.

## Governance and Oversight

Governance has traditionally been viewed as a filter; a way of allocating scarce IT resources among many competing projects. In an environment where IT has a limited capacity and the company's needs for IT are insatiable, governance provides a way to say no to proposed projects, absolving IT leaders from having to take personal responsibility for such decisions.

**Traditional governance approach:** Hunter and Westerman's book _Real Business of IT_ shares the traditional view of governance.

- The basics of the [governance] process involve project sponsors

1. developing a formal proposal that incorporates estimated benefits, risks, and resource requirements and
2. submitting the proposal to decision makers who select preferred investments from the proposals ... the first question to be answered in assessing a proposed initiative is this: exactly how, and how much, will the investment affect and improve business performance?

**Mark's reality check:** I imagine a sort of Star Chamber—a dimly lit group of serious, hooded faces ("decision makers") seated around a table, passing judgment on each "formal proposal" presented to them. That last piece of Hunter and Westerman's quote gets me every time. Exactly how and how much will the investment improve the business's performance? Are they serious?

- Do we know exactly how many consumers would buy our new product?
- Exactly what price they would pay?
- Exactly how much it would cost us to design and produce it?
- Will our competitors launch a competing product?
- Will our market be wiped out in a dramatic fireball from space, or will the Four Horsemen ride in just as we start our TV commercial campaign?

I will turn off my sarcasm engine for a moment. Look—it turns out that the future involves lots of uncertainty. No one knows exactly what the benefit of an investment will be—no one even knows approximately what it will be—in fact, I doubt that anyone could agree exactly on what they even mean by "benefit" and how they would measure it. Yeesh. What a basis for making such important decisions!

These Waterfall governance and oversight practices are not only inconsistent with Agile principles, but also fail to take advantage of the power of the Agile way of working. By proceeding with agility:

- We can reduce the risk of our governance decisions—once we admit that there is substantial risk in making decisions in an uncertain world, the subject of the next chapter—by quickly deploying functionality, learning, and adjusting plans.
- We can conduct experiments that test the assumptions in our business cases.
- We can reduce the overhead of our governance processes and make smaller, incremental decisions with correspondingly lower risk.
- Lastly and critically, we can encourage the teams that create value for the company rather than standing in judgment of them.

**Characteristics of an Agile governance and oversight model:** Before we dive into an Agile governance and oversight model, let's think about what characteristics such a model should have in order to both take advantage of the Agile mindset and remain consistent with it.

- the investment decision and the oversight process would form a seamless continuum wherein the execution of the initiative would yield valuable information by which the governance decision could be adjusted. We would manage risk by only committing resources to the smallest piece of work that would give us such useful learning.
- we would gauge progress by seeing operational results. Agile and Lean approaches allow teams to quickly put product in the hands of users. This not only delivers value immediately, but also lets us validate the features that have been deployed.
- we would carefully set boundaries for planning. A detailed plan is a less effective basis for governance than validated learning based on actual delivery. The more advance planning we do, the longer it takes to get a product to market; the longer it takes to get a product to market, the more risk we assume.
- ur governance decisions would not be based on a set of required requirements, but instead on high-level objectives. Instead of telling the project team how to do its job, we might begin the project with a hypothesis of what will best accomplish the objectives, but then allow requirements to change. Based on what we learned, we would re-validate these hypotheses.

**Oversight in the Federal Government:** In speaking to the government officials responsible for overseeing our IT programs—our very own Star Chamber—I frequently heard them say things like, "I want you to tell me what you are going to do and when you are going to finish, then I want you to tell me your status and what is left to do. I want to know exactly what I will get for my money and when."

- My team would respond by producing its Agile interpretation of what the overseers were asking for. That might include lists of user stories, burndowns, definitions of done, product roadmaps, and, well, in the government, about 100 different piles of paper.
- Now, I believe that this was a dead end: it was a Waterfall solution to the problem.

**A Better Way - Develop an Agile oversight process incrementally:** The overseers were right to demand what they did—they were effectively the customers of our Agile governance process, and we had to find a way to satisfy them as customers. When it came to making the governance decision, what the Star Chamber really cared about was whether they believed the money would be well spent, and spent on an initiative that was important to the agency. What we really had to show the Star Chamber was

- that the desired outcome represented a critical goal for the agency,
- that the outcome justified the spending that was proposed,
- that the team was capable, and
- that the Star Chamber would frequently be consulted and would be able to influence the team's actions, including changing or eliminating the budget.

Now, the first governance and oversight step.

- We presented to Our Very Own Star Chamber the proposed outcomes and budget, some justifications of why we believed it was plausible, and just enough description of the execution team and its process to convince the Star Chamber that the team was capable.
- Then, we did something unprecedented in formal government oversight—we had a discussion. The Star Chamber had the chance to give feedback, steer the program in different directions, and ask that the budget be changed. It was a full participant, not just a passive judge of proposals.
- We agreed to give Our Very Own Star Chamber a monthly one-page summary of the program's status (more on that later) and appear quarterly for a more detailed discussion.
- At any time, they could call us in if they saw something alarming in the monthly update. With that, the program was approved to begin.

Now the focus shifted to oversight at my level, and, as with many of our Agile programs, we set up a regular cadence for reviews.

- Every two weeks, we would have a quick meeting between the program team, me, and the business unit leader who was my peer. The main purpose of these meetings was to laugh a lot, make fun of the Star Chamber's serious facial expressions, and enjoy the successes we were having—in other words, an opportunity for, um, "vigorous discussion."
- Every quarter, I would do something I called a release cycle review, and then we would go back to the Star Chamber for an update discussion.

**How to gauge success:** To gauge the success of the project to date, I need to know only two things.

- The first is what the initiative has delivered so far. Delivery refers only to finished, deployed capabilities that are being used by the business, and I am especially interested in any measures of the delivered value of those capabilities. To show me what the initiative has delivered so far, the team prepares a Value Delivery Register—a high-level summary of the value that has been delivered.
- The second thing I want to know is how much we have spent so far. Spending in this case is measured in dollars, or in time, or in whatever other metric is most appropriate (what we are typically looking for is opportunity cost). We use a simple, one-page document we call the Financial Summary for this purpose.

**How to gauge plans:** To gauge the plans for the future, I again need to know two things.

- I need to know, as of now, to the best of the team's knowledge, what value it thinks it will deliver in the future—its roadmap—more detailed for the near future and more coarse-grained and tentative for the long term.
- Then I need to know what its high-level budget is for that future work.
- By comparing these two things—roadmap and budget—I can decide whether the business case for the investment is still attractive. Often, the plan for the future is to continue exploring the ideas originally brainstormed in the impact map. That makes it easy.

This oversight approach is simple and powerful. Requiring only four short documents, it nevertheless gives all stakeholders good insight into the status of the initiative. It allows me to have control—or at least influence—over the direction of the initiative. It is based on a positive, supportive approach—what I most want to hear about are successes to date and good ideas for the future. It encourages conversation about impediments and lets the team coordinate with other teams and with enterprise initiatives.

It is also a logical extension of the continuous feedback and learning principles that underlie all Lean and Agile practices. Daily standups and burndown charts give the team rapid feedback on whether it will finish the work of the sprint on time. Sprint reviews provide frequent feedback from stakeholders. And my two-week and quarterly reviews give the team feedback from management. There is magic here: all of these types of feedback increase the velocity of development without anyone working any faster!

## Risk

_The presence of uncertainty is the simple reason why Agile approaches work better than plan-driven approaches—it is also the reason why a good IT leader will often have to make "wrong" decisions. An IT leader adds business value by adopting an intelligent attitude toward risk._

**Risk is the chance of a negative impact resulting from uncertainty.** We can reduce risk—often at a cost—but there is generally no way to eliminate it.

- Almost all of our decisions have potential negative consequences, if only the opportunity costs of not having chosen a path that would have turned out to be more profitable.
- As an IT leader making decisions under conditions of tremendous uncertainty, your choices will often turn out to be wrong.

**Agile and plan-driven models have very different ways of dealing with uncertainty.** Plan driven approaches, even Waterfall, have always acknowledged that the future is uncertain. But this uncertainty was treated as a potential aberrance—a risk or eventuality whose impact required mitigation.

- The basic plan would remain valid, and the risk of the unexpected could be managed within the plan by itemizing potential risks, actively working to prevent them, and, if necessary, building slack into the plan to manage the potential impact of the risk on schedule.
- Such an approach assumes that the risks are bounded and can be itemized, that we can know the risks in advance, and that we have a way to (try to) control them.
- The relationship between uncertainty, risk, and change is far too complicated for such control when delivering IT systems, where complexity is overwhelming and the number of potential failure modes is high.
- In weighing the things known for certain against the uncertainties of the future, we are sure to find that the uncertainties dwarf the certainties, and that the uncertainties are not small potential deviations from the initial plan—they are the very substance of the project.

**The Agile way to deal with uncertainty is to create options and then "buy" information to more accurately assess probabilities.** Traditional teams attempt to drive out uncertainty by planning and analysis. Agile teams tend to drive out uncertainty by developing working software in small increments and then adjusting.

- Waterfall plans are made at the moment of greatest uncertainty—the beginning of the initiative.
- Working in an Agile way, we can leave options open and be prepared to accommodate a range of scenarios as the future unfolds.
- Jez Humble and his co-authors suggest that instead of using detailed planning to manage risk, we instead use experiments.
- When we encounter a risk, we should think of something we can do that will help us gain information to mitigate it. We build something, measure results, and thereby learn enough to cope with the uncertainty. "The purpose of measurement," they remind us, "is not to gain certainty but to reduce uncertainty." Uncertainty is still a given, but we want to drive out as much as we can until it stops being cost-effective to do so. We can take this as yet another definition of what it means to be Agile.

**Why do people feel like there is risk in an Agile approach?** They are worried about the schedule for delivering what they think of as FOC. The perceived risk is that the project will be "finished" late.

- This, as we know, is based on the outdated idea that we define the scope of the system ahead of time and keep working until we deliver it. That is precisely what we do not do in an Agile approach.
- Instead, we focus on reducing the risk of deploying functionality later than "as soon as possible." We deploy small value-adding chunks, continuously.
- In the Waterfall, we were worried about getting FOC delivered soon;
- With an Agile approach, we go this one better—we make sure that we deliver each individual piece of functionality soon.
- If it becomes truly necessary to hit a schedule milestone, then we can adjust our scope to be sure that we do so.
- The importance that we have attached to the timing of FOC is just another example of the misconception that IT delivery is about delivering discrete, finished products. We want our FOC because we think that is the point at which we are finished investing and just need to "maintain." But unless we want functional and technical debt, a lumpy EA, and a need to do an expensive and risky transformation effort, FOC is in no sense a "final" operating capability.

## Quality

_It is difficult for IT to gain a seat at the table when IT is always failing, but on the other hand, an IT leader who is reacting to statistical noise—failures that he or she has already chosen to accept—is destroying business value. An IT leader must have the necessary technical skills, make impeccable decisions under uncertainty, and then have the courage to face the consequences._

**In the plan-driven model, quality was easier to understand.**

- We specified what the system should do, and then measured quality as adherence to that specification.
- The opposite of a defect was "working as designed," even if the design was poor.

**In the Agile world, though, it is a more complicated matter.**

- Clearly, we do not mean adherence to specification, but do we mean spare-no-expense-best-in-class? Probably not that, either.
- We are constantly making quality decisions, especially in a Continuous Delivery model, as we decide whether the quality of each individual feature is adequate for the feature to be deployed.
- It is easy enough to say that the feature is ready for deployment when it passes all of its tests. But is quality a simple yes-or-no attribute? If it passes its tests, is it high quality? And how can we assess the quality of something that is unfinished—that will later be added to, incrementally?
- Perhaps we should separate the concepts of deployability and quality. A feature is simply deployable when it passes its tests; that is a yes-or-no question independent of quality.
- Once the feature is in production, we can assess its quality based on its fit to need, or perhaps its actual success in accomplishing the business outcome for which it was intended.

**Fail often, fail fast—but fail well.** Why in the Agile world do we talk about the need to fail and to fail often? This is a linguistic ambiguity—we are talking about a different kind of failure—in fact, a kind of failure that is the opposite of defects and outages.

- Trying things out is a way of learning in the Agile world; it is a kind of feedback cycle that lets us make good decisions in the normal course of work.
- Let's say that we are deciding between two different open source products for building a piece of the system and do not know enough of their impacts to make the choice. In the old-school way of making the decision, we would do research, debate the choice, maybe do a proof of concept.
- In our new world, we can simply implement one of the approaches and see how it works for us. We could even try the other approach as well and compare. We are comfortable with the idea that we will break things in testing, because the end result of doing so is that we can make a decision more quickly and with more good information available.
- "Failing" in this sense is simply an efficient process we use to select among alternatives.

## Shadow IT

_Agile ways of working support a community approach to IT, where IT leaders achieve their objectives by mobilizing the skills and passions of a broad community and encourage the members of that community to work together across organizational silos in a way that values skills and contributions._

**Shadow IT—rogue IT, IT that is out of the control of the IT organization.** It is what has saved IT up to this point. It is a powerful phenomenon that we have not yet learned to take advantage of, caught up as we are in the contractor-control model of IT. Shadow IT is what happens when the IT organization is unable to meet the needs of a part of the company, perhaps due to capacity constraints or to the governance process's limitations.

**A picture of today's emerging workforce.** These characteristics of today's emerging workforce reinforce the changes I have been describing, making them almost inevitable.

- **Respect for skill:** Your new IT workforce will respect co-workers who have impressive technical skills, and will have little respect for people who don't. Skill is demonstrated through hands-on "shipping" of product. Management for the sake of management is not respected.
- **Get things done:** The hierarchy must be flattened. Layers of management get in the way of goals. The employee wants the shortest possible path to shipping code without needing layers of approval. Management should be close enough to the action that they can demonstrate understanding—witnessing employees' contributions and removing impediments.
- **Cross-functional and team-based:** It used to be natural for ops specialists to do ops, developers to do development, and testers to do testing. Now, crossover skills are increasingly important. On a delivery team, employees will help each other across roles in the interest of shipping code. If there is a backlog in exploratory testing, people who normally do development will help test. Software engineers will oversee their code in production and help make changes to the infrastructure if necessary to improve performance.
- **Fairness and social responsibility:** The workplace must be fair. Arbitrariness provokes negative reactions. If someone needs to be on-call to solve problems ("wear a pager"), then everyone should share in that responsibility.
- **Focus of roles is changing:** The software engineer role is increasing in importance. Tests and infrastructure are now both represented in code; with SDN, soon even the network will be. Infrastructure can now be tested, like code; it can be placed in version control.
- **Technology matters:** Most IT people are technologists; they need to work with technology, to touch technology, to walk and talk technology—at least some of the time. They are in your IT organization because they enjoy technology; they are proud to be technologists. It is time to shake off the last traces of the attitude that this is something to be ashamed of or that they need to be controlled, learn to speak the language of the business, or start wearing jackets and ties.

## The CIO's Place at the Table

_IT leadership runs the business along with the others who run the business. The seat at the table is earned by being at the table._

The role of senior IT leadership has always been framed in terms of control—the underlying theme of interactions between IT leaders and the rest of the business has been to "keep your people under control, provide good customer service, deliver what you say you will deliver, and you will be rewarded with a seat at the table." This way of thinking has become less and less tenable as we ask IT to step up and play a more central role in the company by driving its digital agenda.

Agile approaches hold the promise of changing this paradigm, but IT organizations have not thoroughly absorbed this message.

**The critical change is that of moving from a plan-driven approach to an Agile approach, based on learning and adapting. This is deeply opposed—let me say that again—deeply opposed to the control paradigm.** If the main goal of IT leadership is to demonstrate that they can control projects and make them deliver according to plan—in other words, that they can eliminate uncertainty from the real world—then they cannot be Agile. You cannot strictly adhere to plans and also be Agile, which is to say that you cannot strictly adhere to a plan and also facilitate change and organizational responsiveness. It is not a conflict in execution—it is a conflict of values.

In the Agile world, senior IT leadership, and the CIO in particular, must look at their jobs in a new way if they want to secure that seat at the table. Here are a few of the critical characteristics of the new IT leadership role.

**Driver of Outcomes:** IT leaders must take responsibility not for delivery, but for outcomes, in the same sense that marketing and sales are not just responsible for delivering TV commercials and sales calls, but for delivering revenues, as well. IT must drive outcomes in terms of revenue, cost reduction, sustained competitive advantage, employee happiness, and innovation.

**Manager of Uncertainty:** Agile and Lean thinking give IT powerful ways to manage uncertainty. By establishing short, robust feedback cycles and flexible decision-making processes, by creating options and grooming enterprise capabilities so that they will be responsive to change, and by demonstrating the value of information, IT can lead the organization in learning and in deriving business value from good risk management and from making the most of opportunities that present themselves.

**Steward of Assets:** senior IT leadership has the responsibility for stewarding three critical assets: the Enterprise Architecture asset, the IT people asset, and the data asset. These three assets represent the capabilities of the company and its ability to address the future

**Contributor:** The senior leadership team includes someone called the CFO, who helps lead the company from the point of view of someone who is an expert in finance; the CMO is someone who contributes expertise in marketing to running the company; the COO contributes expertise in operations as one of a group of leaders of the company. It follows that the CIO is the member of the senior leadership team—the team that oversees the entire enterprise—who contributes deep expertise in information technology.

**Influencer and Salesperson:** The critical skill for someone who is leading an enterprise, only a portion of which is under his or her control, is the ability to manage through influence. The CIO needs to sell his or her ideas to the rest of the organization—to influence the use of technology in areas he or she does not directly control. To do so, the CIO must build relationships with peers; understand the outcomes they desire; demonstrate how his or her ideas can help them achieve their outcomes; and explain, convince, and follow through.

**Orchestrator of Chaos:** I began this book posing the question of how senior IT leadership can play a role in an environment of autonomous teams working directly with product owners from the business. The answer, I think, lies in this kind of leadership by influence. Takeuchi and Nonaka, the authors of the Harvard Business Review article that was an inspiration for the Agile community, say that "subtle control is also consistent with the self-organizing character of project teams."12

**Enabler:** We have been afraid of "rogue" application development, or shadow IT. There has been good reason for that. Rogue applications are often unreliable and insecure; IT winds up having to fix them when they become mission critical. But are they always insecure and unreliable? Do they have to be? If everyone is really becoming more tech savvy, might it not be a better idea to support and encourage rogue development?

**Impediment Remover:** The leadership model that seems to work best with Agile approaches is servant-leadership. The Agile team is committed and hands-on; they will tend to know best how to accomplish the objectives they are given. The best thing that a manager can do is to help the team do what it knows how to do by removing impediments. Tell the team what you need, let them do their work, and ask them how you can help. There are many things that a senior manager can do more efficiently than the Agile team because of his or her organizational power; those things should quickly be brought to the manager's attention, and the manager should deal with them immediately.

**Manager of Managers:** As long as a team has boundaries, there will be decisions that need to be made from outside its boundaries, and people who need to be—er, um, "influenced"—on the outside. The team should have the primary responsibility for exercising that influence and for framing those decisions. And the team requires empowerment—that is, freedom from command and control—within its solutioning boundaries, but the effort of coordinating the activities of different teams, other actors, and other parts of the business still requires some sort of management.
