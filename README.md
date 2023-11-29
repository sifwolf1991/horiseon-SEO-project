# Horiseon Website Accessibility Improvements


## Table of Contents

1. Description
2. Installation
3. Usage
4. Support
5. Contributing
6. Authors and acknowledgment
7. License

## 1. Description

Let people know what your project can do specifically. Provide context and add a link to any reference visitors might be unfamiliar with. A list of Features or a Background subsection can also be added here. If there are alternatives to your project, this is a good place to list differentiating factors.

The aim of this project was to examine the provided website code, CSS stylesheet, and assets for bugs, and make improvements to enhance the accessibility and layout of the Horiseon website.

General improvements have been made in the HTML file so that all hyperlinks work, images contain 'alt' attributes and descriptions. Improvements have been made to the CSS stylesheet so that selectors have been consolidated to reduce redundant code. 

Some styling attributes were added to the CSS code for page resizing purposes, before it was understood that topic hadn't been covered yet and those improvements were not required. Based on skills learned in that topic, in future this would have made use of flexboxes and media enquiries.

## 2. Installation

The HTML code and CSS styling can be accessed by installing a code editor such as Visual Code Studio. The website is deployed over GitHub and can be viewed in a web browser.

## 3. Usage

The website can be used as the Horiseon business official homepage, for users to get information on services offered by Horiseon, including Search Engine Optimization, Online Reputation Management and Social Media Marketing.

The HTML and CSS stylesheet provides comments to identify different parts of the code.

The website now has a more descriptive title, ‘Horiseon – Social Solution Services’ in the header for the purposes of search engine optimization.

A navigation bar in the webpage header provides working hyperlinks for Search Engine Optimization, Online Reputation Management, and Social Media Marketing, which take the user to the corresponding topic for more information. A bug in the hyperlink for ‘search-engine-optimization’ was fixed to ensure this link worked.

Alt tags were added to the hyperlinks to provide descriptive text if the images failed to load.

A ‘style’ tag specifying max-width: 100% and height:auto was added to images to ensure they scaled to fit the window if minimized.

In the CSS stylesheet, the header div selector specifies ‘position’ as ‘relative’ to ensure the heading hyperlinked text remains inside the blue header when the window is resized.

The selectors ‘search-engine-optimization’, ‘online-reputation-management’ and ‘social-media-marketing’ have properties height: 50%, width: 100% and overflow: auto added to ensure text and images don’t run outside their div containers when the page is resized.

Separate CSS selectors under the ‘brand’ class have been consolidated into a single selector called ‘brand-item’, to reduce redundancy.

## 4. Support

For support, users can contact tydamon@hotmail.com.

## 5. Contributing

Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". 
1.	Fork the Project
2.	Create your Feature Branch (git checkout -b feature/NewFeature)
3.	Commit your Changes (git commit -m 'Add some NewFeature')
4.	Push to the Branch (git push origin feature/NewFeature)
5.	Open a Pull Request

## 6. Authors and acknowledgment

The author acknowledges and credits those who have contributed to this project, including:
•	Provided Code Refactor Starter Code
•	https://git.bootcampcontent.com/Monash-University/MONU-VIRT-FSF-PT-11-2023-U-LOLC
•	Chee Ho Tai
•	Pranita Shrestha

## 7. License

Distributed under the MIT License. See LICENSE.txt for more information.