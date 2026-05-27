# AI Is More Useful to Experienced Developers Than People Think

I’ve been writing software for around 30 years now, and one thing I’ve noticed is that developers tend to define themselves by whatever stack they happen to be working in at the moment.

I’ve been asked a million times what stack I work in, and I get why people ask. It’s a useful shorthand. But I’ve never really thought of myself as a C# developer, or a PHP developer, or a ServiceNow developer, or whatever label happens to fit the current project.

Over the years I’ve worked in Lotus Notes/Domino, Vignette StoryServer with Tcl , PHP/MySQL, ASP.NET/C#, SQL Server, Oracle-backed systems, ServiceNow, Grav CMS, and a bunch of internal applications nobody outside a company would ever recognize. Some of those technologies are still around. Some probably shouldn’t be.

The point is, I don’t remember every framework I’ve ever touched in detail, and I don’t think that’s actually the valuable part of experience anyway. What sticks with me are the patterns.

After a while, you start seeing the same problems show up in different forms. A workflow gets awkward. A maintenance decision comes back to haunt someone. A screen makes perfect sense to the developer who built it, but not to the person who has to use it all day. The technology changes, but a lot of the underlying problems are familiar.

That’s where AI has become genuinely useful for me. I don’t see it as a replacement for engineering knowledge. I think it works best when there’s already enough experience behind it to ask better questions and recognize better answers.

A good example is the website work I’ve been doing for my own science fiction novel, including web-based puzzles that tie back to clues hidden in the story. I used XAMPP and Grav CMS, neither of which I had worked with before. Grav uses a flat-file structure, Twig templates, theme inheritance, modular content, and a very different setup than the database-backed systems I have spent most of my career in.

Before using AI, ramping up on that probably would have meant a lot more trial and error, digging through documentation, reading Stack Overflow posts from 2012, and spending two hours figuring out why one tiny thing refused to render correctly.

Now AI can help shorten that process quite a bit.

It helped explain how Grav organizes content and routing. It helped relate Twig concepts to things I already understood from Razor and MVC work. It helped me troubleshoot session handling and think through restricted-access logic for some puzzle-related site features. What it did not do was make the actual decisions.

I still had to figure out whether the structure made sense long-term. I still had to test the behavior myself. I still had to decide where logic belonged, what was maintainable, and what would turn into a future headache. AI can suggest five ways to solve a problem, but experience is what lets you recognize when three of them are technically correct and still bad ideas.

That’s the part I think gets missed in a lot of AI discussions and anti-AI rhetoric. There’s a version of the conversation where detractors talk about AI like it either replaces developers entirely or has no value at all. I don’t think either position matches reality very well.

What AI is very good at is helping reduce ramp-up time in unfamiliar environments. It acts a little like an interactive translator between technologies. You can ask questions in terms you already understand and get answers mapped into the framework you’re currently learning.

For experienced developers, that’s powerful because most of us already have a mental library of architecture patterns, workflow problems, debugging habits, UX mistakes, and maintenance scars. The issue usually isn’t “can I understand this system?” The issue is how long it takes to become productive in it. AI helps compress that timeline.

I think that’s especially true for people like me who are more tool-agnostic by nature. I’ve spent most of my career building internal tools and workflow systems. Those environments change constantly. Sometimes you inherit a clean modern stack. Sometimes you inherit a fragile internal application held together with old documentation and institutional memory.  Sometimes you have to modernize a Microsoft Access-based application--yikes!

A lot of development work comes down to finding the part of the process that keeps slowing people down, then building something practical enough that they do not have to keep fighting it every day.

That pattern goes back further than my software career, actually. When I was in the Navy aboard USS Sacramento, I built a Quattro Pro-based tool to automate fuel tank calculations used during underway replenishment planning. Before that, those hog-and-sag calculations could take roughly six hours. The tool cut that down to something closer to 15 minutes.

The technology was different, but the work felt familiar: someone had a painful manual process, and I understood the workflow well enough to build a practical tool around it. To this day, that is the kind of software work I enjoy most.

AI hasn't changed that. It's just made it easier to get oriented when the surrounding technology is unfamiliar.

And to be clear, I’m not talking about blindly pasting generated code into production and hoping for the best. I’m also not talking about replacing junior developers. A junior developer still needs the chance to develop judgment, troubleshooting skills, and an understanding of how systems behave in the real world.

What AI does well is help experienced people move through the “I haven’t seen this exact framework before” phase faster than we used to. You still need judgment. You still need to think about architecture, UX, maintainability, and whether the thing will still make sense six months from now when somebody else has to touch it.

That’s the part I try to keep in mind, especially with internal tools. The demo is the easy part. The real test comes later, when someone has to use it every day, trust the output, work around its rough edges, and eventually ask for one more “small” change.

At that point, nobody cares how clever the original solution was. They care whether it helps them do their job without making the rest of their day worse.
