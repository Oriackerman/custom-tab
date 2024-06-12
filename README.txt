Custom-tabs-plugin 


The component is based on ACF pro, therefore, to activate the component, it is necessary to ensure that ACF is installed on the site.

To install the component, download the ZIP file, go to Plugins, then click on Add New, and select the plugin.

The "Custom Tab" page is essentially a brief summary of the component.
The "Edit Tabs Groups" page is where you add, delete, and manage the content you want to place.
After entering "Edit Tabs Groups", click on "Add New" where you have the following options:

tab_title = the name of the tab.
Background for tab = the background for wherever the recommendation block is.
recommend = where you can insert any content you want to appear as a recommendation.
Person = contains details about the recommender, including name, title, image.
logo for company = the logo you want to appear.
logo gallery = a gallery of logos you want to appear below.
Urls = text for a link and a link to where you want it to direct.
percentage = responsible for the content of the second block appearing to the right of the recommendation.
Using the "Add Row" button, you can essentially add more tabs and as much content as you want.

SCSS to CSS :


I used Sass by running the command npm install -g sass, and then I used Sass --watch, which listens to what I write in the file and compiles it into a CSS file.

Here's an example of the code I wrote in SASS:
I defined variables $font57: "proxima-nova", sans-serif; and $fontw2: 400; where one specifies the font-weight and the other the font-family:

p {
  font-family: $font57;
  font-weight: $fontw2;
}

Then, through the compiler, it updates to regular CSS.


Note : 
I did not add design editing options through the component, except where there are text boxes, in order to keep the design as it is.






