# Resource Hub - Jared Hasen-Klein
#### This is the repository for the new version of the Resource Hub, live as of May 17, 2019. The current version of the site is at [hub.jaredhk.com](http://hub.jaredhk.com).

## Purpose of transition
* Before the transition, there were two ways the resources were stored:
  1. On individual sites (e.g. fll18.jaredhk.com, deepspace.jaredhk.com)
  2. On "mini sites" of the Resource Hub (e.g. hub.jaredhk.com/sites/frc2016)
* The mini-sites all look different and most of them look bad. This is because of a lack of CSS and time spent copying and pasting.
* The full sites look good but are confusing to find and not cohesive
* This project hopes to unify all of those sites

## Goals of the new site
* Faster page load times
* Better appearance
* Easier to find content
* Better tracking (links, downloads, etc.)
* Unified look and feel
* Encourage users to look at other resources beyond their program

## Framework, layout, etc.
#### CSS/JS
* Twitter Bootstrap
#### Links,  files, embeds
* Links use `/redirects/program/year/page.html`
* Generally, external links to other websites will not go via redirects. These don't need to be tracked as closely and also likely won't change on the other end. For example, linking to Techbrick will not have a redirect URL but linking to a Google Sheet calculator will.
* Files are either stored on Google Drive and generated for download, One Drive and generated for download, or at `/files/program/year/page.html`
* Calculators are embedded from One Drive and exposed via JS

## Contributing
I am a full time student and work on this project for the sole reason of the fact that I wish these resources existed when I was competing in robotics and I know they help others. I also take big inspiration from the resources that _were_ available to me (hey, Techbrick!) and want to continue that legacy. That being said, this is all a volunteer project that I can only work on when I have time. I would love your help. Here's how you can be helpful:
### Reporting Bugs
Whether you are technical or non-technical, you can report bugs you encounter on the site using the ([Issues](/../../issues) tab on GitHub. These issues can be typos, broken links, wrong point values on a calculator - anything!
### Fixing Issues - Pull requests welcome!
If you are technically inclined, I would love help dealing with the issues and anything else you see fit. Submit a pull request and I will gladly take a look. The framework for the site is very simple so if you know any HTML, you should be able to pick it up very quickly. If you need help, feel free to ask!
### Creating content
Currently, there is no way to directly get help with most of the resources on this site. That's because most resources are stored externally (e.g. on spreadsheets) which make them hard to collaborate on. However, if you have new resource ideas or problems with current resources, definitely open an issue so we can discuss. I am more than happy to work with you to try and find a way that you can help. I am also looking to decrease dependency on external services. So, if you are interested and looking for a big project, start playing with calculators, game tests, or anything else and figure out how to make them with just HTML, JS, and CSS!

## Todo
### Redirects of old sites
### Longer term
- [ ] Upgrade to Font Awesome 5
- [ ] Create contributing guidelines
- [ ] Add feedback buttons on each page (maybe)
- [ ] Make future calculators not spreadsheet based (maybe)
- [ ] Universal footer
- [ ] Universal updates box for each program
- [ ] Condense Bootstrap 3/4, condense CSS
- [ ] Transfer private/systems to somewhere on this site (maybe) #10
