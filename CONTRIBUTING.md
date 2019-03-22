# Contributing
Changes and improvements are welcome! Feel free to fork and open a pull request.

Please follow the house rules to have a bigger chance of your contribution being merged.

## House rules

### How to make changes
 - To make changes, create a new branch based on `master` and create a Pull Request to master. Do not create one from `gh-pages` unless strictly necessary.
 `gh-pages` is different from master. It contains sharing features, analytics and other things that have no direct bearing with the game. `master` is the "pure" version of the game.
 - Please edit the SCSS files present in `style/`: `main.scss` and others if you want to modify the CSS. Don't edit the `main.css` because it's supposed to be generated.  
 Use the `sass` gem to compile your SCSS modifications. Install the `sass` gem by running `gem install sass` once Ruby is installed.  
 To run SASS, use the following command:  
 `sass --unix-newlines --watch style/main.scss`  
 SASS will automatically recompile css when changed.
 - `Rakefile` contains some helpful tasks for development. Feel free to add tasks if needed.
 - Please use 2-space indentation when editing the JavaScript. A `.jshintrc` file is present to help the code to follow the guidelines if installing and running `jshint`.
 - Please test modification thoroughly before submitting a Pull Request.

### Changes that might not be accepted
We have to be conservative with the core game. Modifications will be evaluated carefully before being merged. Some modifications won't be merged.

 - Undo/redo features
 - Save/reload features
 - Changes to how the tiles look or their contents
 - Changes to the layout
 - Changes to the grid size

### Changes that are welcome
 - Bug fixes
 - Compatibility improvements
 - "Under the hood" enhancements
 - Small changes that don't have an impact on the core gameplay
