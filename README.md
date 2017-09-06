# TMDB-HTML-Assignment

Included in this repository is the TMDB_API.html file, which will open in a native browser. Click "Clone or Download" on the repository main page, and "Download Zip" onto your local machine. Access and click the HTML file to run it in your default browser.

!!!(PLEASE NOTE: This has been tested in Google Chrome Version 60.0.3112.113, Mozilla Firefox Version 55.0.3, and Microsoft Edge Version 38.14393.1066.0. Results may vary with different browsers, particularly older browsers that may not support tag functionality that more recent browsers do.)!!!

Overview:
HTML5 (with Javascript, Ajax, and a little CSS for good measure) seemed to lend itself well to this project. Javascript deals well with API calls, and HTML5 provides a good, intuitive structure for the webpage front-end design. Python and Django were also considered since I have Python experience, but ultimately not utilized. It would be an interesting experience to go back and attempt to recreate the work using Python and Django. HTML5 was appealing because the project was essentially "standalone"; whereas alternative methods considered would need libraries and other peripheral assets installed, HTML5 is ubiquitous and can easily be opened in any browser with Javascript, CSS, and Ajax. I don't have access to any sort of website hosting, so the HTML file will be opened locally on the machine it is being run on.

Instructions:
-Select and open the HTML file.
-Refer to the "HOW TO" blurb. Essentially there are two different searches the user can run:
1. Movie Search: Search for list of movies by name. This will return a list of movies (up to the top 20) that contain the word or phrase  that  was entered. Each movie will list its corresponding ID number.
2. ID Search: Search for additional information about one particular movie. This will return all available information for the particular movie corresponding to the ID entered. IDs can be found using the first search method, or by inquiring via TMDB's website.
-Repeat either search as desired.

Challenges:
Javascript is something I have dealt with primarily on the QA side of the Agile environment. It has been an interesting and fun experience to delve deeper into it. I also needed to set up the API request with Ajax, which I was unfamiliar with, so it has been useful to get Ajax knowledge under my belt. I did not want to clutter the screen too much with information, which is ultimately why I separated the two searches. The movie information is already not the most intuitive thing to read, so I decided to make the ID search return one movie at a time, and utilize line breaks, regular expressions, and string manipulation to make it more user-friendly while still accounting for differences in data returned by the API. Overall, this sort of assignment was something I was familiar enough with to handle without much issue, but there were a few challenges that kept it interesting and exciting.

In Summation:
Thank you very much for the opportunity to work with a new API and expand on my knowledge of Javascript. I have not dealt with Ajax before, this was a good test not only to introduce myself to Ajax but to more familiarize myself with HTML5/CSS and Javascript. I hope you enjoy using this application, and I look forward to hearing from you regarding it! 

-Daniel

