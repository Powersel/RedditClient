# RedditClient
Reddit application for MacOS

Your assignment is to create a simple Reddit client that shows the top entries from https://www.reddit.com/top
To do this please follow these guidelines:
- Assume the latest platform and use Swift
- Please refrain from using AFNetworking, instead use NSURLSession - Support landscape
- Use storyboards
The app should be able to show data from each entry such as:
- Title (at its full length, so take this into account when sizing your cells) - Author
- Entry date, following a format like “X hours ago”
- A thumbnail for those who have a picture
- Number of comments
In addition, for those having a picture (besides the thumbnail), please allow the user to tap on the thumbnail to be sent to the full sized picture. You don’t have to implement the IMGUR API, so just opening the URL would be OK.
Also include:
- Pagination support
- Saving pictures in the picture gallery - App state-preservation/restoration
- Support iPhone 6/6+/X screen size
Note:
Please refrain from using external libraries (by way of using CocoaPods and similar), as we want to see your coding skills as much as possible :)
Some resources:
- Reddit top feed: https://www.reddit.com/top.json
- Reddit API (accessible via Chrome): https://www.reddit.com/dev/api
