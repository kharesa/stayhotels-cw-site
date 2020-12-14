# Task-3-Website-development Group 2 STAY HOTELS

# Description 

This part of the coursework required us to develop the website using the design created in the previous deliverable of coursework 2.

This website is implementing the design created in the previous coursework-2 and the functionality of the website using primarily HTML and CSS, and a small amount of JavaScript.

# What does this include?

There are 3 folders and 12 files including this readme file and 11 HTML files of the pages. 
Example shown below:

```html
<!--HTML Document for Group 2 page designed by Kharesa-Kesa and Kingsley Charles -->
<!--November - December 2020 -->
<!doctype html>
<html>
<title>STAY HOTELS | Homepage</title>
    <style>
        body { 
            display: grid;
            grid-template-areas: 
                "header header"
                "homepicture search_box";
            grid-template-rows: 15% 1fr;
            grid-template-columns: 70% 1fr;
            grid-gap: 0px;
            height: 100vh;
            margin: 0;
        }
```
The styles are stored in the ccs folders and the images used are held in the images folder.
Example shown below:

```css
/* CCS STYLE SHEET deisgned by Group 2 Khareas-Kesa and Kingsley*/
header, footer, homepicture, search_box, div {
    padding: 20px;
}
#pageHeader {
    grid-area: header;
    background-color: rgb(131, 131, 131);
}
#mainhomepicture { 
    grid-area: homepicture;
    background-image: url("images/homepagereception.jpg");
    background-repeat: no-repeat;
```

# What is this for?

The focus of this work is on website design, usability and interactivity. There is no sophisticated back end programs such as database systems. We are interested in how well our implementation fits our design.

# Project status

This project is as of now, complete, the code is free to browse but no future pulls will be commited past the 17th December 2020

# Support

For any contact for this reach out to kharesa1, kingslet108 or lin.wang@qmul.ac.uk. [QMUL](https://qmplus.qmul.ac.uk/course/view.php?id=15599)

# Authors and acknowledgment

The code in the following files were authored by Kharesa-Kesa and Kingsley. This is being used academically and does not represent any commercial entity or company.
