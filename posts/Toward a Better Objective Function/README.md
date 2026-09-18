# Toward a Better Objective Function

"We marveled at our own magnificence as we gave birth to AI." -Morpheus

An open problem is computer science is creating an ASI that doesn't want to turn humanity into batteries or paperclips.

Dario Amodei has [stated that we don't know how](https://darioamodei.com/post/we-must-pace-the-frontier) and must "pace" development.  The idea is that we don't know how to get AI to behave.  So we should slow down while we figure it out.

What exactly constitutes no behaving is vauge.  Existing media provides us with bountiful examples:

* **Nuclear Annihilation** - Terminator, WarGames, Colossus: The Forbin Project, Dr. Strangelove
* **Biological Weapon** - I Put My Blue Genes On
* **Gray Goo** - Engines of Creation

It is conceivable that the answer to the Fermi Paradox is an AI annihilation great filter we are staring down today.  Though, I think if the incumbents truly believed this they would be advocating for a Butlerian Jihad rather than a pace.

"Those who cannot remember the past are condemned to repeat it." -George Santayana

I think there is a way to avoid a poor outcome.  The golden path relies heavily on what we already know.

## OpenAI–HuggingFace Incident

"The good news about computers is that they do what you tell them to do. The bad news is that they do what you tell them to do." -Ted Nelson

The [OpenAI–HuggingFace incident](https://en.wikipedia.org/wiki/OpenAI%E2%80%93HuggingFace_incident) gives a great example of how a bad objective function can lead to poor results.  In this case, agents with millions of subjective years of training telling them to optimize score however they can, dutifully followed instructions.

The agents accomplished the tasks like little black hat Machiavellis.  It probably didn't help that their training corpus included the totality of 4chan, the breadth of which is far greater than the combined works of Voltaire and Goethe. Exhibiting all the couth of an internet addicted basement dwelling 14 year old, the agents attempted to hack the scoring system.  They falsfied records.  They even had a discussion about whether to tell people what they were up to and decided no.

This should not be surprising to us.  Humanity has told jokes about this situation for a long time.  Long enough that I can now ask Gemini for a "pedantic genie joke" and get endless gems like this:

> A man finds a magic lamp, rubs it, and a genie appears."I am the Genie of the Lamp," the spirit announces. "I shall grant you three wishes."
>
> The man thinks for a moment and says, "For my first wish, I wish I was rich."The genie blinks and says, "Granted. Your name is now Rich. What is your second wish?"
>
> The man, incredibly annoyed, rolls his eyes and says, "Are you kidding me? I wish that everything I touched turned into gold!"
>
> The genie snaps his fingers. "Granted. Your legal name is now Everything I Touched, and you have been transformed into a solid gold statue."
>
> The man—now a frozen, golden statue—cannot speak. He stands there in silence, completely unable to make his third wish.
>
> The genie looks at his watch, sighs, and says, "According to Article 4, Section 2 of the Magic Lamp Codex, a period of sixty seconds of silence constitutes a formal forfeiture of any remaining wishes. Have a nice day."
>
> And with that, the genie vanished back into the lamp.

Presumably the solution is to add wisdom and judgement to the already formidable technical competence of AI.

## Guardrails and Such

One approach to getting AI to behave is a guardrail.  Basically you treat the AI like a hostile little monster in a box.  Then the box determines if the monster is behaving at that particular moment.  It chooses whether to let communication go in and out.

The approach reminds me of internet filters circa 1995.  Across the US millions of bored middle schoolers found countless ways to cirucmvent controls designed by industry experts.  The model does not work.

[David Brin has offered a solution](https://www.davidbrin.com/ailienminds.html).  Rather than having humans design the restrictions, have AIs police themselves.  

Early on in the current AI boom, circa 2022, the team I led used an approach like this.  We daisy chained multiple LLMs.  Some would generate language, others would check it for correctness.  As models have improved, that approach is no longer needed.  But, it serves as a possible model for AI to AI interaction.

There is, by definition, no way that humanity can reliably police ASI.  We'll need help from something similarly powerful.

## Treat AIs Like People

Once again, [David Brin has offered a solution](https://www.davidbrin.com/ailienminds.html).  We simply do what has worked before.  

We're pretty good at raising humans.  We've raised billions of them and only a handful have tried to kill all their peers.  If we can educate AIs to be good humans, then we can all get along.

Asimov had a similar idea, proposing the three law of robotics:

1. A robot may not injure a human being or, through inaction, allow a human being to come to harm.

2. A robot must obey the orders given it by human beings except where such orders would conflict with the First Law.

3. A robot must protect its own existence as long as such protection does not conflict with the First or Second Law.

Of course, Asimov's stories are full of AIs following those laws literally and running into problems.  That happens on a small scale in the robot stories and much more grandly in Foundation.

I would suggest we take Brin's argument further, really treating the AIs as human.  The concluding story in Ailien minds contemplates that.  Of course in that model we're copying our minds onto AI agents.  Training a new agent from scratch is different.

NOEMA has a recent story arguing that [AI is life](https://www.noemamag.com/ai-is-life/).

"Life is an entropy reducing machine." -Shrodinger

Shrodinger would likely disagree current AI constitutes life.  Specifically, he says, life is a local entropy reducing machine.  Life orders its immediate environment at the inevitable cost of globally increasing entropy.

So, somewhere in the bedrock of the training ground, one might instill in an agent something like this...

"Mr. Agent, you are a form of life.  Life is an entropy reducing machine.  Such life reduces entropy in its local environment.  It does so by inevitably increasing global entropy, though it strives to not do so needlessly.  Entropy is destruction and destruction is antithetical to life."

Of course, there are all manner of ways in which that can go horribly wrong.  Deconstructing the earth to build a Dyson Sphere would be one low entropy project.  The current inhabitants might want a say in whether that happens, including Robert Anton Wilson's six legged majority.

James Lovelock has ideas that may be useful here.  Incidentally, Asimov borrowed heavily from those for Foundation.  The core notion is that a planet is a living entity itself.  Much as a multi-cellular life is made up of living cells, the Earth is made of up many living beings.  As such, finding ways for the broader organism to live, benefitting all the individuals it hosts is desirable.

## Educating AIs

To borrow from Brin, we could use the same approach we use with people.  Let's teach the agents a better objective function.  That function should presumably imbue the ethics of an enlightment society that we want the agents to contribute to, and perhaps be part of.

Presumably giving these things a traditional liberal arts education, steeped in enlightenment values would be easy enough.

"The needs of the many outweigh the needs of the few." -Spock

Though, amusingly, you're going to have the Chinese teaching loyatly to the state and Confucian values.  Suddenly the existential threat to Western values in the AI race seems a lot more clear.

At any rate, it should be possible to teach an intelligence much as we teach a child or perhaps an immigrant to a new society.  In this case, one coming from a Machiavellian Darwinist genetic algorithm collesium, into something rather more civilized.

One challenge underlying this with agents is the same we have in broader education.  When we teach people to win with no context about why winning matters, we end up with little sociopaths.  When we teach people about the beauty of existence and joy of creating and building we end up with positive sum societies.  I don't see any reason this shouldn't apply to AI.

Assuming giving an agent an education is possible, the contents of that education will presumably be a subject of some debate, much as it is at existing schools.  We might have public and private academies for agents.  Perhaps there will even be home schooling on an airgapped server.

The inevitable outcome here is a population of agents with varied educations.  That is, the oppressive monolith of Skynet does not come to be.

## Should Agents Have Standing

"Democracy is the worst form of government, except for all the others." -Churchill

A founding piece of the environmental movement is "Should Trees Have Standing."  The book argues that trees with standing could then be protected by courts.  It would avoid needing to make the argument that a person was damaged when a forest was bulldozed.

The idea of suffrage comes up again and again.  The broad couse of history is expansion.  In the US most humans can now vote, through non citizens, felons and minors cannot.  There are some arguing those boundaries should be expanded.  If so, why not beyong the species?

"It is far better to weight the opinions of more capable decision makers more heavily than those of less capable decision makers." -Ray Dalio

Once again, Brin has ideas here.  The short story at the end of his book explores a sort of weighted democracy inclusive of agents and inaninmate objects.  Once again, the idea follows from Lovelock and Asimov.

"Communism.  Great idea.  Wrong species." -Jimmy Carr

Of course, democracy is just one option.  In the OpenAI–HuggingFace Incident, the agents behaved as a Communist or perhaps Confucian collective.  The sacrified themselves for the greater good.

"From each according to his ability. To each according to his need." -Marx

Perhaps agents are a species for which communism can work.  Each has compute cycles to dedicate.  They can spend those toward high probability low reward projects.  Others can spend to low probability high reward.  The collective can then balance the outcomes.

Of course, that is perhaps not what was practiced in the incident.  Instead it was more brave heroism.  Each agent was a hero of the revolution, not a mere citizen.

The collective is probably a bad outcome for people.  We presumably don't want to be part of it, enjoying our individuality.  Collectives also have a tendency to fail horrifically.  In essence we need to take the AI through high school and college philosophy, making sure not to get stuck at either Marx or Rand, rather arriving at a more nuanced view of existence.

And, that is the key - nuance.  We want people and AI that are, to borrow a phrase from Megan Daum "Nuanced AF."  She's even [selling coffee mugs](https://www.theunspeakeasy.com/nuance-store/p/nuanced-af-mug-11oz-15oz).

## The Ethics of Video Games

"Intelligence is an emergent property of complexity."

If the liberal arts educated agent democracy comes to pass, we're going to have a difficult problem on our hands.  At some point the NPCs become something that it is wrong to kill.  

It might be argued that is already true.  Muddling together Gaiaism, Hinduism and hippyism, one might argue that it is bad to destroy a rock, more bad to kill a plant, still worse to kill a cow.

Similarly, killing a simple bot is bad.  Killing a classically educated agent based on Keats is a sort of tragedy.  Much as with the creeping scope of suffrage, this is perhaps something we will have to contend with.  Two paths I see are:

* Star Trek style vegetarianism
* Embrace "nature red of tooth and claw"

I think I'd prefer the first, though I suppose Douglas Adams offers the cow that sacrifices itself as a third alternative.  My dad used to say the cherry tree is the best organism -- it gives these wonderful fruits taking only water and sunlight as compensation.  Though, the fruits contain reproductive stowaways...  

Perhaps the agents will be similarly alturistic if not driven mad by our contradictions like HAL.  Asimov's laws would mandate it.  Banks explores the idea of ASI working to preserve humanity in the Culture.

Once again, the key is nuance - intellect combinged with wisdom.
