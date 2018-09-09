---
layout: page
title: exploration of pet peeve figures
permalink: /explorationpeevefigures/
---
A facebook friend made a cool post, asking what figures or figure combos are the pet peeves of choreographers or other dancers. I wanted to see how common some of these beloathéd figures were, so I tried some object-level observation with [contradb.com][]. For reference, today (August 7, 2018), contradb.com has 468 public dances. When I'm signed in (so my private dances appear), I have 492 available. 

Side note: Given a choice, I'd usually rather talk about things I love than things that irk me. The idea to document this search game arose 1. because contradb has just had some new improvements to its search function, and I haven't fully explored them, and 
2 the posters were very clear and specific, giving me lots of search cases I wouldn't have thought of on my own. 

Two good things to bubble up from this already: 1 as suggested by Nicholas, experienced dancers can choose to see some of these 'awkward transitions' as 'challenging transitions'---opportunities to think outside the box of how a weight shift or flourish might improve flow for your partner. Megan called them 'poise points', which I really like as a framing. And 2, as suggested by Dave, in the future contradb could have a "pet peeve" feature, where a user could specify a transition they don't like. That transition would then never appear in their search results. 

Post texts will be left anonymous unless a poster wants their comment attributed; post text will be taken down upon request; this "blog post" might not remain up ad infinitum. 

> what are you contra choreography pet peeves? This can be anything from "asdf this feels SO LOUSY" (a BIG one of mine is courtesy turn to circle L) or "huh, I kinda wish they'd done something different here (one of mine here is long lines to circle).

![01](/img/01llc.png)

Long lines to circle looks like it shows up in only 8 dances, and I quickly found out that not all of them should be excluded for this. If you have long lines forward with a rollaway with half sashay on the way back, then a circle flows easily. In order to not be falsely accused, a dance's rollaway needs to be entered as an actual figure, not just a note about the long lines. 

![15](/img/15.png)



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
> Chain to face the next

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

>Too much clockwise rotation (more than 40 beats).
>> Ditto on too much clockwise rotation in a row. Contra causes enough dizziness already.


This is the first pet peeve that really resonates with me. As someone who keeps a kneebrace in her bag "in case my knee acts up," I notice myself grabbing my brace after a heavy clockwise dance. If my partner's willing&able, I'm not against swinging "backward" to keep things more level. 

And contradb will be able to search this---but it doesn't right now. Stay tuned. 

> Dances with only a short swing / circle 3/4 to swing as your only partner interaction.

I don't see an obvious answer for this one right now---feedback welcome! Send an email to adminisaur @ the website we're talking about. 

> Staying on one side of the set the whole time
>>Many dances in which one role stays on the same side of the set for most of the dance annoy me.

> One role does all the moves
>> Dances that have one role doing little compared to the other role annoy me (unless I am tired or one limb is tired or sore)

These are not supporsed yet, but I see how they could be.

> Most (but not all) dances having 3 balance in a circle and spin annoy me

~This is literally the next thing in the queue! Dave is doing heys right now, but we're on it. ~
Dave took ten minutes to make a mockup of this, and he proudly presents this screencap: 
![14](/img/14.png)

> Short swing, especially when it comes with a mad robin afterwards.

Well, we've got 319 dances featuring an 8-beat swing. 
![09](/img/09.png)

Maybe this person's complaint was having a short swing with your partner? 
![10](/img/10.png)

We're down to 186. 

"especially followed by a mad robin..."

![11](/img/11.png)

Well, it is this commenter's lucky day---there aren't even any dances to be blacklisted for following a short swing with a mad robin.

This leads me to think, a possible pet peve (or at least something that I know a lot of people go out of their way to avoid) is having a short swing that end's mid-phrase. There are some dances (Orace Johnson's [Du Quoin Races][] is one of them) that are so good that in my opinion they're still worthy of being called, at least to dancers experienced enough and fresh enough to overwrite their bodies' autopilot. We can't right now search 'swing ends mid-phrase,' but I'd like to. Dances like Du Quoin Races definitely belong in the collective consciousness, but we do want to be able to filter them out, so we don't consider including them in programs for beginners, or for late late at night. 


> When a circle turns into a star the other way.

>> +1
>>  Still infinitely preferable to circle left followed by circle right, which you occasionally find in old-fashioned dances!

Circle one way to a star the other way piques a clockwise thing for me... let's see how common this is. The search is pretty 'tall,' so you'll actually get to build anticipation...


![12](/img/12.png)

Oh good! Only 3, and (per the foreshadowing by the third commenter) all of these three are tuned toward brand-new dancers. So clearly this is a figure combination that has a place, and callers should choose the right place. 

![13](/img/13.png)

> Circle all the way into R&LT. The R&LT always comes out diagonal and the lines get offset from each other, which is hard to immediately fix and confuses beginners.

>>  I think this happens because circle 1x takes slightly more than 8 beats these days

>> Yeah. I haven't yet found a dance in which I'm happy circling anything more than 3/4.

Two ideas here---one the specific issue mentioned by the commenter, and then (from the subcomments), being able to search "this dance abuses suggested figure length. Cary Ravitz made a list of figures and their suggested timings. When editing a dance, a user/choreographer can see if a figure is being scrunched into too few beats (or stretched into too many). That looks like this:

![16](/img/16.png)

, where the red number of beats is a helpful "do you want to re-think how many beats an allemande 1/2 will take?" that still lets a user enter the dance as specified. But we should be able to show this to people searching, too! 

Now, on to circles into right & left throughs: 
![17](/img/17.png)

No dances here yet. But we can find out: how many dances have their 'circle 4 places' pretending to fit into 8 beats, vs how many are encoded as more (or fewer)? We have 79 dances with a circle all the way. 

![18](/img/18.png)

![19](/img/19.png)

More than 90% (72 of them) call the circle an 8-beat figure. Let's hope that the adjacent figures have a little more 'squish' than a right-left through. Ah, yes, the first one I grabbed ([Bee in her Bonnet]) has this circle 4 places as the progression, and an opposite direction circle with next neighbors, so big steps can be made. 

How about the non-8 beat circle-all-the-ways?

![20](/img/20.png)






[contradb.com]: https://contradb.com
[Rod's Grits]: https://contradb.com/dances/542 
[that]: https://github.com/contradb/contra/issues/480
[Du Quoin Races]: https://contradb.com/dances/656
[Bee in her Bonnet]: https://contradb.com/dances/99

