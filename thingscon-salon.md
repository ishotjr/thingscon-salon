## Rebble: Pebble Reborn
### ishotjr
Lead Emoji Sprinkler, Rebble  
https://twitter.com/IShJR  
https://github.com/ishotjr  
<sub>
	https://github.com/ishotjr/thingscon-salon  
	*press `S` to view speaker notes, which include a ton of great links!!*
</sub>  
Note:
Hi, I'm ishotjr; I'm not big on fancy titles so I prefer to go by "Lead Emoji Sprinkler" at Rebble, since I'm notorious for my overuse of emoji reactions in Discord and when writing blog posts and ... anywhere else it's possible to use emojis!  The last link here is the repo for this presentation - if you press `s` while viewing it you can see my speaker notes which include a ton of source links and other fun facts!  
TODO: bowtie/star man/my ten watches as background  



## Pebble is dead.

on December 7th, 2016, [Pebble announced that they were ceasing operations](https://web.archive.org/web/20180705003113/https://blog.getpebble.com/2016/12/07/fitbit/)
Note:
TODO: shrug as background  


## Long live Pebble!

two days later, on December 9th, 2016, [the Rebble web site went live](https://rebble.io/2016/12/09/rebble-pebble-reborn.html), announcing our intention to "maintain and advance Pebble functionality, in the absence of Pebble Technology Corp."  
Note:
TODO: Rebble logo  



## the long version!
Note:
that was the short version; would you like to hear a slightly longer version?  

## it started in Delft!
Note:
I'm not sure how many of you were aware of this, but this ThingsCon Salon is a homecoming of sorts - Pebble actually started out as a bike computer - an idea that founder Eric Migicovsky had while riding his opafiets ("grandpa bike") to class at Delft University of Technology!  
TODO: cap of emigi riding bike  

## Watchduino
Note:
Eric's [first prototype](https://www.youtube.com/watch?v=jPt5SnKrDI8) was a custom Arduino-based PCB with a couple of buttons, a small LiPo battery, and a screen scavenged from a Nokia 3310.  It displayed SMS messages, music track information, and - oh yeah - it also told the time!  
TODO: cap from vid  

## the Allerta inPulse
Note:
The Watchduino prototype evolved into the [inPulse smartwatch](https://web.archive.org/web/20121105155457/http://www.getinpulse.com/specs) for BlackBerry (and was eventually made compatible with some Android devices).  They were accepted into the [Y Combinator](https://www.ycombinator.com/) program (spoiler: [Eric became a partner](https://blog.ycombinator.com/welcome-eric-holly-diego-matt-nic-kyle-adele-jose-matt-ramon-and-gia/) there post-Pebble) and after running into difficulty funding their next evolution, [turned to Kickstarter](https://www.kickstarter.com/projects/getpebble/pebble-e-paper-watch-for-iphone-and-android), where they raised 10 times their $100,000 goal in 28 hours, ultimately exceeding 100 times the original target with a final total of $10.2MM - [a Kickstarter record at the time](https://www.kickstarter.com/projects/getpebble/pebble-e-paper-watch-for-iphone-and-android/posts/209297) - a [record still held by Pebble](https://www.kickstarter.com/discover/most-funded) thanks to the subsequent [Pebble Time campaign](https://www.kickstarter.com/projects/getpebble/pebble-time-awesome-smartwatch-no-compromises).  



## my Pebble story
Note:
So, that's a little history on Pebble - I wanted to share my own story to help explain my passion for these devices and what drives me to keep them alive long after others may consider them "obsolete".  

### Kickstarter
Note:
Pebble was the first Kickstarter project I had ever backed, and I was actually pretty disappointed with the delays (I chose grey, and it shipped after black Pebbles were already available on store shelves) - and then when it finally arrived it had a screen tearing issue right out of the box (but quickly received a replacement).  
TODO: Kickstarter/PebblePressPack1  

### SDK
#### PW-DOS
Note:
Usually when I get a thing, my first instinct is to start hacking on it, but the [early SDK](https://web.archive.org/web/20120523103349/https://pebblewatch.heroku.com/blog/2012/04/10/pebble-sdk/) was a bit intimidating, and I played with [`SDK 2.0-BETA1`](https://developer.rebble.io/developer.pebble.com/sdk/changelogs/2.0-BETA1/index.html), but it wasn't until [Developer Preview releases of 3.0](https://developer.rebble.io/developer.pebble.com/sdk/changelogs/3.0-dp1/index.html) in preparation for the upcoming Pebble Time that I really started actively developing for Pebble.  I published my [PW-DOS Command Line Watchface](https://apps.rebble.io/en_US/application/550f2f3a46cb79c9bc000044?native=false&query=pw-dos&section=watchfaces) based on one of the tutorials and it's still my daily driver to this day!  
TODO: PW-DOS "marketing"  

### Pebble Rocks Boulder
Note:
once I got into Pebble dev, however, it became a bit of an addiction - there's just something really rewarding about wearing your work on your wrist all day, every day - I'd often forego pretty much all sleep on weekends exploring new SDK features and ideas.  Then a friend and I found out about the [Pebble Rocks Boulder hackathon](https://www.hackster.io/hackathons/pebble-rocks-boulder/a-pebble-hackathon) at which the fabled smartstrap functionality would be unveiled, allowing external hardware to interface with Pebble devices (I'd already been working on prototypes in anticipation of the firmware that enabled it).  
TODO: PRB pics  

### Time for Another Round (Ottawa)
#### layoffs?!
Note:
half a year flew by, and after the amazing experience I'd had at PRB (we won, but the real prize was getting to meet so many other Pebble devs and even real, live, actual Pebblers!), I jumped at the opportunity to attend another hackathon (I say "jumped" but what I really mean is "drove North for 10 hours into a frozen Canadian winter hellscape"!).  Another amazing event (and another win) *but* with [Pebble having just laid off 25% of its workforce](https://www.theverge.com/2016/3/23/11292742/pebble-laying-off-25-percent-of-staff), the Pebble staff who were originally to attend had to cancel their plans.  
TODO: Twitter pic  

### Pebble A2 (Rockstar)
#### the book
#### appstore curation
Note:
as a result of the Ottawa hackathon, I gained the confidence to start a meetup here in Ann Arbor (aka became a Pebble "Rockstar" which also granted me special access to devrel staff), and embraced every possible avenue by which to become involved, including helping with [the book](https://pebble.gitbooks.io/learning-c-with-pebble/content/) and appstore curation.  
TODO: PebbleA2 logo and group pic  

### Pokemon GO Radar
### smartstraps
Note:
Meanwhile I continued to spend all of my time on Pebble development, such as the [Pokemon GO Radar Pebble Watchapp](http://ishotjr.com/pokemon-go-radar-pebble-watchapp-poc/) (#10 game of all time!) and [PW-DOS Keyboard Smartstrap](http://ishotjr.github.io/2015/11/29/pw-dos-touchscreen-keyboard-pebble-smartstrap.html)  
TODO: PoGO Radar Twitter pic and PW-DOS keyboard smartstrap  



## rumours and discord
### The Information
Note:
As I mentioned, Pebble had already had layoffs in March of 2016, and [rumours abounded](https://techcrunch.com/2015/05/20/even-with-18-million-in-the-bank-rumor-has-it-that-pebble-is-on-the-rocks/) from then on.  As a *Rockstar* I had some additional insight, such as the annual Developer Retreat seeming increasingly unlikely to happen - allegedly due to pressure to ship the Pebble 2, Pebble Time 2, and Core (in retrospect I wonder if they were in fact working on the final "kitchen sink" release!).  Then late on November 30th, someone posted The Information's (paywalled) scoop [Fitbit To Buy Pebble](https://www.theinformation.com/articles/fitbit-to-buy-pebble) to the developer chat, which then echoed (though with no additional firm evidence) across the tech blogs - and we all started to freak out.  
TODO: information screen cap    

### confirmation
Note:
The next week was a confusing time, as Pebble had not confirmed any of the rumours - instead Tweeting and running giveaway contests as if nothing was wrong, as well as promising a long-overdue Kickstarter update.  Some really, really strange things happened during this period, such as the [famous "shrug" Tweet](https://www.reddit.com/r/pebble/comments/5fumcz/whatwhat_does_this_mean/dan83rh/) and the [(alleged?) hacking of a Pebble team member's Reddit account, resulting in a frank confirmation of Fitbit's acquisition](https://www.reddit.com/r/pebble/comments/5gbpsx/official_pebble_short_update_post_is_not_official/) - which was denied - only to later be [officially confirmed in an announcement on December 7th](https://web.archive.org/web/20180705003113/https://blog.getpebble.com/2016/12/07/fitbit/).  
TODO: shrug  

### a loveletter
Note:
When we finally received official confirmation, I penned an open letter - or as I called it, a [*love* letter to Pebble and the community that had grown around it](http://ishotjr.com/a-love-letter-to-pebble-and-the-pebble-community/).  I included in it links to resources such as the [pebble-dev wiki](https://github.com/pebble-dev/wiki/wiki) where we'd started to amass our collective knowledge in preparation for post-Pebble survival, and the [Discord server](https://discordapp.com/invite/aRUAYFN) where we were all congregating.  [Pebble Tweeted a link to my blog post](https://twitter.com/Pebble/status/806733571041861632) which helped spread awareness of our efforts beyond the Pebble dev core.  
TODO: tweet  

### Rebbleion
Note:
Two days after Pebble's announcement, [the Rebble web site went live](
https://rebble.io/2016/12/09/rebble-pebble-reborn.html), declaring our intent to "bring the many disparate efforts under a single banner, concentrating energy and enthusiasm to maximize the likelihood of continuance and resurgence of Pebble as a platform" as well as introducing the [Team](http://rebble.io/team/) and [Projects](http://rebble.io/projects/).  
TODO: team cap  



## wiki, archive and reveng
Note:
The next few weeks were a frantic outpouring of productivity - each team member focused on their area of expertise or a feature they were particularly passionate about preserving, and by December 19th, we had replacement Android and iOS apps underway, a new appstore frontend largely completed, and heaps of insight into the inner working of our beloved Pebbles via over 100 commits to our community wiki.  
TODO: Panic store cap https://imgur.com/a/sfnx1  

### appstore
Note:
Less than two weeks after Pebble's announcement, the [appstore API](https://github.com/pebble-dev/wiki/wiki/Appstore#api-info) had already been [reverse-engineered](https://github.com/pebble-dev/wiki/wiki/Reverse-Engineering-the-Official-App-Store), including overriding the [boot URI](https://github.com/pebble-dev/wiki/wiki/Mobile-Application-URI-Bootstrap) to [load an alternative version in iOS](https://github.com/pebble-dev/wiki/wiki/Appstore#new-host-your-own-app-appstore-in-the-pebble-ios-app).  
TODO: wiki cap  

### firmware
Note:
Meanwhile, the firmware team [used IDA to reverse engineer the Pebble Time firmware](https://github.com/pebble-dev/wiki/wiki/Assorted-IDA-notes) and hack together new, FreeRTOS-based firmware capable of drawing to its display!  
TODO: https://youtu.be/_IiCGeqjdI4 cap    

### archive
Note:
Additionally, the Pebble appstore, documentation, and other important data had all been backed up for posterity.  
Oh! And we even had a mascot!  
TODO: http://rebble.io/404 cap  



## RebbleOS

### FreeRTOS-Pebble
Note:
With the insight gained from reverse-engineering projects, new firmware was able to be developed, based on an [example FreeRTOS implementation for the `STM32F4` family of microcontrollers](https://github.com/wangyeee/STM32F4-FreeRTOS) that the Pebble Time and subsequent devices run on.  This project became known as RebbleOS, and six months after Pebble was shuttered, we had an open-source replacement for Pebble's graphics routines, as well as fonts, bitmaps, and layers all functional in our new firmware.  
TODO: https://github.com/pebble-dev/pebble-dev.github.io/blob/master/_posts/2017-04-23-rebble-community-update-3.md

### UX / BT
Note:
By early 2018 we had half a dozen or so regular contributors to firmware, and the ability to dynamically load watchfaces and watchapps (initially they had to be baked into firmware)!  Notifications, scrolling, and the status bar made the RebbleOS experience far closer to that which Pebble users expected.  Oh - we also had a really cool Rebble logo splash screen!  
Additionally, Bluetooth communication was finally functional, transforming the standalone watch into a true smartwatch with real, working notifications!  
Around this time, [Rebble was named number 15 in Wareable's 50 wearable tech predictions for 2018](https://www.wareable.com/wearable-tech/best-wearable-tech-2018-506) - ahead of Amazon, MIT, Microsoft, Nokia and...urm... Neuroscience?!  
TODO: https://github.com/pebble-dev/pebble-dev.github.io/blob/master/images/community-update/Peek_2018-01-23_12-55.gif  



## RWS and The Rebble Alliance

### a firm deadline...
Note: Pebble's shuttering actually had minimal effect on the core Pebble experience for most users, thanks to an arrangement made with Fitbit to keep the web services that powered the appstore, weather, dictation, Timeline, etc. online until the end of 2017 - in fact they even actively promoted Rebble in the [December 2016 blog post where this was announced](https://developer.rebble.io/developer.pebble.com/blog/2016/12/14/first-steps-forward-with-fitbit/index.html)!  At this time, Fitbit lacked any smartwatch product (no, the Blaze does not count!), nor even the ability for 3rd-party developers to develop for their devices.  
TODO: TODO  

### ...receives an extension
Note: Fitbit did the Pebble community another solid, [extending support for our ecosystem](https://dev.fitbit.com/blog/2018-01-24-pebble-support/) for an extra six months, until June 30th, 2017.  At this point, however, it became clear that we were up against a deadline at which point a big chunk of functionality, including the appstore, Timeline, dictation and weather features, would disappear, unless we replicated a significant amount of Pebble infrastructure.  
TODO: https://dev.fitbit.com/images/blog/20180124/180124.Rem%20Tweet-Blog-Hero-a020c32da71df20c5e3c3d66290774aa.jpg  

### a new hope...
Note: this is where we got a bit lucky. I've tried not to include names in this presentation for the most part, since there are far too many contributors to list, but Katharine deserves special mention. The developer of CloudPebble, which was eventually acquired by Pebble (along with KB herself!) had been active in discussions since the beginning of Rebble, but ended up almost single-handedly taking on the task of recreating the necessary web services.  With her [smart glasses project at Intel having been shut down](https://www.theverge.com/2018/4/18/17255354/intel-vaunt-shut-down), along with its parent division (another scoop by The Information!), she had a little time on her hands until her new position at Google started, which lined up perfectly with Pebble's web services' impending doom.  
TODO: https://pbs.twimg.com/profile_images/1054087765690744832/_o743J4b_400x400.jpg  

### the Rebble Alliance
Note: it turns out that running servers costs money, so we had to form Rebble Alliance, LLC and do all the business-y things.  Katharine also came up with a brilliant business model: beyond servers (well, actually ours is a serverless architecture running on AWS Lambda, but...) the greatest expenses turned out to be dictation and weather, from which emerged a "freemium" model whereby everyone could use Rebble for free, but dictation and weather required a $3/month subscription.  As long as we could get 1,000 users, we would hopefully bring in enough revenue to cover our projected costs.    
TODO: obfuscated spreadsheet fragment  

### it's Rebble time!
Note: leveraging the boot server override mentioned earlier, it's now possible to convert all of a user's API endpoints to Rebble Web Services [with the tap of a button](http://rebble.io/howto/).  Users who created a Rebble account before the June 30th deadline were even able to carry over their existing apps.  A tweet from Eric urging users to sign up before the deadline gave us a significant signal boost, resulting in coverage in most of the major tech blogs.  And in over 100,000 users tapping on the aforementioned button!!!  
TODO: Stripe customer graph obfuscated by emigi tweet: https://twitter.com/ericmigi/status/1007441782848679936  



## mobile apps
Note: unlike web services which had a specific expiration date, the mobile apps continue to function for the most part.  Every major iOS and Android release is met with fear that it may finally render our devices non-functional, but for a platform that "died" two and half years ago, Pebble is doing amazingly well.  Fitbit were kind enough to release updated versions of the apps which relaxed their reliance on cloud services - and specifically facilitated the backdoor method by which we'd loaded our alternative appstore.  We had a small setback recently when the Android app was removed from Google Play due to new permission requirements (nobody got the warning emails unfortunately) but we're working with Fitbit to try to get that resolved, and have an archived copy available in the meantime.  

### Gadgetbridge, Dialer and the Rebble suite
Note: existing Android app [Gadgetbridge already supports most Pebble functionality](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Pebble), with some intentional limitations due to their focus on privacy.  We recently acquired [Dialer for Pebble](https://apps.rebble.io/en_US/application/532323bf60c773c1420000a8?section=watchapps) - which users have been leveraging as a workaround for an issue displaying caller info on Android 9 - in order to continue maintenance and address a few known issues and limitations.  Eventually, I envision offering a suite of Rebble enhancements and workarounds to optimize the user experience as various legacy code and functionality runs into barriers.  The existence of workarounds relaxed the need for ground-up replacement apps, so these have not received much developer attention lately.  
TODO: Dialer for Rebble cap  



## who made Rebble possible?

### Pebble
Note: Pebble developed a passionate community of users via their Kickstarter, social media, and other outreach efforts.  Their single greatest achievement, and the reason why Rebble has worked, in my opinion, is their phenomenal developer community, fostered by an amazing developer relations team, unparalleled documentation and examples, delightful dev tools and SDK, and events like the hackathons that I attended, the meetups that I and other "Rockstars" organized, and their legendary annual developer retreats.  Additionally, their propensity to keep things "open" - for example allowing sideloading of watchfaces and apps, or having screws on the backs of later "OG" Pebbles to facilitate repair - has helped the ecosystem outlive its creators.    
TODO: devrel/docs  

### Fitbit
Note: I take every opportunity that I get to thank Fitbit for their ongoing support and cooperation - it's easy to see them as having "killed" Pebble, but really Pebble died on its own, and Fitbit just acquired some choice pieces from what remained.  And their web services extension, mobile app updates, and ongoing cooperation has made our work at Rebble much easier than it could possibly have been otherwise.  
TODO: pebbleXfitbit  

### contribs
Note: I'm not going to name names because there have been dozens upon dozens of contributors along our journey - but every contribution - whether a simple graphical asset, or an entire swath of functionality - is a work of passion, and something for which the entire Pebble community is eternally grateful.  One of my personal favorite things to see with this project is novice devs working with more experienced team leaders to make real, lasting contributions that they can point to and say "I did that!"  Thanks to everything being open source, we recently had a contribution out of the blue that implements the missing Timeline functionality, which just blew me away!  
TODO: team/contribs  

### support
Note: Rebble is not all just devs! We have an amazing support team that provide real-time troubleshooting, complete how-to guides, and more, in order to keep everyone's Pebbles running!  
TODO: HOWTO  

### subscribers
Note: we literally couldn't do it without our subscribers!  Cloud services cost money, and dictation and weather are shockingly expensive - so those $3 subscriptions really make providing web services possible.  
TODO: subscribe button  

### believers
Note: even if you're not a developer, or member of the support team, or a subscriber, you can still make an impact.  One of the best things about this project is seeing all the appreciation - the tweets, the Reddit comments, the emails just to say "thank you for keeping my beloved watch alive!"  
TODO: heart  



## looking forward
Note: 
TODO: rocket/soon  

### challenges
Note: one of the biggest challenges we face is the relentless pace of technology, while much of the Pebble ecosystem remains frozen in time.  The mobile apps for example are a constant source of anxiety, with each major OS version potentially breaking something which we have absolutely no control over or ability to update.  Hardware is also in finite supply - there will never be *more* Pebble watches than there are today, only fewer - and as batteries age and buttons break and waterproofing fails, the supply continues to shrink.    
TODO: this is fine  

### competition
Note: while legions of fans look to Rebble to keep their Pebbles alive, one of the surprising things we've seen is the number of *new* Pebble users - countless Reddit comments and Discord messages and emails from users who bought a Pebble for the first time specifically on the strength of the ecosystem as it stands today.  There's still really nothing quite like Pebble; I've accumulated over a dozen smartwatches trying to find anything even close; a lot of us hoped Fitbit's acquisition would mean something Pebble-like, but even the Versa, which may vaguely resemble the Pebble Time Steel physically, has proven an absurdly far cry in my experience: pathetic battery life (often less than two days), no always-on screen - and the screen never ever comes on with the raised arm gesture, continual syncing and Bluetooth problems - and just NONE of the charm and raw utility of the Pebble.  
TODO: TODO  

### `TODO`
Note: at present we have a functioning appstore, but no replacement developer portal, meaning no new apps have been available in the appstore since mid-2017.  I've got a plan for a workaround but have not had time to develop it yet.  Thankfully watchfaces/apps can be sideloaded, so the main shortcoming of the current situation is the lack of aggregation.  Timeline was another feature that was not possible to ship in time for the June cutoff, but we've actually received a pull request from a previously unknown contributor which looks extremely promising and should hopefully be deployed soon.  
TODO: dev portal cap - see ishotjr?  

### hardware
Note: there are currently multiple replacement hardware projects in progress.  A friend and I developed a FreeRTOS-based e-paper prototype in early 2017, and though I got a bit busy with other Rebble stuff in the interim, we recently picked back up on a new color prototype.  Additionally, another "big board" and form factor prototype are underway in the `#hardware` channel on Discord; so the likelihood of replacements existing by the time original hardware starts to dry up seems more and more promising.  
TODO: Josh' big board, aion original and new prototypes  

### community
Note: as I type this there are over 700 users online on our Discord server.  The Pebble subreddit has almost 37,000 members, with 128 online as I write.  Close to 8,000 individual customers have made subscription payments.  I have at least a dozen or so support emails that I've had to ignore for a bit to get my presentation done in time.  The community is thriving, growing, with new innovations, unbridled enthusiasm, and an incredibly bright future.    
TODO: discord online cap?  



## Rebble: Pebble Reborn
### ishotjr
Lead Emoji Sprinkler, Rebble  
https://twitter.com/IShJR  
https://github.com/ishotjr  
<sub>
	https://github.com/ishotjr/thingscon-salon  
</sub> 