# Primitive Web
*Old tricks for the new web.*

Have you ever noticed how most science fiction films depict the future? There’s always new technology—new vehicles or weapons or languages that represent a leap forward in our ability to do things—but there always seem to be many things that come from the past. As if progress required a move backwards. As if people decided that an older way of working was for some reason better. Automated robots patrol an outdoor market where food is sold from decrepit wooden baskets and bins. Gravity-defying spaceships transport soldiers who fight with electric swords.

I want to propose an improvement to the way we use the internet—specifically the data that makes up the web and the way we consume it. And like those science fiction films, it requires us to take a step backwards. We should take what we’ve learned with us—all the protocols and frameworks and APIs and cloud services—and use this knowledge to see if there’s something we might have missed along the way, something that could make the web much more useful than it currently is.

---

If someone were to define the component of the web at its most atomic level, they would likely say a web page. Web pages often contain resources, of course, like text and pictures and videos, but most people would instinctively say the web is made up of web pages. If you were thinking of going surfing, you might check the ocean tides in your area or a web page that listed the local weather. If it’s something you frequently used, you would bookmark the web page that contained that data so you could find it easily. If you wanted to know the soup of the day at your favorite restaurant, you might bookmark the web page that lists their menu.

Both the weather and restaurant pages contain a lot of information, bits of data that you don’t need. The surfer may only need to know what time low tide is, but that piece of information is buried amongst water temperature, wind, and a hundred other things on the local weather page. They can bookmark the page, but notice, they cannot bookmark the data itself. The bookmark will get them close, but depending on the complexity of the page, they may still have a few more clicks or scrolls to find the actual bit of data they are interested in.

The times of upcoming low and high tides exist as data somewhere—useless variables without a meaningful context. The organization that provides the web page takes that data and combines it with other information in a way they feel will be most useful for those that need it. The resulting web page is useful for some people but represents needless complexity for others who only need a single point of data from the page.

Imagine if the surfer could bookmark and later access the exact piece of information they want—the timing of the ocean tides—without having to click and scroll and scan for the right bit of data. Imagine if the web developer was able to expose those bits of data in such a way that anyone (with no programming knowledge) could bookmark things and make use of them.

Now think of another person looking to see what their favorite restaurant’s soup of the day is. They have the restaurant’s page bookmarked, but the soup of the day isn’t actually listed. Why? Because it’s too much of a pain for the cook to log in to a website and update the values. So people have to call the restaurant directly and ask them over the phone what their soup of the day is. That data, a simple string of text— “French Onion Soup”—is there for the taking. But it takes so much work to get it. Even if their soup of the day was listed on the restaurant’s website, a hungry customer would still have to go to their site and scroll around until they found it.

Imagine if someone could find the soup of the day listed on the restaurant’s page and bookmark the soup of the day itself? Not the page, but the actual data point. That could be a better way to make use of the restaurant’s data. That person doesn’t need to make use of a fancy WordPress site, hosting, updates, themes, and PDF menus—they simply want to know what that restaurant’s soup of the day is.

> That’s a lot of technology being used some customers that often don’t want or need. Why is it necessary at all?

A web browser and all the hyperlinking throughout the web is meant for discovery. For serendipity. That’s great for when you’re looking for something. But what happens when you’ve already found it? What happens when you know what you’re looking for—the time of the next low tide or the soup of the day—you know exactly how to find it but don’t need hyperlinks, headers, footers, forward buttons or back buttons. You just want to consume a single piece of data. This is where the power and complexity of the modern web and browser become a hindrance. Most people don’t realize it, because it’s all they’ve ever known.

Recall what Henry Ford famously said. Slightly paraphrased, “If I would’ve built what people wanted, they would’ve asked for a faster horse.” He didn’t build a faster horse, but something entirely different—something most people would have never thought to have asked for. Most didn’t know cars or internal combustion engines existed. Others who had seen them knew they were too expensive for the average person to purchase. So, a better horse would have been all they could have imagined.

Because we’re going back in time, let’s forget about the concept of the web browser or web pages at all for a moment. Imagine an absolutely primitive web where there is no site or page for the surfer to check the tide charts. What they do have is a bookmark for a piece of data they care about. Rather than a web browser meant for discovery, they might have an app on their phone that simply displays the data they care about—nothing more. They are not browsing the web in any way—that would be much too fancy for our primitive throwback technology stack. They are simply consuming that single point of data—the local tide chart. A timestamp of the next low tide. A timestamp of the next high tide.

For the soup-lover hoping to score a delicious lunch, they also aren’t browsing the web. They have a URL to a specific piece of data—a string of characters that informs them what the restaurant’s soup of the day is. Rather than opening a web browser, clicking on a link to the restaurant’s page, then scrolling down to look for their phone number, they have opened a primitive web viewer that lists the updated data points they’ve saved. “French Onion Soup” the app displays. That’s all they need to know. This primitive web has become extremely useful to them.

Currently, for the cook at the restaurant, the complexity of updating the soup of the day is much worse than those who want to know what it is. The cook has to click on a link to the company website, then login with a username and password. They then have to go into an Admin interface and find the page that lists the soup of the day. Edit the text on the page, save the page, then exit out and preview the site to make sure the changes took effect.

