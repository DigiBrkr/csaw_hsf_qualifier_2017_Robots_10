# Robots  
10 points
>As you found in his browser history, he's visited an interesting site
>My scraper for the Clearsoc site might've missed something...

## Solving it

The hint tells us that the challenge has something to do with web scrapers and the name of the challenge `robots`,  points us in the direction of the site's `robots.txt` file. This file provides instructions for web scrapers and search engines on how to treat the site you can read about it [here.](https://en.wikipedia.org/wiki/Robots_exclusion_standard)
So to solve the challenge we simply go to the site's `robots.txt` file at: https://clearsoc.hsf.csaw.io/robots.txt.
The link will probably be dead by time you are reading this, however, I've provided the files so you can play with them if you so choose.
And that gives our flag:
```
flag{h3ll0_roboragioto_s4n}
```
