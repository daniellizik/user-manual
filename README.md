# user manual, how I prefer to work and how to work withme

Prior to becoming a SWE I worked in a retirement home kitchen as a prep/line cookie also dishie, server, etc., for six years. SWE at its worst times is two orders of magnitude easier than food service. When prod is on fire, stakeholders are beligerent and the codebase looks like a hellskitchen pasta fiasco, that's Tuesday afternoon in a kitchen. On a Tuesday in a kitchen, my coworkers are brandishing knives at us, there's cockroaches everywhere, the guests in the dining room have dementia, for some reason the assistant staff hired to help in the dining room also have dementia, a few of the FOH staff are totally checked out but due to, reasons, the boss gives them the OK so you have to do 2/3x the work to cover. Is that an excuse or a story? More like an exuse, I'm working on it.

So if at times I come off as beligerent, uncouth, abrasive, whatever...that's where I come from. A kitchen. I can't apologize for my heritage but I can ensure you that I'm always working on my personal skills in order to work better with people.

## TLDR

> What drives me nuts?

- RTFM attitude, ad hominem and general asshole behavior. This is unacceptable. If this is your preferred attitude, let me make it abundantly clear to you, **you will not work with me**.
- When we don't strive to be people that we ourselves want to become. Don't cut corners at your coworkers expense. 

> How can people work well with me?

Before submitting work and thinking "ok...this is good enough", second guess yourself. Is it really? If you were reviewing, would you find a mistake? Do it for your team. Be the engineer you want to work with

> What are some things that people misunderstand about you that you should clarify?

In the past I have received feedback that I understand the theory of good management, but my personality is cold. I agree with this observation. I am introverted and having 5+ hours of meetings a day is exhausting. The real definition of introvert/extrovert is that extroverts derive energy by interacting with people; introverts derive energy by being alone and silent. So for me, having meetings and 1-on-1s all day is incredibly emotionally and mentally draining. If we are on a slack huddle at 6pm and I'm helping you debug something and I sound like a huge asshole, I'm really sorry. I try, but it's really, really difficult. Its not you, its me.

People also feel that I am very cold and ruthless when conversing on slack vs in real life. I agree with this. Maybe it's because how I grew up with online games? When moving my fingers to respond to some visual stimulus I see in slack, there is no personal connection. I have to slow down and think about the person behind the icon. This takes mental fortitude and time on my part, so I'm really sorry if I jump this step and say things way too direct or uncouth for your preference. You can help me by having a chat and explaing your own user manual to me :) 

## Intro

At TableCheck my role is somewhat blurred.

https://www.patkua.com/blog/5-engineering-manager-archetypes/

This is a good article that describes the fluidity of the role, these days I'm probably 25% project/process manager, 50% tech lead, 25% people manager

As an engineering manager my primary responsibility is to ensure the consistent delivery, quality and reliability of our user facing products. Secondary responsibilities include anything which supports the primary, such as intrapersonal relations, career goals and support, team building and dynamics, team comms, etc. 

As a tech lead my primary responsibility is to ensure the technical implementation of our user facing products can satisfy the requirements of the engineering manager's primary responsilities. This sounds vague, but the primary goal of tech is to satisfy the needs of the business (deliverables), NOT the other way around. Technology serves the needs of the business and its customers. We don't build random over-engineered shit simply because it tickles our fancy and makes us feel smart. I build shit like I'm stupid: as simple as possible, as complicated as necessary.

## Mantra

I only have one rule: get your stuff done. Other than that, do whatever you want (within reason and good will).

I am not draconian and do not ever wish to micromanage people. My only "rule" is to follow loosely-defined principles which should guide you through your career. Rules can change, principles should be solid (i.e., "strong convictions loosely held"). Think of life as a series of line segments A to B. The point is not to follow some arbitrarily rigid rule-based process which forces you through a series of steps to get to point B, but to understand *why* we must get to point B and figure out the optimal path to get there. As a manager I determine the end goals, you determine how to get there.

## HR-ish stuff

For the most part, pure HR issues should be addressed to HR, not me.

### Work life separation/balance

Work to live, never the other way around.

### PTO

Those that report to me should freely take their PTO **whenever they want**. There is no "request period", you do not need prior 2 weeks approval. If you need a personal day, take it. If you are sick, rest. **Your PTO is yours, not mine**, and you should use it as you see fit. However, you should also be transparent about it with your team and let them know when you are on leave. **Be the developer you want to work with, and do unto your coworkers as you would have them do unto you.**

### Working hours, notifications

