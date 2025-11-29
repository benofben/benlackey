# Fixing the Internet Part 2

This post was originally transcribed by my iPhone while hiking with Olive nearby Yssingeaux on July 3, 2025.  I tried to use Gen AI to clean it up but that didn't work well.  Ultimately, I started editing it into sentences and paragraphs.

<p><img src="IMG_1794.jpeg" width="300"></p>

There is a notion that the problem with social media is that you’re the product because you don’t pay for it.  That’s not accurate. 

## Broadcast Media

If you look back, broadcast media is the obvious counter example or predecessor as the case may be. Watching the big networks, you didn’t pay. You got free content. The cost was in the advertising. You had to sit through commercials. Presumably some percentage of the audience purchased things to make the whole thing go around. 

The problem with social media is something else.  You’re not paying for it, so you don’t get what you want. You get what the vendor wants.  That’s been the same for decades.

It’s similar to broadcast television 50+ years ago in that the vendor is trying to pull you in for as much time as possible. The difference is it’s become more insidious. It’s become more addictive.  That could just be characterized as a change in technology. We’ve gotten better at. 

I’ve heard that characterized as providing a Brooks Brothers level of service at Walmart prices. Facebook can cater content to every whim in an extremely personalized way.  The cost is low because that process is automated.  An expensive sales person need not be paid.

## Social Media

The issue with social media is something else.  It’s that consuming the product makes you worse, not better. There should be an opportunity here.

If we cast back to the 90s there was a notion of cyber utopianism.  The web was going to make everyone better.  It was going to allow us to talk to each other. This would breakdown barriers, and as such make violence impossible because who wants to fight with someone they know? Instead it’s balkanized us -- broken us into little hate filled groups who not only don’t understand, but don’t want to understand the other.  It’s unclear how that happened. Everything looked pretty good until the dot com bust.  The bust happened and out of it this new generation of social media came.

## On Killing your Customers

One issue is the feed. The feed is designed to be as addictive as possible. It’s not designed to give you what you want, whatever that may be. It’s certainly not designed to teach you anything. It’s just there to keep you endlessly scrolling. All this seems to imply an opportunity for web content that doesn’t destroy its users, but makes them better. 

It’s presumably a problem that the drug dealers have if they're selling people heroin. Your customers eventually disappear. They die off. 

Now that’s hyperbolic in the social media case, say the people consuming 12 hours of TikTok a day. They aren’t gonna die off literally at least in any near timeframe, but they cease to exist economically. They can’t hold down a job for the fact that they spent too much time on the damn thing. Worse, the thing errodes skills that might allow them to hold a job.  

Paradoxically viewing all this media kills critical thinking.  You’re caught in your own isolated echo chamber, not exposed to new ideas despite constant exposure to media. Beyond tha there are the documented concerns about attention span. Economically productive activities have a tendency to require some sort of attention span.  Manual repetitive labor tends to be less economically productive than the attention span requiring higher order jobs.

This brings us back to the original question. Social media as it exists today, and possibly even more broadly the web, is actively making us worse. It would seem there’s an opening for things that make us better, if only because the customer base would be prolonged. A better web might enhance their ability to pay versus whittled it down until it disappears into nothingness.

One possible metaphor is college.  Good colleges thrive on producing graduates who are economically productive. Those people, decades later, return the gift in the form of contributions to endowments. 

Decades is probably too much to hope for from a web business model. But maybe there’s an argument to be made that the current generation of social media companies, that is the ones that came after MySpace and before whatever the next post TikTok generation is, are trapped in a form of innovator dilemma.

Meta probably deserves kudos for looking at TikTok and creating Instagram Reels, their knock off analogous experience.  

All the current generation of social media share a commonality that in the walled garden. This is also characterized more positively as the Cathedral versus the Bazar. The Bazar was the Internet we had before with people creating say GeoCities sites with their own personal website and interests.  Each was a very special butterfly with unique design and thoughts. 

MySpace provided turn key ease of use on top of that.  For it you paid with less ability to customize your website. People got really really clever with CSS configurations and so forth. 

