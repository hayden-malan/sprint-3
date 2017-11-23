What happens to the layout when screen resized  to less than 550 px:

The icons that used to be side by side are now rearranged to be below one another. 

 How do you think that works?

 I think in the CSS, @media (min-width: 550px) is used to ensure that all the settings that usually take up a lot of space, eg. these icons which take up 33 percent of the screen in 3 columns next to one another, won't do that if the screen is less wide than 550px. 
  
  Other Media Queries are also used, for example @media (min-width: 400px) is used to ensure that the window cannot be made less than 400px small on a desktop browser.