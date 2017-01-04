---
layout: default
---

# About the Project
The world's largest particle accelerator, the Large Hadron Collider (LHC), is operated by the <a href="http://home.cern/about" target="_blank">European Organization for Nuclear Research</a> (CERN). The LHC collides protons at incredible energies, producing an enormous amount of data that must be analyzed using <a href="http://wlcg.web.cern.ch/" target="_blank">the Worldwide LHC Computing Grid</a> (WLCG). The computing power of the WLCG is immense, with over 170 supercomputers located in 42 countries. However, computing power is always in demand! The <a href="http://lhcathome.web.cern.ch/" target="_blank">LHC@Home project</a> was designed to use extra processing power from Internet volunteers using typical PCs to help compute results for the LHC experiments. When the volunteers' PCs are not in use (like when the screensaver is active), the software kicks in to use the extra processing power that is available. Until recently, normal PCs had one limitation, however: their internet connections were too slow to download full data sets from the WLCG, which limited the types of jobs that volunteers could do. Now, blazingly fast gigabit fiber connections are becoming commonplace in Kansas City, so a team at CERN reached out to Kansas City to collaborate. New software has been developed specifically for gigabit fiber users in Kansas City that will take advantage of the bandwidth, enabling volunteers' computers to perform analysis of real LHC data and submit the results back to the WLCG.

# How do I join?
Contributing is easy, and takes about ten minutes to set up. You'll set up LHC@Home and then configure your computer for the KC Gigabit Challenge.

1. First, you will prepare your computer to run the vLHC@Home software, which needs two parts. One part is a platform called BOINC to manage connections between your computer and CERN servers, and the other part is a program called VirtualBox that runs the CERN analysis software. <a href="http://boinc.berkeley.edu/download.php" target="_blank">Install BOINC from this download link</a>. If you are on Windows, be sure to get the version _with_ VirtualBox. If you use Mac OS X or Linux, download and install VirtualBox separately from <a href="https://www.virtualbox.org/wiki/Downloads" target="_blank">the VirtualBox website</a>. If you have trouble, consult steps 1 and 2 from <a href="http://lhcathome.web.cern.ch/join-us" target="_blank">this LHC@Home setup guide</a>.

2. Next, add the LHC@Home project to your BOINC installation. When you launch the BOINC client for the first time, it will ask you for a project URL. The CERN+KC Gigabit Challenge project URL is `https://lhcathome.cern.ch/lhcathome/`, or you can select "LHC@Home" from the list of options. Note that there are several LHC-related projects in the list, and you need "LHC@Home." If you have trouble, consult step 3 from <a href="http://lhcathome.web.cern.ch/join-us" target="_blank">this LHC@Home setup guide</a>.

3. Now that your computer is connected to CERN, we need to enable the special options for the KC Compute Challenge! Without this step, your computer will just perform "normal" jobs, not the jobs that are specially-created for gigabit fiber users. For users in KC with gigabit fiber internet connections, your turbo-charged internet can be put to use analyzing full datasets from the CMS experiment! Go to the <a href="https://lhcathome.cern.ch/lhcathome/prefs.php?subset=project" target="_blank">LHC@Home preferences page</a> and make sure you enable "Run test applications" and check the box for "CMS Simulation." We recommend that you do not check the other boxes for other applications unless you are having trouble running CMS jobs. The CMS jobs are specially made for gigabit fiber users, so in order to make the best use of a gigabit connection, select "CMS Simulation" only. Theory and Sixtrack jobs have lower requirements and are suitable for all users (not just gigabit users).

4. Finally, to participate in the CERN+KC Challenge, you must join "Team Kansas City!" The special jobs for fiber users are currently limited to participants on Team Kansas City, since this is a limited test. To join, go to the <a href="https://lhcathome.cern.ch/lhcathome/team_display.php?teamid=8410" target="_blank">Team Kansas City page</a>, log in to your account, and click "Join this team." Make sure <a href="https://lhcathome.cern.ch/lhcathome/home.php" target="_blank">your account page</a> says you've joined the team on the right side.

5. Now you're all set! Thanks for joining and happy computing! You can track your statistics and see how your computers' crunching ability ranks against others by logging in to the <a href="https://lhcathome.cern.ch/lhcathome/" target="_blank">LHC@Home BOINC site</a> or read more about the software at the <a href="http://lhcathome.web.cern.ch/" target="_blank">LHC@Home project page</a>. If you need more help or have questions, check out the <a href="http://lhcathome.web.cern.ch/faq" target="_blank">LHC@Home FAQ</a> and <a href="https://lhcathome.cern.ch/lhcathome/forum_index.php" target="_blank">LHC@Home forum</a>. Also, share this page:

<a href="https://twitter.com/intent/tweet?button_hashtag=CERNKC&text=Use%20your%20gigabit%20internet%20to%20analyze%20Large%20Hadron%20Collider%20data%20and%20help%20research%20in%20particle%20physics!" class="twitter-hashtag-button" data-url="https://cernkcchallenge.github.io/CernKCChallenge/">Tweet #CERNKC</a> <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>
<div class="fb-share-button" data-href="https://cernkcchallenge.github.io/CernKCChallenge/" data-layout="button" data-mobile-iframe="true"><a class="fb-xfbml-parse-ignore" target="_blank" href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fcernkcchallenge.github.io%2FCernKCChallenge%2F&amp;src=sdkpreparse">Share #CERNKC</a></div>

# Your Impact
The research at the Large Hadron Collider contributes to our fundamental understanding of the universe. Particle physics research also drives innovation in fields ranging from medical imaging and cancer treatment to homeland security and next-generation energy and transportation technologies. In fact, the World Wide Web was developed at CERN! <a href="http://www.symmetrymagazine.org/article/october-2013/why-particle-physics-matters" target="_blank">Read more about the wide-ranging impacts</a>. Contributing to this project is an easy way to help push the boundaries of physics and advance science!

# Contact
Get stuck? Having problems? First, consult the <a href="http://lhcathome.web.cern.ch/faq" target="_blank">vLHC@Home FAQ</a>. Second, let us know by <a href="https://lhcathome.cern.ch/lhcathome/forum_index.php" target="_blank">posting in the LHC@Home forum</a>.

<div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/en_US/sdk.js#xfbml=1&version=v2.6";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>
