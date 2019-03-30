---
layout: post
title: "Survival Guide"
date: 2019-03-30
description: |
  There are a few principles you should follow
  in order to make your project successful in
  Zerocracy; pay attention to them!
author:
  name: Yegor Bugayenko
  twitter: yegor256
---

[Zerocracy](https://www.zerocracy.com) is a great platform to manage
a software development project ... if you understand how the
world of wild animals, also known as pay-by-result freelancing
microtaskers, works. If you treat them as you used to
[treat](https://www.youtube.com/watch?v=1OFgf8XYI2A) traditional
full-time programmers, [you will lose](https://www.youtube.com/watch?v=SdrtZIW5JtY).
You will lose your money, your time
and will blame Zerocracy. I don't want this to happen, that's why
this blog post with a short list of important principles/hints.

<!--more-->

**Proof-of-Concept First**.
Don't let the architect invite programmers to the project, until the
prototype is ready, build pipeline is configured,
and the product is deployed to production, as our
[Lifecycle](https://www.yegor256.com/2014/10/06/software-project-lifecycle.html) suggests.
You have to confirm
visually that the prototype proves that the key technical objective
of the project is achievable. Only then you start adding programmers to the team.

**Strict Pipeline**.
Don't approve the prototype unless its build pipeline includes unit testing,
static analysis, and test coverage control, as this
[blog post](https://www.yegor256.com/2015/06/08/deadly-sins-software-project.html)
suggests. There could be more elements there, but these three are absolutely mandatory.

**Read-Only Master**.
Never let anybody, including yourself, any third-party experts, your full-timers,
or auditors to have write access to the `master` branch, as
this [blog post](https://www.yegor256.com/2014/07/21/read-only-master-branch.html)
explains. If the architect
insists on having it, report this behavior to us, we will crucify him/her.

**Don't Negotiate Rates**.
Don't pay less than freelancers are asking. Well, sometimes you can do that,
but as a rule I would suggest to agree to what they are asking. Our management
system is very strict, demanding, and stressful. You may lose good people
if they will be financially unsatisfied. So, don't be cheap, you will only lose
and remain with weak programmers.

**Don't Chat**.
Most likely you used to communicate with programmers in chats like Slack
or Telegram. You will do yourself a bad favor if you continue doing it
with Zerocracy architect or, God forbids, programmers. GitHub must be your
only communication instrument, as
this [blog post](https://www.yegor256.com/2014/10/07/stop-chatting-start-coding.html) suggests.
You still find phone calls more convenient?
Blame yourself when the project falls apart.

**Don't Trust Them**.
Every week you absolutely must invite an external auditor to your repository
and ask them to check what is wrong and what can be done better, as
suggested [here](https://www.yegor256.com/2014/12/18/independent-technical-reviews.html)
and [here](https://www.yegor256.com/2017/11/21/trust-pay-lose.html).
Demand them to provide their feedback in form of GitHub tickets.

**Talk to the Community**.
When you are ready to start a project, submit the [RfP](https://www.zerocracy.com/rfp).
Right after that, join our [Telegram chat](https://t.me/zerocracy). Stay there
and ask all questions you have about your project, the progress you have,
the mistakes you think your architect or your team is making. Don't be quiet,
share your concerns! We will help. If you try to resolve them yourself,
blame yourself when the project fails.

**Read First**.
You absolutely must read/watch these articles and videos:

  * [Software Outsourcing Survival Guide](https://www.yegor256.com/2015/06/15/software-outsourcing-survival-guide.html)
  * [How to Avoid a Software Outsourcing Disaster](https://www.yegor256.com/2015/05/21/avoid-software-outsourcing-disaster.html)
  * [How Micro Is Your Tasking?](https://www.yegor256.com/2017/11/28/microtasking.html)
  * [Employee Turnover Is Good for the Maintainability of Your Code Base](https://www.yegor256.com/2015/12/29/turnover-is-good-for-maintainability.html)
  * [10 Typical Mistakes in Specs](https://www.yegor256.com/2015/11/10/ten-mistakes-in-specs.html)
  * [Hourly Pay Is Modern Slavery](https://www.yegor256.com/2015/07/21/hourly-pay-modern-slavery.html)
  * [Meetings Are Legalized Robbery](https://www.yegor256.com/2015/07/13/meetings-are-legalized-robbery.html)
  * [M59: How to not get frustrated when dealing with freelancers and microtasking?](https://youtu.be/w3HwEtFU2wo)

**Focus Them**.
Don't let them work without focus control. Make sure your architect
knows which parts of the scope are the most important and focus the
team to work with them first. This
[video](https://www.youtube.com/watch?v=w3HwEtFU2wo) explains how.