Facebook and its analoges went further initially exposing some ability for customization.  People may remember the zombie and vampires games that operated as plug-ins to Facebook. As the platform matured those APIs have been increasingly closed off. 

Because the platform is hosted by Meta with no openness and no ability to take it in host elsewhere, the API‘s were really the only way to get at your data. Facebook is increasing friction with more and more qualifications to get API access at all. Then they are weakening the API themselves. 

Facebook has consistently raised the height of the wall around their garden.  This makes it difficult for competitors to take their data and profit off it.  At the same time Facebook is making inevitable some sort of displacement from an innovator.

## Back to the Future

There’s an interesting difference between the current crop of Silicon Valley entrepreneurs, and the earlier creators of the Internet. The most trivial characterization is to look at organizations like DARPA and Bell Labs and note that the nerds who created the Internet, and UNIX for that matter, were doing so to try to build a beautiful thing.  This wasn't because they saw opportunity for personal enrichment. 

They did build a beautiful thing. They built a lot of infrastructure that was later used to build the cathedral / walled gardens we have today.  However, the underlying infrastructure still remains.  In many cases it is more robust than what was initially built. 

This raises the question of what new things should potentially be created if we are to reopen the internet and make it something that serves the user.  This is contrast to the rent seeker selling advertising that is served today. 

The x86 instruction sets that have dominated server hosting for decades remain largely open and interoperable.  Even Apple shifted to x86 for its laptops.  The caveat here is the iOS stack that remains extremely closed. 

There’s also an emerging trend with ARM processors that are extremely low cost and interoperable as well. Cloud providers are building out stacks of those.  Many millions of edge devices run on that technology as well.  However, those devices are often closed and difficult to customize for software, hardware and even legal reasons.  This includes the DMCA. 

If we move up the stack a little, we can take a look at operating systems.  The most obvious open operating systems are the Linux-based operating systems.  Android remains largely open, though it is often customized to make it more closed. 

There’s another analog in Apple, taking BSD and customizing it into their laptop / desktop operating system.  Apple replaced the earlier versions of the operating system that had been developed entirely in house.

Contrast Microsoft and their failure to capture the phone market.  This has restricted the ability of the Microsoft ecosystem to span environments.  This makes it difficult to serve a modern user who expects both to be able to operate on a PC.

## It's always DNS...

The network stack is really interesting in the wall gardening of the Internet.  If we go back to the late 90s it was still relatively common for a user to have a static IP address. This probably lasted the longest at corporations that were slow moving.  Workstations retained static IP‘s into the mid 2000s. 

however, as the Internet grew, users served less and less.  They operated clients more and more.  That allowed DHCP to take over.  It became common to map a single static IP address to many many underlying IP addresses, most of which were not readable. 

This was the move from every internet participant being a server to internet participants being clients.  They were no longer servers.  This was both a user driven event as well as something happening because of the evolving technology moving hand in hand. 

I wonder if the IP space restrictions and the slow move to IPv6 exacerbated this problem.  If a greater number of IPs had been available earlier, perhaps applications would’ve lingered as combined client servers longer and then users might’ve picked up on taking advantage of the benefits of an open internet.

We now live in a world where your device has an IP assigned, but that is buried under many layers. That makes it non-readable for accessing from other devices on the Internet.  That change alone, killed the peer to peer, anarchic or democratic, depending on how you perceive it, original nature of the internet.  There are hokey solutions on top of this.  Various forms of dynamic DNS attempt to route around the damage here.  However, those typically fall victim to port filtering, firewalls and such common now.

The fundamental protocol that the internet relies upon has been intentionally broken over the past 2 1/2 decades.  This damage was done primarily by ISPs and hardware vendors working around the restrictions of IPv4.  An additional contributing factor was the limited desire of the average internet user to serve content.

There may no be an unserved desire to spread content. Many users who post to platforms like YouTube, TikTok, and, back when it was called Twitter, suffer from the platforming.  Either the vendor of the social media platform or a vicious mob decide that that user should no longer be able to use the platform.  The platform should be a public good or utility instead of private product. 

