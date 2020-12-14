# Task-3-Website-development

This part of the coursework required us to develop the website using the design created in the previous deliverable of coursework 2.

This website is implementing the design created in the previous coursework-2 and the functionality of the website using primarily HTML and CSS, and a small amount of JavaScript.

# What does this include?

There are 3 folders and 12 files including this readme file and 11 HTML files of the pages. The styles are stored in the ccs folders and the images used are held in the images folder.

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

The code in the following files were authored by Kharesa-Kesa and Kingsley. This is being used academically and does not represent any commercial entity or company.
