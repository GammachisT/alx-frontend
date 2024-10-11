# 0x00. Advanced HTML
![image](https://github.com/IamNaeto/alx-frontend/assets/105589308/ed794963-9c24-4d3e-b000-d9122cb02023)


Welcome!


Welcome to the Web Stack specialization. The 3 first projects will give you all basics of the Web development: HTML, CSS and Developer tools.

In this project, you will learn how to use HTML tags to structure a web page. No CSS, no styling - don’t worry, the final page will be “ugly” it’s normal, it’s not the purpose of this project.

Important note: details are important! lowercase vs uppercase / wrong letter… be careful!

#### Concepts
- [HTML - elements of a web page](https://intranet.alxswe.com/concepts/543)

## Resources

##### Read or watch:
- [HTML 5.2](https://intranet.alxswe.com/rltoken/3ZeSykXeV9rQhzFiW5GHcg)
- [HTML: HyperText Markup Language | MDN](https://intranet.alxswe.com/rltoken/XWdv6hMca_9jks7PN2gsbA)
- [HTML Reference - A free guide to all HTML elements and attributes](https://intranet.alxswe.com/rltoken/H59e408ohxV9x_tYOWSxvg)
- [Can I use… Support tables for HTML5, CSS3, etc](https://intranet.alxswe.com/rltoken/u6RvQ_45Xpw82Awl82NZcg)
- [HTML Cheat Sheet - WebsiteSetup](https://intranet.alxswe.com/rltoken/6SV9Z98vlb8iehxHnl9YJg)

## Learning Objectives
At the end of this project, you are expected to be able to [explain to anyone](https://intranet.alxswe.com/rltoken/F24l2-dtHshauXRVkZicyw), without the help of Google:
- Which guidelines to follow for HTML
- How to create the skeleton of an HTML5 page
- How to use semantic HTML tags to structure a web page
- Which use cases to use `` div `` vs `` span ``
- The semantic value’s of `` header`` , `` main ``, `` footer ``, `` article ``, `` nav ``, `` section ``, `` aside ``
- How to use headings (and why it’s important to follow the hierarchical order)
- How to make lists in HTML
- The differences between medias (SVG, GIF, PNG, JPG)
- How to structure data in a table
- How to integrate a video in a webpage
- How to integrate an audio file in a webpage
- How to embed external content
- How to correctly structure an HTML page

## Requirements
- A ``README.md `` file at the root of the folder of the project is mandatory
- Your code should be W3C compliant and validate with [W3C-Validator](https://intranet.alxswe.com/rltoken/Q-XyLkED_pMjSGEuZKb7Fw)
- ``Techium`` will be the name of the company we will use across our webpages.

## Sitemap of the project
![image](https://github.com/IamNaeto/alx-frontend/assets/105589308/9ad410f8-afa2-4e17-80a2-d5284f7e8337)

## Wireframe of ``Techium`` project
![image](https://github.com/IamNaeto/alx-frontend/assets/105589308/23aa9e90-3fba-41ad-aff1-08a8017976fa)

## Tasks

### 0. Create your first webpage
- Create your first HTML file ``0-index.html`` with:
- Add the doctype on the first line (without any comment)
- After the doctype, open and close a ``html tag``
- Add the language tag, specify English for [ISO language code](https://intranet.alxswe.com/rltoken/xBn1Co-FmScJ9Fn8bi6pCQ) and add the direction tag (ltr or rtl) on the html tag.
- Open your file in your browser (the page should be blank)

##### W3C won’t pass - you can ignore it

### 1. Structure your webpage
- Copy the content of 0-index.html into 1-index.html
- Create the head and body sections
	* inside the html tag, create the head and body tags (empty) in this order

##### W3C won’t pass - you can ignore it

### 2. The head - meta charset, viewport, title, description, favicons
![image](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/11/2ba3a0d7878316de5aaa.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20241011%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241011T112631Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7e8358d0f8be9cf0e6557f232d7bfeb6054e71122f8c3a200eb16b8b4ec1346d)
#### Meta charset:

- add a meta tag inside the head:
- add the charset attribute with the value utf-8
- Viewport:

- add a meta tag inside the head:
- add an attribute name on the tag and specify that it is the meta viewport
- add the key width with the value device-width
- add the key initial-scale with the value 1.0
- add the key viewport-fit with the value cover
#### Title:

- add the title tag just after the meta viewport with value: Homepage - Techium
#### Description:

- add a meta tag inside the head section
- add an attribute name on the tag and specify that is the meta description
- add another attribute called content
- add the following description: Techium is a digital agency
#### Favicons:

- download the image above to use as a favicon
- Use the tool at https://realfavicongenerator.net/ to generate all the favicon formats
- take the favicon.ico and favicon.png and place these at the root of your project directory, so that it is siblings with your [0-9]+-index.html files.
- inside the head, create 2 link tags with these 3 attributes: rel, type, and href.
***the first link tag:***

	* rel: icon
	* type: image/x-icon
	* href: ./favicon.ico
***the second link tag
	* rel: icon
	* type: image/png
	* href: ./favicon.png
