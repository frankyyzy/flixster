# Flixster

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src="http://g.recordit.co/WCBDBsUMOF.gif" width=250><br>

### Notes
It took me a while to configure how the assistant editor works.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthough GIF

<img src="http://g.recordit.co/w0JyJQCRnc.gif" width=250><br>

### Notes
I was stuck for a while as the poster images are not showing up after I followed the tutorial. I then realized that I didn't put the size after the URL.
Another issue I had is that I made a typo about a variable and after I realized it and changed all instances of the variable the code won't compile. I later realized that it's the problem that the objects are not associated with the correct variables any more as the variable is an outlet for label in my main storyboard.
