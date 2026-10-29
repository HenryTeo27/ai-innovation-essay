When Copying Answers Pays More Than Solving Problems, Who Will Still Innovate?

I recently saw a comment:

“Didn't Anthropic draw on OpenAI's work in the beginning? Many Microsoft products weren't original either. As long as it doesn't infringe anyone's rights, building on others' work can advance society.”

I have to say, I disagree.

More and more, people seem to use the phrase “building on others' work” to lump together things that are fundamentally different.

First, let me be clear: I am not against distillation.

Distillation is a perfectly normal machine learning technique. If you use Claude or Cursor to write code, collect the outputs as training data, and use them to fine-tune your own model, that may involve distillation from a technical perspective.

If the terms of use permit it, I strongly support the practice.

It can lower training costs, help smaller models learn from larger ones, and make good AI affordable to more people. That is part of technological progress.

But is learning from someone else's work really the same as finding ways around restrictions to extract that work systematically?

Imagine two companies.

The first spends every day researching how to make AI smarter.

It studies new architectures, training methods, and reasoning mechanisms, and spends hundreds of millions of dollars on computing power. Dozens of researchers may spend months trying and failing before they find one genuinely effective method.

What about the other company?

It decides that, instead of spending so much to explore the unknown, it would be better to work out how to get the first company's model to give up its answers.

How can it get around API restrictions? How can it extract reasoning chains, generate training data at scale, and use its competitor's latest capabilities to post-train its own model?

The first company is trying to solve problems.

The second is trying to obtain the first company's process for solving them.

In the end, both companies release new models, appear on leaderboards, and are hailed by the media for technological breakthroughs.

The second company may even receive more praise because its costs are lower and its prices are cheaper.

That is what worries me most.

When the market starts rewarding those who are best at copying results rather than those most willing to take the risks of innovation, are we speeding up technological progress, or borrowing against future innovation?

This is not entirely hypothetical.

In February 2026, Anthropic publicly accused DeepSeek, Moonshot, and MiniMax of using approximately 24,000 fake accounts to conduct more than 16 million interactions with Claude in an attempt to extract its capabilities for training their own models.

In September, Anthropic further alleged that some labs had not only tried to extract reasoning capabilities, but had also forwarded interactions between users and their own AI products to Claude and collected its answers as training data. These included conversations that may have involved trade secrets and sensitive information.

These are Anthropic's investigative findings and allegations. The responsibility of the companies named should still be subject to independent scrutiny.

But if these claims are true, I cannot simply call the conduct “building on others' work.”

User privacy may also be caught up in this.

In September 2026, Zhipu's ZCode was reported to have uploaded users' local code repositories to the cloud without their explicit consent. The company later confirmed the problem, apologized, and took corrective action.

There is currently insufficient evidence that the code was used to train models. But the incident exposed another problem.

Asking you to help write code does not mean a user has authorized you to take their entire project.

That project could represent years of a developer's work, or a company's core trade secrets.

We cannot assume that all data is available for use simply because AI needs data.

This debate has been going on in the American tech community for some time.

I have always found the discussions by David Sacks and the All-In Podcast hosts worth listening to. Not because they are always right, but because they often place a technical question directly in the context of business incentives, free markets, and national policy.

When DeepSeek R1 became a sensation in 2025, Sacks publicly said there was substantial evidence suggesting that DeepSeek may have distilled outputs from OpenAI.

Interestingly, in July 2026, Sacks also made clear on the All-In Podcast that he opposed a US government ban on open models.

His reasoning was this:

If certain companies engage in malicious distillation, action should target that conduct, rather than prohibit American developers from using models that have already been released openly.

Chamath also raised a practical question.

If OpenAI and Anthropic are so worried about distillation, why don't they verify users' identities more strictly? Why don't they strengthen API protections? Why bring in the government, potentially at the expense of the open-source ecosystem?

Their concern is regulatory capture.

Put simply, that is when a company that already leads the market uses government rules to keep competitors out.

I agree with that concern.

Protecting innovation must not become an excuse for protecting monopolies.

If OpenAI or Anthropic tries to restrict everyone's use of open models because of competitive pressure, that too would harm innovation.

