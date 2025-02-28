# tabscrape

Playground for scraping, parsing and presenting chords and tabs in the terminal


### Why?
While I've been tacitly willing to trade tranches of my personal data in exchange for community-provided (_gratis_) chords and tablature for many years now, things have really gotten out of hand. 

Somewhere among the perceptual nightmare of its popup banners, deceptive design patterns and casual abuse of RAM, visiting sites like UG has become an almost insulting experience. I just want the damn text. 

And thus arrives tabscrape: hopefully a fruitful tool by itself as well as a project to serve as my intro to web scraping.

### Goals
- Planned fzf integration for tablet-friendly TUI.
- Try out different scrapers + scraping methods
- Experiment with presentation of formatted output (TUI, epub/pdf, typst, etc.)



## Reference / Inspiration

### Alternative UG front ends

- https://github.com/kmille/freetar
  - https://freetar.de
  - (uses BeautifulSoup)
- https://github.com/zachpmanson/penultimate-guitar
  - https://pg.zachmanson.com
- https://github.com/BenoitBellegarde/UltimateTab
  - https://ultimate-tab.com

### UG Purpose-built Scrapers / Downloaders

- https://github.com/maTurjo/webScraperGuitar
- https://github.com/jabbey1/UGDownloader

### General-purpose Scrapers

__Python__
- https://www.crummy.com/software/BeautifulSoup/bs4/doc/


__Rust__
- https://github.com/Y2Z/monolith
- https://github.com/mattsse/voyager
- https://github.com/utkarshkukreti/select.rs
- https://github.com/spider-rs/spider
- https://github.com/rust-scraper/scraper
  - uses Servo
  - Example: https://github.com/gregstoll/rust-scraping
- https://github.com/fefit/visdom
- (old?) https://github.com/dermesser/scrapeprice


__Browser automation tools__
  - https://github.com/puppeteer/puppeteer
  - https://github.com/microsoft/playwright


__Parsers__

(ToDo)
