## Friday, 8 August, 2025

### Thoughts
I gave my first attempt at getting the two-column structure in. For now, I just got the dates and facts put in, to give me something to work with, and it did not work. I am kind of not surprised though, the thing I am trying to build my idea from was from an image gallery. 

### What I Did

When examining the Build a Photo gallery project, I noticed that they used flexbox applied to a container that held all the images. For now, I just took the dates and put them in a p element unformatted and then used the same code I wrote for the Photo Galary and created a temporary class to try to see what happens.  

### Next Steps

I think the first problem I need to solve is the things I am planning to turn into stackable columns are too wide. I need to put a maximum width to each column and then make sure the text wraps.  

### Thoughts

My first thought was right. I just needed to limit the width of the text and then add wrap to the columns to let them stack like I wanted with flexbox! That is so cool! 

### What I Did

I created a column class set a max width, enabled flex-wrap, and added a bit of padding to ensure it did not look to cluttered. From there I attached that class to the two divs that hold the facts I previously added, played with the width of my browser a bit, and found that it worked perfectly. I was half expecting this to take a lot more work, but instead, it went super easy. And all of that from just looking up how to add text wrap using flex, referencing prior work I have done, and then using my own problem-solving skills. 

### Next Steps

Polish up the data I have already added to make it look nice, add photos, the quotes about them, and likely a few other things I am missing. 