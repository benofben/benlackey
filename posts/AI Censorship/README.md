# AI Censorship

These are some very rough notes on AI censorship.

I've been playing around with various AI image generators for a [card game I'm working on](https://github.com/jrucs).  I've been running into censorship.  Gemini gets mad about things as inncuous as "draw me a sexy water elemental."  Though, the censorship is inconsistent.  

Grok has issues too which is wild.  Grok was supposed to be the open no censorship AI.  I really wonder who or what is putting pressure on them.  It looks like [Grok is running on OCI](https://www.oracle.com/news/announcement/xais-grok-models-are-now-on-oracle-cloud-infrastructure-2025-06-17/).

It would seem to open an opportunity for a company to provide uncensored AI.  There seem to be many barriers to that though.

At the top level there is a quiestion of jurisdiction.  In Europe, they're merrily cooking up ideas for censorship.  China is kinda funny in that they don't believe in IP but censor speech, one of the many contradictions of a totalitarian regime.  The US is probably the most free jurisidciton from a speech perspective, unless you go full on seasteading or something.

On the technical side, the most obvious issue is that the AI will probably run in a cloud.  The 3 main cloud providers all have responsible AI initiatives that include censorship.  So, my guess is that they would censor a vendor attempting to offer uncensored models.  I kinda wonder if you'd be best off running on OCI or Ali Baba in the US.

Even if the 3 cloud providers didn't deplatform you, they likely wouldn't let your model run in Bedrock or its analogs.

You could try custom hosting.  The capital outlay to build up infrastructure would be enormous.  And you would be at an extreme disadvantage to the cloud provider offerings which are integrated into other parts of their portfolio -- search with Google and Office with Microsoft to name two examples.

Some people are jail breaking models and just running them locally.  I wonder a bit if we're due for a cloud counter revolution.  This might be a move back to distributed machines much like the end of the mainframe and dummy terminal era now roughly 50 years ago.  The mere fact that it seems unimaginable may make it likely.

It's non obvious to me how you break out of this.  However, it does seem whoever succeeds will capture the market, initially of people who have censored requests and later of a wider public who just doesn't want to deal with an AI that won't do what they ask of it.

That said, I may be wrong.  We've been in a multi decade backslide from a free speech peak around the birth of the internet.  As corporate interests and walled gardens sprang up, they curated the internet to be less free and more comfortable to the perceived desires of their customer base.  Legislation has moved in lockstep as social values have become more constrained.  Maybe we'll be happy with our censorship.  We have been for long periods in the past, that is, most pre enlightenment societies.
