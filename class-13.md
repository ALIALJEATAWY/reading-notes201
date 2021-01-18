# HTML

## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS


***ersistent local storage is one of the areas where native client applications have held an advantage over web applications.***


* ***Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:***

* *Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:*

* *Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)*

* *Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful*



### A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5


***In the beginning, there was only Internet Explorer. Or at least, that’s what Microsoft wanted the world to think. To that end, as part of the First Great Browser Wars, Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.***



### INTRODUCING HTML5 STORAGE

*t’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site.*




***HTML5 STORAGE SUPPORT***
*IE* *FIREFOX* *SAFARI* *CHROME*  *OPERA* *IPHONE* *ANDROID*
8.0+	3.5+	4.0+	 4.0+	  10.5+	   2.0+	     2.0+



**HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string.**




