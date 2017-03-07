# Building a CLI Gem Walk through
​*This video walks through the process of planning and building a CLI Gem.*​

*There will be more videos on the process of building a more complex Gem as well as on refactoring and improving a CLI Gem

## Objectives

1. Planning your application
2. Generating and setting up a basic Gem
3. Basic CLI User interface
4. Setting up your Objects
5. Setting up your Scraper
6. Bring it all together!


## Video

<iframe width="100%" height="720" src="https://www.youtube.com/embed/_lDExWIhYKI?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

[MP4](Needs Upload)


## Summary

* Planning the Gem
* Beginning the Gem building process
 * Setting up or generating the basic structure of the Gem
 * Creating and stubbing out the executable file 
* requiring files - `require` and `require_relative`
* Coding the CLI Class - our Controller
 * Stubbing out the CLI Class with hardcoded return data - here doc 
 * Creating the menu
* Setting up our Deal Class
 * Today method to return todays deals
 * stubbing out our first deal instances with hardcoded data
 * setting up the deal class attributes
* Testing our data in console
* wire our menu with conditional to work with our deals array
 * iterate and display deals
 * fix spelling on availability
* Setting up our scraper class - Deal class method or individual class?
 * set up `Deals#scrape_deals` method
* Adding gem dependencies to the app
 * Add dependecies to gemspec
 * development dependencies or regular dependencies
* code individual scrape methods for each site
 * Use css selectors to scrape desired information
 * create new deal object and set it's attributes based on scraped info
 * logic for availability
* final thoughts and tips on building process

## Code

- [Daily Deals Gem repository](https://github.com/learn-co-curriculum/daily_deal)
<p class='util--hide'>View <a href='https://learn.co/lessons/oo-cli-data-gem-walkthrough'>OO CLI Data Gem Walkthrough</a> on Learn.co and start learning to code for free.</p>

<p class='util--hide'>View <a href='https://learn.co/lessons/oo-cli-data-gem-walkthrough'>CLI Data Gem Walkthrough</a> on Learn.co and start learning to code for free.</p>
