# The Bookery

A digital library that carries free books accessible to all South Africans.

## Kgomotso Mbele

ST10467825
kgomotsombele@outlook.com
Repository link: [https://github.com/KgomotsoMbele/WEDE5020-TheBookery]

## Project Overview

The aim of this project is to make a website that is readily accessible for South Africans.
What this means to me is that the site has to be low bandwidth, with minimal content to load and have lite downloads.
With that in mind, I have made the site quite simple and minimalistic, paying homage to Cape Town with the colour scheme as well.

## Goals and Objectives

- Improve Access: Provide free digital books in Zulu/English via low-bandwidth platform.
- Community Engagement: Host monthly virtual Q&As with SA authors.
- Partnership Growth: Onboard 10 schools in Khayelitsha within 1 year.

The main objective is to bring literacy to the parts of our communities that do not have readily available access to high speed internet
or cannot get to public libraries due to their own circumstances. These books can also educate our generation and generations
to come on older literature that shaped the world of literacy and books. Some of the books on the site are
world renowned and massively popular.

## Features

- Logo animation site wide
- Easy to follow page linking
- Google Calendar integration for easy viewing of events
- Library sectioned off with shelves, complete with book covers and quick, lite downloads
- Decently contrasted text and buttons
- Easy to download books (some with illustrations)

## Changelog

- Version 0.1
  Started laying the foundation for the website. After identifying how many site pages would be necessary, all the necessary HTML files were made for the pages.
  I added a stylesheet and set up a basic style for the main title.
  Keeping this start very simple.

- Version 0.2
  Added all the additional folders for some file structure and uniformity.
  Got started with some test assets to put in my asset folder and set up some image displays.

- Version 0.3
  Started styling the site to look like the wireframes. Implemented a standard navbar across all pages as well as a footer section, some navlinks and some animations/effects on the home buttons I pointed out on the wireframes. Grouped things a bit better to allow for better manuverability and customisations. Probably going to start adding all the colours I mentioned in my proposal and see if they work well together or if I am going to work on a different colour palette.

- Version 0.4
  Started working on my home page hero section. Spacing is not looking great as I am trying to get the larger text and smaller text to be spaced vertically as in the wireframe but it is not looking good, neither is the hero section image. Aside from that, also working on the library page. I have basically 1 shelf now and found the limits of my countainer for how many books can fit there so going to make a comment in the code for this so I can have a reminder. I think the way I will be going forward, if I cannot implement a carousel correctly, I'll individually make multiple shelves and use that to display the books.

- Version 0.5
  The library page section has been fully completed. I have made all the shelves I intended to make, loaded all the books with their covers all displaying individually. They are all downloadable in an ePub format as that format allows for the lowest download size. Library page is also quite responsive and compatible with mobile sized screens. Same can be said about the Index page and About Us page. Hero section on the Index page was resolved and is good as well as the About Us page hero section. Reworked the CSS styling sitewide with a new overall colour scheme.

- Version 0.6
  Currently have everything else done and working on implementing good JS site wide. I've made all but 1 page responsive for mobile and that's the Contact us page. I believe maybe the embed link styling just has to be worked on but it'll probably bug out so I will need to be careful with that and keep a close eye on it. I'm trying to make my navigation menu turn into a hamburger menu when it's mobile as my main javascript for this site but right now, it isn't displaying correctly which is problematic. That aside, the site's in a decent spot. I have begun mobile testing by making a QR code live server that I can scan with all manner of mobile device to test.

- Version 0.7
  Fixed and improved mobile navigation and restored the Library page structure. The hamburger menu now displays and opens correctly on mobile across pages. I fixed head/header markup problems on the Library page. The JavaScript that toggles the menu was made more robust so it still opens even if a page's CSS unintentionally hides the nav. Small styling tweaks (z-index and bar visibility) were applied to prevent the hamburger being overlapped or invisible on narrow screens. Please test the navigation on a mobile viewport and confirm everything looks right when you can.

- Version 0.8 
  Added descriptive title tags and meta descriptions across all pages to improve SEO. Created and configured `robots.txt` and `sitemap.xml` files to guide search engine crawling and clarify the site’s structure. Added basic security measures including input validation. Conducted full testing across all pages for responsiveness, accessibility, and consistency.

  - Version 0.9
    Updated the Contact page with a proper Google maps embed though I had to update my CSP for that so I adjusted that to allow Google Maps embeds to work. I enhance my alt text a lot better for the covers for the books on Library. Double checked that everything loaded alright

## Sitemap

<img width="994" height="385" alt="image" src="https://github.com/user-attachments/assets/01aa19e6-59a7-4c6d-8018-8a8ebbcb1698" />

## References

Netlify. (Accessed August 8). Available at: (https://www.netlify.com/)
MDN Web Docs (JavaScript) (Accessed August 8) - Available at: (https://developer.mozilla.org/en-US/docs/Web/JavaScript)
Google Fonts (Accessed August 8) - Available at: (https://fonts.google.com/)
Figma (Accessed August 8) -Available at: (https://www.figma.com/resources/learn-design/)
Project Gutenberg(Accessed August 22). Free access to e-books. Available at: <https://www.gutenberg.org/>
SA Education Statistics (Accessed August 8) - Available at: (https://www.westerncape.gov.za/)
SA Mobile Network Report (Accessed August 8) - Available at: (https://www.gsma.com/mobilefordevelopment/wp-content/uploads/2023/03/South-Africa-Mobile-Economy-2023.pdf)
