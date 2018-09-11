# Milestone Project: User-Centric Frontend Development (HTML5 / CSS3)

The brief for this Milestone project was to create a website for a band (specifically The Monkees) and to include various media elements such as pictures, audio, and video, as well as a contact page and links to various social media presences.

I decided instead that I would construct a site dedicated to the Discworld series of novels by Sir Terry Pratchett. I felt that I could deliver a better, more personally relevant site than was proposed from the original brief and still achieve the goals it had outlined.
 
## UX
 
I designed the site as an introduction to the Discworld books, providing information and content that would be useful to as broad an audience as possible without overloading a user in details. The site’s structure and content is a good balance between covering all of the important aspects of the Discworld and its creator, and external sources for more in-depth information.  It primarily services the following user types:

- Users that have no previous knowledge of the stories, the characters, or the different arcs spanning the books, looking to understand what the series is all about and get in touch
- Users with some general knowledge of the book series, but looking for more information on the adaptations that have been made.
- Users familiar with the series, and looking for more information on Discworld, as well as sources to purchase the novels and other merchandise in various formats.

Adobe XD was used to create wireframes for each of the pages both in [Desktop](https://github.com/10xOXR/milestone-project-1/tree/master/wireframes/Desktop) and [Mobile](https://github.com/10xOXR/milestone-project-1/tree/master/wireframes/Mobile) formats.

## Features

The following is a summary of the features already in place and those that could perhaps be implemented in the future.

### Existing Features

- All images are hyperlinks to their full-sized versions and open in new tabs.
	- This allows users to get more detail from any image rather than relying on the smaller versions in the site. This is particularly helpful for much larger images, such as the map of the Discworld.

- Back-to-Top button that appears only once users have scrolled beyond 300 pixels.
	- A simple navigational function, implemented in Javascript, which allows users to return quickly to the top of any page without the need to scroll manually.

- YouTube videos and Audiobook samples are directly embedded in the site.
	- Users can watch the trailers for the TV adaptations of three Discworld books and listen to samples from eight audiobooks without the need to leave the site.

- ‘Further Resources’ page contains externals links to six other related sites.
	- This allows users to access more information on the Discworld, merchandise, and the social media pages for Terry Pratchett.

- Contact form validates that information has been entered into each field in the expected format before allowing submission.
	- This prevents users from accidentally attempting to submit blank or otherwise incomplete contact information.

### Features Left to Implement

- Contact form information isn’t saved or emailed to any location.
	- At this time, the information that a user enters into the contact form is simply erased when the ‘Submit’ button is pressed. I didn’t want to include the POST code for test dumps as this would navigate away from the site.

## Testing

### Browser Compatibility

I tested the site to be sure that it rendered consistently and as expected in all major web browsers, both desktop and mobile versions. This included:

- Ensuring all elements are responsive and that all content is legible.
- Testing that the Navbar changed as expected in line with media queries, collapsing to a hamburger menu below 768 px.
- Ensuring that Bootstrap breakpoints operated as expected and that element column sizes make sense for each.
- Site was test-rendered using desktop and mobile equivalents of:
	- Chrome (Versions 67 – 69)
	- Firefox (Version 60 & 61)
	- Opera (Version 55)
	- MS Edge (Version 42.17134.1.0)
	- Safari (Version 12)

### Testing Matrix

A test matrix created in MS Excel can be found [here](https://github.com/10xOXR/milestone-project-1/blob/master/misc/page_tests.xlsx). It details all of the tests made to ensure the site renders consistently across different devices and browsers, and that all functionality performed as expected.

### Noted Issues

The Flexbox elements used in the Navbar do not render correctly in Safari on macOS 10.14, with the text appearing off-centre instead of centred. I attempted to correct this using the Safari browser prefixes for Flexbox but was unable to correct the problem.

## Technologies Used

- [HTML5]( https://www.w3.org/TR/2017/REC-html52-20171214/)
	- Used to construct the site pages.

- [CSS3]( https://www.w3.org/standards/techs/css#w3c_all)
	- Provides styling for all pages and their content.

- [Bootstrap 3.3.7]( https://getbootstrap.com/docs/3.3/getting-started/)
	- Used for quickly styling HTML elements in known ways in order to reduce the required amount of written CSS. Some Bootstrap elements were further styled or overwritten in the main CSS stylesheet.

- [Font Awesome 5]( https://fontawesome.com/icons?d=gallery)
	- Icon elements used in the ‘Further Resources’ table.

- [jQuery]( https://jquery.com/)
	- Used to enable the Back-to-Top button functionality. Although outside the scope of this project, its inclusion provides a better user  experience.

- [Google Fonts]( https://fonts.google.com/)
	- Fonts used on the site are provided from Google Fonts. They are more visually relevant to the overall design of the site, and cannot be hosted locally on GitHub.

## Deployment

The site has been deployed using GitHub Pages and is available to review [here]( https://10xoxr.github.io/milestone-project-1/).

Local deployment is not required.

## Content

Text content on all pages was copied and/or amended from the following sites:

- [TerryPratchettBooks.com](https://www.terrypratchettbooks.com){:target="_blank"}
- [Discworld Wiki](https://wiki.lspace.org/mediawiki/Main_Page){:target="_blank"}
- [Goodreads.com](https://www.goodreads.com/series/40650-discworld){:target="_blank"}
- [Discworld.com](https://www.discworld.com){:target="_blank"}
- [Fandom Discworld Wiki](http://discworld.wikia.com/wiki/Main_Page){:target="_blank"}
- [Wikipedia](https://en.wikipedia.org/wiki/Discworld){:target="_blank"}

## Media

Videos courtesy of YouTube and audiobook samples from [Audible.co.uk]( https://www.audible.co.uk/series?asin=B00HRG5ZPU).

A complete source for all media can be found in the [Project Outline]( https://github.com/10xOXR/milestone-project-1/blob/master/misc/Project%20Outline.docx)
 Word document.

## Acknowledgements

Perpetual thanks to [Tim Nelson]( https://github.com/TravelTimN) for his suggestions, fixes, and patience while I put all of this together.
