---
author: "Jonas Wouters"
date: 2019-02-14
linktitle: Taking a break from Apple Mac
title: Taking a break from Apple Mac
tags: [
    "hardware",
    "software",
    "hardware",
]
---

It all started many years ago. Back in the late '90s until the mid-'00s, I was a big Linux fanboy. I even [contributed to After Linux From Scratch](http://www.linuxfromscratch.org/hints/downloads/files/OLD/afterlfs.txt) (zertox) back in 2001, now called Beyond Linux From Scratch.

<!--more--> 

I never really left Windows because I loved the Macromedia tools. Being a big fan of sites like [eye4u][eye4u], [nrg.be][nrg], [ldg.be][ldg] and [derbauer.be][derbauer], I was really into building flash websites and that only really worked well on Windows. I played some games back then, but the ones I played usually ran better on Linux. Dual-booting to Windows was the only solution.

When I was working for a couple of years, I was able to afford my first Apple Mac Mini, and later on the Powerbook 17". I fell in love with the hardware and the ecosystem. A short time after that, they moved to Intel, and things got even better because you could run Linux/Windows in a virtual machine. I was fortunate enough to have an employer that was willing to buy me a MacBook, for the great work I did for him. 

I convinced my whole family to convert to Apple, and as a result, those frequent phone calls for support were almost non-existent anymore. 

I always preferred native applications over their web-based counterpart. Thus I wanted to create software for OSX, and a couple of years later for the iPhone/iOS. I loved most software because it was all beautiful like those flash sites I dreamt about before. It Just Works, and as that saying bears my initials, I later named [my company][justworks] after it.  

Creating apps for OSX or iOS never really took off for me. I created some things, but most of it was proof of concepts for a client, and nothing got published in the App Store. 

Summarised, I loved MacOS, and it was the best of both Windows and Linux. It had Adobe software, Office, Unix Shell, great hardware, beautiful apps and a package manager (Homebrew). I no longer needed my Linux/Windows machine and bought a console to play games. On top of that, maintaining a Mac was far less work than maintaining my Linux (I was making it myself difficult after all, with Linux From Scratch and Gentoo). 

## So, what changed?

Back when I had the PowerBook and the Mac Mini, I could go to one of the Apple resellers, and I would get the service I expect — not being treated like a child that can't work with a computer. I guess this is the result of Apple becoming mainstream. Nowadays I don't even like to go into an Apple Reseller store anymore because I can't stand the way they talk to me. People at the Official Apple Stores are better trained, yet mostly oriented to consumers. 

I got the first MacBook Pro Retina, and it was one of the best machines I ever had. Up until the moment that the battery started failing at random points during the day (a hard power-off at 20% or even 80%), and the Apple Reseller was not willing to replace the battery because they blamed the user/me for some software that uses a lot of resources. I solved this issue by buying the last version of its generation and selling the old one. The performance was the same, for half the price I paid for the other one, but I longed for more, for 32gb of ram. 

I bought the latest MacBook with the touch bar even though I was sceptical at first. It didn't have 32gb of ram, and as a developer, I use the function and escape buttons all the time. The escape issue was easily fixed by assigning it to caps-lock, and because I really wanted to use the touch bar, I even removed my external keyboard and worked directly on the MacBook keyboard, with as a result I spilt a couple of drops of Cola on the thing and had to bring it in for repairs. 

Surely they fixed the thing for a hefty price, and a two week wait without a replacement device. They had to replace the whole top cover because it is, for them, 1-piece replacement part.  The replacement also solved some issues I had with a couple of keys that didn't always work very well even before the spill, which turned out to be the biggest issue with the new keyboard design. 

Besides the hardware and support, I had other issues. My USB speakers stopped working after I played a video for a few seconds. When playing music, it worked for longer, but not indefinitely. This problem could be solved by replacing some sound drivers with older ones, but System Integrity Protection prevented that with the latest MacOS. In the end, I just bought new speakers, but System Integrity Protection was still a PITA on more than one occasion. 

Other issues were slow Docker performance on MacOS, fan noise, keys that stopped working again, and a bunch of other minor annoyances. 

I was eying the competition for a while already, and I was getting [more and more excited][surface-and-the-ipad-pro] with Microsoft Surface hardware. Checking [r/unixporn][unixporn] a lot to see if I could get comfortable with Linux again after being spoiled by beautiful apps on MacOS. 

## Enter Windows, for a couple of months.

The MacBook was gone (stolen while trying to sell it) and I build a new desktop computer. For a fraction of the price of the new MacBook Pro, I got a machine that was faster in every regard. I have to give credit to Apple for the great NVMe performance, my desktop just barely performed better. 

The desktop is great. I don't hear the fans come on, it's performant at all times (no throttling), I've got plenty of storage, and if something breaks, I can repair it myself. 

Windows is decent, but I was forced to reinstall it a couple of times when weird errors started popping up that I was unable to solve, and it was easier to do a reinstall of the system. 

Windows Subsystem for Linux (WSL) was slow and annoying, and eventually, I just used Git for windows which worked with fewer problems. 

I wanted to keep Windows for easy access to games. Playing cooperative games and adventure games with my oldest son is a lot of fun. So I started experimenting with Linux in VMWare, but couldn't get used to the suboptimal performance.  Using VMWare also caused Docker for Windows to no longer work because you had to disable Hyper-V.

## Coming home to Linux.

So, back to dual-booting? No, I learned about another possible route. VFIO or GPU passthrough to a Windows VM in Linux. Long story short — It works, and everything I have runs as smoothly as on a native Windows. 

These days I run NixOS on all my hardware. I've got two desktops, and a Lenovo Thinkpad.  All are provisioned using the [same configuration][nixos], and together about as expensive as a single MacBook Pro. 

Thanks to NixOS, all my systems are easy to set up and predictable. If something breaks during an upgrade, I can quickly roll back and continue working without issues. I still have a lot to learn about it, but that will come with time. 

In the end, this setup fits my workflow at the moment. Everything changes constantly. If the new Mac Mini would've arrived earlier, I might have switched to that and deal with the Docker and other issues I had. 

I'd argue that my i3 + Polybar + Rofi looks better than the equivalent on MacOS. Some apps might look like crap, but the most important ones look the same on any platform. 

Over time, I tried choosing cross-platform solutions for apps I frequently use (todo, notes, calendar, ..) and that allows me to use any platform at any time. Lock-in is easy, but no longer necessary as there usually is a great solution that supports other platforms. 

I'm still on iOS for my mobile devices, and that works excellent for consumption.  I [got that iPad Pro][surface-and-the-ipad-pro] in the end, and it's good enough for when I'm not at one of my desktops.  The Thinkpad laptop is my backup in case I have to work away from my desktops. 

I love the freedom of Linux and the savings on hardware. 
I have missed Linux, and I'm happy to be back "home". Needs will change, and maybe I'll eventually get back to MacOS or Windows, but for now, I don't see a reason to. 

Are there things I miss? Better scaling support would be nice for when I would get a 5k display in the future. I'm used to my ultrawide now, so I'm patient. I'm very curious about the VR/AR evolution. I love what Microsoft is doing in this space, and I'm afraid Linux will be left behind at first. 


[lfs contribution]: http://www.linuxfromscratch.org/hints/downloads/files/OLD/afterlfs.txt
[eye4u]: https://www.youtube.com/watch?v=3aT4wt0fmGU
[nrg]: https://www.youtube.com/watch?v=UcYKyqKve88
[ldg]: http://www.ldg.be/v1/
[derbauer]: https://www.derbauer.de/
[justworks]: http://justworks.be/
[unixporn]: https://reddit.com/r/unixporn
[surface-and-the-ipad-pro]: /surface-and-the-ipad-pro
[nixos]: https://github.com/jonaswouters/nixos-configuration/