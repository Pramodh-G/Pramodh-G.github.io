---
title: Notes on the attention economy
date: 2025-07-05
---

_This is an excerpt from my journal - with extra research. Part one of a three part series._

## _A setup_

I'm on a flight from Vancouver to San Francisco. It's an early morning flight - 7am to 9:45am. Everyone's either cranky or sleepy (or both). It's a 6 seat per row plane. I start to people watch, and notice patterns. 2/6 people on my row are on TikTok. 4/6 people on the row ahead of me are on either Instagram reels or TikTok.

I sneak a peek at the feed of a curly-haired, freckled, married guy. The "algorithm" has figured out that he likes black and white motivational videos. He scrolls, ignoring the flight safety instructions. A scantily dressed woman dancing pops up on his screen as a flight attendant comes by to check if everyone's wearing their seatbelts. He snaps back into reality, turning his screen off. Once the threat is averted, he goes back to staring at his screen.

There's another guy seated in front of me. An Apple ecosystem ad - iPhone, Apple Watch, AirPods. I observe what he's scrolling through. He uses TikTok in landscape - streaming audio to his pods. A few TikToks of the Afghan cricket team show up - they chase 30 runs in 6 balls. He speeds through the video at 2x, quits TikTok. Replies to a text on WhatsApp - but quits midway once there are blue ticks on his messages. He opens TikTok - this time to create a story about him being on a flight - making sure to focus on the screensaver on his watch face. He scrolls past the WhatsApp status his friends have posted. All this - under 3 minutes.

The only two people who didn't use their phones were older passengers - falling asleep from exhaustion as soon as they boarded. The two people I described above put their phones aside once the flight is too high to receive network. They lean back, close their eyes - as Vancouver shrank, revealing magnificent views of the Canadian Rockies.

The irony on a flight bound for SF was stark. You see Palantir ads at airport gates, people talking about AI agents, AGI timelines and funding rounds - Yet the most successful technology on that plane was the one reducing human attention to its most primitive state. This goes beyond just planes - pervading every moment of our interactions with others.

