# MovieApp
This is a movies app displaying box office and top rental DVDs using the [Rotten Tomatoes API](http://developer.rottentomatoes.com/docs/read/JSON).

Time spent: `8 hours`

### Features

#### Required

- [ ] User can view a list of movies. Poster images load asynchronously.
- [ ] User can view movie details by tapping on a cell.
- [ ] User sees loading state while waiting for the API.
- [ ] User sees error message when there is a network error
- [ ] User can pull to refresh the movie list.

#### Optional

- [ ] All images fade in.
- [ ] All images should be cached in memory and disk: AppDelegate has an instance of `NSURLCache` and `NSURLRequest` makes a request with `NSURLRequestReturnCacheDataElseLoad` cache policy. I tested it by turning off wifi and restarting the app.
- [ ] Customize the highlight and selection effect of the cell.
- [ ] Add a tab bar for Box Office and DVD.
- [ ] Add a search bar: Missing
