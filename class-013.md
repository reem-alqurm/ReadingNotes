
# “The Past, Present, and Future of Local Storage for Web Applications”

![Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSnJH1mQBJpwumU3uRVgCubx_jp_5TUNj6qMA&usqp=CAU)

* web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

 - Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.

* What we really want is

- a lot of storage space 
- on the client
- that persists beyond a page refresh
- and isn’t transmitted to the server.

## USING HTML5 STORAGE

* HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string.
* If you are storing and retrieving anything other than strings, you will need to use functions like `parseInt()` or `parseFloat()` to coerce your retrieved data into the expected JavaScript datatype

## TRACKING CHANGES TO THE HTML5 STORAGE AREA

* If you want to keep track programmatically of when the storage area changes, you can trap the storage event.
* The storage event is fired on the window object whenever `setItem()`, `removeItem()`, or `clear()` is called and actually changes something. For example, if you set an item to its existing value or call `clear()` when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.

*****************************************************************

## [ Home ](https://reem-alqurm.github.io/ReadingNotes/)
