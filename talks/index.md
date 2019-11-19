---
title: Talks 
tab: talks
---

## Talks

### The End of the AppSec Team  
_LASCON X 2019_, _OWASP Bay Area November 2019_

Is your application security team large enough? After growing beyond a few people, security teams often find themselves desperately trying to hire more AppSec folks. While this is good for those of us in the industry, is it even mathematically possible to hire enough AppSec folks to handle the amount of code, features, platforms, and products the rest of your organization is churning out? Even with all the tools one can buy, it is unlikely the AppSec Team can ever match the pace of the rest of the engineering team. If the AppSec team can never be big enough, what can we do? Well, let’s hop into our time machines, skip past the current AppSec grind, and take a look into the future at the end of the AppSec team.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vQSTeH8_31rjRx-FSXYLMemMKZvLxTWOWUP4HsaBuUyccSrPRGQoewl12PXkmugXxph9lkKmQGY7_H8/pub?start=false&loop=false&delayms=3000))

### Continuous Security for DevOps Velocity  
_ISSA LA Summit 2019_ and _DBS AppSecCon 2018_

The security industry initially reacted to the "DevOps" movement with dismay: developers deploying code themselves? Hundreds of deploys per day? How could security teams possibly keep up with that rate of change? As the DevOps approach has become a mainstream development method, security teams have begun to embrace DevOps and discover the security benefits enabled by the DevOps methodology. Adapting to a DevOps world requires not just the security team to change how they operate, but a realignment of how security permeates the entire organization.

In this talk I share my experiences integrating security with fast-moving development teams, the successes and failures I have seen, as well as guidance on turning DevOps into DevSecOps.

([Slides](/papers/Justin_Collins_ISSALA_Summit_2019.pdf))

### The Unreasonable Struggle of Commercializing Open Source  
_RailsConf 2019_

With at least $55 billion in open source-related acquisitions in 2018, you might think we finally figured out how to fund and monetize open source software. Unfortunately, we have only reached an awkward stage of growing pains! With conflicting goals, people are struggling to turn their OSS work into revenue while not losing the powerful open source effects which made the software successful in the first place.

