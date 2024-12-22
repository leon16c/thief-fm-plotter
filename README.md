
# Thief Guild FM Plot

Site available at https://leon16c.github.io/thief-fm-plotter

A tiny side project I did because I've recently gotten into Thief FMs and I like rating visualization despite having absolutely no background whatsoever in statistics and data science. This is something I generate and update manually, not a tool where you can enter names to visualize them, sorry.

If you would like to see names added or have any other ideas, feel free to [contact me on Thief Guild](https://www.thiefguild.com/user/5758/chilling).

Maybe I'll clean up the code and post it in the future, although Thief Guild does not provide an official API so I don't know about that yet.
## Features and Limitations

### What it does

- shows missions by author in respect to release date and average rating on Thief Guild,  
  dots also increase in size the more votes they have on Thief Guild
- interactive plot with the ability to zoom and hide authors (double click author to isolate)
- supports up to 20 different authors (possibly even more, but I ran out of colors)

### What it can't do

- dynamically add authors, the plot is generated using Python and can't truly be modified
- properly display collaborations, due to the way data is fetched, each mission only shows one author

## Acknowledgements

 - [Thief Guild](https://www.thiefguild.com/)
 - [plotly.py](https://github.com/plotly/plotly.py)
 
