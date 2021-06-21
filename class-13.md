![img](https://clementbuchanan.github.io/reading-notes/images/html5.jpg)

## What is HTML5 storage?

It’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. HTML5 storage is more secure. Some refers to it as Local Storage or DOM Storage. It does support the folowing browsers:

- IE 8.0+
- Firefox 3.5+
- Safari 4.0+
- Chrome 4.0+
- Opera 10.5+
- Iphone 2.0+
- Android 2.0+


![web](https://image.slidesharecdn.com/webstorage-180528082855/95/html5-web-storage-2-638.jpg?cb=1527496583.png)

### What is HTML Web Storage?

With web storage, web applications can store data locally within the user's browser.

Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.

Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

### Local storage before HTML5

Before HTML came about userData allows web pages to store up to 64 KB of data per domain.

Flash objects were created to store up to 100 KB of data per domain.
Flash-to-JavaScript bridge called AMASS (AJAX Massive Storage System), was invented but it was limited by some of Flash’s design quirks.
By 2006 accessing LSOs from JavaScript became an order of magnitude easier and faster.
Flash gives each domain 100 KB of storage “for free.” Beyond that, it prompts the user for each order of magnitude increase in data storage (1 Mb, 10 Mb, and so on).

#### Web applitions only option is to store data as cookies which have downsides:

Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.

![cook](https://navigators.com/priv_browser.gif)

### The future of HTML5
Currenly the future looks good for HTML5 but there is more to life than “5 megabytes of named key/value pairs,” and the future of persistent local storage and there are competing visions. One vision is SQL. In 2007, Google launched Gears, an open source cross-browser plugin which included an embedded database based on SQLite. This influenced the creation of the Web SQL Database. Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database, allowing you to store code from JavaScript.