From the perspective of someone who has gone through the pain of commercializing open source, let’s take a deeper look at the unexpected challenges and potential solutions.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vRrUr9_SQPQnQq-jKt4QLrBQ2t9WBL2XIuKw38kboGYXmMwxK3r2-xTsQsWkIy7b3W-LnhzAwQyJxFo/pub?start=false&loop=false&delayms=3000) \| [Video](https://www.youtube.com/watch?v=mCrOi9QQCwU))

### The Evolution of Rails Security  
_RailsConf 2018_

Rails has a reputation for being secure by default, but how deserved is that reputation? Let's take a look back at some of the low points in Rails security history: from the first Rails CVE, to the controversial GitHub mass assignment, the 2013 Rails apocalypse, and more recent remote code execution issues. Then we'll cheer ourselves up with the many cool security features Rails has added over the years! We'll cover auto-escaping, strong parameters, default security headers, secret storage, and less well-known features like per-form CSRF tokens and upcoming Content Security Policy support.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vQlIfuxVc8H44UvSD6l_oX97mMutgk9FtyABlymTKGPnBm0fNjdkWvStQYmWHLbYM2bBFC-kw7YwxBN/pub?start=false&loop=false&delayms=3000) \| [Video](https://www.youtube.com/watch?v=Btrmc1wO3pc))

### Absolute AppSec Episode #12

Catching up with Justin Collins, creator of Brakeman/Pro, during LocoMocoSec 2018 Conference from Kona, HI.

([Audio](https://absoluteappsec.com/episodes/Absolute_AppSec_Ep_12.mp3) \| [Video](https://youtu.be/few9AN1zwPE))

### Taking on the King: Killing Injection Vulnerabilities  
_AppSec California 2018_

How do we dismantle the reign of dangerous and prevalent vulnerabilities? "Injection" has crowned the OWASP Top 10 since 2010, while cross-site scripting (a type of injection) has maintained placement in the top four since 2003. If these two vulnerabilities are well-understood, well-documented, and have "clear" solutions, why have they remained on the OWASP Top 10 for nearly 15 years? Let's take a step back to examine what causes injection (and XSS) vulnerabilities and potential plans for their dethronement.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vR8pW1qRdO3ZESkvrcS2UdzYh6xe8uSzFKKrWD0W29HCu5HtYCq6EJD17ovmBLL7fryNy_kWSicAVbZ/pub?start=false&loop=false&delayms=3000) \| [Video](https://youtu.be/g_24036NDhM))

### Brakeman Lightning Talk  
_RailsConf 2017_

1 minute lightning talk.

Use Rails? Use Brakeman.

([Slides](https://speakerdeck.com/presidentbeef/brakeman-railsconf-2017-lightning-talk) \| [Video](https://www.youtube.com/watch?v=KGi9wRHWvB0&t=1120s))

### A Technical Tour of Real-World Web Application Vulnerabilities
_CodeMash 2017_

You’ve seen the headlines: *"TWITTER HACKED!"* and then it turns out someone had a weak password like “dadada”. Or else the details are so hazy it’s impossible to tell what actually happened. As a result, security issues become vague problems that happen to *other* companies.

But there is good news! Thanks to the growing popularity of bug bounties and public disclosure, it is easy to take a peek into real security vulnerabilities at well-known companies and learn from them. This tour includes stops at Facebook, Twitter, United Airlines, Domino’s, Instagram, and more! This tour covers all relevant technical details, no fluff. Please fasten your seatbelt and keep hands, feet, and head inside the bus at all times.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vSO2YPP0uPHL7uJOyOie-g3a0JkRZbGPEm_iqdY6wEfEaTjTmkM7Ym3FI1AaSDM-L5d2FMYEV_rhg5W/pub?start=false&loop=false&delayms=3000))

### Static Analysis for Security and DevOps Happiness
_AllDay DevOps 2016_

It is not enough to have fast, automated code deployment. We also need some level of assurance the code being deployed is stable and secure. Static analysis tools that operate on source code can be an efficient and reliable method for ensuring properties about the code - such as meeting basic security requirements. Automated static analysis security tools help prevent vulnerabilities from ever reaching production, while avoiding slow, fallible manual code reviews. This talk will cover the benefits of static analysis and strategies for integrating tools with the development workflow.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vQVJyvkAtW6cqBvrcfgYPotUV1zjh5mW_rTAxeexMza9ihcrNxKI9pusJuOcmyTrxNvNLVpa06CWmkn/pub?start=false&loop=false&delayms=3000) \| [Video](https://www.youtube.com/watch?time_continue=12059&v=652TOZwGfB0))

### Practical Static Analysis for Continuous Application Security
_DevSecCon London 2016_

Static code analysis tools, which attempt determine what code does without actually running the code, provide an excellent opportunity to perform lightweight security checks as part of the software development lifecycle. Unfortunately, building generic static analysis tools, especially for security, is a costly, time-consuming effort. As a result, very few tools exist and commercial tools are very expensive. On top of that, commercial tools are often not built for continuous integration and they may not support the languages and frameworks you use.

The good news is building targeted static analysis tools for your own environment with rules specific to your needs is much easier! This workshop will go through straight-forward options for static analysis, from grep to writing rules for existing tools through writing your very own static analysis tool.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vQYSb13QIKoeUR1JwFDG-8to72F09dHx0OXQ9Lbv5u_fa2F3hE3HhacwW1nLH4lIFZ64GXiCtNDOQji/pub?start=false&loop=false&delayms=3000))

### Practical Static Analysis for Continuous Application Security
_AppSec USA 2016_

Static code analysis tools that attempt determine what code does without actually running the code provide an excellent opportunity to perform lightweight security checks as part of the software development lifecycle. Unfortunately, building generic static analysis tools, especially for security, is a costly, time-consuming effort. As a result very few tools exist and commercial tools are very expensive - if they even support your programming language.

The good news is building targeted static analysis tools for your own environment with rules specific to your needs is much easier! Since static analysis tools can be run at any point in the software development life-cycle, even simple tools enable powerful security assurance when added to continuous integration. This talk will go through straight-forward options for static analysis, from grep to writing rules for existing tools through writing static analysis tools from scratch.

([Slides](https://speakerdeck.com/presidentbeef/practical-static-analysis-for-continuous-application-security) \| [Video](https://youtu.be/VXJNuDV6DQo))

### Practical Static Analysis for Continuous Application Security
_SecTor 2016_

Static code analysis tools that attempt determine what code does without actually running the code provide an excellent opportunity to perform lightweight security checks as part of the software development lifecycle. Unfortunately, building generic static analysis tools, especially for security, is a costly, time-consuming effort. As a result, very few tools exist and commercial tools are very expensive – if they even support your programming language.

The good news is building targeted static analysis tools for your own environment with rules specific to your needs is much easier! This talk will go through straight-forward options for static analysis, from grep to writing rules for existing tools through writing static analysis tools from scratch. Since static analysis tools can be run at any point in the software development life-cycle, even simple tools enable powerful security assurance when added to continuous integration.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vT2-Xb5tDF3XyfRGE95-5M57KN1pUxhGq7-r9-PvmuvIRq9g9biF96Hc6apRR13KlTIMpESIUyg3Cdu/pub?start=false&loop=false&delayms=3000) \| [Video](https://sector.ca/sessions/practical-static-analysis-for-continuous-application-security/))

### Riding the Rails Safer with Brakeman
_RubyConf Brazil 2016_

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vQ80qusKjGpyMtQJ7xsLL-GPHyekiahm9D5lW5fYNL9GnFe_nbh_Ke-0na_jv7d0pgMyrx9LLQEJkkV/pub?start=false&loop=false&delayms=3000) \| [Video](https://www.eventials.com/player-embed/OTc2OzU5MTAy/))

### Static Analysis “Tricks” for Ruby
_Ruby Remote Conf 2016_

Static analysis (determining information about a program without actually running it) may seem like a strange fit for a dynamic language, but for many use cases static analysis can work just fine for Ruby. For example, a security tool like Brakeman does not need to accurately understand every application it scans – it only needs to do a reasonable job of finding vulnerabilities. Building static analysis tools for a specific goal is much easier than you may think, even for dynamic languages. In this talk, we’ll cover how static analysis works in general and then go through some of the little "tricks" Brakeman uses to better understand the code it scans.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vSAQHKNeGRVqOhe7RMPoUkgFToHPIX14cdscRdUvEcFbWS5f4o5sYGkilnIMZfOmZ6WKWWxIrrLa-J6/pub?start=false&loop=false&delayms=3000))

### Brakeman
_FogCity Ruby September 2016_

The Internet is a dangerous place to deploy applications alone! Take Brakeman with you. Brakeman scans the source code of Rails applications to find potential security vulnerabilities. Learn what Brakeman can do for you and how best to utilize it in your development workflow.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vTc2tY-E2fHkRUVKq58rG6qa6ZJV24ZFZ4Tw2mWSpkITnOCNTM27n3lF5aD71g5nKA654nPu8UqH1_L/pub?start=false&loop=false&delayms=3000))

