# The Fork in the Road: How LibreOffice Was Born from a Crisis of Trust

**Course:** Open Source Software (NGMC)
**Type:** Individual Case Study
**Max Marks:** 100

| | |
|---|---|
| **Student Name** | Shreyash |
| **Registration Number** | *(fill in your reg number)* |
| **Date of Submission** | *(fill in date)* |

---

## Section A: Establish the Context

### What happened and why it mattered

OK so here's the short version of what went down.

There was this office suite called OpenOffice.org. Sun Microsystems had open-sourced it back in 2000, and over the next decade it became the go-to free alternative to Microsoft Office. Millions of people used it. Governments adopted it. A large community of volunteers contributed code, translations, documentation, bug fixes. On the surface it looked like a textbook open-source success story.

But there was a problem underneath that most regular users never saw. Sun controlled the project in ways that made a lot of contributors uncomfortable. The biggest issue was something called copyright assignment. If you wanted to contribute code to OpenOffice.org, you had to sign a legal agreement giving Sun joint ownership of whatever you wrote. So you'd spend your weekends fixing bugs or adding features, and at the end of it, Sun owned the legal rights to your work alongside you. On top of that, Sun employees controlled the release schedule, decided which features got in, and could veto community proposals. The community could suggest things, but Sun had final say on basically everything.

Why did people put up with it? Because Sun was mostly OK about it. They weren't perfect, but they weren't actively hostile either. So contributors grumbled but stayed.

Then Oracle bought Sun in 2010. And that changed everything.

### Why Oracle was the trigger

Oracle is a very different company from Sun. Sun had a messy but real relationship with the open-source world. They open-sourced Java, they open-sourced OpenOffice, they contributed to various projects. Oracle is primarily an enterprise database company. They make money from big contracts, and they're known for being aggressive about intellectual property.

