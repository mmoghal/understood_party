# 01 HTML, CSS, and Git: Code Refactor

## Description

A marketing agency has tasked us with refactoring an existing website to make it more accessible. The existing code has been refactored to meet a certain set of accessibility standards. The Horiseon website is organized into three main sections, including a banner and a right sidebar with a navigational header. Semantic elements have been used to clearly describe their meaning to both the browser and developer. Alternative text attributes have been added to provide information about images in case a user cannot view them. The code refactoring process has been completed without altering the external behavior of the website.

## Installation
N/A

## Table of Contents

1. Visit [Deployed Application](https://mmoghal.github.io/understood_party/) for Horiseon

2. Application Image

![alt Image of the application](https://github.com/mmoghal/understood_party/blob/main/assets/images/digital-marketing-meeting.jpg)

## Code Comments and Refactoring

•	Grouped all selectors with the same CSS rules using a comma separator in a single rule

•	Wrapped the main content using the main element and changed the class .content to main section and .benefits to aside element for better semantic meaning

•	Utilized a common class for all the aside elements and another class for the images

•	Employed a single class for all the articles and separated classes for the images

•	Removed duplicated code

•	Added comments for better readability

•	This approach made the HTML more semantic, reducing code duplication and keeping the codebase clean and concise. It also makes it easier to target each article with CSS or JavaScript.


## Usage

To access various parts of the webpage, utilize the navigation panel located at the top right corner. To discover other content on the page, simply scroll either upwards or downwards.

## Credits
Code refactoring completed by Muhammad Moghal

## License

Please refer to the LICENSE in the repo.