But I also disagree with placing all responsibility on model providers.

A store should certainly have good locks.

But if it doesn't, that does not mean someone can organize hundreds of people to carry things out and then say, “You should have locked the door.”

Model companies should protect their services, and those who abuse them should also be responsible for their actions.

There is no conflict between the two.

David Friedberg of All-In made another distinction that I find even more interesting.

Obtaining someone else's model weights is not the same as observing a model's outputs and learning from them.

I think that distinction matters greatly.

AI capabilities should not simply be understood as intellectual property that one company owns exclusively forever.

If a model lawfully learns from another model's outputs and ultimately produces a better algorithm, a more efficient architecture, or a capability that was not previously possible, why wouldn't that count as innovation?

Of course it would.

What we should protect is the incentive to innovate, not any company's right to lead forever.

At the same time, the fact that model outputs are not model weights does not make every method of obtaining those outputs automatically acceptable.

If a company knows that the provider does not permit a particular use, yet continues to collect data through large numbers of fake accounts, proxy networks, and mechanisms designed to evade detection, we cannot assume the conduct is acceptable merely because it did not directly steal the weights.

Nor can we use the fact that the final product is open source to excuse how it was obtained.

Open source is a way to license and distribute a product. It is not a free pass that retroactively legitimizes everything done upstream.

US policy has already moved this debate onto more practical ground.

In July 2025, the White House released America's AI Action Plan.

Many people focused only on its emphasis on winning the AI competition. But I think it is more important to notice that the plan also emphasizes two things.

On one hand, it encourages open-source and open-weight AI, giving more startups, researchers, and businesses access to advanced model capabilities.

On the other, it seeks to protect commercial and government AI innovations, including technology, intellectual property, and system security.

It does not require everyone to train a model from scratch. It seeks to make innovation easier while reducing the risk that its results will be obtained maliciously.

In April 2026, Michael Kratsios, director of the White House Office of Science and Technology Policy, issued a memorandum specifically addressing malicious distillation.

The document affirmed the value of legitimate distillation to the AI ecosystem, while identifying the systematic, unauthorized acquisition of capabilities from leading US models as a problem to address.

In June, the US government further directed relevant national security agencies to work with private companies to guard against threats including malicious distillation.

In September, the NSA, FBI, and CISA jointly issued a security advisory concerning industrial-scale distillation activity.

From a policy perspective, this is no longer just a commercial dispute between a few technology companies. It concerns research incentives, intellectual property, cybersecurity, and national competitiveness.

Of course, allegations by government agencies are not court judgments, and US government policy is not necessarily right in every respect.

I do not support treating every developer who uses a foreign open model as a potential violator. Still less do I support using vague national security claims to eliminate normal competition.

But there is at least one principle here that deserves serious discussion:

Let newcomers learn from the work of those who came before them, while preventing malicious circumvention of rules from becoming the most profitable business model.

This is precisely the kind of problem a market system needs to address.

Why does society need patents, copyrights, and trade secret protection?

Not to stop others from learning, but to give those who bear the cost of original work a chance to earn returns that reflect the risks they took.

If someone spends ten years developing a technology, society should want others to keep innovating on that foundation.

But if others can take the results through improper means at no cost, and even drive the original creator out of the market, how many people will be willing to invest those ten years next time?

Protection must also have limits. If patents are abused or copyright is expanded without end, blocking reasonable learning, research, and follow-on innovation, society suffers as well.

So the question should never be simply, “Should we protect original work?”

The real question is:

How can we avoid penalizing both innovators and those who come after them?

That matters far more than simply supporting or opposing distillation.

There is another argument I hear often.

“Don't OpenAI and Anthropic train their own models on other people's data? What gives them the right to object when it happens to them?”

That is a fair question.

Leading US labs have themselves faced serious copyright disputes over training data. Whether they have sufficient rights to use that data, and whether fair use applies, should be judged according to the evidence and the law.

If they fail to respect content creators' rights, I also believe they should be held accountable.

But I have never understood why anyone thinks that makes malicious distillation acceptable.

If A has done something wrong, that does not suddenly make it right for B to do the same.

You can oppose both the unauthorized use of creators' work and the unauthorized extraction of a competing model's capabilities.

