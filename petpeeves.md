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

> Doing any move twice in a row (like long lines or balances)

got 7 likes, and that will be available at the same time

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

Two ideas here---one the specific issue mentioned by the commenter, and then (from the subcomments), being able to search "this dance abuses suggested figure length. Cary Ravitz made a [list] of figures and their suggested timings. When editing a dance, a user/choreographer can see if a figure is being scrunched into too few beats (or stretched into too many). That looks like this:

![16](/img/16.png)

, where the red number of beats is a helpful "do you want to re-think how many beats an allemande 1/2 will take?" that still lets a user enter the dance as specified. But we should be able to show this to people searching, too! 

Now, on to circles into right & left throughs: 
![17](/img/17.png)

No dances here yet. But we can find out: how many dances have their 'circle 4 places' pretending to fit into 8 beats, vs how many are encoded as more (or fewer)? We have 79 dances with a circle all the way. This does sound like a good candidate for making a user preference "pet peeve," so dances that have a circle 4 places then right left through never show up in your searches.

![18](/img/18.png)

![19](/img/19.png)

More than 90% (72 of them) call the circle an 8-beat figure. Let's hope that the adjacent figures have a little more 'squish' than a right-left through. Ah, yes, the first one I grabbed ([Bee in her Bonnet]) has this circle 4 places as the progression, and an opposite direction circle with next neighbors, so big steps can be made. 

How about the non-8 beat circle-all-the-ways?

![20](/img/20.png)

Interesting.

> Down the hall and arches and diving to get back

>> can you elaborate? This hadn't occurred to me as a thing not to like!

>> This is also my least favorite move. As a tall person, scrunching myself up to get under the arch kills flow and momentum, and trying to make a usable arch with a short partner is also awkward. And the whole move just feels like something I was already too old for in second grade. Other ways of turning around after a down-the-hall flow a lot better and don't feel as goofy.

I could search this two ways: just showing a list of dances that has a right-hand-high-left-hand-low or thread-the-needle. More usefully, though, say I want to call a cance that has a down-the-hall, but I want to avoide those two enders. I'm fine with any other. Great! We've got 52 dances to choose from. 


![21](/img/21.png)

![22](/img/22.png)

> Only the active couple swinging. 

> I hate waiting.

>> One possible fix is to tell people they can swing with the person behind them in the other line? I’ve never actually seen this done on a large scale, but that might be interesting.

>> It can be fun when I have neighbors I enjoy dancing with. But if I've been looking forward to swinging the person I asked to dance, and have to wait half the dance to do it... ugh.

>>> Alternating actives, I presume, makes this BETTER, but does it make it better ENOUGH?

>>>> ...I still hate waiting

>>>> Alternating the Actives makes it *much* better. I've had to experience what it's like to start at the bottom of the line and do nothing but occasionally gate the Ones and simply look at my partner the rest of the time for ten minutes straight with no variation. The opposite of fun.

>>>> I have no inherent dislike of "chestnuts" per se. I just feel that they should only be done when the sets are short enough that everyone gets the opportunity to get all the way up and back down the line during the dance.

This is easy to search, and we see that for most of the dances where only the actives swing, the dance enterer thought that information was central enough to the dance to include it in the hook. Definitely a choice to make consciously in the right settings, not by accident or for a long hall. 

![23](/img/23.png)

> Dig for the oyster, dive for the clam.

>> Yeah, this is a square dance figure that does not lend itself well at all to contras

>>> "Let's waste 8 beats, or more likely 16 if both couples do the move!"

>>>> Yep pretty much, not to mention there is no flow whatsoever to or from anything so any continuity the dance might have had is just gone. Why anyone would put this in a contra is beyond me

Well, that's rare enough in contras that we don't have a figure for it. But you could still see if it is in any dance, by clicking "Figures", then "custom" from the word cloud. 

![24](/img/24.png)

