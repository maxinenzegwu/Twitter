Project 3 - SimpleTweet

SimpleTWeet is an android app that allows a user to view their Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: 9 hours spent in total

## User Stories

The following **required** functionality is completed:

* [ ]	User can **sign in to Twitter** using OAuth login
* [ ]	User can **view tweets from their home timeline**
  * [ ] User is displayed the username, name, and body for each tweet
  * [ ] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
* [ ] User can **compose and post a new tweet**
  * [ ] User can click a “Compose” icon in the Action Bar on the top right
  * [ ] User can then enter a new tweet and post this to Twitter
  * [ ] User is taken back to home timeline with **new tweet visible** in timeline
  * [ ] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
* [ ] User can **see a counter with total number of characters left for tweet** on compose tweet page
* [ ] User can **pull down to refresh tweets timeline**
* [ ] User can **see embedded image media within a tweet** on list or detail view.

The following **stretch** features are implemented:

* [ ] User sees an **indeterminate progress indicator** when any background or network task is happening
* [ ] User can view more tweets as they scroll with infinite pagination
* [ ] User can **open the twitter app offline and see last loaded tweets**. Persisted in SQLite tweets are refreshed on every application launch. While "live data" is displayed when app can get it from Twitter API, it is also saved for use in offline mode.


## Video Walkthrough

Here's a walkthrough of implemented user stories:

![App Demo Link](https://github.com/maxinenzegwu/Twitter/raw/master/Kapture%202020-07-02%20at%2018.34.15.gif)

## Notes

Had some difficulty learning SQL to implement persistence

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright 2020 CodePath

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
