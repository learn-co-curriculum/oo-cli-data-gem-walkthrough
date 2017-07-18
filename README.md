# Building a CLI Gem Walkthrough
This video walks through the process of planning and building a CLI gem. There will be more videos on the process of building a more complex gem as well as on refactoring and improving a CLI gem.

## Objectives
1. Planning your application
2. Generating and setting up a basic gem
3. Basic CLI User interface
4. Setting up your Objects
5. Setting up your Scraper
6. Bring it all together!

## Video
<iframe width="100%" height="720" src="https://www.youtube.com/embed/_lDExWIhYKI?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

## Summary
- Planning the gem.
- Beginning the building process.
  + Setting up or generating the basic structure of the gem.
  + Creating and stubbing out the executable file.
- requiring files with `require` and `require_relative`.
- Coding the `CLI` class — our controller.
  + Stubbing out the `CLI` class with hard-coded return data.
  + Creating the menu.
- Setting up our `Deal` class.
  + `#today` method to return today's deals.
  + Stubbing out our first `Deal` instances with hard-coded data.
  + Setting up the `Deal` class attributes.
- Testing our data in the console.
- Wire up our menu with conditional logic to work with our array of deals.
  + Iterate over and display deals.
  + Fix spelling on `#availability`.
- Setting up our scraper class — should we use a Deal class method or a standalone class?
  + Set up `Deals#scrape_deals` method.
- Adding gem dependencies to the app.
  + Add dependencies to gemspec.
  + Development dependencies or runtime dependencies?
- Code individual scrape methods for each site.
  + Use CSS selectors to scrape desired information.
  + Create new `Deal` objects and set the attributes based on the scraped info.
  + Update logic for `#availability`.
- Final thoughts and tips on the building process.

## Code
- [Daily Deals Gem repository](https://github.com/learn-co-curriculum/daily_deal)

<p class='util--hide'>View <a href='https://learn.co/lessons/oo-cli-data-gem-walkthrough'>Building a CLI Gem Walkthrough</a> on Learn.co and start learning to code for free.</p>
