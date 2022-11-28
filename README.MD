
## Running the script 
- add jemdoc to your path \n
- run ` jemdoc  -o publications.html publications.jemdoc ` \n
- run ` jemdoc index.jemdoc` \n

## Tracking the website through analytics 
- you have to manually add the google analytics tag to the compiled html file:
- To do that insert it right after `<head>`
- To get the snippet, follow instructions here `https://support.google.com/analytics/answer/1008080?hl=en`
- pick the ua-tag not the g tag
Note: jemdoc.py was modified to add description metatag

OR Just add this the tag in the hidden_file.txt

## Adding a new page to the left hand side menu
- Add the page to the `MENU` doc
- run ` jemdoc  -o page.html page.jemdoc ` for every page and then run ` jemdoc index.jemdoc` \n 

## Adding a new table with a new style 
You have to add the table specs in `table.css` and then add the `table.css` in the preamble of the jemdoc that will contain the table if it's not already there. 