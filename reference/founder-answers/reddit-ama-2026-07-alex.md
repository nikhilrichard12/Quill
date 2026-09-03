# Founder answers: I'm one of the founders of a new AI startup, Littlebird. We're building an AI that remembers everything you work on so you don't have to catch it up. Here to chat about how we built it and where we're taking it. AMA!

Source: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/
Thread posted: 2026-07-14 by u/Littlebird_Shivi. Transcript generated 2026-09-03 by Magpie from the thread's RSS feed (244 entries in the feed at fetch time).

What this is: every answer in the thread from a Littlebird founder or a Littlebird_* team account, in the order it was posted, with a permalink and date on each. Provenance for the Bible is FOUNDER-STATED (a dated public statement with a permalink); team-account answers are labelled as such and carry the same tier only where the Bible has adopted them. Questions are not reproduced (the feed does not link comments to parents); most answers restate them.

Answer counts: u/Littlebird_Alex 56, u/YardLeast3268 16, u/Weak_Ad3685 2, u/Littlebird_Shivi 2, u/Littlebird_Michael 1, u/Littlebird_Deep 1.

## Opening post

u/Littlebird_Shivi, 2026-07-14, https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/

Hello Reddit, I'm Alex, co-founder at Littlebird AI. We just raised $11M to build what we call a "full-context" AI, and I want to be an open book about how we got here. Ask me anything.

 It started from a simple frustration: AI models are brilliant, but they have no idea what you're working on. So you end up spending ten minutes copy-pasting Slack threads, docs, and emails into a chat window just to get a useful answer. The intelligence was never the bottleneck. Context was.

 So we built an assistant that already has it. Littlebird AI learns from what's on your screen and sits in on your meetings, so it takes notes, remembers your work, manages your to-dos, and takes action across your apps (Gmail, Calendar, Drive, Notion, Todoist, etc.) without you catching it up first - it works across Mac, Windows, iOS, and Android.

 Because an AI with that much access lives or dies on trust, the privacy model came first. It stores text, not screenshots. Your data is never sold or used to train models. You can pause it, exclude any app or site, and delete your data anytime.

 Happy to go deep on any of it - the app itself, how we think about trust and access, why we store text instead of screenshots, or what changes when your AI has full context instead of starting from zero every time.

 Alright, that's my intro. Fire away - I'll do my best to give you answers worth reading.

  [Edit: Thanks everyone for joining and asking such thoughtful questions! That's a wrap on this AMA.

 Really appreciate everyone who took the time to learn more about Littlebird, our vision for full-context AI, and where we're headed next. We'll keep an eye on the thread and follow up on any remaining questions when we can.

 Thanks again to everyone who participated and made this conversation so great! We'll be doing more AMAs like this in the future, so we hope to see you back for the next one.]

## Answers, chronological

### 1. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oxzz615/

this is the case with claude, chatgpt, granola, gemini, even gmail itself which stores data sent by other people. this data is shared with you, it's still yours, it's not ours! we're just stewards of your data and you can delete or download it all any time and take it with you.

### 2. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy003jy/

on android yes, on IOS it's tricky! apple doesn't really allow it

### 3. Alex (co-founder), u/Weak_Ad3685 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy432rt/

hey sorry to hear that, we were losing a lot of money per user before, we're constantly working hard to provide more usage and delivering a cost efficient product, you should see more improvements to limits soon

### 4. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy47soo/

hey, we're working on moving inference to more cost efficient models as they come out, and optimizing them to perform well in the product. Littlebird is very expensive to run and we were losing lots of money per customer for a long time, as we grow that becomes unsustainable. We currently only *break even* per customer so I can promise you we're not being stingy with usage!

 The good news is that amazing and more cost efficient models are coming out so we should see more intelligence and more usage over the coming weeks and months

### 5. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy480bx/

we already integrate with CRMS! our customer success lead uses it all the time to update our CRM. which one(s) do you need that we don't integrate with yet?

### 6. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy496xb/

for sure. we'll need to raise more. for large enterprise customers we will offer on prem deployments later this year

### 7. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy49njz/

Completely eliminating all hallucinations is really difficult for any LLM product. We're also working hard on trying to fix the temporal invalidation problem you mentioned, but this is actually an unsolved research problem. Basically, the agents aren't smart enough to know whether some colleague that you used to work with quit or whether this project is complete, etc. We're doing fundamental AI research into this problem, and we have some exciting developments that should improve the experience, especially for power and pro users, soon. It's called the "personal world model" and it dynamically updates a graph about your life to try and prevent old / stale facts from entering the chat

### 8. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy49yey/

We use lots of different AI models, and we're constantly optimizing this to try to deliver the best experience for you guys. Due to how fast the AI landscape is changing, the models change. Hopefully, over time, part of the value we can provide is delivering the best overall AI user experience to you guys for the lowest possible cost. That's what I see our job is. Since we're not like OpenAI or Claude, married to our own models, we're happy to serve whatever models perform best for the lowest cost. We will continue to try to do that. We still, of course, have a long way to go here, but expect continuous improvements in intelligence and price.

### 9. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4a55s/

Yes, very shortly. In fact, we already have calendar access, so I'm not sure what it's missing there. Can you let us know if there's some calendar functionality that we can't do that you want, because it really should be able to do more or less anything there. As far as file system access, it will have that in the next few weeks.

### 10. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4amjc/

Yep, we'll be shipping support for local MCPs very soon, in the next few weeks, so you'll be able to do this as a first-class citizen.

### 11. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4cmbe/

yep we're working on that as we speak. Taking actions for you on the internet definitely would come with some risk of prompt injection so we would do a lot of security testing before launching anything that came with PII leakage risk. that being said, the models are definitely getting better at defense so i'm fairly optimistic it will be safe for many use cases

### 12. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4cqmf/

we'll look into this, can you downvote the bad chats and file an in-app support request?

### 13. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4hslj/

everything that's not excluded for privacy reasons gets put into a vectordb (turbopuffer https://turbopuffer.com/ (https://turbopuffer.com/)) which is the same one that cursor and notion use, it's all stored on hardened AWS server. There are various reasons we do this. One of them is so that your data is available to you across devices. The other reason is that it's actually easier to keep your data secure on a hardened enterprise-grade server than it is on device.

### 14. Littlebird team, u/Littlebird_Shivi, 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4htwe/

Hi! There isn't a Zoom call for this AMA. This Reddit thread is the place to be.

 We're hoping to host a live webinar in the future, and if we do, we'll be sure to email everyone with the details. We'd love to have you join us here for the AMA.

### 15. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4i7wu/

Noted. I think we already have something like this, but maybe we need to do better in terms of showing it. have you checked in settings?

### 16. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4iii2/

fair we're planning on doing an inbox / notification center and will consider prioritizing it based on your feedback!

### 17. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4ivd1/

For sure, this has always been the exact goal. In fact, memory is the easiest part of the product to explain, but the goal is to build a true extension of your mind that is the most powerful problem-solving AI product on the market across your entire life.

### 18. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4j5b4/

So many, hard to know where to start. Facts no longer being true or relevant is really tricky, and there's just a lot more engineering that goes into building a good LLM agent than I would have expected. Finally, just even getting good data to start with and maintaining that data pipeline so that we get high-quality data end to end that preserves semantic information like who said what when is a lot of work.

### 19. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4ja17/

You will be able to download it (you can now!!) and we'll delete it.

### 20. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4jbyf/

This is a product failing, and we will fix this. Have you looked at the Usage tab in Settings?

### 21. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4jhza/

Yeah, sorry, we sort of de-prioritized this, but we'll try to revamp it. We have a lot of features we're cooking!!

### 22. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4jnl2/

It sort of consistently evolves rather than being one static idea, and there's a lot of intuition involved... I tend to trust my gut and figure out as we go.

### 23. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4jtlz/

I think the models available to us continue to deliver increased intelligence at lower cost, and we are going to pass all of that on to you guys. Also, of course, we will raise more.

### 24. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4jxrx/

Have you applied on gem? send an email to [talent@littlebird.ai (mailto:talent@littlebird.ai)](mailto:talent@littlebird.ai (mailto:talent@littlebird.ai))

### 25. Littlebird team, u/Littlebird_Michael, 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4k7rr/

We have an affiliate program, you should apply! https://partners.dub.co/littlebird (https://partners.dub.co/littlebird)

### 26. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4kgn9/

Well, it's not only privacy. It's also because text is primarily what matters, and images are a lot more expensive to store and heavy weight, and I think they have less relevant information in general.

 Our PII filters are not PERFECT, and it's absolutely possible that we could inadvertently capture an api key, but it's rare. Also, for what it's worth, I'm one of the founders, and all of my personal data is also sitting on our servers. We take security very seriously and do everything possible to keep the data secure. I don't think that there is anything uniquely risky about Littlebird versus, say, your Gmail getting hacked, which is honestly a lot more likely of a practical risk.

### 27. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4kun0/

We're fortunate in that one of the founders was able to provide us capital to get started. The bar for raising external funding keeps going up, so now I think it's definitely easier to raise if you already have some traction, especially if you are outside of Silicon Valley. That being said, I would definitely advise you to cold email and cold pitch people, as well as trying to get warm intros to investors. Basically, get capital by any means necessary. Get creative, be bold, be proactive.

### 28. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4kz7b/

Lots of human expertise. I do not trust LLMs as judges of outputs. We do tons of evals, both human and human-written evals that we then run on models.

### 29. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4ljlf/

I can assure you that your debit card info was certainly not leaked from Littlebird. If we had any security incidents, we would notify all of our users, but we have had zero security incidents thus far.

 I don't think it's spyware, and I don't think it's really that different than many other products that are widely used. Granola takes meeting notes from meetings. ChatGPT can plug into your email and Slack and all sorts of things where it has access to all sorts of data. There is nothing truly unique about data from screen. For instance, in iMessage, you can also get that into Claude or ChatGPT through a local integration, the DB is unencrypted and lots of people do this.

### 30. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4lpzh/

whaaa i don't recall denying anyone! email me again?

### 31. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4n1pd/

those are very different parts of the business - marketing is a cost to grow and acquire new users, token spend is something that scales linearly with users. We are not too worried with margins right now, we we want to deliver an amazing product to users, and over time we hope we can figure out a way to make money while delivering you all an amazing product. The market is so big, so we're just not focused on making money right now. We want to make something really useful and grow it.

### 32. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4n8uo/

First of all, I'm terribly sorry to hear that. That is a fascinating use case, and I'd love to speak, if you have time, about how you're using it. We are definitely seeing lots of non-productivity-related use cases, and it's possible that we should, in fact, adapt our marketing to reflect this.

### 33. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4nhw1/

yes. we're working on it now, if you have team features in mind you'd want we'd love to hear about them.

### 34. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4nmvp/

Very sorry to hear that. Our lead developer is actually working on voice output as we speak! Hopefully in the next week or two

### 35. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4o0zx/

We're shipping this very, very soon :)

 I like to pan-sear in cast iron or stainless. lately more stainless

### 36. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4o33u/

This is coming in the next week or so!

### 37. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4oe81/

Absolutely. I just don't think the local models are there yet, unless you have a crazy powerful computer. We just haven't prioritized it because it's relatively few users that would be able to do this.

### 38. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4opdv/

It's a very interesting question, and to be totally honest, I'll have to think about this for a bit. I would think it should be robust to different language pairings, but I don't actually know off-hand that much about how different language embedding spaces work. It is definitely not inherently English-first. However, due to the training data distribution, it's possible that the models or the embedding models still do slightly better in English.

### 39. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4ouxi/

We will work on this, and it should improve. There is no fundamental limitation here. I'm not sure why it's not quoting the links. Please downvote chats where it does this. That would help us debug and improve the system. We actually already have specific evals around link inclusion, and we measure those, but we will try to improve them further.

### 40. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4pext/

hmm we'll look into this!

### 41. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4ptyd/

hmm, if they have MCP servers yes, otherwise, maybe? would have to look into it

### 42. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4pxdi/

This is a known product limitation and problem, and we are working on it right now. I hope that it will improve in the next week or two.

### 43. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4q2cm/

Too lenient -- I think you mean too stingy? We are working hard to deliver you more intelligence for lower cost. You should see improvements over the next few weeks.

### 44. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4q86n/

As far as the next integration, our aim is to support basically everyone with a public MCP server. Local MCP servers will soon be supported en masse as we are rolling that out in the next week or so.

### 45. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4qjd0/

Thanks so much. We work really hard on it and appreciate the kind words.

### 46. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4r137/

The MCP server is so new that I think it just hasn't made it into what we call self-knowledge yet, but we'll fix this. AppleScript is something we absolutely want to support, and we will soon. Hummingbird and Littlebird both actually have options for three different modes:

  - Quick - Default - Research  Just make sure to select the correct one in Hummingbird and the main app.

### 47. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4rosf/

Hi! thanks for the kind words. Yes, we've this form (https://forms.gle/o6k5db4aZRdBVZpU9), you should also join our discord - https://littlebird.ai/discord (https://littlebird.ai/discord) where we share updates.

### 48. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4sfrb/

Thanks so much. I'm really interested to hear if it's improved since you last used it. I hope so. Any other feedback you have too please send along!

### 49. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4sw9l/

We'll consider that, but free users do still cost us money and we're still a small company so we're just trying to balance the desire to offer a good product for free and our economic realities.

### 50. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4v7bl/

Sorry to hear that, feel free to let me know more about your usage pattern. It's possible that we can figure out optimizations in product or provide suggestions to help make it better.

### 51. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4wqac/

would you mind dm'ing me with your email? given what you are going through we're happy to offer free usage of the product

### 52. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4xwdu/

We do have a beta tester program. If you comment on Discord, we'll add you to it!

### 53. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4yp9t/

We have SOC II Type II cert and HPPA certified, there are some architectural changes behind the hood that happen if you need HIPAA compliance, so it's important to check that box in the app.

 Our approach to memory is honestly very complicated and hard to explain succinctly because we have many different kinds of memory.

 It doesn't require any manual management. In fact, I think us exposing when the agent is updating any particular memory store is probably just confusing users and was a mistake on our part. Some of the memory systems the agent has to update manually, and this sort of master memory system everything goes into so that the agent can always find any particular piece of data that it wants.

 I guess conceptually the way to think about it is that there are tiers of memory or hierarchy. We have a sort of condensed version, which the agent maintains, that has important, quickly accessible facts about your life. Then there is the sort of master brain that holds the full repository of data where the agent can find anything that you've seen or read, sent, heard, etc.

 Basically, the goal of the product is to make all of this seamless and invisible so you don't have to think about it.

### 54. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4yzsx/

Our approach is pretty different. Obsidian requires you to manually manage things, as far as I understand. The goal for Littlebird is to have a full second mind that you don't have to manage!

### 55. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4zonx/

Makes sense. I think basically what you're saying is you haven't found a killer use case for littlebird other than recall? What things do those other products do better than Littlebird?

### 56. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy4zt52/

Where did it fail you? Would love to hear about where it disappointed you.

### 57. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy52e86/

what would you like to see in that version?

### 58. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy52qlq/

can you link the app? if it has a MCP, you should be able to connect it to Littlebird.

### 59. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy56c1c/

you can ask it to remember to use the integration or add in settings -> chat -> instructions, and it should work much better.

### 60. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy56uvk/

Sorry to hear that, feel free to let me know more about your usage pattern. It's possible that we can figure out optimizations in product or provide suggestions to help make it better. Also we do see most of our users using us significantly more with time, especially as newer features allow them to replace other apps they're on.

### 61. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy57jqv/

research mode is the most powerful agent, unfortunately, it's a universal problem with AI that it tends to give overconfident -- and sometimes wrong -- answers.

 Our belief is that your data is actually more secure on hardened enterprise grade servers than on device!

 Projects disappearing, we will definitely fix, and right now, you can upload images to chats in projects, and they will be saved, but if you mean you want to be able to upload files associated with the project, yes, we will support that too.

### 62. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy586it/

I don't think that's any different than, for example, you using Gmail or Google Meet and using their transcription functionality. We're the same, and the data would be stored actually in the same place, which is on a hardened enterprise-grade server. The data is still yours. We are just safeguarding it and have enterprise contracts with Amazon where the data is stored on AWS East. If we shut down, we would delete all of your data, and of course you can download it at any time. The data is always yours to download. We also try to make this really easy for additional transparency and trust

### 63. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy58yjq/

Have you see any issues due to this? It should start working right after you open a page though.

### 64. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy59sqv/

Both, we want Littlebird to be the command center for your life allowing you to orchestrate everything via Littlebird. While also supporting the most common workflows in a native first class way. Btw the MCP server (https://support.littlebird.ai/article/littlebird-mcp-server) is really useful for multi agent setup.

### 65. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy5a23q/

For a fix today, ask Littlebird to remember to always link to these references, and you should see improved response.

### 66. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy5ak0o/

we do have a changelog channel on discord https://littlebird.ai/discord (https://littlebird.ai/discord) which is more up to date.

### 67. Alex (co-founder), u/Weak_Ad3685 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy5bwh7/

I use it more for work than I do for personal. The most common use cases for finding information and for recall. I would say the next most common use case is for discussing work dilemmas or technical issues. Hummingbird Is not yet live on Windows, unfortunately!

### 68. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy5g38s/

No you didn't. Ask away!

### 69. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy5jaim/

fair, we can add a note on the website re hummingbird being mac only feature! I don't yet have an ETA on windows i'm sorry to say but I think within a month or two max

### 70. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy5lc26/

also just tbc this is Alex i was just on a personal account

### 71. Alex (co-founder), u/Littlebird_Alex (company account), 2026-07-17

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy5nrq2/

The short answer is yes. We've thought about building this for a while, but there have just been higher priority things to do. Our wish list is always longer than our ability to build and we have to ruthlessly prioritize.

### 72. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-18

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy8hg66/

yes we released it earlier this month.

### 73. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-18

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy8hpmv/

We've some very interesting projects in the pipeline which would help with this, I would email you once it's in a more concrete shape for initial rollout.

### 74. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-18

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy8i2d1/

Chats within a projects will have access to all files uploaded in the project. And yes notes will be similar to Assistant Notes. The global notes space would also have significantly more room with an upcoming update.

### 75. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-18

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy8i53f/

It's planned but not in work, we're releasing it first in the desktop app.

### 76. Tushar (co-founder), u/YardLeast3268 (personal account), 2026-07-18

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oy8izjl/

It's possible the menu bar state is not in exact sync, but you don't need to worry about non excluded part not being captured. While the menu bar state shows paused, it still only applies to excluded content. I'll see if we can expose this as an explicit option in settings though. The reason we'd it excluded by default was to avoid confusion in cases where an excluded url or its title gets captured, if it's part of the shortcuts user has on the new tab page.

### 77. Littlebird team, u/Littlebird_Deep, 2026-07-19

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/oyfik9u/

Hey, could expand more on Projects disappearing?

 We show all projects in sidebar if they are favourited, or show 5 max with "more" to open projects page that lists all projects

### 78. Littlebird team, u/Littlebird_Shivi, 2026-09-02

Permalink: https://www.reddit.com/r/littlebird/comments/1uwjcxc/im_one_of_the_founders_of_a_new_ai_startup/p7es39a/

Yes! Littlebird captures iMessage context by reading your active screen on Mac. And later in September, you'll also be able to connect iMessage directly under Settings > Integrations for a dedicated chat channel. It'll be out soon!
