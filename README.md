Thanks, in advance, to whomever reads this narrative and provides feedback. I'm hoping some of the feedback will include how better to generate such a narrative.

A thought - Can someone demo how to ask for help on Slack?

To prepare the for the homework, I first went back and rewatched all the lectures, replicating on my own every example covered in class. I became more comfortable with .git, figuring out that our class repo is solely on gitlab. I was confused where the repo resided after completing a class exercise creating a class repo on github.

On to the project at hand, I read it over and decided to tackle first the things I believed easiest for me.

Googling, I generated a favicon and added it to the site. I also found some code that would automatically populate the current year in the copyright, as it was showing as 2019.

I added a <meta> tag with a site description.

I also edited the index.html <title>, employing a convention I saw in other SEO company websites.

Looking over the assignment and reading online for good alt= descriptions, I generated some of my own for the site and added them to index.html. I also used tineye to look up the images to see if there was any particularly good alt= content to influence my own. I didn't find much, I imagine that's because the images are stock.

Next up, I tried changing many div tags to semantic tags and altering the .css to address that change. In so doing, I rendered the website much worse off than before. Evidently, I'm still unclear about elements, classes, and ids in css.

Also, during this semantic tag substitution process, I realized I do not have a good, efficient method for implementing, testing and, either approving or rejecting a changes to my code. My understanding is that I need to save the index.html in order for changes to take effect before I open the index.html in my default browser. That said, I'm happy to have started picking up some keyboard commands for repetitive tasks. I toggle word wrap in Visual Studio Code by option-z and open an index.html in the browser with option-b. Anything to avoid the mouse.

There was an issue, too, with my index.html being cached in Chrome, I believe, because when I removed the favicon code, saved, and reloaded in Chrome, the favicon was still present in the browser tab. After I cleared my browsing data, the favicon was cleared. I'd like to create an environment in which Chrome is only showing me the most current version of whatever I'm requesting be displayed, without, what I assume, are cached files, including those showing up in the tab, like the favicon. I wonder if any of my index.html refreshes looked like the previous version because the file was cached.

Realizing I was in way over my head, I Googled looking for sites looking like the one I was editing. I came across something similar, but I couldn't translate it to all the specifics of the homework.

Then, realizing Horiseon is a pretty rough play on words (is that what it is? it's not a portmanteau...), I Googled it and "refactor." Out came a few various versions of refactoring this assignment, as well as past students asking for help on message boards!

I found https://github.com/jorguzman100/01_Code_Refactor_JGR, and really appreciated the clarity of his readme (other than the misspelled "aknowledgement" at the end).

Reading over Mr. Guzman's index.html, style.css and README.md, I start to get a better idea of what I lack in terms of strategizing how to tackle an assignment like this. Up until this point, most of our work has focussed on generating content. I'm not yet sure how to tackle fixing problems I didn't create without creating a host of new issues!

All this said, credit to Mr. Guzman. I copied his code into my own, substituted my alt= descriptions, added the favicon, copyright year, and that brings us up to date. I should say, I'm not entirely sure how well his code satisfies the assignment, but the website loads, which is better than where I was before I sought solutions on Google.

Given the opportunity to do this again - something I'll afford myself this week, I think I'd be more aggressive about pursuing setting up the best process to tackle this task. I haven't done so yet because I'm hesitant to ask questions in class, knowing everyone's ponied up $10K to be there. When I rewatch the videos and hear myself trying to ask questions I don't even know how to form with the correct jargon, it's pretty painful. I also find myself thinking "just Google this."

I've recently added a second monitor, which has allowed for my being able to navigate simply taking class over Zoom. That first week and a half was partially lost on me from all the mis-tabbing back and forth on my 13" MacBook Air.

I am willing to pay someone for one-on-one tutoring to help get me up to speed. My impression is that most of my classmates either have prior experience or have figured out how to catch up. I'm confident I can approach their level pretty quickly, given the opportunity to one-on-one with someone.

Alright. Now I'm going to attempt to push all of this up to .git and submit the repo link and URL through the homework page.



# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
