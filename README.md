# Instructions to run the code
Since this is mainly raw html and css, no external package needs to be downloaded. We can run this code with the vscode extension package of Live Server which should then run this project in localhost

# Design Choices
- I have seperated and split the html into 2 sections the header and body
- All images are stored in assets folder
- The header section is divided and seperated into 3 sections with a flex row property
- flex-grow is used for the search bar to acheive the search bar to be the entire width
- To minimise the amount of repeated css codes for the main body section, i have created a common card css that applies to all of the cards
- Flex column is used to split the body into 3 sections
- Simillarly, to prevent repeated css codes, the fonts are seperated into color classes e.g if the day posted is grey i have created a class specifically for grey color 