Disable slack notifications on your phone. Those that report to me have never been on call, therefore, there is no need to look at slack past your working hours. And as we are flex, these hours are "more or less" up to you, within reasonable limits and good will. Typically at TableCheck our hours are 1030 JST to 1930 JST. Sometimes we clock out at 1800. Sometimes we clock out at 1700. If you get your stuff done, nobody cares.

For more complicated edge cases related to clocking in/out and working hours, DM me. Again, I'm not draconian and I don't really care *how* it gets done, as long as it *gets* done.

### Visa/permanent residency support, relocation to Japan, etc.

Consult HR.

### Intrapersonal issues

DM me.

## Tech lead responsibilities

My responsility for training individual contributors is not to "teach you stuff". The act of learning concept A or process B or technology C is *your* job, *not* mine. It is *your job* to read documentation autonomously in order to understand how to use a new technology. It is *your job* to read through our proprietary codebases autonomously to understand how they work. It is your primary responsibility to learn that which is deemed necessary in order to satisfy the requirements of the engineering manager (deliverables).

However, it is *my* responsibility to teach you about the purpose of the product itself, the pain points of the customers, and instill within you any wisdom that cannot be learned simply through code/documentation. The world is not perfect, and information is always incomplete. It is our job as engineers to be skeptical of our understanding and seek out additional sources of information that can further enhance our understanding, in these cases, it is useful to reach out to people that have been in the company longer than you to transfer this undocumented institutional knowledge. Essentially, you are responsible for that which you *can* be held responsible for, as sophist as this may sound. My responsibility as tech lead/engineering manager is to help you understand concepts for which you are not individually responsible.

My primary pedagogical function as a tech lead is *teach you how to learn* and how to become an efficient *decision maker*. Many times you will come upon a problem for which there are multiple competing solutions. In the cases where there actually is a most appropriate solution, your responsibility as an individual contributor is **NOT to immediately give up and ask for help**. You *must* hypothesize the multiple solutions, weigh their pros and cons, and make the decision yourself. There will come a time in your career (maybe it has already happened) when you must make the call and there is nobody to ask for help. I am preparing you for that time.

Let's go over an example of when you should *must* able to make a decision yourself: it is Friday afternoon and your PM asks for an urgent hotfix to deploy a bug reported by a big client. Maybe your team as a guideline not to deploy on Fridays. But your PM asks you to break the rule because it is mission critical. What do you do? You understand the severity of the bug, judge how long it would take to fix, assess potential for regression, and then make the call. None of that information is hidden from you, it is **your job** to seek out the information required to make the decision, then decide.

In the cases where the knowledge required to make the most accurate/informed decision is not privy to you, it is wise to ask for help from others. An example: big client A wants a change that would affect how the multi-tenant app behaves for all other clients. You have no data on how the rest of the clients use the app. So, reach out to various subject matter experts (your PM, consultants, sales, etc.) to get a sense of how important the change is and its theoretical repercussions. Typically, when you require additional business/institutional knowledge, you will have to reach out to the business side of the organization. For technical issues, **you** should strive to understand as much of the problem space as possible. **Is not your coworkers job to handhold you through the technical decision making process.**

The common theme here is, for information that is publically available to you, you **must** make a concerted effort to seek it out. Is it **NOT** anyone else's job to search for you, that is yours and yours alone.

## Meta-Communication

- Communication: Very low context; I strive to say things as straight as possible. People have commented that this style is "dry" or "lacks warmth" which is ok, fair point.
- Evaluation: Direct negative feedback; like the above, I prefer not to use the "shit sandwich". SBI or Radical Candor are better frameworks. "It's not mean, it's just direct." What that said I'll never use ad hominem or deliberately act like a jerk.
- Leading: Very egalitarian; I want you to make decisions, not me.
- Deciding: Concensual (but I will be a tie-breaker if necessary); very much like the above. Sometimes for the sake of speed/time I will just make a decision but the team members should be able to do meta-decision making and determine if some decision should itself be consensual or heirarchical.
- Disagreeing: Moderately confrontational; typically constructive criticism should be delivered in private DM, but should be delivered frankly and to the point.
- Scheduling: Linear time; let's have our meetings on time and end them early.
- Persuading; can be specific or holistic. I can adjust this as per the audience. 

## Feedback

I believe in radical candor and the idea that being direct is not being mean. My feedback at times may seem direct, but its for the sake of learning. I subscribe to the Arnold school of "unimpressed coaching while watching a person grind it out in the rack" https://www.youtube.com/watch?v=v7cvJozA28o