### ...But Doesn’t Rails Take Care of Security for Me?
_RailsConf 2016_

Rails comes with protection against SQL injection, cross site scripting, and cross site request forgery. It provides strong parameters and encrypted session cookies out of the box. What else is there to worry about? Unfortunately, security does not stop at the well-known vulnerabilities and even the most secure web framework cannot save you from everything. Let's take a deep dive into real world examples of security gone wrong!

([Slides](https://speakerdeck.com/presidentbeef/dot-dot-dot-but-doesnt-rails-take-care-of-security-for-me) \| [Video](https://youtu.be/3P9naxOfUC4))


### Brakeman Lightning Talk  
_RailsConf 2016_

Three minute introduction to Brakeman.

([Video](https://youtu.be/DHHHnPwSY5I?t=55m6s))

### Continuous Security with Practical Static Analysis
_CodeMash 2016_

Static code analysis tools, which attempt determine what code does without actually running the code, provide an excellent opportunity to perform lightweight security checks as part of the software development life-cycle. Unfortunately, building generic static analysis tools, especially for security, is a costly, time-consuming effort. As a result very few tools exist and commercial tools are very expensive - if they even support your programming language.

The good news is building targeted static analysis tools for your own environment with rules specific to your needs is much easier! This talk will go through straight-forward options for static analysis, from grep to writing rules for existing tools through writing your very own static analysis tool. Since static analysis tools can be run at any point in the software development life-cycle, even simple tools enable powerful security assurance when added to continuous integration.

([Slides](https://speakerdeck.com/presidentbeef/continuous-security-with-practical-static-analysis))

### Rise of the Machines: Security Automation at Twitter
_DevOps Enterprise 2015_

In 2009, multiple security incidents at Twitter resulted in an investigation by the Federal Trade Commission (FTC). As part of its 2010 decision, the FTC instructed Twitter to form and maintain an effective information security program. By 2012, Twitter had exploded with hundreds of millions of Tweets sent every day and a rapidly growing engineering force. The amount of new code being written quickly outpaced the security team, leading them to consider ways of reducing their workload by automating tools and processes.

Security automation at Twitter started with a desire to automate a single static analysis tool. From there we started to see more opportunities to write code to prevent security vulnerabilities, instead of manually to find vulnerabilities. This talk will cover that journey, our philosophy for unobtrusive continuous security, the simple yet effective tools we used, and the general approach I believe works for multiplying impact through automated security.

([Slides](https://speakerdeck.com/presidentbeef/security-automation-at-twitter-rise-of-the-machines) \| [Video](https://youtu.be/5aSN97IrFkk) \| [Interview Video](https://youtu.be/-iw029eArsQ))

### Brakeman and Rails Security
_Ruby Rogues 219_

Episode 219 of Ruby Rogues -  Brakeman and Rails Security with Justin Collins.

([Podcast](https://devchat.tv/ruby-rogues/219-rr-brakeman-and-rails-security-with-justin-collins))

### The World of Rails Security
_RailsConf 2015_

Learning to keep your Rails application secure is an often-overlooked part of learning Rails, so let's take a trip through the world of Ruby on Rails security! The journey will start with an overview of security features offered by the popular web framework, then we'll detour through dangerous pitfalls and unsafe defaults, and finally end with suggestions for improving security in Rails itself. As a bonus, we'll talk about how to integrate security into the development process.

([Slides](https://speakerdeck.com/presidentbeef/the-world-of-rails-security-railsconf-2015) \| [Video](https://youtu.be/AFOlxqQCTxs))

### Security Tech Talk
_WePay Tech Talk January 2015_

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vS97hr06oQ084GPPP5Br0gJfSxEL1ykYq58F6uwRmPHkghxQKuAOX4nLP0djSiTmmpkfyF_Q51LQjZs/pub?start=false&loop=false&delayms=3000))

### World of Ruby on Rails Security
_OWASP NoVa/DC September 2014_

Take a quick trip through the world of Ruby on Rails security! The journey will start with an overview of security features offered by the popular web framework, then detour through dangerous pitfalls and unsafe defaults, and finally end with suggestions for improving security in Rails apps and integrating improvements into the development process. 

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vSLQGMDnsSWKSBFWgUvkGxvqbxDIS6ZT8-HmpsArALt4Dk9YuAiyJLaaGDnY38WoJhTziw8PfE1k5W8/pub?start=false&loop=false&delayms=3000))

### Mobile Ad Hoc Networks Are Coming, But We Aren't Ready
_Midwest.io 2014_

In any given day, you likely carry your pocket computer (AKA "smartphone") within wireless range of hundreds of other pocket computers. In schools all over the US, students are sending an unrelenting stream of instant messages to each other while sitting in dense networks of little wireless devices. Yet we continue to rely on cellular towers, WiFi access points, and the Internet to transmit messages for us while we are actually closer to the destination than they are!

Mobile ad hoc networks (MANETs) consist of many devices moving around and communicating with and through each other, without any predetermined infrastructure. While MANETs have been a research topic since the 1970s, much of the research has focused on the networking piece: basically the transport layer protocols and below. Much less attention has been given to creating and supporting applications for these networks, yet killer applications drive adoption!

This talk will briefly describe MANETs, but focus mostly on MANET application development: the challenges, the potential solutions, and the very promising - and very near - future. MANETs are ready to break through to the mainstream. Will you be ready?

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vTd1P48acQf9tUxTbLCBojjGyAZhjJ4I61MoTDOauoyKkItF03cBqi8WBRKrUtwcHw-iTd2ExQI0450/pub?start=false&loop=false&delayms=3000) \| [Video](https://youtu.be/nYeIBLve-pc))

### Making Your Life Easier with Static Analysis for Dynamic Languages
_BSidesLA 2014_

Security tools abound for statically-analyzing statically-typed languages, but sadly dynamically-typed languages are often dismissed as "too hard" or even "impossible" to analyze. Of course, that's nonsense! We can and should have tools for dynamic languages and their frameworks. But while commercial tools continue to lag behind in this area, sites running on web frameworks like Rails and Django are proliferating. I hope to offset that discrepancy by getting you excited about static analysis and demonstrating it might not have to be that hard. This talk will also include lessons learned while writing Brakeman (a static analysis security tool for Rails) and the many ways static analysis can be used to make your life easier, whether you are a developer or a security professional or both.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vShIJyJEGb1MYNP2c94W_WU02MxXZ_nz93xrayeBiTYEqIbO6PvUT14A4mLXJlybp4dtA5yFXtrf45e/pub?start=false&loop=false&delayms=3000))

### Using Brakeman and Automation in Practice in the SDLC and Stuff
_NetflixOSS Meetup Season 2 Episode 3_

([Video](https://youtu.be/kda8RZ5NIlM))

### Making Your Life Easier with Static Analysis for Dynamic Languages
_CactusCon 2014_

Security tools abound for statically-analyzing statically-typed languages, but dynamically-typed languages are often dismissed as "too hard" or even "impossible." Of course, that’s nonsense! We can and should have tools for dynamic languages and their frameworks. But while commercial tools continue to lag behind in this area, sites running on frameworks like Rails and Django are proliferating. I hope to offset that gap by getting you excited about static analysis and demonstrating it might not have to be that hard. This talk will include lessons I’ve learned while writing Brakeman (a static analysis security tool for Rails) and the many ways static analysis can be used to make your life easier, whether you are a developer or a security professional or both.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vRjwkq8bR0OVflZOCDHSj6QcuBYjLCLG-R54QP0nLCks9jnn2n8fzGHGknvv5tHWkv6rhFea1km9VuF/pub?start=false&loop=false&delayms=3000) \| [Video](https://youtu.be/JaRlq6mI5wE))

### Tales from the Crypt
_RailsConf 2014_
(with Matt Konda and Aaron Bedra)

In this talk, three Rails security specialists will take a journey through a terrifying Rails application to illustrate common security problems we have seen in the real world. The discussion will include how to identify, fix, and prevent the issues with an emphasis on practical advice. Along the way we will share our experiences and perspectives concerning securely implementing applications. We hope it is a bit scary, and yet fun... like a horror movie!

([Slides](https://speakerdeck.com/presidentbeef/tales-from-the-crypt) \| [Video](https://youtu.be/zZtDOX9kXRU))

### Interview with Creator of Brakeman
_RailsConf 2014_

[Video](https://youtu.be/dltMEsgPa0c)

### Defending the Bird
_Yet Another Conference 2013_
(with Alex Smolen)

The product security team is responsible for ensuring the security of all code Twitter ships. This means proactively finding and fixing vulnerabilities using automation, working closely with engineering teams throughout the company to design and implement secure systems, and building security features into the product. To make all this happen and execute at a fast pace, we practice an agile process and build tools to support rapid information transfer. First, we'll talk about our approach to using automation to ensure that we ship secure code by getting the right information to the right people at the right time. We will also discuss our security review process, which is focused on improving the pace of development and cooperative problem solving. Finally, we'll talk about how we develop security features for Twitter, including our recent improvements to login verification. At Twitter, our goal is to reach every person on the planet. Having a global reach means understanding and responding to many threats. We want to share the details of our team's organization and process that allows us to keep Twitter secure as we continue to rapidly scale.

([Slides](https://www.slideshare.net/yandex/defending-the-bird-justin-collins-alex-smolen-twitter) \| [Video](https://events.yandex.ru/lib/talks/1126/))

### Security Automation at Twitter
_OWASP NoVa June 2013_
(with Neil Matatall)

Despite the apparent simplicity of Twitter, a large quantity of code is shipped every day. Despite our best efforts, the product security team cannot effectively review that much code. Using Brakeman, a static analysis security scanner for Ruby on Rails, was the first step towards automating the review process. However, this quickly grew into a need for automating not just running Brakeman, but also other security tools and technologies. For example, our effort to apply security headers universally across our sites requires a central location for analyzing CSP reports.

While working on and thinking about security automation, we have come up with a set of philosophies to help guide our decisions which we would like to share with you. In this talk we will discuss Brakeman and security headers in depth, along with how we have integrated these tools and others into our security automation dashboard (SADB).

### Static Analysis for Ruby (It’s Okay to Be Sloppy)
_LA Ruby Meetup March 2013_

Statically analyzing programs has been proven to be both undecidable AND uncomputable even for statically typed languages...so why even bother trying it with Ruby, which includes `eval`, `method_missing`, `const_get`, and `send`?
As with many "impossible" problems in computer science, there are benefits to finding solutions that are "good enough" and not worrying too much about perfect results. This talk will cover the techniques Brakeman (Rails static analysis security tool) uses to improve accuracy and relevance of security warnings with Ruby data flow analysis. Hopefully this will demonstrate the usefulness of static analysis even on very dynamic languages.

([Slides](https://docs.google.com/presentation/d/e/2PACX-1vQNycUKgIkC2HeSd1y-Dru66tTDT3ZE-RfRnI5maCjI60GSQhXikFjfSMcxjTPM3L8hoK217pwx9fNv/pub?start=false&loop=false&delayms=3000))

### Keeping Rails Applications on Track with Brakeman
_RailsConf 2012_

A recent report by Veracode found cross-site scripting in 68% of surveyed web applications and SQL injection in 32%, even though these are well-known, easily preventable, and easily detectable vulnerabilities. As applications grow larger, it becomes harder and harder to manually verify that every line of code is adhering to security guidelines - even given the built-in protection available with Ruby on Rails.

[Brakeman](http://brakemanscanner.org/) is an open source static analysis tool which provides painless vulnerability scans of Rails code from "rails new" through deployment. Running Brakeman as a part of continuous integration provides feedback during all stages of development and can alert developers immediately when a potential vulnerability is introduced. Bringing security testing as close to the developer as possible (even scanning as files are saved) means security problems are caught faster - and the sooner problems are found the cheaper they are to fix.

As a static analysis tool, Brakeman can be run without worrying about deploying the whole application stack: no web server, database, configuration, or application dependencies required - not even Rails itself. This allows fast, easy vulnerability scans on any Rails project. We talk a lot about testing in the Ruby and Rails community, but somehow security testing is passed over. This needs to change! This talk will cover how to incorporate Brakeman into Rails development and how it can improve application security, as well as a look into how Brakeman works internally.

([Slides](https://speakerdeck.com/presidentbeef/keeping-rails-applications-on-track-with-brakeman) \| [Video](https://youtu.be/p3VMf3oQWKg))

### Put Your Robots to Work: Security Automation at Twitter
_AppSec USA 2012_

(with Neil Matatall and Alex Smolen)

With daily code releases and a growing infrastructure, manually reviewing code changes and protecting against security regressions quickly becomes impractical. Even when using security tools, whether commercial or open source, the difficult work of integrating them into the development and security cycles remains. We need to use an automated approach to push these tools as close to when the code is written as possible, allowing us to prevent potential vulnerabilities before they are shipped. We worked with development, operations, and release teams to create a targeted suite of tools focused on specific security concerns that are effective and don’t introduce any noise. This presentation will give an overview of what we’ve done over the past year, what we have learned along the way, and will provide advice for anyone else going down this road.

([Video](https://vimeo.com/54250716))

### Brakeman and Jenkins: The Duo Detect Defects in Ruby on Rails Code
_AppSec USA 2011_
(with Tin Zaw)

Ruby on Rails (RoR) is a popular web application development framework with support for Model-View-Controller architecture, "convention over configuration", "don't repeat yourself" or DRY principle, and test-driven development. The framework is designed to be resistant to web security exploits such as cross-site scripting, SQL injection and cross-site request forgery.

Even with built-in protections, it is possible, and often witnessed, that security flaws get introduced in Ruby on Rails code. Brakeman, a static code analyzer for Ruby on Rails code, is designed and developed at AT&T Interactive by Justin Collins to detect such flaws during early phases of development cycle. To further reduce the burden on the developer, Brakeman is integrated into a continuous build and integration server called Jenkins, formerly known as Hudson.
This talk will focus on basics of security features in Rails framework, advantages of using static analysis for discovering security issues, design and development of Brakeman, and how Brakeman and Jenkins are used together at AT&T Interactive to reduce security defects. The only static code analyzer for detecting security defects in Ruby on Rails code, Brakeman is available on GitHub under open source license.

([Slides](https://speakerdeck.com/presidentbeef/brakeman-and-jenkins-appsec-usa-2012))

### Brakeman
_LA Ruby Meetup October 2010_

Brakeman is a static analysis tool for finding web vulnerabilities in Ruby on Rails applications. This new tool provides a crucial testing step in the development process, without requiring any deployment of the application. The talk will discuss what Brakeman does and does not do, how it works, and why everyone writing Rails applications should be using it.

### Brakeman
_AT&T Interactive_

([Video](https://youtu.be/2MzrnBiNgZ4))