We saw this in spades leading up to the 2020 election when Jack Dorsey still owned Twitter. Because of political or philosophical disagreements, potentially quite justified with Donald Trump, Dorsey chose to platform him. This led to further Balkanization of our social media with additional walled gardens, such as Parler and Truth.  These are now entirely right wing echo chambers.  

We saw the reverse when Elon Musk bought Twitter and renamed it as X.  Left leaning users departed the platform not because of the deplatforming, but because of ideological disagreements with the new owner. New platforms such as the Blue Sky and Mastodon popped up.  

## Beyond Good and Social Media

Social media is just one facet of the overall issues with the internet. Even if we widely adopted a purportedly open system such as Mastodon on the social media front, there’s a larger desire and larger potential public good of having an open internet for everyone.  The net neutrality folks have been fighting for those benefits for sometime. 

We’ve talked about the network stack. We’ve talked about social media.  

Parts of the internet remain largely functional.  A user can today register a new domain name. Even in the comically polluted DNS namespace, a user can find something.  There are various inexpensive services that will provide hosted DNS.  They even let the user insert custom records.  

Functionality has been restricted in the website hosting analog and social media.  DNS remains a very bright spot in the internet, still functioning well incredibly robustly.

Other parts of the internet have been less resilient to rent seeking. Email stands out in particular. Early hosting providers such as Yahoo! and Hotmail realized that they could make a business hosting an email server for a user at a given domain. It’s become common to charge a premium for a custom domain.  This makes sense to support the cost of administration.

The business model for these hosted email services is much the same as social media or any other typically free internet service today. It’s supported by advertising. 

That’s had two negative impacts on the development of email over the last few decades.

1. Number one is compromising the ability of smaller servers continue sending mail 
2. Encryption.

## Number 1 - Sending mail

In the late 90s, it was quite possible to plug a server in and begin running your own email server. I used to do that.  Other people did too. 

As Hotmail and its analogs took off, those walled gardens became increasingly restrictive about what email they would receive from where and what they would forward.  Part of this was a legitimate concern about spam.  However, hidden within that legitimate concern was an opportunity for monopolistic behavior.  Large email service vendors, in ceasing to accept emails from Russian and spam servers, also ceased to accept and forward emails from smaller servers run by internet enthusiasts.

That’s led to centralization of what was once a distributed protocol.  Today it is extremely difficult to start a new email server.  If you do, it’s likely that the main hosting companies will mark any emails or originating from your server as spam and refuse to forward them to their intended participants, once again breaking the internet.  

## Number 2 - Encryption

The centralization of email has held back another technology. encryption.  In the late 90s there were encryption key exchange parties.  People would exchange their keys with other users face-to-face so that they could be assured their communication between one another would be encrypted going forward. Some of this was good security posture.  Some of it was paranoia blended with the love of over engineering.  

Regardless we built good encryption technology.  However, it was never used because the main mail hosting providers don’t want to end encryption.  That would make it very difficult to read your emails and advertise you things based on the contents of those emails.

Reading you email is something that many of the providers seem to be doing.  You probably had antidotal experiences that seem to validate that claim.  I know I have. 

We do have some encryption.  It's just not for email.  Instead it's point to point from the client to the email server. In email other standards have been ignored or not invested in because they restrict an email provider's ability to monetize.

Vrious mechanisms to send and download email through open protocols, POP, ICMP, SNMP, all spring to mind.  Those protocols in some cases are available at a premium. In other cases they are available with the free advertising supported products however, they are rate limited to such an extent that it’s difficult to pull down large volumes of emails and ever switch providers. This becomes yet another form of lock-in into walled gardens built on top of once open protocols.

Unlike social media and taking a more broad stance web hosting in general, the email protocols still exist.  They are still broadly used for interchange.  The problem is fixable if a sufficient number of mail servers were willing to ignore the spam rules and forward around emails from smaller providers.  That would have to happen hand in hand with smaller email servers starting to exist again. 

## Auth and Auth

