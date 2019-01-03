# D3-Data-Journalism
An Exploration of Public Data Visualization with D3.js

![screenshot](https://github.com/ejhagee/D3-Data-Journalism/blob/master/images/screenshot.png)

### Description
This project uses D3.js to visualize some state-level data about population health based on 2014 U.S. Census data.  It similates an on-line newpaper article with an interactive visualization.  Three risk factors (obesity, smoking, and uninsurance rates) are plotted against three perhaps underlying factors (income, poverty rate, and age).

### File Structure
- The base webpage template is index.html.
- The assets folder contains everything else of relevance
- assets/css holds two styling files, styles.css and d3style.css
- assets/data holds the data set in data.csv
- assets/js holds .eslintrc.json and app.js, the latter of which runs the javascript code that contains the visualization

### Running
Due to loading in a csv file, many browsers will fail to load this unless run on an http server.  This project was developed with the `python -m http.server` method.
