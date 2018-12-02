# Soul of wit is a tool for writing better.

Take a minute to paste in your prompt--the title of your story, the comment you're responding to, the subject of the email you're about to write.

Think about your audience. Then, begin.

As you type, soul of wit highlights tired cliches, turgid diction, unnecesary jargon, and other crap.

> Writing meant to convince will be twice as effective if it can be made half as long. -pg


## Example

### Before

> `In our time it is broadly true that` political writing is bad writing.
> Where it is not true, `it will generally be found` that the writer is some kind of rebel, expressing his private opinions and not a ‘party line’.
> Orthodoxy, of whatever colour, seems to demand a lifeless, imitative style.†

### After

> Most political writing is bad writing.
> When it's not bad, it's often the work of some kind of rebel, expressing their private opinions and not a 'party line'.
> Orthodoxy, of whatever color, seems to demand a lifeless, imitative style.

† This example is from *Politics and the English Language* by Orwell. The essay is fantastic and part of my inspiration for making this tool. It's a catalog of the ways in which people lard their language--trying to sound smart, trying to hide bad arguments, or simply out of habit. It's a concise guide to better writing. Ironically, George Orwell makes a few of the mistakes he describes. "In our time it is broadly true that..." is a doozy.


## How does it work

Big Data™, stats, and our own judgement.

We extracted common phrases from the full text of English Wikipedia. We added open access scientific papers, plus the Enron dataset--half a million emails, full of fatuous corporate-speak, made public during a government investigation. This gave us canned phrases characteristic of bad English: "just to circle back", "buy-in from all stakeholders", "it is generally accepted that", "left as an exercise for the reader".

Part manually and part mathematically, we separated the bad from the merely common. Finally, we wrote a minimal web app to highlight as you type.

This is a tool, not a service. It's free and open source. Nothing is sent to a server. Your text stays on your computer, and the highlighting algorithm runs in your browser.
