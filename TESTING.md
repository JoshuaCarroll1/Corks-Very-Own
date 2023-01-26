# Testing

Return back to the [README.md](README.md) file.


## Code Validation


### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjoshuacarroll1.github.io%2FCorks-Very-Own%2Findex.html) | ![](documentation/valid1.png) | Section lacks header h2-h6 warning |
| About | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjoshuacarroll1.github.io%2FCorks-Very-Own%2Fabout.html) | ![](documentation/valid2.png) |  Section lacks header h2-h6 warning |
| Photos | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjoshuacarroll1.github.io%2FCorks-Very-Own%2Fphotos.html) | ![](documentation/valid3.png) | Pass: No Errors |
| Restaurants | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjoshuacarroll1.github.io%2FCorks-Very-Own%2Frestaurants.html) | ![](documentation/valid4.png) | Section lacks heading. Consider using h2-h6 |
| Sports | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjoshuacarroll1.github.io%2FCorks-Very-Own%2Fsports.html) | ![](documentation/valid5.png) |  Section lacks heading. Consider using h2-h6 |
| Nightlife | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjoshuacarroll1.github.io%2FCorks-Very-Own%2Fnightlife.html) | ![](documentation/valid6.png) | Section lacks heading. Consider using h2-h6 |
| Exploring | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjoshuacarroll1.github.io%2FCorks-Very-Own%2Fexploring.html) | ![](documentation/valid7.png) | Section lacks heading. Consider using h2-h6 |



### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.


| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjoshuacarroll1.github.io%2FCorks-Very-Own%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![](documentation/css-validation-style.png) | Pass: No Errors |


## Browser Compatibility


I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![](documentation/chrome1.png) | Works as expected |
| Safari | ![](documentation/safari1.png) | Minor CSS differences |
| Edge | ![](documentation/edge1.png) | Works as expected |
| Brave | ![](documentation/brave1.png) | Works as expected |

## Responsiveness



I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Screenshot | Notes |
| --- | --- | --- |
| Mobile (DevTools) | ![](documentation/mobile1.png) | Works as expected |
| Tablet (DevTools) | ![](documentation/tablet1.png) | Works as expected |
| Desktop | ![](documentation/desktop1.JPG) | Works as expected |
| Macbook Air M2 | ![](documentation/macbook1.png) | Works as expected |
| iPhone 12| ![](documentation/iphone1.jpeg) | Works as expected |

## Lighthouse Audit


I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Desktop | ![](documentation/lighthouseHD.png) | Few warnings |
| About | Desktop | ![](documentation/lighthouseAD.png) |  Few warnings |
| Photos | Desktop | ![](documentation/lighthousePD.png) | Slow response time due to large images |
| Restaurants| Desktop | ![](documentation/lighthouseRD.png) | Slow response time due to large images |
| Sports| Desktop | ![](documentation/lighthouseSD.png) | Slow response time due to large images |
| Nightlife| Desktop | ![](documentation/lighthouseND.png) | Slow response time due to large images |
| Exploring| Desktop | ![](documentation/lighthouseED.png) | Slow response time due to large images |

## User Story Testing


| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to find a restaurant in Cork, so that I can eat in Cork. | ![](documentation/feature01.png) |
| As a new site user, I would like to find sports activities in Cork, so that I can find fun places to play sports in Cork. | ![](documentation/feature02.png) |
| As a new site user, I would like to find Cork's nightlife, so that I can to find pubs/ nightlife in Cork. | ![](documentation/feature03.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![](documentation/feature04.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![](documentation/feature05.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![](documentation/feature06.png) |

## Bugs


- Images Layout: Images were not going side by side with flex
    ![](documentation/bug01.png)

    - To fix this, I used grid css.


## Unfixed Bugs

There are no remaining bugs that I am aware of.
