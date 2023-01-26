# CORKS VERY OWN


## UX

In this section, I will briefly explain your design processes.

### Colour Scheme

Explain your colours and the colour scheme.

- `#460C68` used for my H1, H2 text.
- `#D5F5E3` used for Body and H3 background.
- `#BCCEF8` used for Footer and Header Background.
- `#000000` used for Paragraphs text.

I used https://colorhunt.co/ to find my palette.


![](documentation/colorhuntdocs.png)


I've used CSS `:root` variables to easily update the global colour scheme by changing only one value, instead of everywhere in the CSS file.

```css
:root {
    /* P = Primary */
    --p-text: #460C68;
    --background: #D5F5E3;
}
```

### Typography


- [Shadows Into Light](https://fonts.google.com/specimen/Shadows+Into+Light) was used for the primary headers and titles.

- [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk?query=space+g) was used for all other secondary text.

- [Anton](https://fonts.google.com/specimen/Anton?query=anton) was used for the navigation text.

## User Stories


### New Site Users

- As a new site user, I would like to find a restaurant in Cork, so that I can eat in Cork.
- As a new site user, I would like to find sports activities in Cork, so that I can find fun places to play sports in Cork.
- As a new site user, I would like to find Cork's nightlife, to find pubs/ nightlife in Cork.
- As a new site user, I would like to find places to explore in Cork, so that I can explore Cork.
- As a new site user, I would like to find photos of Cork, so that I can see the best photos of Cork.

### Returning Site Users

- As a returning site user, I would like to find multiple different restaurants in Cork, so that I can .
- As a returning site user, I would like to find multiple different sports activites in Cork, so that I can so that I can find more places to play sports in Cork.
- As a returning site user, I would like to find multiple different places in Cork with nightlife, to find more pubs/ nightlife in Cork.
- As a returning site user, I would like to find multiple different places in Cork to explore, so that I can explore more places in Cork.
- As a returning site user, I would like to find multiple more photos and about the page, so that I can find out more about the page and more images.


## Wireframes

In this section, display your wireframe screenshots using a Markdown `table`.

Instructions on how to do Markdown `tables` start on line #213 on this site: https://pandao.github.io/editor.md/en.html

To follow best practice, wireframes were developed for mobile, tablet, and desktop sizes.
I've used [Balsamiq](https://balsamiq.com/wireframes) to design my site wireframes.

### Home Page Wireframes

| Size | Screenshot |
| --- | --- |
| Mobile | ![screenshot](documentation/wireframes/mobile-home.png) |
| Tablet | ![screenshot](documentation/wireframes/tablet-home.png) |
| Desktop | ![screenshot](documentation/wireframes/desktop-home.png) |

### About Page Wireframes

| Size | Screenshot |
| --- | --- |
| Mobile | ![screenshot](documentation/wireframes/mobile-about.png) |
| Tablet | ![screenshot](documentation/wireframes/tablet-about.png) |
| Desktop | ![screenshot](documentation/wireframes/desktop-about.png) |

### Photo Page Wireframes

| Size | Screenshot |
| --- | --- |
| Mobile | ![screenshot](documentation/wireframes/mobile-contact.png) |
| Tablet | ![screenshot](documentation/wireframes/tablet-contact.png) |
| Desktop | ![screenshot](documentation/wireframes/desktop-contact.png) |

Repeat for any addition wireframe pages you have.

## Features

For some/all of your features, you may choose to reference the specific project files that implement them.

### Existing Features

- **Link to menus/ external pages**

    - Link at end of sections to help Site Users find out more information about websites.
    - This is in the restaurants, sports, nightlife and exploring page at the end of most paragraphs!

![](documentation/feature01.png)

- **Link to sections**

    - Link to four sections (restaurants, sports, nightlife and exploring) to other pages for ease of access.
    - At the bottom of Home/ index and About page.

![](documentation/feature02.png)

- **Map**

    - Map on about page to show Cork only!
    - Under About Page section.

![](documentation/feature03.png)



### Future Features


- Google maps view #1
    - Under every section I would like a google maps view of where exactly to find it.
- Contact page #2
    - Wanted to add a usable interactive contatc page and add to the navigation.
- More sections on each page #3
    - Would like to continously add more restaurants and other sections to make it more inclusive to people in Urban areas.

## Tools & Technologies Used


- [HTML](https://en.wikipedia.org/wiki/HTML) used for the main site content.
- [CSS](https://en.wikipedia.org/wiki/CSS) used for the main site design and layout.
- [CSS :root variables](https://www.w3schools.com/css/css3_variables.asp) used for reusable styles throughout the site.
- [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) and/or [CSS Grid](https://www.w3schools.com/css/css_grid.asp) used for an enhanced responsive layout.
- [Bootstrap](https://getbootstrap.com) used as the front-end CSS framework for modern responsiveness and pre-built components.
- [Materialize](https://materializecss.com) used as the front-end CSS framework for modern responsiveness and pre-built components.
- [Git](https://git-scm.com) used for version control. (`git add`, `git commit`, `git push`)
- [GitHub](https://github.com) used for secure online code storage.
- [GitHub Pages](https://pages.github.com) used for hosting the deployed front-end site.
- [Gitpod](https://gitpod.io) used as a cloud-based IDE for development.
- [Markdown Builder by Tim Nelson](https://traveltimn.github.io/readme-builder) used to help generate the Markdown files.

## Testing

For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Deployment

The site was deployed to GitHub Pages. The steps to deploy are as follows:
- In the [GitHub repository](https://github.com/JoshuaCarroll1/Corks-Very-Own), navigate to the Settings tab 
- From the source section drop-down menu, select the **Main** Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://joshuacarroll1.github.io/Corks-Very-Own)

### Local Deployment

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/JoshuaCarroll1/Corks-Very-Own) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, type the following command to clone my repository:
	- `git clone https://github.com/JoshuaCarroll1/Corks-Very-Own.git`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/JoshuaCarroll1/Corks-Very-Own)

Please note that in order to directly open the project in Gitpod, you need to have the browser extension installed.
A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository.
You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/JoshuaCarroll1/Corks-Very-Own)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployment

Use this space to discuss any differences between the local version you've developed, and the live deployment site on GitHub Pages.

## Credits

In this section you need to reference where you got your content, media, and extra help from.
It is common practice to use code from other repositories and tutorials,
however, it is important to be very specific about these sources to avoid plagiarism.

### Content

Use this space to provide attribution links to any borrowed code snippets, elements, or resources.
A few examples have been provided below to give you some ideas.

Ideally, you should provide an actual link to every resource used, not just a generic link to the main site!

| Source | Location | Notes |
| --- | --- | --- |
| [Markdown Builder by Tim Nelson](https://traveltimn.github.io/readme-builder) | README and TESTING | tool to help generate the Markdown files |
| [Chris Beams](https://chris.beams.io/posts/git-commit) | version control | "How to Write a Git Commit Message" |
| [W3Schools](https://www.w3schools.com/howto/howto_js_topnav_responsive.asp) | entire site | responsive HTML/CSS/JS navbar |
| [W3Schools](https://www.w3schools.com/howto/howto_css_modals.asp) | contact page | interactive pop-up (modal) |
| [W3Schools](https://www.w3schools.com/css/css3_variables.asp) | entire site | how to use CSS :root variables |
| [Flexbox Froggy](https://flexboxfroggy.com/) | entire site | modern responsive layouts |

### Media

Use this space to provide attribution links to any images, videos, or audio files borrowed from online.
A few examples have been provided below to give you some ideas.

If you're the owner (or a close acquaintance) of all media files, then make sure to specify this.
Let the assessors know that you have explicit rights to use the media files within your project.

Ideally, you should provide an actual link to every media file used, not just a generic link to the main site!
The list below is by no means exhaustive. Within the Code Institute Slack community, you can find more "free media" links
by sending yourself the following command: `!freemedia`.

| Source | Location | Type | Notes |
| --- | --- | --- | --- |
| [Pexels](https://www.pexels.com) | entire site | image | favicon on all pages |
| [Lorem Picsum](https://picsum.photos) | home page | image | hero image background |
| [Unsplash](https://unsplash.com) | product page | image | sample of fake products |
| [Pixabay](https://pixabay.com) | gallery page | image | group of photos for gallery |
| [Wallhere](https://wallhere.com) | footer | image | background wallpaper image in the footer |
| [This Person Does Not Exist](https://thispersondoesnotexist.com) | testimonials | image | headshots of fake testimonial images |
| [Audio Micro](https://www.audiomicro.com/free-sound-effects) | game page | audio | free audio files to generate the game sounds |
| [Videvo](https://www.videvo.net/) | home page | video | background video on the hero section |
| [TinyPNG](https://tinypng.com) | entire site | image | tool for image compression |

### Acknowledgements



- I would like to thank my Code Institute mentor, [Tim Nelson](https://github.com/TravelTimN) for their support throughout the development of this project.
- I would like to thank the [Code Institute](https://codeinstitute.net) tutor team for their assistance with troubleshooting and debugging some project issues.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for keeping the slack channel up to date with useful tips.
- I would like to thank my parents, for believing in me, and allowing me to make this transition into software development.
- I would like to thank my girlfriend, for supporting me in my career development change towards becoming a software developer and motivating me to keep on top of study daily.
