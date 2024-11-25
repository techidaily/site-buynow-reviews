---
title: Exploring Just-In-Time Compilation & Its Limitations for iPhone Game Emulators Under Apple Policies
date: 2024-11-20T21:01:08.110Z
updated: 2024-11-24T22:23:20.863Z
tags:
  - games
  - tv
  - movies
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/a-hand-holding-an-iphone-with-an-emulator-and-an-x-over-the-apple-store-logo.jpg
---

## Exploring Just-In-Time Compilation & Its Limitations for iPhone Game Emulators Under Apple Policies

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* JIT compilation is crucial for emulator performance, but Apple restricts it for security reasons.
* Emulators use JIT to optimize performance by recompiling code on the fly.
* Apple's limitations may change, but for now, emulator users must wait or consider jailbreaking.

 While Apple seems to have opened the floodgates when it comes to emulator apps on iPhone, iPad, and Apple TV, you may have noticed that certain systems are conspicuously missing from the menu. There's a good chance that's because of a specific feature known as "JIT" compilation being restricted by App Store rules.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  What Is JIT?

 JIT compilation is short for "Just In Time" compilation. Compilation is the process of turning programming code into machine code. You can write something in, for example, C code and then compile it for any system, whether it's an x86 CPU as found on most Windows computers or an ARM CPU as found on mobile phones and tablets.

 JIT compilation, as opposed to ahead-of-time compilation, has numerous advantages, not least of which is adaptability to what's currently happening on the computer and what the user is asking the program to do.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Why Do Emulators Need JIT?

 The developers of emulators have found that the JIT approach lets them achieve levels of performance and efficiency that would otherwise be impossible. Using the JIT technique, the emulated CPU code from the original system can be recompiled to native code for the target host system on the fly. Once that code has been recompiled, it can be cached and used the next time the same call is made without compiling again.

![An iPad running G-Police next a  physical original copy of the game and a PS4 controller](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/an-ipad-running-g-police-next-a-physical-original-copy-of-the-game-and-a-ps4-controller.jpeg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Sydney Louw Butler / How-To Geek

 Using the JIT method, it's possible to create self-modifying code, which has become a common approach in video game emulation. This is necessary in some systems because many older systems, particularly cartridge based systems, would load code from the cartridge dynamically and seemingly arbitrarily based on the exact game state. JIT allows for essentially real-time handling of this approach. JIT also lets the emulator optimize the recompiled code to take advantage of the host system as much as possible.

 I'm not a programmer, but even from my point of view, JIT seems like an extremely powerful tool when applied to the tough problem of emulation, based on what I've read.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Why Doesn't Apple Allow JIT?

 Unfortunately, another type of software that can make great use of JIT and self-modifying code is malware. If an app can generate and execute code during its runtime, that opens up the door to all sorts of shenanigans So compiling all the code ahead of time makes it much easier to ensure that the code is safe. Apple also likely doesn't want to have a situation where an app changes its behavior after being approved. Something which can't happen if the pre-compiled code is static.

 The knock-on effect is that software which relies on a JIT recompiler to work at usable speeds won't be approved for the App Store. This is the reason given for the [absence of the popular Dolphin emulator](https://oatmealdome.me/blog/why-dolphin-isnt-coming-to-the-app-store/).

 Of course, there is an alternative to a JIT recompiler, called an "interpreter", but this is many times slower than the JIT method. So while it would work, it would be unplayable. Either we'll have to wait until the iPhone 30 to get the interpreter running fast enough, or we have to hope that Apple loosens its restrictions a little.

##  Things Could Still Change

 It's early days for the emulation scene on the mainstream App Store. Apple may yet decide to loosen this requirement for emulators, or adapt its policies to ensure an adequate level of security for these apps. This will likely be something that's worked out between those approving apps and those developing them. 

 Of course, this issue doesn't exist for those who jailbreak their devices, which lets them [sideload](https://tech-haven.techidaily.com/navigating-nuance-the-human-advantage-over-bots/)any code they like. However, I wouldn't recommend anyone to do that without a terribly good reason, and for most people the downsides of jailbreaking simply aren't worth being able to play retro games on their i-devices.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-visionary-designs-for-future-mojave-dwellings/"><u>[Updated] 2024 Approved Visionary Designs for Future Mojave Dwellings</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-lineup-of-photo-backdrop-alternatives/"><u>2024 Approved Exclusive Lineup of Photo Backdrop Alternatives</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ergodyne-topo-mat-evaluation-the-ultimate-anti-fatigue-standing-pad/"><u>Ergodyne Topo Mat Evaluation: The Ultimate Anti-Fatigue Standing Pad</u></a></li>
<li><a href="https://some-approaches.techidaily.com/gratis-online-converter-swf-in-mov-format-via-movavi/"><u>Gratis Online Converter: SWF in MOV Format via Movavi</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-infinix-hot-40i-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Infinix Hot 40i</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/insights-into-the-streamlined-build-of-the-new-samsung-galaxy-s2/"><u>Insights Into the Streamlined Build of the New Samsung Galaxy S2</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/mars-colonization-adventure-city-building-game-sparks-exciting-martian-storms-and-enthralling-entertainment/"><u>Mars Colonization Adventure: City-Building Game Sparks Exciting Martian Storms and Enthralling Entertainment</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/navigating-through-the-latest-and-greatest-gaming-consoles/"><u>Navigating Through the Latest & Greatest Gaming Consoles</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-how-to-add-stickers-to-whatsapp-the-ultimate-guide-for-2024/"><u>New How to Add Stickers to WhatsApp-The Ultimate Guide for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/stabilizing-your-digital-footprint-after-erratic-snapchat-sign-offs/"><u>Stabilizing Your Digital Footprint After Erratic Snapchat Sign-Offs</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-how-to-successfully-upload-videos-with-images-on-reddit/"><u>Step-by-Step Guide: How to Successfully Upload Videos with Images on Reddit</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-premiere-picks-expertly-reviewed-best-pc-sound-card-models/"><u>The Premiere Picks: Expertly Reviewed Best PC Sound Card Models</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-poco-x5-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Poco X5 for Parents | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unlocking-high-quality-display-for-less-2020-lenovo-tab-m10-fhd-plus-reviewed/"><u>Unlocking High-Quality Display for Less: 2020 Lenovo Tab M10 FHD Plus Reviewed</u></a></li>
</ul></div>

