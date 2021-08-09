# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS


#  Local Storage
 ersistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions

## A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5
 In the beginning, there was only Internet Explorer. Or at least, that’s what Microsoft wanted the world to think. To that end, as part of the First Great Browser Wars, Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.



## INTRODUCING
What I will refer to as “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter.

## HTML5 STORAGE SUPPORT

- IE 8.0+	
- FIREFOX 3.5+
- SAFARI4.0+
- CHROME4.0+
- OPERA10.5+
- IPHONE2.0+
- ANDROID2.0+



# How does localStorage work?
To use localStorage in your web applications, there are five methods to choose from:
1. setItem(): Add key and value to localStorage
2. getItem(): This is how you get items from localStorage
3. removeItem(): Remove an item by key from localStorage
4. clear(): Clear all localStorage
5. key(): Passed a number to retrieve the key of a localStorage


***What we really want is***
* a lot of storage space
* on the client
* that persists beyond a page refresh
* and isn’t transmitted to the server