# Geocaching small game
(empty project)

## How to create a new game

### Setup
* Fork the repo
* Configure GitHub pages on forked repository

### Design 
* Open https://[yourAccount].github.io/[forked repository name]/generator.html
* For each place
   * Go to location
   * Shoot a detail
   * Press Add button
   * Add hint message for this location
   * Loop
* Replace places.js by generated code displayed on page
* Rename all pictures 0.png, 1.png, ...
* Commit and push all changes

### Test
An easy way to test :
* Record all your places
* Use the "copy to clipboard" feature and Github web UI to update places.js from your mobile device
* Open https://[yourAccount].github.io/[forked repository name]/index.html?reverse=1
* Walk the complete reversed path "end from start" to test all the GPS recorded locations

### Play
* Open https://[yourAccount].github.io/[forked repository name]/
* Play
   * Cheat mode : once page is displayed, add &debug=1 at then end of the URL
