# InfoBord CO2 footprint frontend software

## What this is
Frontend Software for InfoBord UF's system to display and compare CO2 footprints. This part of the system (the frontend) is what displays the data to the user in a way which easily can be interpredted and understood. As part of the repository and the frontend this directory contains the template files to make more pages/items for project fruit.

## Installation/Updating

1. Do a git pull or download the repository maually.
2. Place the contents of this directory (the one containg this readme.md file) inside the desired directory in your display system (the www folder in InfoBord UFs case).
3. Navigate to the css directory.
4. Remove the css document that should not be used, either the right or left one. (the file named "left.css" should be removed if the desired display is the right screen and vice versa). Always keep the file named "index.css" (provided you don't want to make your own theme)
5. Copy the template and edit the data inside to your liking to create new pages/items (the possibilities are endless!)
6. Name the file to make it corespond with the NFC tag-id from the backend to link the page to a tag. (InfoBord UF uses seems to be using NTAG213 format)