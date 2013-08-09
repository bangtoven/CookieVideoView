CookieVideoView
===============

Extension to Android VideoView. Adding session cookie header to request.

Features
--------
- Add cookie header to the request which VideoView makes. (Native Android VideoView doesn't do this.)
- Find proper cookie value based on requesting URI's domain.

Notice!!
--------
- This library requires loopj's "[Android Asynchronous Http Client](http://loopj.com/android-async-http/)".
- You have to maintain cookies with **com.loopj.android.http.PersistentCookieStore** class

Usage
-------
- (in java) Import **com.bangtoven.cookievideoview.CookieVideoView**
- (in java) Change **VideoView** to **CookieVideoView**
- (in xml) Change **VideoView** to **com.bangtoven.cookievideoview.CookieVideoView**
- That's it!
