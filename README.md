## Overview

My overall design choices for this site were to stay minimalistic and simple. I stayed with a color palette of black, gray, white, and yellow to focus on key areas.

**Header:** 
  - The header is consistent across all pages and includes the name of the site in the top left, links to all available sites in the center, and external links on the right.
  - The header consists of three flex boxes: 
    - The left flex box contains the site name, which doubles as a side menu for smaller screens.
    - The center flex box holds the site links, which disappear on smaller screens.
    - The right flex box holds external links.
  - Links have hover effects to show active redirects, and a yellow bottom border indicates the current page. This yellow bottom border is hard-coded to change with the active site.

### Background and Footer
**Background Video:** 
  - A tree video plays in the background on all pages, emphasizing the outdoor activities theme.
  - The video is placed in a container for better positioning and has an overlay to add a blur effect. This blurring also obscures the watermark on the video.
- **Footer:** Located at the bottom left, the footer contains additional information like my email address.

## Pages

### Main Page
**Main Feature:** 
  - The home page is the introductory page for the user and is not meant to have content other than expressing the purpose of the site.
  - A central button guides users towards more content, linking to the bushcraft site.
  - The button has a hover effect.
  - An animation brings text in from the right, highlighting the focus on outdoor activities.

### Contact Page
  - A simple form in a card allows users to enter their name and message.
  - The name input field has autofocus.
  - The submit button matches the style of the main page button.

### Content Pages
  - All content is placed in cards for easy modification.
  - Cards have a slide effect.
  - A class view for the main container allows for multiple cards, each with a consistent style.
  - The layout is in column form to keep focus on one card at a time, though this can be adjusted to multiple columns for more content.