If we extend our backwards journey one more time to the restaurant cook, let us once again remove the luxury of websites, web pages, and web browsers. Pretend they don’t exist yet. The cook wants to update a single listing, and to do that, things have gotten much more simple. They open their app and click on the soup of the day text field. They type in a new value and hit save. Anyone who has the URL for that data point saved somewhere will see the new value anytime the next time they access it. They might even receive an update that it changed.

These two bits of data—the local tide charts and a soup of the day listing—might provide some usefulness to people, but real gains appear when many other data points surface within this primitive web. What’s the temperature outside? Is your restaurant open or closed right now? What’s the latest Bitcoin price? Think of all the points of data we might consume on any given day. Think of being able to bookmark those specific bits of information rather than the web pages they might be buried within.

Without the encumbrance of traditional websites and web pages, creating and consuming data might become much easier and more personal: It might rain—is my child’s sports practice canceled or not? Thankfully, the soccer coach has published this tiny bit of data on the primitive web and you have it bookmarked. It is an on/off switch: Soccer Practice is ON. The coach has no tricky WordPress site or group texting software to manage. Just a flick of a switch on their phone and everyone who has bookmarked that “primitive” will know what’s going on.

## What are primitives?

If you can envision the primitive web, then consider what primitives are—the most basic building blocks of any programming language. For the primitive web, these might be variables that hold different types of information: strings, numbers, Booleans, arrays, and timestamps. With those variable types, much of the data people consume on the web any given day can be expressed.

They might even be nested or combined into more complex structures. Our soup-loving friend could create a primitive array that contains the soup of the day from several other restaurants. Anyone can bookmark that person’s array and see several soup listings from all over town. No one had to create a website or remember a login or password—they just used the web in its most primitive form. Others might create lists of their favorite primitives: concert dates for a band or a list of places that have the latest video game console in stock. With a simple app to create or consume primitives, the web might achieve a usefulness that would be impossible within its current iteration.

This simplification in the way data is produced and consumed on the web improve its utility in many ways. But what about the discovery? The web cannot exist solely as primitives—it would be unusable. Like our favorite science fiction movies, there must be a way to bring this seed of an idea back to the present and combine them in such a way others can benefit.

Combining the primitive web with the future
If we now come back to the present, and possibly to the near future, we should consider how we might integrate the primitive web, with its stripped-down strings and numbers, into the complexity of what we use every day. In order to do that, we should explore for a moment what a primitive actually might be.

A basic implementation of a web primitive might be a simple JSON object:

```
{
  "Name": "Next Wrightsville Beach Low Tide",
  "Type": "DateTime",
  "Value": "2022-01-01 11:21:15",
  "LastModified": "2021-12-31 19:05:09",
  "Owner": "classicalglass1993",
  "Id": "98630f1f-5c9a-47f6-9e7a-4fe3880e7114"
}
```

 And the URL to access this primitive:
```
  primitive.web.com/98630f1f-5c9a-47f6-9e7a-4fe3880e7114
```
Web primitives would likely be publicly accessible but privately editable. If seeing this data and URL makes you think of an API, that’s probably a good thing. The primitive web is made of up extremely simple endpoints that anyone can create and consume. Purpose-built apps might make the data look prettier, but even the raw JSON would be basic enough for someone to make sense of should they hit the URL directly in a modern web browser. Browser plug-ins could style raw web primitives so that they appear more user-friendly.

By itself, the primitive web would make finding things difficult. It is built for the creation and consumption of basic points of data, not their discovery. That’s what the traditional web is good at with its searching and hyperlinks. Once you find something useful, the traditional web falls short because you can only bookmark web pages, not the data itself.

There are many ways to leverage the simplicity of the primitive web with the discovery of the traditional web. Developers might tag data points on a given web page as primitives in such a way enabled browsers could detect their presence and offer users a way to bookmark them. WordPress plug-ins might make this process simple enough for basic users. Browser plug-ins might offer advanced functionality for scraping data from a web page and directing it into a primitive.

Traditional websites could list and rank primitives by category or popularity. Web developers could incorporate externally-created primitives into their sites. Advanced primitive publishers might come up with a way to monetize their data by charging developers for access.

Purpose-built apps would show—at a glance—the datapoints the user has saved. They could make creating primitives simple enough for anyone to use—a single endpoint API in less than 60 seconds. Create Boolean. Name it. Label it—"On/Off” or “Open/Closed”—and publish it. URL copied to clipboard, ready to share with your friends and family and beyond.


Like lightsabers and wooden food stands, the primitive web is not meant to replace current technology but augment it. It takes a simple concept from long ago and injects it into an aging infrastructure that could benefit from less complexity. “Adding lightness,” as Lotus racing engineers—searching for anywhere they could drill more holes in things—would call it.

Despite what the old saying implies, occasionally something does come along and is able to teach an old dog a new trick. The world wide web is now over 30 years old—ancient within a technological timeline. Perhaps we can teach it something new: strings, numbers, Booleans, arrays, and timestamps, some of the oldest tricks in the book.