When Oracle took over, the copyright assignment thing suddenly felt a lot scarier. Under Sun, signing over your code rights felt uncomfortable but not dangerous. Under Oracle, the same agreement felt like handing your work to a company that might use those rights against the community. And Oracle gave people reasons to worry. They launched a commercial version of OpenOffice (basically selling the community's work), they stopped communicating with contributors, and they sued Google over Java. That lawsuit had nothing to do with OpenOffice directly, but it showed contributors what kind of company was now holding rights to their code.

The governance problem hadn't changed. The copyright assignment hadn't changed. But the company holding the power had changed, and that was enough to make people decide they'd had enough.

### Legal openness vs practical openness

This is the part I found really interesting when I was reading about this. OpenOffice.org had an open-source license. The LGPL. That means anyone could read the code, copy it, modify it, redistribute it. All four freedoms were technically there. Legally, the project was open.

But practically? It wasn't. One company decided what got released and when. One company owned the copyright. One company could veto any community decision. The code was open but the project wasn't. The community had the legal freedom to fork at any time, but actually doing it meant losing years of infrastructure, splitting the user base, and starting over. Legal freedom and practical freedom are not the same thing, and I think this story makes that really clear.

The interesting question is whether the fork was inevitable from the start. I think it was. Any time you have a setup where one entity controls an open-source project that heavily, you're basically one bad corporate decision away from a crisis. Sun just happened to be benign enough that the crisis didn't happen on their watch. Oracle wasn't.

---

## Section B: The Ethics of Corporate Control

### My position

I'm going to argue that Sun's level of control was understandable but not ethical, and Oracle's continuation of that control was worse. Companies can participate in open source, fund open source, even lead open-source projects. But the kind of control that Sun and Oracle had over OpenOffice.org crossed a line.

### The case for corporate control

I want to be fair to the other side first because the argument isn't stupid.

Running an open-source project costs real money. You need servers, build infrastructure, legal support, project management. Someone has to coordinate releases, handle security disclosures, deal with trademark issues. Sun paid for all of that. They also employed full-time developers who worked on OpenOffice.org as their day job. Without Sun's investment, the project probably wouldn't have existed in the form it did.

So when Sun said "we want governance authority in exchange for all this investment," that's not an unreasonable thing to ask. Companies aren't charities. If you're spending millions of rupees a year on a project, wanting some control over its direction makes basic business sense. If every community decision could override corporate strategy, it would be hard for any company to justify the investment.

There's also a practical argument. Having a single decision-maker can be more efficient than community consensus. Open-source governance by committee can be slow and indecisive. Sun could make a decision and move on. There's something to be said for that.

### Why I still think it was wrong

But here's where that argument falls apart for me.

The code wasn't written primarily by Sun employees. The community contributed a massive amount of work. Translations, bug fixes, testing, documentation, features. These were volunteers who spent their personal time making OpenOffice.org better. They weren't getting paid. They were contributing because they believed in the project and in open source.

The copyright assignment clause turned that voluntary contribution into a corporate asset. When you sign over joint copyright, the company can do things with your code that you might not agree with. They can relicense it. They can use it in proprietary products. They can sell it to someone else. And that's exactly what happened. Sun's rights got transferred to Oracle through the acquisition, and suddenly a company the contributors had never agreed to work for owned joint copyright on their code.

I think there's a meaningful difference between a company that says "we'll sponsor this project, provide infrastructure, and contribute developers" and a company that says "we'll do all that, but we also get to own your code." The first is sponsorship. The second is appropriation, even if it's legal.

The stewardship vs ownership distinction matters here. A steward takes care of something on behalf of others. An owner does whatever they want with it. Sun acted more like an owner than a steward, and when ownership transferred to Oracle, the community paid the price for that. A genuine steward wouldn't require copyright assignment. They'd contribute to the project on equal terms with everyone else.

### Was it different for Sun vs Oracle?

Yes, I think it was. Not because the legal arrangement was different, but because intent matters.

Sun open-sourced StarOffice partly to compete with Microsoft, sure. But they also seemed to genuinely want a thriving open-source project. They employed developers who cared about the community. They made real contributions. Their control was heavy-handed, but it came from a company that was at least trying to participate in good faith.

Oracle didn't care about any of that. They saw OpenOffice.org as a revenue source, not a community project. The copyright assignment clause, which was already ethically questionable under Sun, became actively dangerous under Oracle. The exact same legal agreement meant very different things depending on who was on the other side of it.

This is why copyright assignment is such a problem. It's not just about who holds the rights today. It's about who might hold them tomorrow. When contributors signed those agreements with Sun, nobody was thinking about what would happen if Sun got acquired by a company with a completely different attitude toward open source. But that's exactly what happened, and the community had no protection against it.

---

## Section C: The Forking Question

### Was forking the right call?

I think yes. But I want to work through why, because it wasn't an obvious decision at the time.

The other options the community had were basically: negotiate with Oracle, do nothing and hope for the best, or fork. Negotiating was tried. The Document Foundation actually invited Oracle to donate the OpenOffice.org brand and join the new governance structure. Oracle said no. So that path was closed.

Doing nothing was an option, but it was a bad one. Oracle had already shown what kind of steward it was going to be. It was selling the community's work commercially, communicating poorly, and holding legal rights that it could use aggressively at any time. Waiting around for Oracle to change its behavior would have been wishful thinking.

Forking was the only option that actually gave the community control over its own future. Yes it was expensive. Yes it fragmented things. But sometimes the expensive option is the right one.

### Was Oracle's decision rational?

From a pure business perspective, Oracle's refusal to donate the brand made sense. OpenOffice.org had millions of users. It had brand recognition. Giving that away to a foundation that Oracle didn't control would have been giving up a commercial asset for nothing in return (from Oracle's perspective).

But from an ethical perspective, I think it was wrong. Oracle was holding onto a brand that the community had built. The code, the translations, the documentation, the reputation — most of that came from volunteers, not from Oracle. Refusing to hand over the brand was essentially saying "your work belongs to us and we'll decide what happens with it."

And from a strategic perspective, it turned out to be dumb. Oracle ended up donating OpenOffice.org to Apache a year later anyway, after the community had already moved to LibreOffice and taken most of the users and developers with them. If they'd joined the Document Foundation early on, they could have had a seat at the table. Instead they ended up with nothing.

### The cost of forking

This is the part where I have to be honest about the downsides. Forking wasn't free.

For years after the split, organizations and regular users were confused. OpenOffice or LibreOffice? Which one do I install? Which one is still getting updates? IT departments had to make choices without clear information. Linux distros had to pick a side. Development effort was split. Some contributors stayed with OpenOffice at Apache. The community was fragmented.

That confusion had real costs. People who just wanted a free office suite didn't care about governance disputes. They just wanted their word processor to work.

But here's the thing. The confusion was temporary. By 2013 or so, it was clear that LibreOffice had won. It had more developers, more features, faster releases, and it was the default on every major Linux distribution. The pain of the fork was front-loaded. The benefits — independent governance, no copyright assignment, faster development — have lasted over a decade now.

Was it worth it? Looking at where LibreOffice is today compared to Apache OpenOffice (which has barely released anything in years), yeah. It was worth it.

### The strongest argument against forking

If I had to argue against the fork, I'd say this: the community should have stayed and fought from within. Oracle wasn't going to maintain OpenOffice.org forever. Eventually they would have either improved governance or abandoned the project (which they essentially did by donating it to Apache). By forking, the community created years of confusion and wasted effort on rebuilding infrastructure that already existed.

I don't find this argument convincing though. "Wait and hope the corporation loses interest" isn't a strategy. The community had no guarantee Oracle would let go, and in the meantime Oracle held copyright on all their contributions and could have done anything with those rights. The risk of staying was higher than the cost of leaving.

---

## Section D: Lessons and Generalisation

### What the double fork tells us

The fact that both LibreOffice and MariaDB forked from Oracle-owned projects in almost the same time period isn't a coincidence. It tells you something about the relationship between corporate ownership and open-source health.

When Sun owned both projects, the communities were unhappy but functional. When Oracle took over, both communities concluded within months that they couldn't trust the new owner and needed to leave. Same company, same pattern, same result, two different projects.

I think the takeaway is this: open-source communities can tolerate imperfect governance if they trust the people in charge. The moment that trust is gone, the whole thing falls apart. And trust isn't something you can transfer in an acquisition. Sun spent years building (imperfect) trust with these communities. Oracle inherited the legal rights but not the relationship. The communities didn't owe Oracle anything.

It also shows that corporate acquisitions are one of the biggest risks to open-source projects. A project can have healthy governance for ten years, and then one merger or acquisition changes everything overnight. Any project that depends on a single corporate sponsor is vulnerable to this. It doesn't even require the new owners to be malicious. They just have to have different priorities.

### The Company X scenario

The question asks about a large cloud company that contributes most of the code to an open-source project, controls governance, and uses the project to attract customers.

This isn't hypothetical. This is basically what happens with a lot of cloud-era open source. Companies like Elastic, MongoDB, and Redis have all had conflicts where the company that created the project changed the license or restricted access because they felt cloud providers (mainly Amazon) were profiting from their work without contributing back.

Is this different from the Oracle/OpenOffice situation? In some ways yes. If Company X actually wrote most of the code, their claim to governance is stronger than Oracle's (which inherited rights to code written by volunteers). Creating something is different from acquiring rights to something others created.

But the core problem is the same: a single entity controls an open-source project, and the community is one corporate decision away from losing access or control. The fact that Company X wrote the code doesn't mean the community that uses it, builds on it, reports bugs, writes documentation, and evangelizes it hasn't also contributed something valuable that they stand to lose.

Here's the criteria I'd use to decide if a corporate steward can be trusted:

1. **Do they require copyright assignment?** If yes, that's a red flag. Contributors should own their own work.
2. **Is governance open?** Can non-employees participate in decisions? Is there an elected steering committee or is it all internal?
3. **Do they have a track record of respecting the community?** How do they handle disagreements? Do they communicate transparently?
4. **Is there a plan for what happens if the company gets acquired?** If the governance model doesn't survive a change of ownership, it's not really a governance model.

### My recommended governance structure

If I were advising a new open-source project, here's what I'd suggest:

**On copyright:** No copyright assignment. Ever. Contributors keep ownership of their code. If the project needs a legal entity to hold trademarks or defend against lawsuits, use a Contributor License Agreement (CLA) that grants limited rights for distribution, not full copyright transfer.

**On corporate participation:** Welcome corporate contributions, but cap corporate representation on any governing body. The Document Foundation's rule — no single company can control more than one third of the board — is a good model. Companies can contribute developers, funding, and infrastructure without getting to run the show.

**On decision-making:** Use an elected steering committee with term limits. Major decisions (license changes, governance changes, trademark transfers) should require a supermajority vote. Day-to-day technical decisions can be made by maintainers, but structural decisions need community consensus.

**On succession planning:** Write a charter that explicitly addresses what happens if the project's main sponsor gets acquired, goes bankrupt, or loses interest. The charter should make clear that control stays with the community regardless of what happens to any individual company.

None of this is rocket science. The Document Foundation figured most of it out in 2010. The fact that projects are still making the same mistakes Sun made tells me people don't learn this stuff until they get burned.

---

## Section E: Reflection

Before reading about this case, I thought "open source" basically just meant "the code is public and free to use." Like, if you can see the code on GitHub and there's an open license, it's open source, job done. I didn't think much about who controls the project or what governance looks like behind the scenes.

This case study changed that for me. Finding out that OpenOffice.org was technically open source but effectively controlled by a single corporation was surprising. Everything about the code was open, but the project itself wasn't. The license gave people freedom, but the governance structure took it away. I hadn't thought about those as separate things before, and now I can't stop noticing examples of the same pattern everywhere.

The part that bothered me most was the copyright assignment thing. People contributed their time and skills freely, and Sun turned around and said "we own that now." And then when Oracle bought Sun, all those contributions ended up in the hands of a company that actively worked against the community's interests. Contributors had no say in that transfer. I don't think that's fair, even if it was technically legal.

Would I have made the same choice as the LibreOffice founders? I'd like to think so, but honestly I'm not sure. Forking meant giving up years of work, a known brand name, existing infrastructure, and a large user base. Starting over takes guts, especially when you don't know if people will follow you. The fact that it worked out doesn't mean it was an easy decision.

But I think it was the right one. You can't build something meaningful if you don't control it. The LibreOffice community chose ownership of their project over the convenience of an existing institution, and ten years later they have a product used by 200 million people, governed by an independent foundation that no company can take over. That's worth the pain of starting fresh.

If there's one thing I'm taking away from this, it's that the license is only half the story. The other half is who gets to make the decisions. And if you don't pay attention to that second half, you can end up with "open source" software that isn't really open at all.
