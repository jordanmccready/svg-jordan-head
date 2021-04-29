# website

Objective:
Attempting to pull large SVG file + CSS + JS into Webflow using Github

The purpose of this project was to utilize Anime.js and animate a stylized svg illustration of my face and have it animate.

The only problem was that Webflow only allows 10k characters for it's HTML embed, and my SVG illustration had well over 10k characters.
So I created a new HTML file here, on Github with the SVG Code, CSS stylings, HTML Div structure, and the Animation Script I wanted to run.
Following: https://forum.webflow.com/t/custom-code-character-limit-workaround/97963
I was able to add load the anime library, throw in an ajax container, and direct the ajax container to my new Github costimzed animated SVG face.
I included everything for styling in this file so that I can edit it all here in one place for the effects to take place. 
That way there is no need to go back and forth from github to webflow and be messing around with anything.
