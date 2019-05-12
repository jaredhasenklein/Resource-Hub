# Resource Hub - Jared Hasen-Klein
#### This is the repository for the beta version of the Resource Hub. The current version of the site is at [hub.jaredhk.com](http://hub.jaredhk.com). The beta site is at [hub.jaredhk.com/beta](http://hub.jaredhk.com/beta).

## Purpose of transition
* Currently, there are two ways the resources are stored:
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
* Twitter Bootstrap
* Links use `/redirects/program/year/page.html`
* Files are either stored on Google Drive and generated for download, One Drive and generated for download, or at `/files/program/year/page.html`
* Calculators are embedded from One Drive and exposed via JS

## Todo
### Before launch
- [ ] Favicons #2
  - [ ] Make a favicon
  - [ ] Apply it to every page
- [ ] Standardize meta info for each page #3
- [ ] Create a LEGO timer (based on fll18.jaredhk.com/timer) #4
- [ ] Add Robomats promotion where needed #7
- [ ] Add evergreen/common resources to index (diversity, STIMS, etc.) #8
- [ ] Transfer private/systems to somewhere on this site (maybe) #10
- [ ] Redirect old sites to appropriate pages on new site #11
- [ ] Make project open source and add GitHub link to footer #12
- [ ] Boostrap 3 and 4 are used. Figure out how to condense #13
- [ ] Create `robots.txt` #14
- [ ] Change from beta directory to primary #9
- [ ] Last step: check all links and verbiage #16
### Longer term
- [ ] Upgrade to Font Awesome 5
- [ ] Create contributing guidelines
- [ ] Add feedback buttons on each page (maybe)
- [ ] Create universal email list for all programs (maybe)
- [ ] Make future calculators not spreadsheet based (maybe)
- [ ] Universal footer
- [ ] Universal updates box for each program
