RedditFPWAnalyzer
=================

###DEMO
http://www.tcnj.edu/~jamiesj1/rwa/

###DESCRIPTION:
A Reddit front page scraper that finds trending words from the top 25 posts (not user specific).

###LOOKING TO IMPLEMENT:
- [x] Longest words.
- [ ] Persistant data - keep the old data when the program is restarted.
- [ ] Display data graphically.
- [ ] Scrape specific subreddits.
- [x] Search for specific words and display their position in the trending list.
- [x] Better list of rejected words  - a lot still missing.

###KNOWN BUGS:
- [x] Posts titles with quotes in them are not properly searched for. Should be a simple fix.
- [ ] Data is lost between restarts.
- [ ] MEMORY LEAK? Hits 100% CPU and crashes after so many hours.