then a good old 'find in page' (ctrl + F) will show you dances containig your 'custom' figure. ('Custom' is just 'anything we haven't added to libfigure yet. Our goal is once a figure shows up in 3 unique dances, or dances by 2 choreographers, we should support it. Right now, we just have dive listed: 

![25](/img/25.png)

If you didn't specifically mean the square dance move, and just wanted to avoid arches, try 

![26](/img/26.png) 

> Neighbor star promenade - no chance to negotiate comfortable hold and I'm constantly nervous about whether my neighbor will do something uncomfortable

Well, darn. Our star promenade only encodes who's allemanding in the center right now---no mention of your neighbor / partner being scooped. We wrote revolving door later, and that helps. Looks like we'll need to go back and add information to star promenade. 

![27](/img/27.png) 


> I also hate butterfly whirls. Too many people want to do them as fast as possible and I feel unbalanced and out of control.

>> I do NOT like butterfly whirls. And doing them with neighbors is just...ugh!! Getting tucked into every single neighbor’s armpit.

Same story here. I know butterfly whirls are a polarizing figure---the posters here dislike them, but I really enjoy them. I enjoy a fast whirl, and I also enjoy discovering who my whirl-partner is and adapting to their momentum. I hope people don't stop calling butterfly whirls altogether. 

> Star promenade/Butterfly whirl, esp with neighbor rather than partner. And please never call a dance with hip bumps

>>  curious: is this about disliking the move altogether, or just not liking your odds at getting a good one b/c people don't know how to do it?

>>> For me, I almost always hate it. The momentum doesn't work for me, and the weight connection is weird and I don't like the timing. It makes me groan when I find out there's one during a walk through.

>>>> I am a fan, with the right partner—to me, it can feel like the best parts of a swing and an English gate in one.

>>>>> The star promenade just never works well for me. I'm usually dancing (the role holding allemande grip in the center), and ideally from that position it should feel like an allemande with another person along for the ride. What actually happens is that there's no shared weight between the two of us. I think this is because it's generally too crowded. I don't mind the butterfly whirl itself; it just doesn't work as well without any momentum going into it. I guess if you're going to call star promenades, I would try to have sets with enough space lengthwise

>>>>>> *takes notes to teach these better*

![28](/img/28.png) 

> This is probably specific to me getting motion sick, but i'm not a fan of extra long swings

This can be important to remember---too many similar dances in a night can result in lopsided enjoyment. I wouldn't have known, before reading this comment, that long swings should be spread out (other than just in the context of mixing piece counts up from one dance to the next). This person could try asking for a balance with their partner when feeling nauseated? But perhaps it's better to share the responsibility a bit. 

![29](/img/29.png) 


Or maybe I really want to call a long swing, but concede: we could make it such that there is a long swing with partners, but not neighbors, making negotiation easier? There are still 160 possibilities. 

![30](/img/30.png) 

> Not a fan of facing stars

>> Interesting! Can you elaborate?

>>> I enjoy connecting with my fellow dancers and I dislike connecting with my partner/neighbor visually in conjunction with the frequent fumbling of hands with the other couple.

>>>> I will say, there's only a few good ways to get into them where it doesn't feel gimmicky.

![31](/img/31.png) 


Ooh, this one's interesting. We've adopted the notaion 'meltdown swing' for the 'face to face turn for two when used as a prefix to a swing,' from 'melt down into a swing,' to avoid the confusion about terms. But, using dialects, you can call this 'gyre and swing,' 'shoulder 'round and swing,' or any terminology you prefer / the dance you're calling has asked you to use. Hopefully clearing expectations up. 

> Circling around someone into swing. It always feels redundant, slow, and awkward and I often forget and go straight into the swing

>> Ditto!!! The momentum is also hard for me cause the connection with a partner helps with moving in a circle for me

>>> ...wait huh? Not sure I understand this?

>>>> I can’t remember what the move is called. It’s like a swing but you’re just walking around each other without touching

>> If you're confused by my comment, lemme try to explain it better! When I'm asked to move in a circle (whether alone, or around a partner or like, when we switch from circling right to circling left, that momentum is hard for me to sustain on my own. It almost hurts (my calves mostly) to do it alone, VERSUS when I'm sharing some kind of weight/tension with another person which helps me move with momentum. Is that better?

>>>>> (they're talking about the move with the controversial name) 

> Oh is it that move? I never made the connection

>>>>>> A 16 beat swing can be *really* long, and this is choreographically is a way to have a more reasonable length swing when the timing into it isn't perfectly on the 1 beat (which we should just balance and swing if it were).

![32](/img/32.png) 

This is a charged conversation. Contradb's goal is to increase harmony in the dance community by letting each user choose their own dialect, and translating seamlessly among them. This is not the place for a debate about which is right---our goal is to let people communicate. 

> Larks/gents chain from the left position (but from the right position is totally great)

>> Agreed. This feels like a novelty. And it's *another* clockwise move.

>>> I really like those

>>>> I thought that some folks are trying to make left hand chains as ubiquitous as right hand chains - because the more we do them the better the left hand chains will feel. I've become quite adept at doing chains from either side.

>>>>> are you talking about the LH chain done from a standstill, or the LH chain full stop?

>>>>>>  "left-hand chain" is a better way of phrasing it than what I'd written, and I haven't enjoyed dancing them whether done from a standstill or from motion

Then let's write a search with all chains for the gent, sorted by handedness: 

![33](/img/33.png)

And for ladies: 

![34](/img/34.png)

Well that's interesting! A lot of emphasis on teaching one role courtesy-turn ambidexterity, but no emphasis on teaching the other. I'm tempted to think that having dancers dance both roles for whatever dance is called will disseminate this information faster than writing choreography specifically to impart a lesson? But I guess time will tell!



I have walked away from this exercise with a lot of new understandings, and I hope you have too. I have lots of new goals for contradb's search capabilities. I also sat down and puzzled out "how do I search for that?" for several dance attributes I hadn't known how to search before. 

I also renewed my awareness of how different every dancer's preferences are, and how many different reasons there are to come to and enjoy time on the dance floor. There are a few specific take-aways that will influence what I call (I will swear off 'full-circle-to-right-left-through' to avoid unaligned lines). But on the whole I reaffirm that program variety is important to a good night of dancing. And perhaps program variety on more axes than I had heretofore considered.

I'm grateful for my friend who asked this question, and everyone who contributed their thoughts. I welcome any and all feedback, at adminisaur @ (the database website). I encourage you to add and search dances, as well!


[contradb.com]: https://contradb.com
[Rod's Grits]: https://contradb.com/dances/542 
[that]: https://github.com/contradb/contra/issues/480
[Du Quoin Races]: https://contradb.com/dances/656
[Bee in her Bonnet]: https://contradb.com/dances/99
[list]: http://www.dance.ravitz.us/chor.php#3