A new form of lock-in has been developing faster and faster during the last decade.  That is authentication and authorization vendors with a large walled garden.  Facebook and Google spring to mind.  They leverage that walled garden to have users authenticate in other areas.  So you see phenomenon like see click fix, The community reporting portal used by the city I live in, supporting both Google and Facebook off because they are dominant.  That gives vendors more ability to track users and forms a vicious cycle.  More sites adopt these logins.  All that presumably feeds ad revenue.

## Escaping the Walled Garden

How do we fix all this?  That’s a technological question mixed with business. How do you break down the walled gardens in a way that’s sustainable? 

At a high-level there are the concerns about openness and the impact of addictively structured social media on all of us.  Those high-level concerns aren’t going to prompt in any change.

The more expedient question is what is missing in the internet today that an individual user would like? The feed has been a source of frustration for many users.  They are presented with whatever the feed believes is appropriate for them rather than what they want.  Presumably people want to connect with users they may know or may want to interact with new ones. 

One easy thing missing from the internet today is the ability to follow the friends and users you know and want to follow.   Ideally that information would be presented to you in a way that you choose, perhaps chronologically, perhaps being allowed to search through it. 

As an example, a while back I was scrolling through Facebook and got back maybe five years in my feed.  At that point my feed declared that I was a bot and couldn’t look at any older posts.  This could be viewed as a legitimate bug my guess is Facebook doesn’t get a lot of value from serving old posts on demand, preferring instead of bubble them up as memories for repost. That way they can choose the time place of access.  Typically pulling things off of cold storage is more expensive than whatever hot alternative.

A basic use case is to read updates from the users you want to interact with and no one else.  Interestingly both TikTok and Facebook recently introduced features that provide this to a limited capacity with friends feeds.  Presumably both firms don't want to be trapped by the innovators dilemma and are willing to take some hits in order to maintain their user base.

Also missing from social media is the ability to present any sort of static curated or re-edited content.  That is the homepage if we think back to MySpace.  On MySpace, the homepage was the focus.  The feed was sort of a nice to have addition.

That is a core difference between the old open web and the modern closed web. Previously it was possible to intentionally browse to uncover an item that interested you.  You could then follow it deeper, learning about it.  This required both attention span, and critical. 

The feed based web experience is very different. It’s much more passive.  An algorithm presents information to be user.  They then page through slowly or quickly, depending on their level of interest.  The ability of a user to direct their interest in this is limited.  They can go to another user's page and view that user's other content, but typically presented by some sort of weighted algorithm or chronologically. There’s no ability to follow up on continuity of the single idea.

## Deep linking

As the web has gotten increasingly dynamic, a new phrase has come to be -- deep linking.  A few decades ago that would’ve meant nothing. Everything was a deep link.  Paths were absolute or relative, but any webpage could be accessed simply by passing any URL.

Now, with many dynamic pages, doing rendering on a mix of the client and the server, much content can’t be accessed without a bunch of state that is often difficult to bring along.   In many cases, the content can only be accessed if user is already authenticated.  This makes it possible to restore their state.   

That’s led to another change in how the web works.  If we go back, once again, to the late 90s someone might read a page and have some comments on the page.  They could write those comments on their own page and link the original page.  It was then possible to uncover who had written about what by following referral paths.  With the lack of static pages, that’s no longer possible. 

Then there’s an additional issue. Let’s pick specifically on news sites.  News is become increasingly click baitey. The Times is often criticized for that.  It was previously the paper of record, now, something else.  

Clickbait news generates lots of comments. Interestingly, many of the news sites actually disable commenting. We see that particularly with local papers in Seattle, where his stories on politically sensitive topics such as homelessness often have comments disabled.  It is certainly the right of anyone hosting their own website.

The breaking of static linking in the web has made it difficult to maintain and any sort of history of the web.  The web has become a much less collaborative place. 

There’s an interesting follow on impact for the Internet Archive as pages become more and more dynamic.  The Internet Archive can crawl them and capture anything because every page looks different to everyone else.  Your Facebook homepage is a great example. 

This is another example of balkanization.  Stealing another metaphor perhaps the blind man each have a hand on a different part of an elephant, all accurate and describing their particular elephant part.  Simultaneously they completely miss any notion of water an elephant is.  That is us on the web today and unfortunately, in real life often as well. 

