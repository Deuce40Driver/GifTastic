# GifTastic
## *A Spiffy Hip-Hop Themed Giphy App!*

## Overview
- This application uses the GIPHY API to make a dynamic web page that populates with gifs of your choice. 
- Each button click calls the GIPHY API then updates the HTML with the use of JavaScript and jQuery.
- The app takes an array of Hip-Hop themed topics and creates buttons in the HTML.
- When the user clicks on a button, the page will grab 10 static, non-animated gif images from the GIPHY API and place them on the page.
- When the user clicks one of the still GIPHY images, the gif will animate. If the user clicks the gif again, it will stop playing.
- Under every gif, its rating (PG, G, so on) is displayed. This data is provided by the GIPHY API.
- There is a form which takes the value from a user input box and adds a new button to the page for that topic.

Bonus Goals `Still to Add`
-----------
- Make app fully mobile responsive.
- Allow users to request additional gifs to be added to the page.
- Each request should ADD 10 gifs to the page, NOT overwrite the existing gifs.
- List additional metadata (title, tags, etc) for each gif in a clean and readable format.
- Include a 1-click download button for each gif, this should work across device types.
- Integrate this search with additional APIs such as OMDB, or Bands in Town. Be creative and build something you are proud to showcase in your portfolio
- Allow users to add their favorite gifs to a favorites section.
- This should persist even when they select or add a new topic.
- If you are looking for a major challenge, look into making this section persist even when the page is reloaded(via localStorage or cookies).