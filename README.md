# ArticleSearch_Part-2
This project is designed to run the same way as the first article search project, but it's been modified to run even if it's in airplane mode.
## Required Features

The following **required** functionality is completed:
- [x] Most recently fetched data is stored locally in a database
- [x] If user turns on airplane mode and closes and reopens app, old data from the database should be loaded

The following **optional** features are implemented:

- [ ] Add Swipe To Refresh to force a new network call to get new data
- [ ] Add setting toggle for user to create preference for caching data or not (Using Shared Preferences)
- [ ] Implement a Search UI to filter current RecyclerView entries or fetch data from the search API with query
- [ ] Listen to network connectivity changes and create a UI to let people know they are offline and automatically reload new data if connectivity returns

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src="https://i.ibb.co/QD6zQ4h/Article-Search-Part2-Test.gif" alt="Article-Search-Part2-Test" border="0">


## Notes

The main challenge was figuring out which parts to update for MainActivity, DetailsActivity, and ArticleAdapter and how to update it.

## License

    Copyright [2023] [Codepath]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
