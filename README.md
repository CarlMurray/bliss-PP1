# Features

## Navigation Bar

- The site features a responsive Navigation Bar which includes links to Home, Exercises, About and Contact. 
- Although clicking the logo brings users Home, a dedicated Home link is included in the Navigation Bar in line with UX best practices. 
- Other than Home, links are ordered by importance - Exercises is the main content of the site that users will interact with and as such comes before the About and Contact links.
- The active page a user is on is visually highlighted to help orient the user as they navigate the site.

## Landing Content

- The landing page shows a visual illustration of a person in a yoga pose along with the large headline and a short paragraph of desriptive text - these elements immediately communicate the intent of the site.
- There are two CTAs on the landing page - the primary CTA ("Get started") links to the "Exercises" page and enables users to quickly engage with the site's content. The secondary CTA ("Learn more") links to the "About" page so users can read more about the site's purpose and intent.

# Technologies Used
I used the following technologies, platforms and support in building my project:
- Wireframes and mockups were designed in Figma
- The website is built with HTML/CSS only.
- The Code Institute modules/lessons aided my learning and many of the concepts learned were applied in this project
- Although not part of the Code Institue curriculum, I used various online resources to learn CSS Flexbox which plays an intrumental role in the styling of the website.
- Stack Overflow was used for troubleshooting and debugging throughout the project, as referenced.
- Git was used for version control
- GitHub was used for the project repository
- Google Fonts was used for all fonts on the site
- Storyset.com and Unsplash were the sources of all imagery/illustrations
- FontAwesome was used for the social media icons which then had additional styling applied to them
- Favicon Generator (favicon.io) was used to generate the favicon used
- The site is hosted on AWS Amplify
- Custom domain registered with NameSilo, with a specific subdomain for this project (https://bliss.carlmurray.design)

# Testing
- Responsiveness was tested with Chrome Dev Tools and by testing on various devices (mobile, tablet, laptop, desktop). Am I Responsive was also used to test responsiveness.
- All HTML files were passed through the W3C validator with no errors.
- The CSS stylesheet wass passed through the W3C validator with no errors.
- The website was tested on major browsers including Chrome, Safari, Firefox and Edge.
- All user flows were tested in depth including navigating through content, clicking CTAs, consuming content, video playback and form submission.
- Lighthouse was used to test for Performance, Accessibility, Best Practices and SEO and adjustments were made to improve test results.
>TODO: Screenshot of Lighthouse results
>TODO: Form testing, accessibility testing, usability testing, spell check, content testing

# Bugs/Issues
Debugging and troubleshooting were done constantly throughout development, however there were a number of noteworthy issues:
- During development, the site was tested on an iPhone XS Max to check responsiveness. It was noted that the Newletter Subscribe CTA and Contact Form CTA were not displaying the correct styling compared to the Chrome Dev Tools Inpector, and did not have the correct border radius. After further experimentation and testing, a solution was found on Stack Overflow (https://stackoverflow.com/questions/20640182/iphone-overriding-all-of-my-styles-on-an-inputtype-submit). The cause of the "bug" relates to how Safari on an iPhone renders `<input type="submit">` and was fixed by adding "-webkit-appearance:none;" to the element's CSS rule. 
- As the site was tested on different browsers and devices, it was noted that the dotted `<hr>` element joining content cards was appearing as squares rather than circular dots on iOS browsers. Unfortunately there is currently no natively supported solution for this problem so it was left as is, with the intention of replacing the dots with an SVG in future. (https://stackoverflow.com/questions/11280676/how-to-create-dotted-border-with-round-dots-in-webkit-browsers)
- When testing on different browsers, it was observed that the font weight of the Navigation Links appeared heavier in Safari than in Chrome and as intended. It was found that this is due to the rendering engine of Safari and there is no solution for this "issue". Adding `-webkit-font-smoothing: antialiased;` made a minor visual improvement.
- The site was tested on a 42" LG Smart TV experimentally. The native LG web browser does not render certain elements and styles correctly and browser support is limited. Designing for smart TVs was outside the scope of this project but future revisions may address this functionality.
- During deployment, an attempt was made to setup CloudFlare on the site, however this was unsuccessful. It is believed that there were issues with DNS records and Nameservers, along with lengthy DNS propogation that prevented this from functioning as intended and as such the initiative was abandoned and deemed unecessary for this project.

# Credits

## Images

### Yoga Exercise Images: 
- https://unsplash.com/photos/nqUHQkuVj3c
- https://unsplash.com/photos/xB4ExGcUai0
- https://unsplash.com/photos/rOn57CBgyMo

### Meditation Exercise Images:
- https://unsplash.com/photos/ktPKyUs3Qjs
- https://unsplash.com/photos/dOhJtfXJZfw
- https://unsplash.com/photos/G-JJy-Yv_dA

### Illustrations:
- https://storyset.com/illustration/stress/pana
- https://storyset.com/illustration/yoga-practice/pana
- https://storyset.com/illustration/meditation/rafiki
- https://storyset.com/illustration/mental-health/pana
- https://storyset.com/illustration/enthusiastic/pana
- https://storyset.com/illustration/feeling-blue/pana
- https://storyset.com/illustration/team-spirit/pana
- https://storyset.com/illustration/high-five/pana
- https://storyset.com/illustration/letter/bro

### Favicon
- Favicon Generator (favicon.io)