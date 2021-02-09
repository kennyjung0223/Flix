# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF
<img src="https://imgur.com/TE7wN4X.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app.
while testing my bonus feature, I kept consoling some weird NIL error, so I decided to print out the movie and found that for one of the movies, its backdrop_view was nil, so I fixed it by performing a tertiary operator to use the poster_path view if there was no backdrop_view.

also, I really wanted to complete the second bonus but will have to revisit another time when I have more time to spare.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF
<img src="https://i.imgur.com/gwHQSVe.gif" width=250><br>
<img src="https://i.imgur.com/N4y2Mjp.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app.
accidentally deleted all my work when I initially pushed to GitHub, had to redo my project
