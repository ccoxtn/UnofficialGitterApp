# Overview

This is a simple unofficial Android client for [Gitter](http://gitter.im)

This app is written in C# with Xamarin, I don't have the nerves for Java.  
It will also probably only take about 10 minutes to get this running on Windows Phone.

# What works?
- Room selection
- Message viewing
- Message sending

# What doesn't work?
- Message streaming. It currently polls the messages every 10 seconds or after sending a message and resets the screen
- The OAuth flow shortly redirects to a 404 page, just wait till the room selection is displayed
- If there's any error anywhere, the app will blow up and crash
