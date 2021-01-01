# Network Science Project (Corporate Boards in Norway)

This is a project I did for my Network Science class. The goal was to make use of the tools of Network Science to explore the connections between public limited companies and directors in Norway over the span of 9 years. The dataset used is based off a paper by Seierstad and Opsahl (2011) where they explored Norwegian gender representation law. [You can find the full dataset here.](http://www.boardsandgender.com/data.php)

I used the [`igraph`](https://cran.r-project.org/web/packages/igraph/igraph.pdf) package in R to do the analysis. You can find a detailed tutorial of the igraph package [here](https://kateto.net/netscix2016.html)


I wrote this like a tutorial to my future self so it might be a bit wordy. The Rmd file goes through the entire process from data prep to the final conclusions. The first run of the file will take a fair bit of time, after that the preped data is saved to your working directory and subsequent runs shouldn't take more than a minute.