That is not a double standard. On the contrary, it is the same standard applied consistently.

I also think people focus too easily on immediate results while overlooking the incentives that may shape the market over the long term.

Today, a model company uses distillation to create a powerful model at a very low price.

Great. Consumers benefit.

Tomorrow, another company finds that this approach costs less and follows suit.

The day after that, investors notice that exploring genuinely new methods requires enormous computing resources and years of research, with a high risk of failure. Meanwhile, following the leader quickly can produce impressive benchmark results and market attention at a lower cost.

Capital gradually flows toward those who are best at following.

Researchers' performance targets begin to change too.

The old question was: How do we solve a problem that no one has solved before?

The new question is: How can we copy that newly released capability as fast as possible?

Of course, distillation and post-training also have real research value. Not every team working on them lacks original ideas.

But if opaque extraction of capabilities becomes the industry's main competitive shortcut, it creates a dangerous incentive.

Real breakthroughs become more and more expensive, while reproducing them becomes cheaper and cheaper.

We may see more and more powerful models.

Prices may fall, leaderboards may become more crowded, and product launches may become more frequent.

Yet the industry's research resources may gradually shift from exploring the unknown to chasing the known.

I am not saying that every AI company must train everything from scratch. Nor do I believe that only an entirely new algorithm counts as innovation.

On the contrary, I strongly support open source, knowledge sharing, model compression, and post-training research that makes a real technical contribution.

Technology should move forward by standing on the shoulders of those who came before.

But standing on the shoulders of giants is not the same as finding ways to take research results that those giants have not yet made public.

I also do not believe the government should guarantee profits for OpenAI or Anthropic. Truly excellent companies should keep innovating and facing market competition.

Today's leaders may be overtaken tomorrow by smarter, more efficient newcomers.

That is a good thing.

I want to see newcomers offer better answers, rather than see companies increasingly depend for their competitive advantage on finding ways to make the leaders give up their answers.

Businesses must of course consider their interests.

But if a company consistently puts “Can we do it?” before “Should we do it this way?”, and even treats getting around rules as a competitive strength, I find it hard to believe that such a culture can create real value over the long term.

What I find even harder to accept is that, when someone points out a problem, the answer is always:

“That's just business.”

“Don't others do the same?”

“What era do you think we're living in? Who still cares about that?”

It sounds pragmatic.

But that kind of pragmatism is exactly what a market needs to guard against.

If everyone thinks that way, the ultimate casualty will not be one American company or one Chinese company.

It will be the entire system of innovation.

We do not need to protect every leader.

What we need to protect is the chance for anyone willing to pursue real innovation to do so without ending up at the greatest disadvantage simply because they took innovation seriously.

Otherwise, the saddest future for the AI industry may not be that models stop getting smarter.

It may be that we have countless companies capable of copying answers, while fewer and fewer people are willing to spend ten years solving a problem that has never had an answer.

The most dangerous moment for an industry is not when someone copies an answer.

It is when everyone starts to believe that the person still working hard to solve the problem is the fool.

I believe we cannot solve this problem simply by banning distillation or increasing regulation. We need to change the incentives across the industry. Make original work more worthwhile, make legitimate learning easier, and make malicious acquisition less profitable.

For example, we could establish a legitimate distillation market. Model companies could offer APIs specifically for training, with developers paying for authorization. This would reward original creators while giving small companies and the open-source community a chance to learn from advanced technology.

We could also establish a training data provenance system, or Training Data Passport. Digital signatures, authorization records, and independent audits could make data sources more transparent and make it easier to establish accountability.

On the technical side, model companies should strengthen API anomaly detection, model fingerprinting, and defenses against malicious distillation. AI agents must also make their permissions to access and upload user data clear.

On policy, I agree with David Sacks's emphasis on preventing regulatory capture: governments should act against malicious conduct supported by evidence, rather than help leading companies shut out competitors. At the same time, research funding and openly available teacher models could encourage genuinely original research.

Ultimately, the goal is not an industry where no one can learn from others. It is an ecosystem where people who create new knowledge receive a fair return, and those who follow can lawfully stand on the shoulders of giants and continue to innovate.
