# Aaron Stannard 👋

I build OSS .NET technologies aimed at making it easier to build large-scale applications. 

## ⚡ Work
I'm currently the Founder and CEO of [Petabridge](https://petabridge.com/), a company that provides commercial support, training, and tooling for [Akka.NET](https://getakka.net/), one of the OSS projects I founded. We create products like [Phobos Akka.NET APM](https://phobos.petabridge.com/), [Petabridge.Cmd Akka.NET CLI](https://cmd.petabridge.com/), and OSS tools such as [NBench - .NET Performance Testing](https://nbench.io/).

* 🔭 [See My Talks and Podcast Appearances](https://aaronstannard.com/talks/)
* :bird: [@Aaronontheweb on Twitter](https://twitter.com/Aaronontheweb)
* :bookmark_tabs:	[aaronstannard.com](https://aaronstannard.com/)

## Blog Posts
<!--START_SECTION:feed-->
#### [Introducing Sdkbin - The Marketplace for Software Developers](http:&#x2F;&#x2F;www.aaronstannard.com&#x2F;sdkbin-marketplace&#x2F;) 
*I’ve written several posts recently about creating sustainable open source projects by treating them like proper businesses - my journey for the past 5-6 years since founding Petabridge has been a quest to find a way to create sustainable, profitable business models built on top of the open source software I’ve spent the last 6-7 years developing.

The greatest obstacle to building sustainable open source businesses today is creating the infrastructure required to sell products + services; fulfill those orders; handle billing; and hardest of all - get discovered by customers. Each of these areas requires building repeatable systems in areas that are mostly unfamiliar to software developers.



The hard part of building an open source business should be creating a product users want to buy - not building the mechanisms for selling it.

And so today it’s with great pleasure that I’m announcing a first look at Sdkbin - the marketplace for software developers.



Sdkbin is a project we created at Petabridge to sell our own “open core” products, such as Phobos, and our Akka.NET support plans directly to our own customers.

Features
Sdkbin is meant to be a marketplace for selling NuGet packages, support plans, and in the future other types of software packages (i.e. NPM, Maven, etc):


  Independent software publishers can create storefronts for multiple products and services, with support for different licensing models;
  Sdkbin automatically handles all purchases using credit cards primarily - all metering &#x2F; recurring billing is handled directly through the platform;
  When a customer makes a purchase on Sdkbin, a brand new NuGet feed specific to that customer will be provisioned on the fly with access to packages that they’ve purchased - if the customer fails to renew their subscription or pay for upgrades (depends on the licensing model chosen by the publisher,) they will lose access to their feed or they’ll lose access to future releases of the software;
  Customers will be provided with detailed invoices and spend management tools for all of the different vendors they purchase from on the Sdkbin marketplace - this is designed to make it easier for corporate procurement departments to buy products from third party vendors;
  Publishers will be provided with detailed metrics on how their products are being consumed and which ones drive revenue; and
  Most importantly - customers will be able to discover vendors in the marketplace and, eventually, see trust + service ratings on vendors.


Our target date for shipping the platform and selling our own products on Sdkbin first is July 31st 2020. We will begin the process of onboarding and adding support for third-party publishers shortly after that.

You can sign up for early access to Sdkbin here.

Why Sdkbin?
Why bother building an entire platform to sell NuGet feeds, support services, and so on? Because this has been a historically expensive problem for us at Petabridge - sales costs, i.e. the amount of labor it takes to complete and close a sale, is very high even for small purchases when BigCorp has to talk to live humans at Small Software Startup X to place the order.

When you streamline that entire process to merely entering a credit card number into a form and instantly receiving your product 24&#x2F;7&#x2F;365, the likelihood of closing a sale improves and the level of effort required to close it drops by multiple orders of magnitude.

The dream of Sdkbin is twofold:


  Make it possible for customers to get anything they need, any time they want and
  Make it possible for open source software developers to make money while they sleep.


We believe that by creating a platform that makes fulfillment + sales + operations fully automated, using widely-adopted standards like NuGet to deliver the product, we can achieve both of these. In the grand scheme of things, we’re making it easier to build a world powered by software and solving the open source sustainability problem in the process.

There’s a second benefit to doing this - as Sdkbin gets adopted and used more frequently by customers, the more it becomes a trusted partner to facilitate a marketplace between buyers and customers. This can ultimately help a longer tail of smaller software vendors overcome the notorious “corporate procurement department” problem - because in this case, the party sitting in the middle of the transaction is highly trustworthy and can resolve disputes on the behalf of the customer or the publisher.

How can I get started?
The first step, is to sign up for the Sdkbin mailing list and to fill out our Sdkbin Publisher Survey - the latter will help direct the Sdkbin product roadmap, and the former will allow you to receive updates to it.

If you have any questions, please reach out to us on Twitter @getSdkbin or email us at hi@Sdkbin.com*
#### [The New Rules for Playing in Microsoft&#39;s Open Source Sandbox](http:&#x2F;&#x2F;www.aaronstannard.com&#x2F;new-rules-dotnet-oss&#x2F;) 
*Here we go again. “The Day AppGet Died” - the short version: OSS developer fills a hole in the Windows ecosystem, Microsoft offers him a job to work on this kind of product inside the company, ghosts him, releases their competing product which appears to have borrowed heavily from his designs, doesn’t attribute original developer’s work, Internet gets mad, Microsoft gives a non-apology apology, and maybe some kind of resolution.

The moral of the story:

Another example story on why you can build either something on Microsoft ecosystem or build something popular, but never do both.&amp;mdash; Bartosz Sypytkowski (@Horusiath) May 27, 2020


David Fowler and Damian Edwards, some of the leaders of the .NET ecosystem at Microsoft, more or less concurred:

If I had to boil it down I&#39;d say that .NET as a platform prefers ubiquitous shared abstractions defined by Microsoft. That usually happens the moment something in the platform needs to use it.&amp;mdash; David Fowler (@davidfowl) May 27, 2020


If you build something that enough users want to use in the .NET ecosystem, Microsoft will eventually step in and offer a first party solution because that’s what users prefer. That appears to be what’s happened with AppGet and it’s happened with ScriptCS, NHibernate, and on and on.


  EDIT: After talking to David some more on Twitter following publication, it looks like I may have misunderstood his comment. He meant the abstractions used in the .NET platform, i.e. the interfaces - IDictionary, Stream, HttpClient, and so on. I was talking about the default implementation Microsoft ships of those abstractions - which is what, in my view, competes with the original ideas produced in the OSS ecosystem.


I covered all of this in “The Next Decade of .NET Open Source”:


  I say this as an ex-Microsoft employee, a long time Microsoft fan, and a heavy participant in the .NET OSS ecosystem: Microsoft’s product culture mandates they control everything down the stack. They’re the most risk averse company of all in the entire ecosystem, when it comes to considering third party technologies, and they will only deviate from that strategy when they realize they’re playing from behind.


David’s comment makes it pretty clear that “Not Invented Here” is an intentional strategy to make the underlying .NET runtime and platform secure. He offers some alternatives to end this viscious cycle, such as assembly-neutral interfaces - and the .NET Foundation’s “Maturity Ladder” proposal was another attempt to address this issue.

What is “the issue” - exactly?


  Popular innovations originating from the .NET OSS community are ultimately cannibalized by Microsoft due to Microsoft’s need to have an answer to every question a customer with a wallet might have;
  Microsoft ultimately practices a “one way” OSS model - you can contribute to Microsoft’s projects, but Microsoft won’t support, recommend, or depend upon third party projects even in its own ecosystem unless they achieve critical mass and Microsoft can’t afford to float an alternative (SwashBuckle, XUnit, IdentityServer, come to mind);
  As a result of issues 1-2 on this list, developers willing to take on the burden of OSS will ultimately be driven out the ecosystem and innovation will decline, leading us back to the stagnant ghetto .NET OSS was back in 2014.


It’s worth pointing out - I don’t know any individual developers who set out to create a new OSS project with the intention of building a business around it. That usually happens by accident if at all.

What most OSS developers want is for their work to be used and appreciated. Acknowledgment, attribution, and contribution are the major currencies of open source.

However, in the Microsoft ecosystem even something as trivial as attribution is scarce - because when Microsoft comes along and rips off the design of a popular third party project there’s virtually zero chance they’re going to tolerate the risk that comes with publicly acknowledging their inspirations in writing.

As Hadi Hariri, Head of Developer Advocacy at JetBrains puts it:

Hopefully people will wake up and realise that nothing has changed with Microsoft. They just spent the past few years pushing this marketing OSS pivot because they needed it for their business. It&#39;s still the same tactics, the same foul play.&amp;mdash; Hadi Hariri (@hhariri) May 31, 2020


The New Rules for .NET Open Source
The creation of .NET Core brought about some amazing opportunities in the .NET ecosystem for innovation and creativity. Everything was new and there were opportunities to reinvent how we make world-shaping software and deliver great experiences to our own users. Microsoft was our partner in building a more creative, more open, more compatible, and more free .NET.

That era is over - if it ever existed. We are back to business as usual. If you make something popular in the ecosystem, you can expect it to become part of the platform, offered as a cloud service, built into Visual Studio, or otherwise. You will not be missed.

As Paul Stovell, CEO of Octupus Deploy put it in his post “Why we terminated our partnership with Microsoft”:


  There’s a saying in business that if you want to displace a competitor, you need to build a product that’s at least 10x better. It’s not enough to be “just as good”. Customers will say “why should I use you, we’ve been successful with “. You need a really good reason to overcome that.

  However, in the .NET ecosystem, if you’re Microsoft, that’s not generally true. If Microsoft wants to make a document database, a messaging framework, a unit test framework or a deployment automation tool, it only needs to be 1&#x2F;10th as good before the conversation immediately becomes “why should we use you over the Microsoft thing?”. Microsoft become the default option, even if they’re the last to the game.


The second issue Paul highlights is much the same observation that David made: .NET users prefer 1st party solutions that come directly from Microsoft, even if they suck.

At this point you might be asking yourself: “Aaron, why don’t you just quit the .NET ecosystem, get a Fedora, grow a terrible beard or mustache, take up home brewing, and become a Go programmer already?”

Can’t do that - I look terrible in a Fedora. Also - I have a successful .NET OSS business with employees who like working here. We’re in it for the long haul. But moreover - our community, the .NET community, is responsible for building much of the software that runs the world. It’s a community worth defending and improving.

Microsoft’s central role in .NET subjects it to frequent and necessary criticism. Depleting the .NET ecosystem of innovation, whether by hiring everyone in it or driving them out of the ecosystem through cannibalism, will make .NET worse off for everyone including Microsoft in the long run.

There are three groups that make up the .NET OSS ecosystem:


  Microsoft, the creator of the platform;
  The OSS community, who builds works on top of it; and
  The users, who create value using the works of the previous two groups.


Change must come from somewhere and I have some bad news - it’s not going to be Microsoft (has no short-term economic incentive to change) or the users (Microsoft by default is fine for many of them.)

Incentives matter. It’s going to be the OSS creators who are going to have to reshape the ecosystem by changing and creating new incentives. That’s going to be done by changing the business model of .NET OSS. Here are the new rules for developing open source in the .NET ecosystem:

1 - If you’re filling an infrastructure gap with OSS: logging, configuration, build systems, package management, DI, and so on - accept that you’re going to inevitably get copied if you do it well. Price it in and don’t get mad when it happens. Thank you for your service in improving the .NET ecosystem, even if that work goes unrecognized, but now you know what’s coming.

2 - Incentivize users to care about your project and not just what the project does for them. The slow, creeping force behind the erosion of .NET OSS is a self-inflicted problem: users have no incentive to support third party OSS because Microsoft will eventually assume the costs in maintaining the technologies users use. You heard it directly from the architects who work at Microsoft.

Users need to care about your project in order for it to have a future even after Microsoft creeps into the space. How do you accomplish this?

Some examples of projects that have done this well and how they did it:


  Serilog - even after Microsoft creeped into the logging space Serilog is still an extremely popular logging library. How did they pull that off? By fully embracing what made them different and special: focusing on structured event data inside logs. That level of sophistication isn’t necessary for many users who just want basic logging - but for the developers managing complex systems this differentiator is quite important.
  Akka.NET - my project. Microsoft has now released… I think four different distributed actor system technologies since we launched our project in 2013. We’re still growing rapidly. And we grow because of what makes us different: our actors scale down to support local &#x2F; device use cases, don’t require any third party infrastructure out of the box, our company Petabridge runs lots of trainings and offers hands-on support, and on top of that: lots of Scala developers who switch jobs are delighted to discover that Akka.NET supports much of the same tools, syntax, and ideas as the original Akka project does.
  Autofac - a DI container that is still immensely popular long after Microsoft entered the space. How did they survive? By making strongly typed DI easy, safe, and fun for most .NET developers. The level of documentation they have and the robustness of their technology makes it very difficult to screw up. Developers who rely on DI love Autofac because it’s one of those technologies that “just works.”


The common throughline on these projects: they survive because they’re more than their source code. Each of these projects has active communities which have intrinsic value to users. Microsoft can replace technology; they can’t so easily replace community.

3 - Take OSS sustainability seriously: build a profitable business around your project if you care about long-term viability.

So why would this help change the status quo in the .NET ecosystem? How would this make innovation sustainable long term?

The answer is simple: because you now have an economic incentive to fight for the business of your paying customers. This is why Chocolatey is going to survive the creation of winget whereas AppGet will not: because Chocolatey supports the OSS projects’ founders and contributors livelihoods.

Moreover, breaking the cycle of OSS strip mining requires that corporate users who can afford to pay for OSS software start forming pay-for-OSS habits - and you can only do that by offering something they want.

What are some ways of doing that?


  Consider changing your licensing model - does your code do something complicated and specialized? Dual license it under an aggressive copyleft license like AGPL and require users to purchase a non-transferable, annual license for commercial use. This is what RavenDb and NServiceBus have both done successfully for years. SixLabors is now currently pursuing this for ImageSharp. If you want to get paid for your work, this is a great way to do it.
  Build a moat - can’t change your license? How about offering a managed cloud service for your project? Or proprietary add-ons targeted at big enterprises (auth, access control, and auditing are usually popular.)


4 - Think bigger.

My favorite idea from this list. It addresses an original problem sin with our ecosystem: the problems we address are often small gap-fillers. Why not try something huge and different? Look at Fable and the SAFE stack - these are bold .NET OSS projects. And even if these projects became popular on the same scale as ASP.NET I doubt Microsoft would adopt them - they don’t need to.

Microsoft’s business model is built around fast-following innovators into the greater software ecosystem. The bigger the innovation, the longer it takes for them to enter the space. Small gap-filler innovations won’t take long to integrate into the core of the platform if they’re popular.

Eventually if you are successful with a big, bold new idea Microsoft might want to follow you with their own offering. But that’s a process that will take many years - plenty enough to build a moat. Chocolatey and AppGet were big, bold ideas when they were first created years ago - now they’re commonplace as a result of their success and the success of that type of project more globally in other ecosystems.

Conclusion
Don’t confuse criticism of Microsoft or the .NET ecosystem for mean-spirited trolling. The .NET ecosystem is responsible for building the software that runs the world. The critics who’ve weighed in on this episode largely want to keep it that way. And this is a discussion that should never end - as it’s the only way to avoid repeating the mistakes of our past.*
#### [How to Build Sustainable Open Source Software Projects](http:&#x2F;&#x2F;www.aaronstannard.com&#x2F;sustainable-open-source-software&#x2F;) 
*In my last post about “The Next Decade of .NET Open Source” I alluded to a future blog post about open source sustainability. This is it.



Some background: in January 2015, fresh off of the very public failure of MarkedUp, my first company, and the total destruction of my life savings at the ripe age of 29 - I founded my current company Petabridge. We’re five years old now, growing rapidly, and we’re entirely self-funded.

Petabridge is a business built entirely around supporting the users of its .NET Open Source projects, primarily the Akka.NET project, which I founded out of necessity in order to build a real-time marketing automation product at my previous business.

That’s the origin story of how I got here and why I’m delighted to hear others start talking more actively about the need for “open source sustainability” in communities everywhere. I developed a model that worked for our project and that exact model isn’t translatable to every other project, but the theory that built the model is. And that theory is what I want to share.

Sustainable Open Source Projects are Sustainable Businesses
What we really mean by “sustainable” OSS projects are projects where the core contributors have a sustainable interest in keeping the project going, getting others to use it, responding to bug reports, and so forth.

There’s a time-tested system for creating self-sustaining organizations and it’s called “capitalism,” in which the incentives that further the customers’ interests are aligned with those of organizations responsible for producing the good or service consumed by the customer, thus creating a positive feedback loop and competition that drives innovation, better experiences, and more choices.

Misalignment of incentives are what make OSS unsustainable today - customers, OSS consumers, get something for free and producers get nothing but more unpaid demands for their time in return. Aligning these incentives is the solution to the problem.

Sustainable open source projects are ones that spawn sustainable businesses. Everything else limps along perpetually underfunded, vulnerable to being killed by something as mundane as boredom, and fades into obscurity - replaced by a project and an organization that has incentives that align it to longevity.

Case Study: OpenSSL and Heartbleed



Before I started Petabridge, one of the case studies that nearly scared me off from going anywhere near the open source software market was the OpenSSL “Heartbleed” saga in early 2014. OpenSSL has the kind of success that few open source projects can dream of, being a critical piece of infrastructure used far and wide across Internet giants, cloud providers, and so forth.

OpenSSL is a project entirely sustained by the volunteer efforts of its contributors and donations, and once the damage of the Heartbleed bug became apparent the tech community started a conversation around having Internet giants invest into the OSS projects they use every day for critical infrastructure in their businesses. Prior to the Heartbleed bug in 2014 the OpenSSL Software Foundation received about $2,000 per year in donations, which doesn’t even buy you a week of a senior programmer’s time in Silicon Valley. After the Heartbleed vulnerability captured the attention of the greater developer community the project managed to raise… An additional $9,000.

In the words of Steve Marquees, the OpenSSL Software Foundation president at the time:


  Thanks to that publicity there has been an outpouring of grassroots support from the OpenSSL user community, roughly two hundred donations this past week[3] along with many messages of support and encouragement. Most were for $5 or 0 and, judging from the E-mail addresses and names, were from all around the world. I haven’t finished entering all of them to get an exact total, but all those donations together come to about US$9,000. Even if those donations continue to arrive at the same rate indefinitely (they won’t), and even though every penny of those funds goes directly to OpenSSL team members, it is nowhere near enough to properly sustain the manpower levels needed to support such a complex and critical software product. While OpenSSL does “belong to the people” it is neither realistic nor appropriate to expect that a few hundred, or even a few thousand, individuals provide all the financial support. The ones who should be contributing real resources are the commercial companies and governments who use OpenSSL extensively and take it for granted.


Your project will not be as popular or as essential to the day-to-day work of large government agencies, Fortune 500 companies, or FAANG businesses as OpenSSL. Your donation model isn’t going to outperform theirs… Tidelift, Pateron, or Github Sponsors be damned.

An important note: OpenSSL is very much alive and doing well. I don’t know if they raise enough money in the aftermath of Heartbleed to employ full-time engineering staff or if they carry on using the same model they had in years past, relying largely on the uncompensated volunteer effort of their contributors. In either case, the project deserves nothing but our respect. I only use them as a cautionary tale to show how something as critical as their project struggles acquire the funds it needs relying on a donation model to employ full-time development resources. The lesson is: you should expect a worse performance for your project.

OSS Burnout: Working for Free on Things That Don’t Matter to You
The volunteer model of OSS is ultimately not sustainable in the long run for most projects because of burnout and no real sense of ownership over the project. There are exceptions to this of course, people who take great pleasure and craftsmanship in contributing towards as project they enjoy as a hobby, but they are not the rule.

Open source burnout occurs for core developers and contributors most often because they feel like they have to work for free on things that don’t matter to them. Again, a misalignment of incentives.

You gave birth to this project, put it out there in the world, people began using it, and in starts the deluge of bug reports, feature requests, questions about your design decisions, and so forth. You feel responsible for the quality of your work, but the excitement and validation you had the first time someone opened an issue on your Github repository has long since passed. You used to feel excited about coming home from your day job and spending a couple of hours every other night working on your OSS idea. Now it makes you feel guilty and disappointed in yourself every time you look at the aging pull requests, issues with no responses, and the months since your last release.

I remember watching this talk from Jacob “Fat” Thornton, one of the creators of Twitter Bootstrap, back in 2013 about the subject of OSS burnout (starting at around 20 minutes in:)



When the novelty of working on your OSS project wears off, burn out can set in. The “cute puppy” phase, as Jacob called it, is over… And now you’re left to the rote task of triaging bugs, debugging racy unit tests, creating documentation… No one is giving you upvotes on Hacker News or retweets on Twitter anymore. You feel like you have to work on the project in order to avoid guilt and that’s far removed from the joyful experience it once was.

I’ve been working on Akka.NET, in some way or another, every day for six years - and I still love doing it because when you build a business around your OSS project your incentives for working on it change radically towards something that looks sustainable.

I still have the feeling of craftsmanship I get when I personally solve a nasty bug, create a new sample, add a new feature, or improve the performance of an existing one, all of the things I used to feel working on Akka.NET before running Petabridge became my job - but because my business revolves around supporting OSS customers full time I do this work feeling like “this is my livelihood” rather than “this is my burden.”

I enjoy it when we solve problems even for non-paying anonymous Internet users because I think to myself “our customers are always watching, and maybe this person might be one some day” and thus we try to the best of our ability to take care of everyone. Everyone on our team wants to earn the business of our customers every day.

When your OSS becomes your work, rather than an unpaid obligation, the change in mindset lays the foundation for being sustainable - when you support the project and the project supports you back.

Donation Math
Let’s suppose you are one person working on an amazing OSS project on the side and it takes off; you make 25,000 per year working as a salaried intermediate level programmer in Los Angeles. You start getting lots of bug reports, installations, and it begins to become a burden. You love your project and think it can become something great that will make a real difference to others if you had more time to work on it. How do you buy your own time?

Programmers are very well compensated compared to other professions, given the low barriers to entry and the high salaries plus benefits. A donation funding model for OSS projects probably isn’t a realistic option for developers - because… Well let’s take a look at some math.

Full replacement cost of your current income… When launching a startup I typically use the following formula to determine the full cost of hiring an employee:

Base Salary x (1 + LOD (scalar)) &#x3D; Full Cost


That LOD value in California &#x3D; 40%, because that includes payroll taxes (~8.5% for employees, ~17% for self-employed), healthcare, retirement, parking, bonuses, vacation, etc… We’ll use that figure here.

Your real cost &#x3D; 75,000.

Now break that down into an hourly rate to transform your “work” into quantifiable units.

40 hours per week * (52 weeks per year) &#x3D; 2080 billable hours per year, assuming no vacation
75,000 &#x2F; 2080 &#x3D; $84.13 per hour.


So let’s suppose you want to use Github Sponsors donations to fund your project because you don’t feel like you have any marketing &#x2F; sales experience and starting a business seems too risky. Donation sizes on projects can range anywhere from &#x2F;person&#x2F;month to as high as $500&#x2F;person&#x2F;month from what I’ve seen. Let’s pick a realistic per-person target - 0&#x2F;person&#x2F;month, about the same price as a subscription streaming service.

Let’s suppose you’re willing to work an extra 10 hours per work, as a side gig, on your project: about 40 hours per month. How many donors do you need to break even on those 40 hours per month compared to your salary?

40 * $84.13 &#x3D; $3,365.38
3,365.38 &#x2F; 10 &#x3D; 337 (rounding up) 0 &#x2F; mo donors.


The size, importance, and visibility of your OSS project would need to be tremendous to bring in that many donors. The amount of effort you’d have to spend on just promoting your project to get that many donors is another full-time job in and of itself. Are you willing to put that much time in for an extra $3,365.38 per month? Probably not. This is why I ultimately think the donor model for OSS sustainability is doomed - the numbers don’t scale.

Are a few hundred bucks worth of monthly donations going to change how you feel about putting in an extra 40 hours a week on your project versus living comfortably off just your salary? Unlikely.

Business Math
Let’s take a look at the same scenario as before, but this time we’re going to go into it with an entrepreneurial mindset. Let’s say you want to make as much money as you do right now, but you really want to have the freedom to work on your project full time.

There are multiple models you can use in OSS to go about doing that:


  Services model - sell training, consulting, and support directly to the users of your software;
  Open core model - build something premium and proprietary around your OSS that is valuable to customers with deep pockets, i.e. access control and auditing are important for enterprise users but not your core OSS audience;
  Licensing model - introduce a copyleft license for the OSS and a dual propreitary ($) license for the companies who want to use the technology in their businesses;
  Managed services model  - build some managed services on top of your OSS that you can sell directly as a PaaS-style product, i.e. if you built a distributed database, offer a managed service for that on the Azure &#x2F; AWS marketplace; and
  Reputation model - rather than trying to sell anything to the users of your OSS, use the prestige and popularity of your OSS contributions to attract better job offers for yourself, attract customers to your business, attract engineering talent to your company, draw attention to your other paid products, etc…


Not all projects can support all models. For instance, if you built a CSS UI framework you can’t really do a managed service model - but you can do a licensing model (Highcharts does this) or a services &#x2F; reptutation model (Zurb does both of these).

In the case of Petabridge we build application frameworks, which means that customer code is built directly on top of ours, therefore a licensing model is totally unfeasible and a managed service model probably is too. So in our case, we sell services and open core - Phobos is our APM suite on top of Akka.NET, for instance.

Here’s how the math works differently - suppose you still want to hit that $3,365.38 per month target. You won’t be working full time on the project at that monthly rate, of course - this is just to draw a distinction between the donation model example and a real business model.

How about offering training for a fee or holding an in-person workshop at a conference? If your library is critical enough to a company that is using it in a core area of their own technology, they’ll pay for training and they may also pay for support. Offering online trainings, workshops, remote consulting, or support are all models that make earning $3,365 is much more doable.

On top of that, working on the project now becomes an investment in growing your business - the more work you do to fix bugs and address user issues, the better your reputation becomes with better customers and your addressable market may also expand as the project becomes more mature and more useful to a larger and larger audience. The incentives between the project and its developers are now aligned.

Which Projects Can Actually be Businesses?
The scaling laws around OSS projects will vary, significantly, depending on what the project does. I doubt you can build a sustainable business around something like a serializer - that’d need to be a project that is OSS by virtue of a big tech giant like Google or Microsoft. The problem with a serializer is that, while important, it’s in a space that has lots of great free solutions and it doesn’t really touch many different parts of the business. In other words, it’s a narrow-use case tool competing with lots of free alternatives (like JSON serialization.)

For an OSS technology to be capable of supporting a business, I think it needs to do the following things:


  Be technically complex &#x2F; expensive enough that your customers couldn’t build it themselves;
  Must touch multiple parts of a customer’s business - i.e. a UI framework, queueing system, web framework, databases, etc;
  Must be a radical improvement or departure from current options - can’t be an incremental improvement that another dominant project could just steal; and
  Must offer understandable business value to end-users.


At the risk of catching giant amounts of grief from the Internet, where functional programming technologies and projects often struggle is item number 4. The benefits can be explained to another highly technical person, but often not to someone with purchasing power.

Our serializer example fails test number 2 or 3.

So those OSS examples that fail these tests can’t really be the foundation of a self-sustaining business in and of themselves - that’s why the business models you typically see supporting more marginal type technologies (things that are useful, but not useful enough to buy) are almost always reputation models. Google doesn’t earn any money from supporting Protocol Buffers, but they get a lot of recognition and access to developers doing cool stuff via their OSS engagement. In their case that OSS project is an indirect part of their business, versus something like Kubernetes (another Google OSS project) which is now a major part of every cloud ecosystem on the planet, which is very much a direct part of their business.

Wrapping Up
Petabridge has been five years of really hard work, long hours, emotional roller-coasters, and, especially during the first couple of years of the business, asking myself “am I dumb for doing this?”

But it’s also been five years of adventure, traveling around the world to work with customers, feeling like the work my team and I do makes a meaningful difference to others, interesting technical work, building great relationships with colleagues all around the world, and the satisfaction of creating a sustainable business.

It’s an exciting time to be involved in an open source business because it’s actually becoming easier to sell to larger companies as OSS buy-in is now the rule, not the exception. That battle is already over and open source won. There’s lots of opportunities to disrupt existing projects or create ones in categories that didn’t exist five or ten years ago. But go into the open source world with your eyes open - it can be fun and exciting at first, but ultimately open source is a business.*
#### [How to Configure Visual Studio to Use SourceLink to Step into NuGet Package Source](http:&#x2F;&#x2F;www.aaronstannard.com&#x2F;visual-studio-sourcelink-setup&#x2F;) 
*I love SourceLink - it’s fast becoming a standard practice to include SourceLink support in all open source NuGet packages in order to make them easier to debug. We’ve included SourceLink support in Akka.NET and some of our other projects for some time now.

However, I’m embarassed to admit that I’ve never been able to remember how to get this to work properly each time I switch machines or projects. So, I decided to document how to do it.

Step 0 - Verify That Your Third Party NuGet Packages Actually Support SourceLink
Before you go through the trouble of configuring Visual Studio to support SourceLink you’ll want to make sure that the third party package you’re trying to debug actually supports it.

The official Microsoft documentation on SourceLink has some guidance for how to do this, but odds are high that popular NuGet packages (i.e. ASP.NET, Newtonsoft.Json, Automapper, etc) already support it.

Step 1 - Configure Visual Studio to Support NuGet.org Symbol Sources
For reference, I’m using Visual Studio 2019 with .NET Core 3.0 for most of my day to day work. By default NuGet.org symbol sources aren’t enabled. In order for SourceLink to work properly Visual Studio needs to be able to download these sources, so we have to set this up first.

In Visual Studio, go to Tools –&gt; Options –&gt; Debugging –&gt; Symbols:



Make sure the ‘NuGet.org Symbol Server’ option is checked.

Step 2 - Disable “Just My Code” in Visual Studio
Next, we need to go to the Tools –&gt; Options –&gt; Debugging –&gt; General settings window and disable the “Just My Code” option:



Step 3 - Enable Source Server and Source Link Support in Visual Studio
By default SourceLink support is already enabled in Visual Studio, but source server support is not.

Again, go to the Tools –&gt; Options –&gt; Debugging –&gt; General settings window and make the following changes:




  N.B. If you use Github for Windows &#x2F; Github for Mac, which both use the Git Credential Manager under the covers, checking the “Fallback to Git Credential Manager” will also allow you to use SourceLink for private repositories. However, since it’s unlikely that source code from a private repository is going to make it onto a public NuGet server or symbol server, so you will need another way to distribute the .PDB symbol files SourceLink requires. See “Alternative PDB Distribution” from the SourceLink documentation for some ideas on how to do this.


That should do it. Now we can take it for a spin.

Step 4 - Step into Third Party Code
So I have the following small program:

using System;
using FluentAssertions;
using Hocon;
using Newtonsoft.Json;

namespace SerializationDebug
{
    class Program
    {
        static void Main(string[] args)
        {
            var hocon1 &#x3D; @&quot;
                    foo{
                      bar.biz &#x3D; 12
                      baz &#x3D; &quot;&quot;quoted&quot;&quot;
                    }&quot;;

            ShouldSerializeHocon(hocon1, string.Empty, string.Empty);
        }

        public static void ShouldSerializeHocon(string hocon, string fallback1, string fallback2)
        {
            var hocon1 &#x3D; ConfigurationFactory.ParseString(hocon);
            var fb1 &#x3D; string.IsNullOrEmpty(fallback1) ? Config.Empty : ConfigurationFactory.ParseString(fallback1);
            var fb2 &#x3D; string.IsNullOrEmpty(fallback1) ? Config.Empty : ConfigurationFactory.ParseString(fallback2);

            var final &#x3D; hocon1.WithFallback(fb1).WithFallback(fb2);

            VerifySerialization(final);
        }

        public static void VerifySerialization(Config config)
        {
        	&#x2F;&#x2F; set breakpoint here
            var serialized &#x3D; JsonConvert.SerializeObject(config);
            var deserialized &#x3D; (Config)JsonConvert.DeserializeObject(serialized);
            config.DumpConfig().Should().Be(deserialized.DumpConfig());
        }
    }
}


I’m going to set a breakpoint at the line where we call Newtonsoft.Json.JsonConvert.SerializeObject, since in this case I’m trying to debug an issue with circular references in my code. When the debugger hits that line, make sure you press F11 or use the Step Into functionality to download the Newtonsoft.Json source code via SourceLink and step through it.



You’ll be prompted to download the source from Github and after you click “Accept” you’ll be able to view the source code for that specific version of your package.

And that should about do it. Good hunting!

Appendix: What if we don’t use Github for our private packages?
SourceLink has support for multiple code repository providers, including:


  Azure Repos &#x2F; DevOps;
  GitLab;
  BitBucket; and
  Github, of course.


Thus, if you’re using a non-Github platform for developing a NuGet package you’ll want to make sure you reference the correct platform-specific flavor of the Microsoft.SourceLink package. You can read more about that here.*
#### [The Next Decade of .NET Open Source](http:&#x2F;&#x2F;www.aaronstannard.com&#x2F;next-decade-dotnet&#x2F;) 
*Over the past week there’s been a ton of chatter about the state of the .NET ecosystem and, more specifically, as to whether or not its OSS ecosystem is healthy and sustainable over the long term.

I won’t bother with the details, but the substantive criticisms amount to:


  If you build a popular OSS technology in .NET Microsoft will simply cannibalize it and roll it into a 1st party feature (i.e. Entity Framework cannibalizing NHibernate, built-in DI in ASP.NET Core, etc;)
  .NET users are still overwhelmingly Microsoft-centric - i.e. if Microsoft told its users to store all of their passwords in plain text at least 30% of them would blindly do it because Microsoft said so without considering any second opinions;
  The .NET ecosystem doesn’t built anything “cool” - there’s no innovation here and thus no real way to attract fresh ideas and younger talent to the ecosystem; and
  There’s no way to build an OSS business in .NET.


.NET Ecosystem is Trending Upward
On this blog I’ve loudly voiced my concerns about this viability of .NET as an ecosystem over the years - and here’s how that position has evolved over time (take note of the dates and titles):


  
    
      Date
      Blog Post
    
  
  
    
      July 3, 2014
      “The Profound Weakness of the .NET OSS Ecosystem”
    
    
      May 26, 2016
      ”.NET Core is Boiling the Ocean”
    
    
      May 13, 2017
      ”.NET Core is Probably Fine”
    
    
      June 1, 2017
      “The Coming .NET Renaissance”
    
  


Notice the trend from negative to positive.

That’s because the .NET ecosystem has changed in the following ways, many of which were unthinkable in 2014:


  .NET and C# are now the lingua franca video game development technologies thanks to the efforts of Unity3D;
  Visual Studio, SQL Server, and many other proprietary Microsoft technologies are now cross-platform rather than Windows-only;
  .NET is now truly a cross-platform development environment as a result of .NET Core;
  Microsoft now releases updates to its core runtime and platform technologies (.NET Core, ASP.NET, etc) at regular, frequent intervals rather than its historical 2-3 year release cycles;
  .NET Core is now capable of performing as an infrastructure development framework, rather than just an application development framework, thanks to the renewed focus on performance (i.e. see “ASP.NET Core: Saturating 10GbE at 7+ million request&#x2F;s” from a year ago);
  The rate of innovation with C# itself has increased - from roughly one release every 3 years to 5 releases in the past two years;
  And most importantly, .NET developers consuming third party OSS is now routine, not the extraordinary act of risk-taking &#x2F; deviating from blessed Microsoft heresy that it once was.


If you want to take these improvements in the .NET ecosystem for granted and fart out snarky screeds on Twitter, good for you, I guess.

Room for Improvement
There’s still a lot of room for improvement in the .NET ecosystem, to be sure.

Here, as I see it, are major outstanding issues facing our community in order of importance:

End-User Adoption is Still “Redmond by Default”
.NET users need to culturally normalize the idea of adopting non-Microsoft .NET solutions when those third party technologies are better on the merits.

Some examples:


  If Autofac is genuinely the better tool for your business’ case than ASP.NET Core’s built-in DI, the right behavior is to support Autofac, not lobby Microsoft to incorporate those features directly into their first party DI.
  If SAFE stack offers better developer productivity than ASP.NET Core’s MVC experience does for your business, make a compelling defense of that choice of technology to your peers.
  If Akka.NET offers better performance and flexibility than Microsoft Orleans and that’s what your business needs, make the case.


The status quo is still very much “you can’t get fired if you pick Microsoft” and this results in a dearth of idea and supplier diversity in the ecosystem. It’s one of the reasons why .NET was an intellectual ghetto back in 2014 - and it will turn into one again if end-users don’t change their attitudes.

Notice I’ve been clear about picking third party alternatives when they are better for your use case than Microsoft’s. That’s the only way this can work - non-Microsoft OSS publishers have to win on the merits of their output and appeal to the self-interest of the users.

This also means that .NET OSS publishers have to follow professional product and project management standards - you don’t get to release breaking changes every month and dismiss subsequent user complaints with “well, I use SemVer so you should have known!” The idea behind the .NET Foundation Maturity Ladder (well intentioned but flawed) proposal was to show non-Microsoft OSS projects what the best practices are to help encourage and foster wide adoption.

Third party .NET projects would be wise to start following suit because ultimately this end-user cultural problem is really about risk management, not technology choice. Companies stick to Microsoft technologies not because they’re good but because they’re safe:


  Microsoft isn’t going to go away;
  They back all of their projects with a long-term commitment (although this is the area where they are weakest in recent history;)
  Their technology will be well documented with wide vendor &#x2F; ecosystem support;
  They’re not going to do stupid &#x2F; crazy shit;
  and the technology is going to work well enough.


If you want to see third party technology stand on its own two legs in the .NET ecosystem, that is the quality standard you have to meet - and if your project competes with Microsoft that’s the quality standard you have to surpass. Throwing a project up on Github with a default README ain’t gonna cut it - better start booking up on DocFx and API Approvals.

Pervasive “Not Invented Here” Culture at Microsoft
Microsoft contributes to ecosystem issues through their own product development and evangelism activities, but they’ve tried to speak to those issues through initiatives like the aforementioned .NET Foundation Maturity Ladder.

I say this as an ex-Microsoft employee, a long time Microsoft fan, and a heavy participant in the .NET OSS ecosystem: Microsoft’s product culture mandates they control everything down the stack. They’re the most risk averse company of all in the entire ecosystem, when it comes to considering third party technologies, and they will only deviate from that strategy when they realize they’re playing from behind.

Microsoft’s “Not Invented Here” culture is so strong that other product groups within Microsoft may not adopt technologies produced by a different internal group.

And thus, we’re left with an original pre-Satya criticism of Microsoft that has only become worse as a result their rapid release, OSS approach to .NET: anything that becomes popular in the .NET ecosystem will, eventually, be offered as a first party option by Microsoft if it addresses a big enough audience.

I came up with a list of specific examples, but opted to leave them off of this post as it will inevitably lead to pigeon holing and finger pointing.

So instead I will demonstrate the problem with a theoretical question instead:


  If I developed and OSSed under a commercially-friendly license a faster, low-level networking platform than ASP.NET’s Project Bedrock, let’s call it “Project X” with a 10 year commercial commitment from my company to support it, what’s most likely to happen? Pick one.

  
    Project X’s architecture and changes over time would be “introduced” into Project Bedrock eventually;
    ASP.NET Core would take a dependency on Project X like any other user; or
    ASP.NET Core would take a dependency on Project X if and only if they could become a co-contributor to the repository,
  


If you picked any option other than 1, congratulations - I would love to visit your reality sometime. I expect anyone, including people who actively work at Microsoft, to pick that option overwhelmingly. Why? Because it gives Microsoft what it ultimately wants: total control and freedom over the release cycle of their products. Having to wait for a third party like Project X to push an update so they can, in turn update their projects like any other normal user, probably isn’t be something they can accept no matter how high the quality.

And thus we have the NIH cycle, born from a very good intention to deliver really high quality tools to their users, but inevitably resulting in the unintentional destruction of ecosystem diversity along the way.

There are only two ways this will change:


  Microsoft decides that maintaining a healthy third party OSS ecosystem is in its own best interests and decides to change its practices to support that - but in order for it to do that, there needs to be some cultural changes in the way .NET OSS is developed outside of Redmond.
  Or users can address the first item on this list and push for those third party solutions to be supported over Microsoft’s own because the third party ones are, in some way, objectively better for significant cohorts of users.


Lack of Inspiring, Well-Maintained Third Party OSS
Of all of the criticisms leveled at the .NET ecosystem, this is the weakest argument - because .NET Core is a new phenomenon and it will take ~5-6 years for its effects to seep into the output of the greater OSS ecosystem.

.NET Core is now capable of delivering infrastructure-grade OSS projects, which are the type of notable projects that inspire a lot of confidence in the ecosystem’s health as a whole. Think of Apache Foundation or Cloud Native Computing Foundation-level projects. But these projects are born out of necessity, not someone’s hobby. They take time to develop and there has to be a compelling reason to develop them in .NET. Until recently with the major performance gains and cross-platform capabilities made possible in .NET Core those reasons were largely lacking. This is now changing.

Right now, you can look at the landscape of .NET OSS and see there are infrastructure projects that are alive and healthy: web frameworks, distributed actor frameworks, socket server libraries, messaging systems, databases, and even cryptocurrencies like Neo. But we pale in comparison to ecosystems like Go, Java, and so on. That will change with time.

Sustainability
Every ecosystem deals with this issue - how to make the OSS ecosystem “sustainable.” If you’ll pardon my brevity here, this is a developer’s way of asking “how can I get paid for the work I do on OSS so I don’t have to donate free hours to it all the time?” without trying to sound like a capitalist.

I’m going to address this in a subsequent post, having done this successfully for five years and counting, so please subscribe.

Update: this post is now live here: “How to Build Sustainable Open Source Software Projects.”

Outlook
But one point that bears repeating from earlier: the way .NET developers manage their OSS projects needs to professionalize in order for the ecosystem to shift towards something more open, creative, and professional.

As I said earlier:


  This also means that .NET OSS publishers have to follow professional product and project management standards - you don’t get to release breaking changes every month and dismiss subsequent user complaints with “well, I use SemVer so you should have known!”


If there’s a category of Twitter theater I can do without, it’s other .NET OSS maintainers bitching about Microsoft or how bad the ecosystem is. You’re the biggest part of the problem.

If third party developers in the ecosystem deliver sustainable, professional-grade OSS over the next few years the cultural issues with the ecosystem will head on a course to resolve themselves.

Microsoft is doing a lot of the work of filling in the gaps in the ecosystem right now because many of the third party technologies aren’t actively maintained or supported by a reliable party. The NIH criticisms are still valid, because they will still do that in cases where there are viable third party technologies, but not for all of them.

I’m very optimistic about the next 10 years of .NET because things are already trending in the right direction and at a much faster pace than they have, historically.

As Scott Hanselman showed off on his blog recently, we are going to have .NET running EVERYWHERE before we know it. This means there will be lots of creative, fun, and profitable opportunities for .NET developers to innovate to grow with the same communities they’ve been working within for years… And maybe we’ll all find some new ones too.

So, if you want to pitch in and help create the type of .NET ecosystem you want to see.. Create a Github account, learn how to use it with professional best practices, and find a way to make existing tools better for you or create some new ones.*
#### [Problems and Solutions with the .NET Foundation Maturity Ladder](http:&#x2F;&#x2F;www.aaronstannard.com&#x2F;dotnet-foundation-maturity-ladder&#x2F;) 
*This is largely the text of an issue I posted related to the .NET Foundation’s new proposed Maturity Ladder for .NET OSS projects. I am fully supportive of the .NET Foundation’s stated mission and wrote this in the hopes of trying to help it achieve that through a little tough love.

After reading (.NET Foundation Directory) Jon Galloway’s reply here I want to raise a fundamental problem that exists with the .NET Foundation in its current form that makes some portions of the ladder proposal distasteful, in my eyes as both the proprietor of an independent .NET OSS business, a project contributor, and as someone who deeply cares about the success of the .NET OSS ecosystem as a whole (it’s why I started Petabridge.)

Microsoft and the .NET Foundation are effectively joined at the hip. Its day to day operations and run by largely by Microsoft employees and its interests are fully aligned with Microsoft’s. While the goals and intentions of the .NET Foundation are precisely intended to help foster a healthy third party ecosystem around .NET (Microsoft wants this too,) the fact remains that it’s largely Microsoft’s show and is viewed by users and .NET Foundation members as such. Let’s acknowledge this perception as fact and move onto why it’s an issue.

Microsoft’s Influence on the Behavior of .NET Users
Microsoft has singular influence on the behavior and perception of the .NET community, being the creator of the platform; the developer of the most popular technologies and frameworks on it; and through tremendously high levels of effort: a solid track record of high quality work.

This singular influence comes with what is now a widely acknowledged problem that Jon and the .NET Foundation board are attempting to address through the maturity ladder, per his comments I linked earlier:


  We had some board members campaign and win a board seat with statements like “I’d like the .NET ecosystem to thrive with projects people consider and take dependencies on to be much wider than the narrow “Microsoft-blessed” scope that people and companies generally consider.” At our first board meeting, I asked the board to come up with some specific areas and action groups, and this was one of the seven that made the list. I had other things I’d expected to see on the list, but this wasn’t one of them.


I applaud this and I am certain the lion’s share of the .NET Foundation membership does too. Creating more “package publisher” diversity in the .NET ecosystem through normalizing the adoption of non-Microsoft technologies is essential to accelerating the rate of innovation in .NET as a whole, because Microsoft can only invent and maintain so much.

However, where this proposal goes sideways is it’s a roadmap for how to become a Microsoft-blessed project, with the .NET Foundation (Microsoft) acting as the certification authority. This is the opposite of the stated goal - it keeps Microsoft in the position of central influence over the .NET ecosystem, especially if the .NET Foundation’s maturity ladder gets coupled with pure Microsoft channels like NuGet’s user interface . There really would be no effective distinction between the two organizations.

Ultimately what I believe both I and the .NET Foundation leadership, members, and projects want is an rapidly growing ecosystem with projects that adopt good practices, are well-maintained, and regularly updated. That approach, necessarily, must be decentralized in order for rapid growth and innovation to occur.

The current maturity ladder is a centralized, top-down, and heavy-handed approach - because it defines fairly strict quality control rules that are a reflection of how Microsoft’s own organizations operate. And if it’s implemented in its current form, I’m afraid it will create monoculture among how .NET OSS projects are operated (i.e. they all have to be in the .NET Foundation to be a high quality project, must all use a permissive license, etc) and may further stifle the ability of new projects that don’t have a long track record to get off the ground.

Just to drive the point home about monoculture, a specific example from Tier 3 of the project maturity ladder:


  
    Practices
      
        Complies with .NET Foundation continuation policies.
        Stable packages depend on libraries that are at level #2 or higher.
        Signs packages (Note: this refers to digitally signing NuGet packages, not strong naming).
        Uses static analysis tools to validate pedigree and safety.
        Applies .NET API design guidelines.
        Seeks and applies guidance from .NET Foundation design and architecture group.
        Updates package references regularly to accommodate servicing updates in dependencies.
      
    
  


This requirement effectively eliminates an entire OSS business model: offering certified builds to enterprise users. Most small users (i.e. customers that won’t pay for OSS) are fine with the “buyer beware” culture of OSS. Big companies, who have much larger exposure, are willing to pay a company that contributes to &#x2F; maintains the project for certified builds that are signed and more heavily scrutinized - that’s not going to be the case any longer if an OSS project needs to be tier 3 or higher for BigCo to adopt it, as much of that value is now expected for free under this model.

Running a sustainable OSS project (i.e. capable of funding itself, has natural business incentives to provide high quality work to users) is hard enough and I don’t believe the .NET Foundation ever intended to be in the business of telling those projects how they can and can’t make money, but that’s what introducing an explicit grading system and pushing that down to users will accomplish.

Additionally, I don’t believe the .NET Foundation is properly resourced to even execute such an effort in its current form. It’s a lot of work for a small team and will get worse the more projects being needing infrastructure - there’s a whole issue opened to address this already, so I won’t rehash it further.

Solution: Bottom-up Approach to Maturity
The .NET Foundation has its heart in the right place - widening the range of “acceptable” OSS beyond what is produced in Redmond. I want that too. Everyone does, most of all the developers who aren’t able to use that OSS today because of the historical conservatism of the .NET ecosystem as a whole when it comes to OSS.

The current proposal puts the .NET Foundation as a centralized certification authority for the entire .NET ecosystem. That’s heavy-handed and will ultimately undermine the .NET ecosystem’s ability to become “bigger than Microsoft.”

What I propose instead is a bottom-up approach:


  Never use the maturity ladder as a public grading system of any kind. No lists of “tier 4” or “tier 3” projects. And certainly don’t integrate that language into NuGet.
  If NuGet and other Microsoft interfaces into third party packages  (i.e. Github) want to offer some kind of hint as to how well a project is run, I recommend using something similar to Github Pulse - show that the project has commits from multiple users, automated CI checks, new releases, responses to issues, responds to recent security incidents, etc. The reason why this is fine is because all of that activity is 100% under the control of the project developers themselves - no one had to seek out permission from the .NET Foundation to be rated as a “good” project. This decouples the .NET Foundation from being the arbiter of what is good and what is not. Instead, the project leads themselves decide if they want to put the time and effort into doing those things and act accordingly.
  Projects do not need to be part of the .NET Foundation to achieve everything in point 2; projects like NServiceBus, ServiceStack, RavenDb, EventStore, and so on are trustworthy because those developers can’t pay the bills if they don’t act accordingly. That should be good enough.
  Use the maturity model as a roadmap for guiding projects towards best practices, not a process to be strictly followed. If one project doesn’t want to sign its builds because its maintainers want to offer that as a paid service, let them and their users (consumers and contributors both) decide if that’s ok.
  Leave the forking policies et al in place for .NET Foundation projects, but leave that at a .NET Foundation member project consideration - not something that applies to “any trustworthy .NET OSS” project.


If a project dies or gets abandoned, the objective numbers in point 2 will decline and maybe that project will be forked by users who still have skin in the game. Let it happen - that’s allowing the ecosystem to run itself.

I believe in the .NET Foundation’s mission and that’s why we joined it and I very much want it to succeed. That’s why I felt the need to criticize it and say what might be a painful truth: that it’s still Microsoft’s show and this proposal only makes it further so.  It’s in the best interests of the entire .NET ecosystem, Microsoft and the .NET Foundation included, to make .NET bigger than Microsoft. I hope you will consider my recommendation in the spirit of trying to help us all make that happen.


  See the full issue on Github here.*
#### [It&#39;s Just Not a Big Deal](http:&#x2F;&#x2F;www.aaronstannard.com&#x2F;not-a-big-deal&#x2F;) 
*In my professional life, I’ve actively conditioned myself to tolerate and accept risks when necessary. Risk tolerance is something that can be learned and taught. But risk tolerance is fundamentally a contextual matter - two people with identical means and skills can have totally different reactions to the stressors risk presents.

There are people who will go skydiving but won’t ever, ever leave their stable corporate job that they hate because the alternatives terrify them. There are people like me who won’t jump out of a perfectly good plane, even at gunpoint, but feel totally comfortable entering work situations even with uncertain economic outcomes.

I’m generally confident and assertive, but my biggest regrets in life have come from situations where I failed to be either. In these moments I make a common mistake: when I weigh my choices, I invent additional possible negative outcomes that don’t actually exist.

Small, Safe Worlds
I have my insecurities. Most of them are artifacts of routine childhood slights, like being picked last for the pickup soccer games in fourth grade; I relive them every day as adult anxieties. You’d think after 30-something years I’d be seasoned enough to not be affected by these things. You’d be wrong.

When life presents us with possibilities and choices we view them through the lenses formed through our experiences over time. They shape the landscape in which we decide.

Ultimately these lenses distort reality into a funhouse mirror, tainting our judgment with shades of the past.

With negative experiences, we decline and avoid opportunities for connection, growth, and prosperity because we wish to avoid pain.

We preemptively discount ourselves because we’re afraid we’re not worth our asking price and that we’ll be exposed if we do.

We don’t ask for the promotion we earned. We don’t assert ourselves in situations where our boundaries are crossed. We don’t ask the single neighbor out for coffee. We don’t start that company. We don’t travel to exotic, unfamiliar places. We turn down invitations to make or grow relationships. We engage in safe, people-pleasing, small-ball behavior. We limit ourselves to a smaller, safer world filled with fewer possibilities and people. We retreat to our comfort zone.

Access to Possibility
Like our friend who makes the same mistakes because he or she can’t spot the warning signs, so too can we see that the friend who avoids opportunity does so for reasons that are absurd, childish, and mundane. Our own reasons for doing the same are equally weak, but they hide in our blind spots. Thus we carry on, carelessly closing off opportunity for a different, better, and richer world for ourselves every day.

And why? Because Mrs. Rutherford publicly humiliated us in front of our second grade class for having really shitty cursive handwriting. From that day onward we’ve spent our entire lives avoiding being the center of attention. We wonder why none of our ideas get picked up at work, why we don’t have the friends and relationships we want, and confine ourselves to gilded cages of our own making - all because of an overwrought childhood experience exercising its influence unchecked.

I worry about being liked and respected. Being an awkward, chubby, and nerdy kid made me an easy target for bullying. For a significant part of my childhood, I simply tried to avoid contact with people as best as I could and pursued my hobbies instead. I kept my circle of friends small. I avoided dating until I had women in college dropping atomic bomb-sized hints that they were interested in me. Asking customers for the order terrified me because I was worried my labor and products weren’t worth their true value. My primary social goal was to simply avoid embarrassment.

Change waited for me just around the corner.

During college I realized: I’m in control of what embarrasses me and what doesn’t. Embarrassment was my choice. Being lonely, unhappy, unsatisfied, slighted, and the entire spectrum of socially anxious behavior were outcomes I unconsciously chose all along.

So I made a promise: to reinvent myself as someone who doesn’t get stopped. Choice is my instrument. I made different ones. I’m twelve years in.

If you meet me in-person today, you won’t recognize the man I just described. I’m extroverted; I work the room; I speak in front of hundreds and thousands of people regularly; I assert my boundaries; and I ask for what I want, especially when it’s a big ask. I act with a degree of self-worth that was unavailable to me when I was nineteen years old.

I still get knots in my stomach when I don’t know anybody at a party and I have to mingle with strangers. I’m reluctant to reach out and form new friendships because I worry about looking like an incompetent manchild. I tense up when I’m about to send an email asking for a large order. There are lots of moments, every day and every week, when I fail to act with conviction; when I don’t ask for what I want; or when I fail to assert myself and my boundaries vigorously. I leave a breadcrumb trail of tiny, everyday regrets in my wake. But the upside is: I didn’t even have a wake before.

Like anything else worth doing, broadening our world and learning to say “yes” to the call of opportunity takes practice, repetition, and a generous helping of patience.

How to Get There
We view the “risk” in any given situation through the lenses of our past experience. In the realm of the interpersonal, I thumbed the “risky” side of the scale heavily because my lenses magnified the specter of embarrassment many times over. My imaginary threat often outweighed the real positive potential outcomes. I justified each act of self-disappointment with post-hoc rationalizations.

We all do this.

It’s when we realize that the threats aren’t real that we can make different, better choices. When we’re aware of how our past distorts our view of the present, we open ourselves up to possibility and opportunity.

The hard part is reconciling how we feel with what we should do. Our feelings are real sensations, but they aren’t reality itself. Our negative feelings are the machinery of the mind trying to protect us from aggravating the injuries of the past.

Every day I practice moving past how I feel and instead, learn to act in my own best interests. Do it often enough and it becomes automatic, unconscious, default behavior. Here’s how I do it:

“It’s just not a big deal.”

When I’m afraid to ask for what I want or to say “no” to a request I don’t want to entertain, this is what I remind myself.

If you conduct yourself with integrity there are very, very few situations where asking for anything or saying “no” will lessen other peoples’ opinions of you.

If someone asks you for $20 on the street you’d say “no” without thinking twice about it; so why feel differently when a friend asks you to help them out with a bill? It’s because you’re invested in the friendship and you worry, irrationally, that saying “no” will damage it. The truth is if your friendship is worth keeping then saying “no” has no impact.

Similarly, we don’t think less of the friend for asking in the first place. They needed help and turned to you.

It’s not a big deal they asked and not a big deal that you declined. Repeating this exercise allows us to stop seeing normal, everyday interactions as significant life or death decisions. It reduces the intensity of going about our daily lives. It deepens your power to choose your own boundaries, priorities, and preferences.

“You’ll be glad you did it.”

A phrase from my grandmother that has served me well over the years. When I’m afraid of putting myself in a situation where I feel vulnerable, I tell myself this and I move in that direction anyway.

Asking for an order, asking for a phone number, inviting people over for dinner, discussing an overdue raise with the boss, and millions of other situations that seemed risky in the past become opportunities instead.

When you ask for something you want, the worst that can happen is you’ll be told “no.” You’ll be in the same situation you’re in right now, but with certainty and satisfaction in knowing that you didn’t leave opportunity on the table.

The real power in doing this is the unlimited upside. While most people tremble at the thought of asking their boss for a raise, worried that the act of asking itself might result in a loss of face or favor, you can be the person who actually gets it. Maybe that customer will accept your face value price after all. Maybe that attractive co-worker really is interested in going out with you.

When you act despite your self-doubt and advance your best interests, you value yourself. You grow your access to opportunity. And you’ll be glad you did it either way. Each time you repeat this exercise you take a step closer towards being the person who takes shots on the goal.

Given enough practice, you can become the person who makes them.*
#### [The High Price of Comfort](http:&#x2F;&#x2F;www.aaronstannard.com&#x2F;high-effort-living&#x2F;) 
*Chief among the values prized by fellow millennials is comfort. It’s reflected in our more casual dress and our increasing preference for impersonal forms of communication, such as text or Slack. Our desire to form self-reinforcing informational and social bubbles, where we can limit our exposure to different and potentially disagreeable ideas, is fundamentally driven by a desire to avoid discomfort.

Our comfort fetish began with the “self esteem” movement in the early 1990s, when we were elementary aged-children. It culminated into the (rightfully) maligned “participation trophy” culture. And the trend simply continued on under its own momentum from there, leading to the rise of Safetyism and other developmentally self-destructive movements. The pursuit of comfort above all else puts us in a position where we simply sit through and endure the bad hands dealt to us by circumstance.

As I touched on in my previous post, millennials are extraordinarily risk averse compared to previous generations. Let’s be clear: risk aversion is simply staying in one’s comfort zone. Comfort-seeking is also an aversion to taking responsibility. It places our locus of control outside of ourselves, leading us to believe that we are victims of Baby Boomer’s greed or any other preferred boogey man. It leads us to believe that we are disempowered victims and that the best we can do in life is to merely survive it as comfortably as possible.

The comfort trap is killing us and it is ultimately responsible for our generation’s collective achievement gap. It’s why millennials squeal about work-life balance, fantasize about four day workweeks, and take The Four Hour Work Week literally.

Comfort: the Anti-Achievement
We want:


  To be proficient in our field and hobbies;
  To be respected and recognized by our peers;
  To love and be loved;
  To look and feel good;
  To share our passions and experiences with others;
  To express our creativity and ideas in a manner that pleases us;
  To realize meaningful goals; and
  To know ourselves.


We may differ person-by-person in terms of priorities, mediums, and magnitudes when it comes to these things. But these are fundamental desires that compel us to get out of bed and out into the world each morning.

Comfort is nowhere to be found on this list.

Let’s suppose for a moment that I’m about to graduate college and the pursuit of comfort is my foremost goal. What would my life look like?


  I’d work just hard enough to live in a place that’s comfortable - not great, but not horrible either;
  Eat what made me feel comfortable;
  Wear what made me feel comfortable;
  Socialize where and when I’m comfortable; and
  Stick to activities that let me feel comfortable, like watching Netflix, playing video games, drinking beer, and so on.


I’m describing a “minimum effort” person - someone who puts in just enough effort into day-to-day living to stay within his or her comfort zone. No one wants to be friends with a minimum effort person because they are transactional, weak, disempowered takers.

Most people aren’t “minimum effort” people, but they are “low effort” people. They’ll put slightly-more-than-minimum effort into selective areas because they prioritize some needs ahead of others. But you’re not going to see these people running marathons or winning industry awards any time soon. At work, they’re often the type won’t invest in their co-workers or employers, treating them as merely a means to end… And yet, they’ll still have the audacity to whine and complain about mistreatment at the hands of their employers. They rationalize and defend their lack of achievement as though it’s driven by external circumstances, not internal choices and the overarching desire for comfort. If minimum effort people take, low effort people settle.

The common through-line between minimum and low effort people is that life is something that merely happens to them; not an active experience they lead and direct.

Comfort is the antithesis of purpose and achievement. Successful people with “comfortable” lives only have them because of the risks they took, the struggle they endured, and the achievements they accomplished.

The solution to our problems is recognizing that comfort is an outcome of hard work, not an alternative to it. Therefore, we should change our mindset about what we value and do every day to realign ourselves as “high effort” people.

The High Effort Lifestyle
When you pursue happiness as an end goal, you fail. Happiness is only realized through fulfillment, which comes from engaging in meaningful pursuits like family, faith, career, creativity, community, and so forth.

Comfort works similarly. High effort people prioritize achievement, recognizing that comfort is its byproduct. They take responsibility for their station in life and circumstances regardless of external forces. “It’s not the 2008 Recession’s fault that I don’t own a home; it’s something I can change if I want to.”

The defining trait of a high effort person is they have an internal locus of control. They’re in charge of their own lives. They can affect the outcome. They are not victims.

In each of the areas of human need I highlighted earlier, high effort people don’t settle for the bare minimum.

They don’t want to get by feeling good enough; they want to feel great - because if it’s worth doing something then it’s worth doing well. So join a running team, work with a personal trainer, or take up a hobby like rock-climbing. And here’s the amazing part: although it’s initially uncomfortable to start running at first, the more effort you put into it, the better you get at it. In other words, by struggling through the initial discomfort you come out on the other side better for it and more comfortable.

When you’re uncomfortable, you’re growing. You’re expanding your boundaries and your limitations. You won’t always feel good when you’re doing it, but that’s the point: by being able to tolerate things that were once uncomfortable or “risky,” you grow into the sort of person who can take on even more ambitious things that might have been intimidating or scary once before. When we adopt that mindset that putting a high level of effort into our lives is its own reward, we exercise a high degree of self-ownership and power. People who do this consistently will become better leaders, they’ll get promoted, they’ll feel good, look good, do good work, and most importantly they’ll connect with other high effort people and can build amazing teams, families, and friendships.

So rather than complain about how your workplace sucks, start looking at things you can do to improve it on your own. Even something as trivial as picking up a piece of trash when you see it in the hallway is a good start. Changing your mindset through your behaviors and attitudes doesn’t happen over night. It requires re-committing yourself to the goal of your individual excellence and achievement every day. And the irony is: when you become a high effort person the comfort you were looking for originally will be right there waiting for you and you may not even notice.*
#### [What We Leave Behind](http:&#x2F;&#x2F;www.aaronstannard.com&#x2F;what-we-leave-behind&#x2F;) 
*It was roughly a year ago this week that I fled California in pursuit of greener economic pastures. I came to Texas an economic refugee; despite running a successful business in California for a number of years I watched my profit steadily fall beneath the relentless tide of cost of living inflation, taxes, and so on.

It’s a move I’d been wanting to make for years but timing and circumstance stayed my hand until April 2017. And it was a difficult choice too - I was leaving behind my family in California, who are a short drive away from where I lived in Los Angeles. And I really loved LA itself - it’s a great city where you could do something different every day and not see a tenth of it by the time you die.

I made the choice to leave, happily, because it’s backed by intention: I’m not going to be forced to choose between being able to financially support a family and growing my business aggressively. In California, this is a binary choice for the vast majority of people. Full stop. In Texas, it’s not - I can comfortably do both. And I will do both.

What’s surprised me during the months leading up to my choice and the year or so thereafter is the reaction I get from fellow millennials about the decision to leave. They’d understand if I was forced to move by an employer or some other circumstance, but voluntarily choosing to leave God’s chosen land in glorious California?!?! What about being far away from my family?! What about not being in the tech scene in Santa Monica or the Bay Area?! What about the great Mexican food I’m leaving behind?!?

First, let me state the following unequivocally: Mexican food in Los Angeles and San Francisco is dogshit garbage and anyone who disagrees with that should unsubscribe. San Diego does it better than anyone else in California, period. Second: Tex-Mex is vastly under-appreciated and better than most of what you can get in CA.

Now with that out of the way, let’s address the prevailing millennial mindset when it comes to life, risk, and reward.

Risk Aversion
There have been scores of articles written about the all-around worthlessness of my generation, a time-honored rite-of-passage tradition that every generation has had to endure.

The largest and most accurate criticism is that we’re fundamentally risk-averse. And you can see it in several areas of life:

Finance


  “Millennials aren’t just risk averse, they are the most risk averse generation since The Great Depression.” - Investopedia
  “More than half of people between the age of 21 and 36 have their savings parked in cash, according to a new study by the Brookings Institution, reflecting extreme risk-aversion by the so-called millennial generation.”- Wall Street Journal


Socialization


  “Millennials Are Having Less Sex Than Other Gens, But Experts Say It’s (Probably) Fine” - Forbes
  “This Is Why Millennials Find Making Phone Calls So Terrifying” - Elite Daily


Work


  “Millennials Are to Blame for America’s Vacation Problem” - Travel and Leisure
  “Millennials Are Actually Workaholics, According to Research” - Harvard Business Review


Let me lay this just so I can call out any angry Internet commenters on not reading the article later: I think most of the concerns about the millennial generation are overblown. Also, worth remembering that these trends are for populations, not individuals.

However, I concur with the above articles that the millennial mindset on the whole is vastly different when it comes to risk-taking and adventurousness than previous generations.

We’re afraid to pick up the phone and call a person we’re dating, let alone pack up our belongings and move to a new city sight unseen or demand a raise from the boss. Why?

Having graduated from college in 2008 it’s easy to understand why we’d be more cautious: our economic opportunities blew up right in front of us and in many cases delayed our ability to enter the workforce, buy homes, get credit, and start our adult lives.

That’s one explanation, but in isolation it’s insufficient. Our grandparents, The Greatest Generation, were dealt a far worse hand economically and had World War II to look forward to afterwards. I wouldn’t call them “risk averse” in the slightest.

No, what’s at the core of millennial risk aversion is unfamiliarity with hardship, status consciousness, and frankly our diminished ability or desire to form the types of interpersonal relationships we depend on to pull through under difficult circumstances.

Our grandparents are the children of yeomen farmers, assembly line workers, soldiers, and other professions that are becoming increasingly scarce or have transformed entirely. But what all of those professions had was intimate and recurring instances of hardship. Farms had famines. Factories closed. Wars were waged. Hardship was a familiar and inevitable part of their lived experiences.

We were raised in a comparatively safer, prosperous, and overall more stable world than ones previous generations have grown up in. Hardship is a much rarer and infrequent experience on average for most (but not all) families. And that’s a great thing. What many of us have lost along the way is the ability to make our own mistakes, deal with them, and live without fear of making more of them.

The oft-maligned “participation award” culture we were raised in, at least in the United States, contributes to the problem too. Learning to get back up after getting knocked down is essential to overcoming hardship and being comfortable with taking on existential risks. It’s difficult to learn that when we’re rewarded simply for showing up. How can a person ever develop grit if they don’t start before adulthood?

That prosperity I mentioned in the previous paragraph is the final pillar of our risk aversion. In the age of perpetual connectivity via smart phones and social media, keeping up with the Joneses is a game we now play on global scale. It’s an ongoing game of clipping highlight reels from our personal lives and creating a more successful projection of ourselves. Vacations, new cars, new houses, high end experiences, and speaking as a 30-something elder millennial… oh dear God, the over, over-the-top engagement photos and weddings. Was it really necessary to have two different chocolate fountains flanking either side of the ice sculptures, Tiffany?

Even if you’re not particularly materialistic or status-conscious it’s difficult to be surrounded by constant, literal “status updates” from your peer group every day and not wonder about whether or not you’re “falling behind” relative to everyone else.

Moreover, as our relationships with others increasingly move from the “real world” to the “phone world” (to borrow a term from Aziz Ansari’s Modern Romance) we’ve under-developed our ability to form meaningful, human relationships. Liking someone’s Facebook status updates and Instagram posts (or if you’re a Twitter user, being outraged at something) isn’t an effective substitute for meeting people in real-life and having actual, lived experiences. The social media arms race is about projection; projecting our success, projecting our happiness, and projecting our intellectual and moral superiority. Through continued, heavier, and more frequent use social media isolates and polarizes us. Screaming our rage through a Facebook feed on one hand and doing our best DJ Khaled impression on Instagram with the other, neither one making us whole. I have to wonder about some of my friends - when was the last time you went on a trip somewhere without posting a story about it on Snapchat or Instagram?

All of these elements, together, form a person who simultaneously yearns to project success and confidence on top of a persona that is deeply wary of existential risks necessary to achieve to success. Someone who cares more about the trappings of success than its realization. Thus, we millennials are a people dreading anything that might expose us for who we really are: cowards and underachievers who hide our inadequacies through embellished, heroic tales of our office martyrdom and perfectly captioned Instagram stories about lavish experiences we purchased on credit at 24.99% APR. Taking on true real risk is as alien an act as voting for a politician who won’t raise your taxes in California.

A significant number of my friends and acquaintances construed my voluntary move from Los Angeles, one of the world’s cultural epicenters, to Houston, TX as odd and undesirable  - especially given that I had zero connections to the city. The word “retreat” was used on more than one occasion, and at one point I probably would have said the same. This is where I want to go next.

Group Conformity
Spending 40%-50% of your post-tax income on housing in cool city like New York, Los Angeles, San Francisco, Seattle, or Washington D.C. is the norm for young, millennial professionals who work in knowledge-worker type fields. It can be an extremely rewarding and fun lifestyle, especially if you’re single and childless.

Beneath the surface, many of us stomach the high cost of living in a city like LA because the perception of being from there has intrinsic social capital. It helps craft an image of ourselves as confident and urbane high-earners who are above mere mortal concerns like the cost of living. That’s hardly the truth, but it’s just one more shared delusion of grandeur we all buy into in the age of social media.

Therefore, moving from a “cool” place like Los Angeles to a… less culturally important place like Houston is interpreted as a loss of status by some. Especially leaving voluntarily. In the eyes of the most status-conscious it means you gave up the game and admitted defeat, the most low-status thing you can do. “You couldn’t hack it here with the rest of us morons who pay $45 for brunch, so long the photos of the food look good in a Snapchat story, so you had to go and runaway to Texas.”

It’s difficult to understate just how powerful the pull of “keeping up with the Joneses” is. When I was 24 I had a six-figure job at Microsoft and was light years ahead of my peer group in terms of both earning power and status.

I didn’t think much about that at the time. So at the age of 26, I left Microsoft to found MarkedUp feeling like my process of self-realization was almost complete and I was in total control over it.

But things didn’t work out with MarkedUp. I failed, publicly, and brought down most of my personal savings and my investors’ dollars with it. Oops.

The thing that kept me motivated in the midst of 100 hour work weeks, grinding to save the company from going under, wasn’t so much the thought of losing this great opportunity. It was the fear of looking like a loser; having to lay off loyal employees who had done nothing but bust their ass to save the company, personally calling all of our investors to tell them I’d fucked up, telling vendors we owed money to that we wouldn’t be able to pay them, and worst of all: telling our thousands of users that we were going to have to cut off their service. I did all of those things and, miraculously, didn’t die from it.

However, it’s what happened afterwards that drove this story home for me. At the age of 29 I co-founded Petabridge with what little personal capital I had left. I knew I had an opportunity to build something special around Akka.NET and I wanted to take a chance on that rather than go back to work for the man. We self-funded that company this time around - no outside investors. Money was really scarce for the first couple of years in particular. I made barely enough to cover my rent.

At one point I went an entire year without buying a new pair of pants because I simply couldn’t afford them; all of the pairs of jeans I owned had ripped crotches and numerous coffee stains. It wasn’t until I told my mother about it that she stepped in and helped. I went from thinking I was pretty hot shit at 24 to not being able to buy a pair of Levi’s without help from mom and dad at 30. Welcome to the downsides of taking risk: hitting rock bottom and having to start over.

I felt like a complete and total fraud when I was out with my friends or my girlfriend’s friends. Someone who didn’t deserve a seat at the table. “Damaged goods.”

By this point in time my peer group was light years ahead of me. Getting married, buying homes, going on nice trips, nice cars… Few of these things, individually, mattered to me - but the thought that I couldn’t participate in any of these activities made me question my life choices up to this point. “Did I fuck up when I left Microsoft?” “Should I have taken a stable job after my first company failed?” “Am I cut out to be an entrepreneur?”

I understand why my generation is risk averse because I’ve been to the other side and back again. In an environment where the public projection of success and confidence is more common and important than ever, putting yourself in a situation where you’ll be exposed to real hardship and the distinct possibility of public humiliation is the very essence of millennial dread.

What We Leave Behind
If there’s a second thing I’d ding my generation for, it’d be for letting pervasive cynicism become a core part of our outlook.

For all of my fears, worries, and self-doubt there was an essential truth that I’d completely discounted and overlooked: no one thought any less of me for failing. Most people just admired that I had the balls to try in the first place and be upfront about it when the first business failed. At the time and for a long time afterwards, I couldn’t process that. Instead, I felt like I had lost face and status, branded with an “L” for loser on my forehead.

We assume by default that every one else assumes the worst about us, and that probably isn’t unique to millennials. My failure at launching a business must mean that my friends and family think I’m a failure. But that couldn’t be further from the truth.

We may humor each other by pretending that what we see others post on social media is who they really are, so long as they continue to do the same for us. But we’re not idiots. The 20-something girl posting a blurry Valentine’s Day photo of a bouquet of wilting flowers her boyfriend bought at the last minute off of 1800flowers.com with the “I’m so lucky!!!!” caption isn’t fooling anyone, despite the 400 likes on her Facebook feed. Neither is the 30-something guy posting photos of himself sitting in his company’s corporate booth at the Maverick’s game shoving nachos down his hatch; actual big shots don’t need to remind everyone that they’re a big shot on social media.

In an endless news feed of grandstanding bullshit we truly and deeply value authenticity when we see it. Seeing someone who takes a risk, fails, and get back up again awes and inspires us - because it stands clearly apart from the endless cynical facade of self-promotion and aggrandizement that surrounds us. It’s this authenticity and lived experience that will form relationships with the very people who will help you through the crests and troughs of life and help you emerge victorious, successful, happy, and surrounded with friends.

The truth is, our perception of existential risk is very different from the reality of it. Our peers judge us less harshly than we judge ourselves. And the real parts of the risk, flirting with financial disaster and lost time  or opportunities? What about those?

I’ll answer your question with a question of my own: what do you want to leave behind after you’re gone? Children? Knowledge? Achievements in art or science? An organization? A company? Your acts of decency, charity, gratitude, and good nature told fondly by friends and family?

We escape the job we hate; the crushing interest of student loan and credit card debt; the dissatisfying relationship; our grief; loneliness; and the rest of inadequacies of our lives by pursuing something bigger and harder than our next Instagram story.

Risk aversion is fundamentally prioritizing our daily needs over long-term aims. Forgoing legacy for comfort.

Achievement, distinct from “social media achievement,” necessitates risk. Walking away from a “good enough” but not “great” relationship in pursuit of someone better is a risk. Leaving that comfy corporate job with its great benefits to start a company is a risk. Moving to an unfamiliar place with few lifelines is a risk. Letting your children fail and get back up on their own is a risk.

Hardship is an inevitability of risk; you will eventually take a risk that goes sideways. Rather than treat it like a terminating event for your career and life, adopt that attitude that risk taking requires practice in order to be done well. Failure is the greatest teacher and you will emerge stronger and better prepared for the next and bigger risks.

That has certainly been the case in my life. Petabridge is doing great and I’m happy to report that I can afford to buy my own pants, like a big boy, at the ripe old age of 32.

I “retreated” from California to Texas because it’s a stone on the path of my legacy, which I prioritize ahead of being able to surf on the beaches of Malibu or clinking flutes of champagne with other tech CEOs on the rooftop bars of Santa Monica.

My fellow millennials: do the same. Life is too short to live unintentionally. Choose legacy over comfort. It will lead you on a path that may include hardship, but who you’ll become when you emerge on the other side is someone who no longer needs to project success because that’s you actually are both on and beneath the surface.*
#### [The Necessity of Systematic Thinking](http:&#x2F;&#x2F;www.aaronstannard.com&#x2F;systematic-thinking&#x2F;) 
*I spend a lot of my professional time training other software developers on how to build next-generation applications. Distributed and concurrent systems; stream processing; stateful web applications; soft real-time applications; and so forth. Cutting edge stuff for the majority of my industry.

One of the huge advantages of inexperience, such as when you first graduate from school, is your default state of being with the world is one of perpetually learning and adopting new skills and techniques. You’re not intimidated by taking on a project with lots of unknowns because… every project feels that way during the beginning of your career. But once you’ve been in your industry for a few years you pick up a few things: tools, tricks of the trade, techniques, pitfalls, preferences, methodologies, and so forth.

Fast forward to your five, ten, or fifteen year mark in your career you’ll run into what is an existential crisis for most people: a paradigm shift. The experience can different for everyone. It could be:


  Starting a new job at a really small company with tremendously more responsibilities and influence than you did when you were working for BigCo.
  Being promoted from an individual contributor to a manager.
  Taking on ownership of a product, including both the technical and business side of it.
  Working on a much more demanding and critical project.
  Founding a business and suddenly having to care about things like where revenue comes from.


And so forth.

The common thread among all of these experiences, those of my customers, and my own is: much (but never all) of what we’ve spent our past N years in industry learning isn’t going to get us very far in our new endeavors. We are expected to produce at as high or higher levels than we were before while having to learn reams of new skills, technologies, techniques, and practices on the job.

It can be a stressful and scary proposition; I remember what it was like when I embarked on that process for the first time. Things things didn’t go so well initially, but ultimately I figured it out.

If you make it through to the end of this post you’ll walk away with is a loosely structured methodology for how to handle big challenges in a manner that puts you in control of the ship, rather than merely coming and going with the tide.

Conquer Ambiguity with Systematic Thinking
The greatest stressor for most people undertaking a big, ambitious project is usually its lack of formal structure or definition.

The ambiguity of a new role, new job, or the scope of a big project completely terrifies people who’ve grown up through two decades of regimented classes in school with easily quantifiable grades followed by a number of years working as a worker bee for BigCo with semi-defined hierarchies, business processes, project management systems, pay scales, and the trappings of bureaucracy.

A empirical law of all merit-based organizations: the amount of responsibility you are given is inversely proportional to the amount structure1.

The CEO has the least amount of structure, the cashier working in the checkout aisle is given the most.

When you take on an initiative with greater responsibilities, it is your job to create and provide the structure for seeing it through.

Most people are utterly terrible at this not because this is an innately hard thing to do, but because the very idea of being responsible for defining your own process for accomplishing something is so beyond the average person’s world view they can’t even fathom having to do it.

Become Responsible for Our Own Structure
That’s the first part of your mindset that has to shift: You. Are. Responsible. For. Your. Work. It’s not your manager’s job. It’s not the CEO’s job. It’s not the job of the other people working on your team. It’s yours.

An example. Suppose you’re hired to run a brand new marketing concept at a company and you have total control over how every aspect of it can be done. You’re given a set of goals by your manager (that is their job) and some parameters on how the marketing experience should be delivered to the customers. Your goal is: increase profit by N %. Pretty unambiguous.

What I would do in this situation: review what the company has tried historically in this area, analyze the marketing copy and ads, game out a business process for quantifying returns on a new campaign, and float some test campaigns immediately. Assuming that I didn’t have to deal with an obnoxious procurement department or comptroller I’d have a live and running campaign deployed within my first five days on the job.

The distribution of research to action in week 1 of the job should be for every two hours I spend researching I spend six actually doing something.

What the many people do: fucking panic. Constantly seek reassurance; over-research the problem2; endlessly pursue fake work; and when pressed for results feign ignorance and play dumb. “I don’t know what I’m supposed to be doing!” Bullshit! Your job is to increase profit! Sell more, cost less! It’s basic math!

The difference between the cases in this example is I created my own structure for attacking the problem. I know there’s a ton of stuff I don’t know; I can learn it. I’m also pretty sure there’s a bunch of unknowns no one in our organization knows. I can’t do anything about that so I’m going to experiment and gather data methodically to help determine them.

This is where we must begin - we have to create the system for our work and invent structure where there was none before.

Favor Direct Action over Passive Research by Default
A good rule of thumb for creating structure and systems: always favor direction action by default. We need to build our confidence and awareness up in order to deal with big, unknown problems resolutely; there’s no substitute for first-hand experience.

In the previous example, rather than spend our first week on the job watching a PluralSight course on modern advertising, let’s design a really simple test campaign with a small trial budget and get it up ASAP. We’ll learn a ton in the process and we’ll have results we can share with our team immediately. No one will care if our first campaign (or project or whatever) isn’t a success - the fact that we actually did something on our own initiative already puts us ahead of most.

Passive research such as taking a course, reading a book, and so forth are still worth doing. But you need to do those on your own time (unless it’s your company running the training.) You are still expected to produce even if you have to close a knowledge gap at the same time. This is part of the price of admission for working on exciting and big projects.

The big benefit of direction action is that it is productive and instructive at the same time. You form first-hand experience around the problem and have output to show for it. Never discount the value of social proof and demonstrable output in any human organization; a basic demo or a small completed project counts for a hell of a lot more than “I read a book!” does.

However, you can also turn the exercise of reading a book or other forms of passive research into direction action too if your attitude is so inclined. Show up to your team meeting with a presentation based on what you learned. Share your experience with the team and help them learn too. But can you spot the difference there? Reading a book in your cubicle and hoping to silently get started on some project without interacting or sharing with your team is essentially “hiding” from your work. It’s the knowledge worker equivalent of trying to run out the clock. Reading a book and sharing what you’ve discovered with your team is leadership.

Learn How to Create and Define Processes
Thus far we’ve:


  Accepted responsibility for our work and have chosen to create our own structure and
  Have made the explicit choice to prefer output-producing forms of learning.


The next step is learning how to actually build a system around our work. The takes two things:


  Being able to fit the entire problem space into your head at one time. This means avoiding rat-holing on specific details. You need to design a structure the aligns all of the output you and others in the direction of the same goal, is measurable, and able to be broken down into smaller parts and sequenced into a schedule.
  Define repeatable processes that are capable of being measured and sequenced for executing specific workflows.


I’ll give you a good example: debugging a hard race condition in the network layer of Akka.NET. The reason I’m pretty good at debugging these is because I’ve honed a repeatable approach to doing this over the years.

I begin by reading through the bug report or the failed test and try to form a picture of what all is happening in my head. Usually I’ll draw a sequence diagram showing what should be happening vs. what is actually happening. Then I’ll form some ideas about what is or isn’t happening and build a definitive set of theories that I need to disprove one by one.

This is how you “fit the problem” into your head at once: with structure and definition. From there, I move onto defining a methodology: process of elimination. This is going to be my system for determining the cause and existence of the error. If I have a team working with me I can assign one hypothesis to each team member and have them work in parallel with me.

Next step is defining repeatable, reusable processes. I typically use a flowchart3.



Nothing too complicated about this process, but what it does is gives me a reusable tool I can use each time I have to approach a problem. This process above is just merely trying to reproduce the problem; I have others I use for tracking down the code, fixing the problem, and verifying the fix.

If you don’t invest the time into doing this, you will treat every single task as a one-off. Every new thing you do will be stressful. You will be a low output producer. And you will not succeed in your job. Systematic thinking and ability to invent structure is a necessary ingredient for success in any field.

Wrapping Up
If you build systems around your work you can methodically add structure to ambiguous (ambitious) problems and take something from being an unknowable, complex, and intimidating project to something that is workable and manageable.

There are freaks of nature out there, but most people simply can’t throw their intellect at a giant problem and hope to accomplish much of anything. Successful people work hard to break down big problems and work through them methodically. Start by looking at your own routines for handling your every day work and see where you could make an improvement there using these steps.

This process requires you to take ownership of your work and play the lead role in it. But if you can get this down there’s nothing you can’t do with a bit of time, measurement, and trial-and-error.


Footnotes


  A corollary to this law: the amount of reward you receive is directly correlated to your ability to deliver upon said responsibilities. If that’s not been your experience… Consider quitting?
  See the section on “analysis paralysis” here for further explanation.
  Seriously, invest in a good piece of diagramming application. I use SmartDraw for all of my diagrams. But there are loads of others. They’re in invaluable in helping you define structure around your work.*
<!--END_SECTION:feed-->
