# Welcome to the Scrapeally Project 

This is likely to be a set of tools with documentation of how one might use web scraping for accessibility (a11y)

## The Name 

As a [screen reader](https://axesslab.com/what-is-a-screen-reader/) user,
I like to use project names a speech synthesizer pronounces well.

As a software developer, I'm naturally bad at naming things (e.g., variables, functions, projects).

As a dad, my sense of humer ... 

Scrapeally is a combination of "scrape", for web scraping,
and "ally", for 
[a11y](https://www.a11yproject.com/about/#what-does-the-term-a11y-mean),
with the letter 'l' for the number one.

## High Level

I'm focusing on two tools, 
[Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) and
[Playwright](https://playwright.dev).

### (mostly) Static Sites 

If the site you want to parse is mostly static HTML, Beautiful Soup is probably what you want.
It's fast and  provides a nice interface.
I like to use Beautiful Soup to scrape static sites and organize the information in, what I think is, a more intuitive structure.
This is usually optimized for single letter navigation.

In [my domible project](https://github.com/joeldodson/domible),
the `dicli` tool (installed via pip as an extra)
has an option to parse all the HTML element references from 

### Dynamic Sites

###### end of scrapeally main page 