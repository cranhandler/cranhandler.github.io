---
layout: page
title: exploration of pet peeve figures
permalink: /explorationpeevefigures/
---
A facebook friend made a cool post, asking what figures or figure combos are the pet peeves of choreographers or other dancers. I wanted to see how common some of these beloathéd figures were, so I tried some object-level observation with [contradb.com][]. For reference, today (August 7, 2018), contradb.com has 468 public dances. When I'm signed in (so my private dances appear), I have 492 available. 

Side note: Given a choice, I'd usually rather talk about things I love than things that irk me. The idea to document this search game arose 1. because contradb has just had some new improvements to its search function, and I haven't fully explored them, and 
2 the posters were very clear and specific, giving me lots of search cases I wouldn't have thought of on my own. 

Two good things to bubble up from this already: 1 as suggested by Nicholas, experienced dancers can choose to see some of these 'awkward transitions' as 'challenging transitions'---opportunities to think outside the box of how a weight shift or flourish might improve flow for your partner. And 2, as suggested by Dave, in the future contradb could have a "pet peeve" feature, where a user could specify a transition they don't like. That transition would then never appear in their search results. 

Post texts will be left anonymous unless a poster wants their comment attributed; post text will be taken down upon request; this "blog post" might not remain up ad infinitum. 

> what are you contra choreography pet peeves? This can be anything from "asdf this feels SO LOUSY" (a BIG one of mine is courtesy turn to circle L) or "huh, I kinda wish they'd done something different here (one of mine here is long lines to circle).

![01](/img/01llc.png)

Long lines to circle looks like it shows up in only 8 dances, but that's because I didn't think things through. If you have long lines forward with a rollaway with half sashay on the way back, then a circle flows easily. By adding that the long lines must go forward *and back*, we have only 5 dances.

![08](/img/08.png)

![02](/img/02courtesyturntocircle.png)   
 but courtesy turning directly into a circle left has 27, including at least one that I really enjoy dancing ([Rod's Grits][]) 


I think a question I'll be wondering throught this search project will be "are these 'pet peeve' figure combinations very different from person to person? Or are there some where we're unanimously wishing for a dance to be a little bit different? The only peeve mentioned I strongly identified with was "too much clockwise turning," which we can't search contradb for _today_, so I'm relying on the reports on the thread. 

> Right shoulder Heys into right shoulder rounds and swings

>> +1

>> Just freaking balance! Who writes this?

Well, here I have to be a little embarrassed on behalf of contradb: we can search for heys, but not by who leads them and by which shoulder. Dave is working on [that][] as we speak, but I'll just do the less-refined search in case he doesn't finish til tomorrow. 

![03](/img/03.png)

Hmm! Indeed, even looking at _all_ heys instead of just right heys, this wasn't very popular: only 4 dances out of nearly 500. Luckily, as the last commenter noted, you can just call a dance with the balance instead. 


> Neighbor Courtesy turns into next neighbor balance and swing


got 6 plus-ones, and the question

>> Does a next neighbor dosido improve this at all? 

answered

>> Nope. Everyone’s flow is in the wrong direction unless you throw in a twirl

and 
>> For me, even without the balance it's still awkward. People can't help facing in the wrong direction, it's difficult to line up smoothly with the music, and oh my goodness gracious following in line behind some hotshot who wants to do all kinds of shenanigans on the courtesy turn so that they *always* make your new neighbour late, even to the point of frequently missing the swing altogether...

So, what do we see? I get to test out my search chops. Courtesy turn with neighbor, which progresses you to your next neighbor, to balance and swing. I'm going to start simple, assuming the courtesy turn is coming out of a chain. The "&" operator lets us search 'this figure is the progression', so out of the gate we have 8 dances. 
![04](/img/04.png)

Now, when the chain&progression is followed by a swing, we're down to just two dances. It seems like there was a lot of emotion about this combo, so clearly it's happening in more than 0.4% of dances called. If I specify that the chain progression is followed by a _neighbor_ swing, or a neighbor _balance and swing_, as in the original request, only one remains. 

![05](/img/05.png)

![06](/img/06.png)

So, let's beef this up. We can have courtesy turns in chains, or right & left throughs, or (in some geographies) promenades. 

Nope, the same two dances. 

![07](/img/07.png)

So, to draw so much ire, these dances must exist, and they must be somewhat-frequently called... but they haven't been entered into the crowd-sourced database. I'm going to call this a feature---you're only browsing dances that someone loved enough to share.

This thread continued, and is fascinating. I plan to continue this "research" too, but you're also welcome to join! 


[contradb.com]: https://contradb.com
[Rod's Grits]: https://contradb.com/dances/542 
[that]: https://github.com/contradb/contra/issues/480

