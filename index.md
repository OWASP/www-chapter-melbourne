---

layout: col-sidebar
title: OWASP Melbourne
tags: Melbourne Australia AppSecDay
level: 0
region: Oceania
meetup-group: Application-Security-OWASP-Melbourne
country: Australia
postal-code: 

---



## Welcome
Welcome to the Melbourne, Australia chapter homepage.
We look forward to welcoming you at our events.

Follow chapter news and activites on:
 - [Twitter @OWASPmelbourne](https://twitter.com/OWASPmelbourne)
 - [Meetup.com](https://www.meetup.com/Application-Security-OWASP-Melbourne/)
<br /><br />

### The Meetup
Our talks can be on any aspect of application security, some of our past talks have been:

  - Implementation of Security in the Software Development Lifecycle
  - Creating secure code requires more than just good intentions
  - Top Ten Web Defences
  - Introduction to Buffer Overflows.

Take a look at our upcoming meetups, and past ones at our [Meetup.com Page](https://www.meetup.com/Application-Security-OWASP-Melbourne/). <br />
Watch past meetups on our [OWASP Melbourne Youtube Channel](https://www.youtube.com/channel/UCDwRks28thuvwICPM5VgmSQ) (which we publish videos to when we can).

Last, but not least, we are all volunteers and typically pay for
everything ourselves. If you like what we do and would like to show your support - please consider donating and becoming an [OWASP member](https://owasp.org/membership/). 
<br /><br />


#### Speaking at a Meetup
To be a speaker at the next Melbourne Chapter event, simply message the local chapter leader on [Meetup.com](https://www.meetup.com/Application-Security-OWASP-Melbourne/) with details of the talk. You can also reach out via Twitter DMs, or via emails to one of the Chapter leads.

<br /><br />
### OWASP AppSec Day Conference
[OWASP AppSec Day](https://appsecday.io/) is Australia’s only conference dedicated entirely to building and deploying secure web and mobile applications, covering DevSecOps practices for fast Agile software delivery environments. We aim to provide a welcoming environment for developers, testers, devops engineers and security professionals. To improve their knowledge, skills and to network with other like minded professionals. 

In 2017 we sold 300 tickets to AppSec Day, with a successful event and positive feedback we expanded our venue and for AppSec Day 2018, doubled in size with a sold out crowd of 650 software developers, testers, devops engineers, students and security professionals, interested in learning about building secure web and mobile applications, covering DevSecOps practices for Agile software delivery environments. The feedback from our 15+ sponsors has been positive year after year, with our major sponsor The CommonWealth Bank being with us from the start, supporting us as we grow and helping us succeed in our mission of providing security awareness to as many technology and security professionals as possible. For AppSec Day 2019 we experienced similar growth, with over 800 delegates attended.

Watch past AppSec Day conference videos on the [AppSecDay Youtube Channel](https://www.youtube.com/channel/UCSaEzCX3PAxtdHdMnD60xIw).

<br /><br />
## Participation
The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects, tools, documents, forums, and chapters are free and open to anyone interested in improving application security. Like most chapters, we're volunteer run.

Chapters are led by local leaders in accordance with the [Chapter Leader Handbook](/www-policy/rules-of-procedure/chapter-handbook). Financial contributions should only be made online using the authorized online donation button. To be a SPEAKER at ANY OWASP Chapter in the world simply review the [speaker agreement](/www-policy/speaker-agreement) and then contact the local chapter leader with details of what OWASP Project, independent research, or related software security topic you would like to present.

Everyone is welcome and encouraged to participate in our [Projects](/projects), [Local Chapters](/chapters), [Events](/events), [Online Groups](https://groups.google.com/a/owasp.com/){:target='_blank'}, and [Community Slack Channel](https://owasp.slack.com/){:target='_blank'}. We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert. We also encourage you to be [become a member](/membership) or consider a [donation](/donate) to support our ongoing work.

## Sponsors
### Chapter Sponsors
If you'd like to support our chapter events through sponsorship, please reach out to us via Twitter (preferred), and via email to any of our Chapter Leaders below.

<br /><br />
## Chapter leaders

  - [Daniel Ting](mailto:Daniel.ting@owasp.org) |
    [@hellodanielting](https://twitter.com/hellodanielting)
  - [Aaron Robertson](mailto:aaron.robertson@owasp.org) |
    [@hotpheex](https://twitter.com/hotpheex)

## Contact

  - **[OWASP Melbourne Meetup.com
    page](http://www.meetup.com/Application-Security-OWASP-Melbourne)**.
  - [Twitter, but of course\!](http://twitter.com/OWASPmelbourne)
  - [Slack, yes we have that too\!](https://owasp-slack.herokuapp.com/)
    - We're on Slack Channels `#chapter-melbourne` and `#appsec-day`
  - [but the Melbourne Chapter is more social on Discord](https://discord.gg/uAWze2B) come say hi :)
  
## Events List
{% include chapter_events.html group=page.meetup-group %}

<script type='text/javascript'> 
$(function(){ $(".timeclass").hover(function() { utc_str = $(this).text(); ndx = utc_str.indexOf(':'); st_hour_str = utc_str.substring(0, ndx); st_min_str = utc_str.substring(ndx + 1, ndx + 3); utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(st_hour_str), parseInt(st_min_str), 0); start_dt = utc_dt.setZone(luxon.DateTime.local().zoneName); ndx = utc_str.lastIndexOf(':'); end_hour_str = utc_str.substring(ndx - 2, ndx - 1); end_min_str = utc_str.substring(ndx + 1, ndx + 3); utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(end_hour_str), parseInt(end_min_str), 0); end_dt = utc_dt.setZone(luxon.DateTime.local().zoneName); popstr = start_dt.toLocaleString(luxon.DateTime.TIME_WITH_SECONDS) + ' to ' + end_dt.toLocaleString(luxon.DateTime.TIME_WITH_SHORT_OFFSET); $(this).prop('title', popstr); }); }); </script>
