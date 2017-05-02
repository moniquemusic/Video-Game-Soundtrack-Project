# Video-Game-Soundtrack-Project

This is my capstone project for Springboard's Intro to Data Science course for 2016.

The purpose of this code is to create a database of PC video games with their scores, sales, and soundtrcks.
Scores were collected from <a href='http://www.metacritic.com/browse/games/score/metascore/year/pc/filtered?year_selected=2016&sort=desc'>metacritic.com</a>, a site that aggregates scores from a multitude of gaming websites. It also receives user reviews directly. Sales estimates were collected from <a href='http://www.vgchartz.com/platform/48/microsoft-windows/'>vgchartz.com</a>, and the soundtrack data was collected from Youtube using their <a href='https://developers.google.com/youtube/v3/docs/search/list'>API</a>.

I choose to use Youtube as a metric for soundtrack popularity because video game soundtracks regularly are uploaded to Youtube by fans. Often this is the streamable source that is the easiest to access due to game soundtracks not being covered by, and dare I say not taken seriously by, other streaming platforms.

Ultimately this project taught me a great many things. It taught me that APIs are good sources of data when collected correctly, that the JSON format is a pain to deal with in R, that it is bad to nest a million for-loops within each other, and the importance of taking notes, staying organized, and coming up for air once in a while after losing myself among the nitty gritty details. But most of all, I learned that if I need R to do something complicated, instead of hacking something together that works but takes forever, it's better to do some research and find a package that someone already wrote that will get the job done. I'd like to thank my mentor Andrew Flowers for all the help and guidence he provided, especially when introducing to me some obscure package that instantly solved my roadblocks.
