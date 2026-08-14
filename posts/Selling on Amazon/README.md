# Selling on Amazon

One of my projects is [JRUCS](https://github.com/jrucs).  It's a card game.  The cards are generated from YAML files using AI.  I then clean them up in Photoshop and print them.  A friend gave me the bright idea to try listing them for sale on Amazon.  It's been a journey.

I've been working with Amazon Web Services (AWS) in a profesisional capacity since 2012.  At that time I was at Terracotta.  We did work to list our product on AWS Marketplace at the request of a large customer who wanted to purchase in a PayGo model rather than the perpetual licenses plus support contracts that were typical of enterprise software at the time.  Since then I've done similar work for companies including DataStax, Couchbase and Neo4j.

So, I have some experience both with Amazon's tech stack and the culture.  Amazon culture is built around the [Leadership Principles](https://www.amazon.jobs/content/en/our-workplace/leadership-principles) with customer obsession the first.  It's always interesting being an Amazon Partner.  Many Partners are customers, so it's possible to influence Amazon through that lens.  Additionally, joint customers can be used to influence.  But approaching something as a partner only has little impact.  This mentality keeps focus where it should be.

While ".com" and AWS are seperate, a lot of values and technology seem to be shared.  There's also an aspect of dog fooding.  AWS started to serve .com.  When it became apparent the services would be useful to 3rd parties, Amazon began to sell them.

Siging up as a vendor was pretty straightforward.  I needed the tax ID of JRUCS and other similar information.  I filled out a wizard and a few days later the approval came through.

## Listing

Listing products has been rather more of a challenge.

First off I had to answer a questionare about the new product.  This seems to be an AI powered pseudo flowchart.  I suspect it's intended to avoid listing profusion where different vendors create unque listings for either a brand name product or a generic version.  My work fell into a third bucket - brand new product.

That required me to complete a "Brand Qualification Application."  No big deal.  Amazon seemed to want to ensure that JRUCS was a new thing.  They also wanted to ensure that it was real.  As such, I was required to submit photos of the product.  In this case, I sent in pictures of the deck box.  That application was submitted and approved in a single day on July 2.

At that point, I had a brand in Amazon parlance.  The listing creation dialog was unlocked.  I could create products under that brand.

JRUCS is the brand.  Alchemy is the first JRUCS branded game.  Gods is the second, not yet released.  There are four JRUCS Alchemy products, a deck for each of the four elements: Air, Fire, Water and Earth.  The taxonomy is:

* JRUCS
  * Alchemy
    * Air
    * Fire
    * Water
    * Earth
  * Gods

Going into the listing process, my thought had been to create four listings, one for each element.  At the time only Fire and Water had been printed.  So, I went into the web UI to set that up.  I quickly noticed that the listing could have variations.  So, I modified my plan slightly.  I wanted to have a single listing with two initial variations, ultimately growing to four.

This is where things started to go a bit haywire.  In the UI I was able to enter the product.  However it failed validation because of the title.  The validation was AI based.  I tried 20+ titles.  I opened a support ticket.  Support people suggested various titles as well.  These were things like:

* JRUCS Alchemy Fire
* JRUCS Alchemy - Fire
* JRUCS Alchemy Trading Card Game - Fire

That started on July 2.  On July 4 a support person suggested using a "feed file" rather than the web UI.  That would step around the webform AI name validation.  So, I downloaded the "Product Load Form (PLG)" from the Seller Central website.  This was an interesting sort of deja vu.

To list on AWS Marketplace you need to fill out a PLG and load it into Partner Central.  Partner Central and Seller Central are different but similar.  

The AWS and .com PLF are similar as well.  I have a friend who was in AWS Marketplace back at launch.  He said they took the PLF from .com and repurposed it.  That was meant to be a temporary solution.  However, given Amazon's rather lean management strategy, fast forward 15 years and it's still in use.  On the AWS side the form has grown rather complex.  As an example there is a column for every instance type.  At this point AWS EC2 has had 100s of instance types.  So the spreadsheet has columns with three letters now!

.com seems to have taken a different approach to manage the combinatorial explosion.  Different product types have different load forms.  As I struggled to get the processor to take the PLF, a support person suggested a different form.  That was apparently newer than what I had downloaded from the site.  That worked better.

It satisfyed an odd nostalgia to see the underlying PLF from .com that I had heard about for years but never experienced being on the AWS side.

One thing support cautioned me on was not to round trip.  That is, don't upload a PLF, then download the latest, tinker with it and reupload.  That apprently breaks the process.  That tells me something isn't right in the PLF render from Seller Central.

We found other oddities.  One of my tickets got escalated.  So, I could reach people on the phone.  That part was great.  However the escalation meant I could no longer email to reply to a ticket.  Similarly in one view of the escalated ticket the screenshare button went away.

I assume these are all growing pains.  Seller Central is a new portal with a radio button to select the old.  It's amusing in the Partner Central just made a jump to a new portal about a year ago.  So, I assume this was a long due enterprise wide rewrite.

We next got stuck in what I assume was a weird edge case backwater.  Being a cheap and nimble startup, JRUCS hadn't purchased UPCs.  However, Amazon has an in house method, an ASIN.  So I wanted to use that.  In order for that to work I needed a GTIN exception.  I got that.  However, the form would not take the GTIN exception along with the variations.

To work around that, I dropped the variations.  I was then able to submit the form.  That got past the name issue that had started.  At that point I had a Fire and a Water listing under the JRUCS brand.  I was able to use the webform to clean up issues in the PLF and iterate.

Amusingly with two products under JRUCS I was then able to create the Air product without the AI complaining.  My guess is the precedent of the existing products overrode whatever it thought the problem was.  These AI validations are amazing. However, this experience points to a need to override them in certain cases.

So, I had three listings!

* 🜁 - [Air](https://www.amazon.com/dp/B0H9TLC6RP)
* 🜂 - [Fire](https://www.amazon.com/dp/B0H9VDF7QD)
* 🜄 - [Water](https://www.amazon.com/dp/B0H9VN7R6S)

This whole process took daily work from July 2 to July 23.  It was pretty buggy and there is a lot that could be done to improve it.

## Creating a Store

A brand can have a store.  That is managed on a different portal linked from Seller Central.  I went through that wizard and quickly realized that I needed a trademark to make a store.  That makes a certain bit of sense but does create some overhead.

Amazon suggested some services to file the trademark.  However they were all pretty pricey legal offices from what I could tell.  One review mentioned $20k spent with no trademark.

So, I tried to see if I could do it myself.  That meant going to the USPS Trademark website.  I registered as a user.  Pretty quickly I realized that only a lawyer could file a trademark.  This seems to be a case of regulatory capture.  

That then led to Googling trademark firms.  I found one that was in the hundreds of dollars to file and kicked that off.  That process is still pending.

I am excited to get a store at some point.

## Stocking the Product

So, I had the listing.  Next step was to sell.  There are two options.  A seller can fulfill or can use Fulfillment by Amazon (FBA).  FBA seemed like a good bet.  I wouldn't have to pack or ship.  And presumably customers could get product much faster than I would be able to deliver it.  

Amazon charges to ship to them, storage and then for the fulfillment itself.  Hilariously Seller Central admonishes sellers to not show up at a fulfillment center attempting to hand deliver product to Amazon.

For this to work, I needed to ship JRUCS product to an Amazon fulfillment center.  Since the product doesn't have a UPC, I needed to label it myself.  Seller Central happily has a little flow that walks you througuh this and even prints the labels.

I initally looked at buying a thermal label printer (from Amazon!).  A decent one is about $500.  In that I did discover an Amazon refurbished option for $300.  Being a cheapskate I tried printing at FedEx instead.  That cost less than $5.  Unfortunately it was on sticker paper, not individual stickers.  My wife was ultimately able to separate the stickers from their backing paper using cosmetic tweezers.

The result was a box of 30 Fire decks and another of 30 Water.  I printed a UPS label.  Those were then shipped on July 28.  Despite the enormous Kent fulfillment center being rather close by, the packages went across the country to one in Pennsylvannia.

In poking around, I noticed options to spread product across multiple fulfillment centers.  There were even freight options so you could ship from a factory direct to an Amazon fullfillment center using Amazon services.  It's really neat how Amazon is exposing its supply chain to its vendors.

Anyway... the package showed up 8/4.  For some reason the product didn't show as in stock until 8/9.  So it languished in the warehouse for a few days.  At that point both Fire and Water showed in stock.

## More Trademark Fun

On 8/10, I got an email from Amazon telling me to "Address trademark violation to prevent listings deactivation."  I'm not certain but it seems another AI bot had flagged the Fire listing (but not the nearly identical Water one!) for trademark concerns.  What trademark concerns the email did not state.

Initially I thought the concern was related to the JRUCS Brand Qualification Application I'd already completed, so I shared that ticket with support.  We went back and forth for a bit before the ticket was escalated and I had a phone call.  In that I discovered that the issue was actually the word "alchemy."

Checking the USPS trademark search, I saw there are about 900 alchemy trademarks covering everything from cannabis to cosmetics.  Of course, I don't really want an alchemy trademark.  Chatting with Gemini a bit, I uncovered the legal term "descriptive fair use."  That is, the game is about alchemy, a 1000 year old proto science.  The word is being used to describe that.

On 8/13, Amazon reinstated the Fire listing and it showed in stock again.  However, the Water listing was then removed.  One interesting thing is that the process was different.  Fire showed out of stock.  Water just went 404.  Updates in Seller Central were no longer accepted either.  So, I opened a ticket for that.

I'm now waiting on Amazon to decide there.

## Stocking Challenges

When Amazon sent the trademark email they marked Fire as out of stock.  I asked about that.  The support person opened a new ticket that Amazon then responded to.  The text of the email is a bit astounding.  It includes:

"Our research shows that the 30 units are currently in a virtual short container, which indicates the units are physically lost in our fulfillment center. The system will automatically attempt to virtually remove these units within 72-96 hours. If the units are physically located during this time, they will be automatically added back to your available inventory."

About 12 hours later Fire showed back in stock, though the ticket hadn't yet been updated.  This made me thing the packages were found.

## Conclusion

It's been a really heavy lift to get listed.  I started work on 7/2.  It's now 8/13.  If JRUCS were my sole livelihood and I was dependent on Amazon as my main channel, it this would be a disaster.  

The engine Amazon has built is amazing.  But, it seems intended for very large retailers.  I wonder a bit if it makes business sense to invest in better supporting startups.  It's possible Amazon has intentionally left that market to the Etsys and eBays of the world, then cherry picking the companies that rise from that.

I might provide some updates here as the process continues to play out...
