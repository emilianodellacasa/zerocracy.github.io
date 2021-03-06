---
layout: post
title: "What Is Zerocracy?"
date: 2018-06-06
description: |
  Zerocracy solves a number of problems we
  all experience in software development projects,
  and helps optimize costs and increase quality.
permalink: toc.html
no_disqus: true
hidden: true
---

<style>
.thumb {
  display: inline-block;
  vertical-align: top;
  width: 300px;
  margin-top: 1em;
  margin-bottom: 1em;
}
.thumb img {
  width: 256px;
}
.thumb .subtitle {
  display: inline-block;
}
aside {
  float: right;
  margin-left: 2em;
  margin-bottom: 2em;
  width: 200px;
  font-size: .8em;
  line-height: 1.3em;
}
@media (max-width: 700px) {
  aside {
    float: none;
  }
}
</style>

<script type="text/javascript">
$(function() {
  if (/[?&]p=denis/.test(location.search)) {
    $('#denis').show();
  }
});
</script>

<aside style="display:none;text-align:center;" id="denis">
<img src="/images/denis-syomkin.png" style="width:128px;height:128px;"/>
<br/>
<a href="https://t.me/Denishappy"><img src="/images/telegram.svg" style="width:24px;height:24px;" alt="Telegram"/></a>
<a href="https://www.facebook.com/denis.syomkin"><img src="/images/facebook.svg" style="width:24px;height:24px;" alt="Facebook"/></a>
<a href="https://wa.me/380504641665"><img src="/images/whatsapp.svg" style="width:24px;height:24px;" alt="WhatsApp"/></a>
<br/>
Talk to <strong>Denis Syomkin</strong>, our chief on-boarding guru,
he will guide you through the process.
</aside>

Despite all our efforts,
[most](https://www.projectsmart.co.uk/white-papers/chaos-report.pdf)
software projects still suffer
[from](https://www.infoq.com/articles/software-failure-reasons):

  * High labor costs;
  * Personnel turnover;
  * Low maintainability;
  * Low quality of code and product.

We believe that most of the above is caused by broken
management, not technical incompetence. To solve this, we
recommend <del>replacing</del> empowering a human project manager with
[Zerocrat](http://www.yegor256.com/2018/03/21/zerocracy-announcement.html),
a hosted <a class="highlight">chatbot</a>.

<!--more-->

To make a project manageable by a computer we use a strict
[Policy](/policy.html) which derives the following principles from the
[eXtremely Distributed Software Development](http://www.xdsd.org)
<a class="highlight">methodology</a>:

<div style="text-align:center;margin-top:4em;margin-bottom:4em;">

<div class="thumb">
<a href="https://www.youtube.com/watch?v=AwrMKTFyohg"><img src="https://i.ytimg.com/vi/AwrMKTFyohg/mqdefault.jpg"/></a>
<br/>
<a class="highlight" href="http://www.yegor256.com/2016/09/27/command-control-innovate.html">#NoMagic</a>
<br/>
<span class="subtitle">
  1) We rely on discipline and control much more than on trust and talent.
</span>
</div>

<div class="thumb">
<a href="https://www.youtube.com/watch?v=ODxm7w2DE-g"><img src="https://i.ytimg.com/vi/ODxm7w2DE-g/mqdefault.jpg"/></a>
<br/>
<a class="highlight" href="http://www.yegor256.com/2015/07/21/hourly-pay-modern-slavery.html">#NoSalaries</a>
<br/>
<span class="subtitle">
  2) We pay <a href="http://www.yegor256.com/2018/01/09/micro-budgeting.html">fixed fees</a>
  only for deliverables of <a href="http://www.yegor256.com/2017/11/28/microtasking.html">microtasks</a>,
  never per hour/month.
</span>
</div>

<div class="thumb">
<a href="https://www.youtube.com/watch?v=5Wjczt4w46A"><img src="https://i.ytimg.com/vi/5Wjczt4w46A/mqdefault.jpg"/></a>
<br/>
<a class="highlight" href="http://www.yegor256.com/2015/07/13/meetings-are-legalized-robbery.html">#NoMeetings</a>
<br/>
<span class="subtitle">
  3) We <a href="http://www.yegor256.com/2014/10/07/stop-chatting-start-coding.html">don't talk</a>
  to each other <a href="http://www.yegor256.com/2016/08/23/communication-maturity.html">anywhere</a>
  outside of GitHub tickets.
</span>
</div>

<div class="thumb">
<a href="https://www.youtube.com/watch?v=vXUwE3FGfpg"><img src="https://i.ytimg.com/vi/vXUwE3FGfpg/mqdefault.jpg"/></a>
<br/>
<a class="highlight" href="http://www.yegor256.com/2015/01/15/how-to-cut-corners.html">#NoAltruism</a>
<br/>
<span class="subtitle">
  4) We encourage <a href="http://www.yegor256.com/2014/11/24/principles-of-bug-tracking.html">egoism</a> and
  <a href="http://www.yegor256.com/2018/03/06/speed-vs-quality.html">laziness</a>.
</span>
</div>

<div class="thumb">
<a class="highlight" href="http://www.yegor256.com/2014/04/13/no-obligations-principle.html">#NoObligations</a>
<br/>
<span class="subtitle">
  5) We encourage programmers to work only when they find it profitable.
</span>
</div>

<div class="thumb">
<a class="highlight" href="http://www.yegor256.com/2015/02/16/it-is-not-a-school.html">#NoHelp</a>
<br/>
<span class="subtitle">
  6) We don't teach programmers and we don't help them.
</span>
</div>

<div class="thumb">
<a class="highlight" href="http://www.yegor256.com/2014/04/13/bugs-are-welcome.html">#NoFear</a>
<br/>
<span class="subtitle">
  7) We encourage programmers to find bugs and we
  <a href="http://www.zerocracy.com/policy.html#29">pay them for that</a>.
</span>
</div>

</div>

<!--
no loyalty: everybody works for money
no inequality: we don't care who works for us
no guilt: we work out of greed
no meetings
no estimates
no obligations
no compromises
no excuses
-->

We realize that our approach is very
[different](http://www.yegor256.com/2014/04/17/how-xdsd-is-different.html) from all other
traditional methods of management. In our experience
our way of managing projects gives a lot of
<a class="highlight">benefits</a> to
all [stakeholders](http://www.yegor256.com/2016/07/10/software-project-roles.html):

  * Programmers are more [motivated](http://www.yegor256.com/2017/09/19/what-motivates-me.html);
  * Costs are [lower](http://www.yegor256.com/2014/04/11/cost-of-loc.html);
  * Quality is [higher](http://www.yegor256.com/2016/08/05/distributed-teams-are-higher-quality.html);
  * Maintainability is higher and turnover doesn't hurt us.

The platform was launched to the market in May 2018. Since then
we've already managed to deliver what we promise to a number of
<a href="/testimonials.html" class="highlight">happy clients</a>, this is what [they say](/testimonials.html) about us.

Here is our <a href="/portfolio.html" class="highlight">portfolio</a>,
a short list of projects we completed over the last few years
using our management platform.

To try it out, <a href="https://www.0crat.com/rfp" class="highlight">submit an RfP</a>
and one of [our architects](https://www.0crat.com/team) will get in touch with you.
