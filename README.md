# YourParkingSpace Android Tech Test

## Scenario
You are asked to build a simple app, which allows the user to view posts submitted to the r/Android subreddit. 

## What we require
You will build an app that works across a range of device sizes.

The app will load the current hot submissions from the Android subreddit using the [Reddit API](https://www.reddit.com/dev/api/). You can use [https://www.reddit.com/r/Android/hot.json](https://www.reddit.com/r/Android/hot.json) to get posts.


1. Fetch and display posts in a vertical scrolling list with the most recent first on app open, with a loading indicator during the fetch operation. 
2. If the user scrolls to the bottom of the list, the app should load the next page of results (Refer to the API docs for pagination details).
3. If the user taps on a post, they should be taken to the details of the post on reddit.
4. Each post should give attribution to the author

## Expectations
* Usage of a layered MVVM or Clean architecture, with Coroutines and Jetpack Compose.
* Well structured, reusable code that is maintainable and testable.
* Regular small commits to Git with meaningful messages.
* We expect you to use the latest release version of Android Studio.

## What to submit
* A bundled / archived repository showing your commit history, for example:

```git bundle create <yourname>.bundle --all --branches```

* A covering note that explains the technology choices you have made

## Bonus Points

* Unit Tests
* Offline support / caching
* While you won't be assessed on your design choices, Its always good to have a nicer looking UI that scales well for different screen sizes or orientation.

