# YourParkingSpace Android Tech Test

## Scenario
You are asked to build a simple app, which allows the user to view new posts submitted to the `r/technology` subreddit. 

## Requirements
The app will load and display the new posts from the Technology subreddit using the [Reddit API](https://www.reddit.com/dev/api/). You can use [https://www.reddit.com/r/technology/new.json](https://www.reddit.com/r/technology/new.json) to get posts.


1. Fetch and display posts in a vertical scrolling list with the most recent first on app open, with a loading indicator during the fetch operation.
2. Each post item should display the author, posted duration timestamp, title, image, link flair label and show a numeric index number indicating it's position in the displayed list.
3. If the user scrolls to the bottom of the list, the app should load the next page of results (Refer to the API docs for pagination details). We would prefer if you DO NOT use the android paging library for handling this.
4. Support pull to refresh, such that all posts are cleared and the latest first page of data is fetched again.
5. If the user taps on a post, they should be taken to a post details screen showing full timestamp when the post was created, number of up votes and down votes, number of comments in addition to all info on the list item.
6. Handling errors and loss of network connection.
7. Unit Tests

## Expectations
* Usage of a layered MVVM or Clean architecture, with well-defined data, domain and presentation layers.
* Good use of Jetpack Compose and Coroutines.
* Proper use of abstraction and dependency injection for making code easily testable.
* Well structured, reusable code that is easy to understand and maintain with good separation of concerns.
* Regular small commits to Git with meaningful messages.
* We expect you to use the latest release version of Android Studio.

## What to submit
* A bundled / archived repository showing your commit history, for example:

```git bundle create <yourname>.bundle --all --branches```

* A covering note that explains the technology choices you have made
* #### IMPORTANT NOTE: If you create an online repository for this task on Github, Bitbucket, etc kindly ensure that it is kept `private` at all times.

## Bonus Points

* Offline support / caching
* While you won't be assessed on your design choices, Its always good to have a nicer looking UI that handles missing images and scales well for different screen sizes or orientation.