Picking on the news site again -- we’ve had some great examples recently as the Republicans try to pass their big beautiful bill.  The liberal outlets decry the bill itself.  They make claims about how close voting is on the bill and how marginally likely passing of it seems. 

Contrast the major right wing outlets like new Fox News and the Epoch Times talk about how great the tax cuts will be for a typical American and how the vast majority of Republicans in the house in the Senate have voted along party lines for that measure. 

This is one example.  There are many more in the news currently.  The Iran strike springs to mind as well.  Conservative outlets, post about success in destroying Iran’s nuclear capabilities.  More liberal outlets, call the strikes a failure. This kind of reporting on each side is concerning.   It makes it difficult to ascertain an objective reality without actually laying eyes on yourself.  Without a shared view of reality, it becomes very difficult for democracy to function.  We're seeing this with the increasing votes along party lines.  This is a trend that’s been increasing since the end of World War II.  See chart in Ray Dalio‘s most recent book for background. 

The web today is an enormously more valuable resource than it was during the .com boom.  However we’ve lost many things that we could potentially recover.

## Web 3.0

Many of the ideas in web three are interesting.  There isn’t meaningful technical grounding in web 3.0.  The solutions start with a solution, crypto, and then attempt to find a problem that it can solve.  Unfortunately it’s ill suited for the problem. 

Crypo states itself a store of value.  It is similarly, ill suited for transaction processing.  Volumes are limited to a tiny fraction of what exchanges did decades ago.  Still, somehow out of those failures we keep attempting to apply crypo to new areas. 

## Dencentralization

I do think decentralization is key.  That’s part of why the web was initially successful.  It was designed to be resilient to nuclear strikes. It grew first at college campuses, and later with enthusiast and companies.  The web added more and more nodes, first centralized hosting, and later the cloud pulled everything back into a pre-web 1.0 maybe a web 0.0 model.

This is something that would been familiar to operators in the client server era running on a very large main frame.  These days those linger.  It’s less monolithic time sharing and more time sharing cut across smaller computers with things like Kubernetes running and hosting environments. All this is allowed for very high-quality websites.

In the ideal open web, I’d like to see the notion of internet backbones somewhat disappear. National networks come back with the Internet, being resilient failure.  

Some IOT models were built like that, while others were tree based with inheritance up to a single point of failure. The national networks being built with IOT devices in say 2005 were much less powerful than what’s available today. 

I’m going to pick a particular example. My master thesis advisor had a project partially funded by the defense department where they were dropping plastic cylinders with various sensors -- temperature, GPS, and so on.  Those would form a mesh network.  It was a situational awareness on the battlefield sort of use case.  Those devices by modern standards are ridiculously underpowered.  Yet they were perfectly up to the task.  

Contrast if we fast forward to today, the iPhone I’m dictating on is significantly more powerful than the early web servers. We all use devices easily capable of serving static website of the kind that was popular in the GeoCities and MySpace era. 

One thought I have is that perhaps static content is what users really want.  That is a feed that I could add to chronologically listing off various things I’ve worked on.  I could then pick them up and revise them.  It might bump back to the head of the feed with the revisions in the new version.

Feeds could then be taken by user and combined to provide being subscriptions.   I realize this is essentially a reinvention of RSS. I still don’t fully understand why RSS died.  Clearly more addictive platforms took its place.  That's one cause.

Google created the dominant RSS reader and then in true Google fashion killed it.  Presumably they realized it was more difficult to monetize than other products.

One criticism of RSS is that it strips the look and feel that an author may create around their content.  So finding a way to maintain that would be interesting.

## GitHub

There’s another part of the web sort of the web that’s still working quite well.  It’s git.  On top of git some rather clever people saw the opportunity to build GitHub.  Originally it was a version control system.  Now it's something that’s being used to post strange ad hoc websites that are static.  Part of the advantage of git is it brings along versioning and is a truly portable format.  It’s possible to take a repo existing on GitHub and clone to get file and then do whatever you want with it.
