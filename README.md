# Non4ProfitDataGathering
Data gathering for large Non-for-profit organizations with many local  chapters

Ever wondered how your local chapter stacks up against the chapter from the next state over? Ever wanted to see how you do overall in the nation? Has your organization's board directed you to create a benchmark analysis? No? You say it's because gathering all that data would be costly and difficult? Well, you've come to the right place...

Turns out there is this wonderful thing called an IRS Form 990. Pretty much every nonprofit organization needs to fill one out every year. And all information can be accessed by the public. In the past decade we've started digitizing them and making them available online. Currently the data is hosted on Amazon Web Service and can be accessed by anyone with a little know-how. But the data can be stressful to work with. I myself have tried wrangling this beast of problem. I've made progress on a general solution but it's still lackluster. 

# What...?
Well, I wish I could offer you a complete product that will fulfill all your data wishes, but sadly, this is still a work in progress. 

In the meantime you should check out the following resources as they might be the quick fix you are looking for: 

If you are good with python then check out [990-xml-reader](https://github.com/jsfenfen/990-xml-reader). 

If you want  simple analysis checkout [ProPublica's Nonprofit Explorer](https://projects.propublica.org/nonprofits/)


# Issues I had back in the days
When I was gathering data was that the xpaths, line numbers, and variable descriptions changed all the time. One year a path would be called something like `Return.ReturnHeader.TaxPeriodEnd` and the next year it would be changed to `Return.ReturnHeader.TxPrdEnd`... That's not literally an example but you get the idea of how frustrating that can be. You'd think you could just Regex the data to death but you'd be suprised at just how time consuming that can be. Worst still, that won't help for when they change the xpaths again in the future. It's a neverending battle... 

So, It was hard to find a 'standardized' set of information. And then I found the 990-xml-reader which has a nice feature of outputing 'standardized' data in the form of a JSON file. I have yet to incorporate it yet. Working on that right now...

In the past I've primarily relied on my own mappings of IRS 990's ever changing fields into a standard field but it's just too time consuming and extremely error prone. So that's why I'm looking to the 990-xml-reader to assist in generating consistant data. 


### Now...
If you are still on this repo you'll only find half backed code. Don't expect it to be usable. In fact, don't expect anything at all. I mean, you could run the code, and it might work for you, but don't expect any useful results. So, comeback when I've actually made progress on this...
