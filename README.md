# DPfinder
Finds "Dead Posts" in a VBulletin Forum. Dead Posts are posts with dead links.

DPfinder generates an HTML report which is a summary of the posts with dead links and a link back to the offending post so moderators and admins can edit/delete/move that post.

It saves time by finding the posts for you instead of you having to go thru pages of threads, open each thread, and go thru pages of posts. You run it from the command line and give it the URL for a page of threads, or for and individual thread.

It does BASIC link checking, some hosts can't be checked yet. You see a text version of what is seen in the HTML report as it progresses thru the list of threads.

DPfinder requires Python 3 and has only been tested on FreeBSD, but should run on any Linux variant, and with some testing it might work on Windows with Cygwin.

Once setup correctly, if you have WAR Link Checker installed in your browser, you be able to see the status of the links from the report, otherwise you'll need to click the link for each post and visit the original forum page before you can see the link status. Most browsers block javascript from running in local HTML files. WAR Link Checker uses Javascript to check links, so there is a simple work around.
