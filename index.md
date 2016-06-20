---
layout: default
---

# About the Project
The world's largest particle accelerator, the Large Hadron Collider (LHC), is operated by the [European Organization for Nuclear Research](http://home.cern/about) (CERN). The LHC collides protons at incredible energies, producing an enormous amount of data that must be analyzed using [the Worldwide LHC Computing Grid](http://wlcg.web.cern.ch/) (WLCG). The computing power of the WLCG is immense, with over 170 supercomputers located in 42 countries. However, computing power is always in demand! The [vLHC@Home project](http://lhcathome.web.cern.ch/) was designed to use extra processing power from Internet volunteers using typical PCs to help compute results for the LHC experiments. When the volunteers' PCs are not in use (like when the screensaver is active), the software kicks in to use the extra processing power that is available. Until recently, normal PCs had one limitation, however: their internet connections were too slow to download full data sets from the WLCG, which limited the types of jobs that volunteers could do. Now, blazingly fast gigabit fiber connections are becoming commonplace in Kansas City, so a team at CERN reached out to Kansas City to collaborate. New software has been developed specifically for gigabit fiber users in Kansas City that will take advantage of the bandwidth, enabling volunteers' computers to perform analysis of real LHC data and submit the results back to the WLCG.

# How do I join?
Contributing is easy, and takes about ten minutes to set up. You'll set up vLHC@Home and then configure your computer for the KC Gigabit Challenge.

1. First, follow [this vLHC@Home setup guide](http://lhcathome.web.cern.ch/join-us). The guide will prepare your computer to run the vLHC@Home software, which uses a platform called BOINC to manage connections between your computer and CERN servers. As mentioned in the guide, you will need to add the vLHC@Home project after installing the BOINC software. Its project URL is `http://lhcathome2.cern.ch/vLHCathome`.

2. Now that your computer is connected to CERN, we need to enable the special options for the KC Compute Challenge! Without this step, your computer will just perform "normal" jobs, not the jobs that are specially-created for gigabit fiber users. For users in KC with gigabit fiber internet connections, your turbo-charged internet can be put to use analyzing full datasets from the CMS experiment! Go to the [vLHC@Home preferences page](http://lhcathome2.cern.ch/vLHCathome/prefs.php?subset=project) and make sure you enable "Run test applications" and check the boxes for applications "CMS Simulations" and "Theory Simulations." The CMS jobs are the ones that are special for gigabit fiber users. Theory jobs have lower requirements and are suitable for all users, but it doesn't hurt to have both checked. Your computer will be served jobs suitable for your network and processing power.

3. Finally, to participate in the CERN+KC Challenge, you must join "Team Kansas City!" The special jobs for fiber users are currently limited to participants on Team Kansas City, since this is a limited test. To join, go to the [Team Kansas City page](http://lhcathome2.cern.ch/vLHCathome/team_display.php?teamid=2839), log in to your account, and click "Join this team."

4. Now you're all set! Thanks for joining and happy computing! You can track your statistics and see how your computers' crunching ability ranks against others by logging in to the [vLHC@Home BOINC site](http://lhcathome2.cern.ch/vLHCathome/) or read more about the software at the [vLHC@Home project page](http://lhcathome.web.cern.ch/).

# Your Impact
The research at the Large Hadron Collider contributes to our fundamental understanding of the universe. Particle physics research also drives innovation in fields ranging from medical imaging and cancer treatment to homeland security and next-generation energy and transportation technologies. In fact, the World Wide Web was developed at CERN! [Read more about the wide-ranging impacts](http://www.symmetrymagazine.org/article/october-2013/why-particle-physics-matters). Contributing to this project is an easy way to help push the boundaries of physics and advance science!

# Contact
Get stuck? Having problems? Let us know by [filing an issue in GitHub](https://github.com/CernKCChallenge/CernKCChallenge/issues).