- Child entertainment channels like CoComelon [fine-tuning attention stealing abilities on toddlers](https://www.nytimes.com/2022/05/05/arts/television/cocomelon-moonbug-entertainment.html?campaign_id=61&emc=edit_ts_20220505&instance_id=60520&nl=the-great-read&regi_id=54686842&segment_id=91384&te=1&user_id=bde5ab3cc9b4378d62ec514312d1791c).
> The team deploys a whimsically named tool: the Distractatron.  
> It’s a small TV screen, placed a few feet from the larger one, that plays a continuous loop of banal, real-world scenes—a guy pouring a cup of coffee, someone getting a haircut—each lasting about 20 seconds. Whenever a youngster looks away from the Moonbug show to glimpse the Distractatron, a note is jotted down.


{{< figure src="/attention-economy/coco-melon.jpg" caption="Overly saturated colors gets a baby's attention" >}} 

- Netflix adding [autoplay of next episode](https://news.ycombinator.com/item?id=20566514).
> As part of the autoplay test, we tested how long the countdown should be between episodes. 5 seconds, 10 seconds or 15 seconds. 10 seconds caused the biggest increase in hours watched. We thought that it gave people time to digest what they had just watched, but wasn't too fast (5 seconds) where it became jarring. Interestingly, Netflix recently changed the countdown between episodes to 5 seconds. 

These examples (and many more) - show how getting people _engaged_ to your content has moved from an "art" to a hard science. The loss function these guys are optimizing for is a net zero sum game for humanity. It is interesting to study the progress here. 

## _The Siren's Song_

For social media to become the oligopoly it is today - dominated by meta, snapchat, bytedance - 3 things came together at the precisely right time.

1. A way to monetize social media apps.
2. A way to distribute social media apps effectively.
3. A way to get user engagement quickly with social media.

No two can exist without the other. Makes me wonder at the nightmarish coincidence of it all.

### _Ads = free software_

The earliest form of ad-based monetization at scale came from search engines. No, Google wasn't the first in this race. A lesser known search engine predating Google, GoTo pioneered the _pay-per-click_ model. Advertisers bid for keywords in automated auctions - _if a user searches "cat", show my videos first - I'll pay when the user clicks my content_. While this might seem commonplace now, it was a radical approach - one that Google took and ran with when it thought about monetization. Yahoo realised 20% of its revenue came from people clicking on GoTo links - and bought GoTo. GoTo eventually disappeared into the void, but its advertisement paradigm was revolutionary.

Today, this is what Google's AdSense does - bringing in **HUGE** money for them. As of 2024, ads constitute roughly 75% of Alphabet Inc.'s entire revenue. What Alphabet does is called _pull_ based advertising. Users _pulling_ the content they want by searching for it explicitly. Instead of _creating_ demand through ads (as it happened in TVs and Radios) - they focused on using _existing_ demand well in the instant the user searches. This bought in sustainable RoI - since it was majorly user driven.

While all this was happening - Facebook's user base was growing slowly. Zuckerberg completely focused on _connecting people_ - _monetization_ wasn't a priority. To him, it wasn't a business model, but a way to offset costs.

> It might be nice to get some ads going to offset the cost of the servers.  
>>\- **Mark**, in an interview with the Harvard Crimson.

They soon introduced **Facebook Ads** to manage infra costs -  where advertisements occupied space on your feed. A form of _push_ based marketing - it analysed usage patterns and demographics to recommend ads on your feed. A step back in the user experience, if you ask me.

A push based marketing scheme is based on how popular a platform is than addressing user demand. TV(_which is a platform_) ads are useless if no one gets cable. It focuses on funneling more volume - with lower conversion rates than pull based marketing. A depressing implication of this is: _The more time a user spends on a platform, the more the company earns through ads_.

Today - advertisements have gone one level deeper. Instead of occupying space on your feed separately - They've become a part of the _content we consume_ (influencer marketing). Humans tend to trust other humans recommending products more than looking at a banner. This translates to better engagement rates, while eliminating ad production cost entirely.

As the famous saying goes: _If the product is free, then you're the product_.

### _The mobile explosion_

We have an economic incentive now, but how do we _reach_ distribution at scale? The mobile phone was the harbinger of the attention economy. A simple before-and-after comparison reveals how:

#### _Pre_

Attention was naturally batched. You watched TV in the living room, took a bus to the movie theatre, logged into your PC to check Facebook. There was no other way to catch KBC if you didn't sit in front of the TV at 9pm on Sundays. Attention consumption required mindful transitions to certain places at certain times - what we call **Appointment-based consumption**.

This fundamentally created a different media economic model. Attention required deliberate _capturing_ - so companies optimized for _duration and satisfaction_. TV channels had to make you choose KBC over a Rajini movie. They competed on content quality and depth because switching required physical effort— changing channel bundles, walking to the record store. The economic incentive was retention, not just fleeting engagement.

Another critical feature emerged - **Information is relatively scarce compared to human attention**. Distributing media across the world came with enormous costs. Movies and music often remained local to specific geographies. Not everyone could make movies - equipment & screen rights were expensive. Record labels would only agree to distribute your music to the public if it was _exceptionally_ good. This created natural quality filters.

#### _Post_

**Contrast this situation with today:** Mobiles _eliminated_ appointment based consumption, creating "interstitial" moments - riding elevators, waiting in line. Media could reach you during hundreds of windows throughout the day that previously didn't exist as consumption opportunities.

Persistent connections with _push notifications_ became the first systems designed to interrupt human attention on demand. Once these micro-moments existed, they created a natural market gap. Empty attention became wasted potential revenue. Platforms had to optimize content for these fragmented windows or lose to competitors who did. 30-minute articles simply don't fit a 2-minute elevator ride.

Simultaneously, media distribution economics inverted completely. Anyone could upload music to Spotify or SoundCloud. Anyone could publish videos on YouTube. Digital distribution eliminated geographic barriers. Built-in cameras and microphones meant production costs plummeted.

**Information became abundant - while attention saturated quickly**. 

As a consumer - you could have realised this abundance, curated your information diet immediately. If there had been large enough collective realization, we wouldn't be facing today's attention crisis. Unfortunately, vast market forces acted exactly in the opposite direction. Why wouldn't they - it was a market gap. If company A didn't do it, someone else was going to.

**The mobile phone didn't just enable the attention economy - it made it an inevitable, logical economic conclusion**. What began as a communication tool became an economic model where platforms competed for quantity of distracted moments. 

### _Lip syncing is all you need_

When I started looking into how the attention economy evolved - it wasn't obvious how light, short-form content generated by users was optimal in getting engagement. Two industries solved for this problem from different angles of attack:

#### _Musical.ly: Content Creation friction_

In 2012, Alex Zhu thought he'd cracked EdTech with Cicada - short (3-5 minutes) educational content. The logic seemed bulletproof: _MOOCs had < 15% completion rates, so break it into chunks_. Create high quality content, so people could learn anywhere. It didn't take off as expected, but it taught Zhu that _people want to be entertained, not educated_.

Zhu pivoted to musical.ly, incorporating learnings from Cicada - **Easy Creation** with 15-second videos, pre-loaded music, one-tap recording. Most videos were of lip-syncing and dancing, paving the way for **Easy Consumption**. It grew organically among teenagers (mostly girls) - lowering the barrier of multimedia content creation.

Users flocked to musical.ly to _create_ content, not to _consume_ it.

#### _Bytedance: Content consumption friction_

Back in Zhu's home, China - Bytedance's CEO, Zhang Yiming, had made it explicit that it was an AI company in the search space. Its genesis came from a different problem - the Chinese audience were struggling to _find_ the right information (Google search was banned). The existing search engine, Baidu, had undisclosed ads in their search results. 

In 2012, Bytedance released its first product - Toutiao (Today's Headlines). It functioned as a news aggregator and recommender from multiple sources. Bytedance was legendary for its A/B testing. They ran over 1.5 million total experiments, 2000+ new experiments per day, and 30,000+ experiments running at any point in time. Every algorithm tweak, every user interface change was meticulously observed. All features **had** to lead to an increase in user engagement, average watch time per session, or number of sessions per day. It's rumored that even Toutiao's name was A/B tested.

Users flocked to Toutiao to _consume_ content, not _create_ it. Algorithm was Bytedance's moat.

#### _Convergence_

Bytedance soon released Douyin - cloning musical.ly for the chinese audience. The one crucial differentiator - it was backed by Bytedance's infamous algorithm. Douyin tracked how long you watched a video, how many times you shared it, as indicators of “liking” a video. It unearthed your deepest desires within [40 minutes of scrolling](https://9to5mac.com/2022/12/20/how-tiktoks-algorithm-works/). 

Douyin also logged your usage patterns - to feed into the next iteration of the recommendation algorithm, to make it even better. There were multiple advantages at play here - each compounding in themselves, while holistically creating a self improving flywheel.

- **Network effects**: More influencers on the platform attracted newer users organically through diverse content. 
- **Data collection flywheel:** More users on the platform provide more data to Bytedance.
- **Market Making improvements:** More data implies better matching of user to content, pulling in more advertisement revenue and influencers.

## _Putting 1 & 1 together_

Bytedance bought musical.ly in 2017 for their user base. They swapped out its backend with douyin's algorithm. Rebranded it to _TikTok_. Numbers grew. 315 million downloads in Q1 2020 - the highest quarterly download count any app had ever achieved. Average time spent on TikTok increased from 29 minutes to 58 minutes between 2019 and 2024. The average american teen spends 1.5 hours on TikTok in 2023 (this has likely increased now).

Other apps followed suit(Nash equilibrium) - Youtube Shorts, Instagram reels, Facebook reels, Netflix's Short laughs, Linkedin reels(why even try), Snapchat Spotlight. They take up 4.8 hours of a teen's day **ON AVERAGE**. Global users spend 2.3 hours per day on social media. Users reach for their phones around 100-150 times a day. Each session then lasts for one minute on average.

What happens when we point this tech at 3 billion humans? Can we get ahead? What happened to the curly hair guy and the apple ecosystem guy? - These questions each deserve a post of their own, in parts 2 and 3. In the meantime, during the interstitial moments in your life - elevators, waiting rooms, commutes, at the cafeteria - observe people around you. How many impulsively reach for their pockets? How many are running away from their thoughts? Are they controlling the phones, or are the phones controlling them?

### Related readings 

- https://www.howtheygrow.co/p/bytedance-TikTok-origins-how-they
- https://chinaplaybook.substack.com/p/alexzhu
- https://www.eugenewei.com/blog/2020/8/3/TikTok-and-the-sorting-hat
