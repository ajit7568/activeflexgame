# activeflexgame
hosted link https://ajit7568.github.io/activeflexgame/
![Screenshot (75)](https://github.com/ajit7568/activeflexgame/assets/104454960/d739046c-ca13-49b0-9562-dce40169bbd5)
![Screenshot (76)](https://github.com/ajit7568/activeflexgame/assets/104454960/db769c87-7c1a-4147-98f9-c8be6d676ff4)
![Screenshot (77)](https://github.com/ajit7568/activeflexgame/assets/104454960/1d48158d-bbb8-4610-9c3c-dfb88bc52bfc)
HTML Structure:

<!DOCTYPE html>: Declares the document type as HTML5.
<html>: The root element of the HTML document.
<head>: Contains metadata and external resources.
<meta charset="UTF-8">: Specifies the character encoding.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport settings for responsive design.
<title>: Sets the title of the web page.
<link>: Links to external resources such as stylesheets and fonts.
rel="stylesheet": Indicates that the linked resource is a stylesheet.
<body>: The main content of the web page.
Header (nav):

<nav>: Represents a navigation section.
<div class="profile-sec">: Contains profile information.
<img>: Displays an image (profile picture).
<h5>: Displays the name.
<p>: Displays additional information (membership status).
<ul class="menu">: Contains navigation menu items.
<li>: Represents a list item (each menu option).
<img>: Displays an icon.
<p>: Displays the label for the menu option.
<div class="pro-container">: Contains promotional content.
<h5>: Displays a promotional message.
<img>: Displays an image (game controller icon).
Main Content (section):

<section>: Represents a section of the content.
<div class="title-container">: Contains the title and progress bar.
<h2>: Displays the title.
<div class="progress">: Represents a progress bar.
<div class="game-container">: Contains game information.
<img>: Displays an image (game cover).
<div class="game-details">: Contains game details.
<h3>: Displays the game title.
<p>: Displays additional details (platform).
<div class="progress">: Represents a progress bar.
<p>: Displays the completion percentage.
Styling (CSS):

The styles for the elements are defined in an external CSS file (style.css).
The <link> element in the <head> section connects to the CSS file.
The provided Google Fonts are imported to use the "Poppins" font family.
Overall, this code creates a simple web page layout with a navigation menu, profile section, game information, and progress bars.
CSS code contains styling rules that define the appearance of various elements within the web page. Here's an explanation of each section:

Global Styles:

Sets a common style for the entire page.
Defines background color, margins, padding, and font-family.
Header and Paragraph Styles:

Sets common styles for headings and paragraphs.
Resets margins and specifies text color.
Layout:

Defines the layout for the main content using the flexbox model.
main: Represents the main content area and uses flex layout.
nav: Represents the navigation section and uses a flex column layout.
section: Represents the content section and uses a flex column layout.
Game Container:

Styles for the individual game containers.
Sets background color, border-radius, and box-shadow.
Defines padding, display, and alignment.
Game Image:

Styles for the images within game containers.
Sets max dimensions, border-radius, and image alignment.
Profile Section:

Styles for the profile picture and related elements.
Defines width and border-radius for the profile picture.
Sets up a flex column layout for the profile section.
Small Text:

Styles for small text elements.
Sets a reduced font size.
Pro Container:

Styles for the promotional container.
Defines background color, border-radius, and padding.
Uses flex layout and justifies content space around.
Progress Bar:

Styles for the progress bar.
Sets width, height, background color, and border-radius.
Navigation Menu:

Styles for the navigation menu.
Resets padding and removes list bullet points.
Uses flex layout for the list items.
Menu Item:

Styles for each menu item.
Defines display, gap between elements, and alignment.
Sets margin for spacing between menu items.
Title Container:

Styles for the title container.
Defines margin-bottom for spacing below the title.
Game Details:

Styles for the details section within a game container.
Sets margin to position it to the right of the game image.
Percentage and Progress Bar (Game Container):

Styles for the percentage text and progress bar within a game container.
Adjusts margins for positioning and styling of the progress bar.
