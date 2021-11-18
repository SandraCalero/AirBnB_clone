# 0x01. AirBnB clone - Web static

## General

- What is HTML
- How to create an HTML page
- What is a markup language
- What is the DOM
- What is an element / tag
- What is an attribute
- How does the browser load a webpage
- What is CSS
- How to add style to an element
- What is a class
- What is a selector
- How to compute CSS Specificity Value
- What are Box properties in CSS

## More Info
![hbnb_step1](https://user-images.githubusercontent.com/85451781/142458861-e91597e3-67fb-440f-a177-17a030792409.png)

## Tasks

### 0. Inline styling

Write an HTML page that displays a header and a footer.

Layout:

- Body:
  - no margin
  - no padding
- Header:
  - color #FF0000 (red)
  - height: 70px
  - width: 100%
- Footer:
  - color #00FF00 (green)
  - height: 60px
  - width: 100%
  - text Best School center vertically and horizontally
  - always at the bottom at the page

Requirements:

- You must use the header and footer tags
- You are not allowed to import any files
- You are not allowed to use the style tag in the head tag
- Use inline styling for all your tags

![939d6b9448e63776610d05d2226aa8985209ee4d](https://user-images.githubusercontent.com/85451781/142459081-18eb52c6-0686-4168-9321-fbd790abc215.png)

**Repo:**

- GitHub repository: AirBnB_clone
- Directory: web_static
- File: 0-index.html

### 1. Head styling

Write an HTML page that displays a header and a footer by using the style tag in the head tag (same as 0-index.html)

Requirements:

- You must use the header and footer tags
- You are not allowed to import any files
- No inline styling
- You must use the style tag in the head tag

The layout must be exactly the same as 0-index.html

**Repo:**

- GitHub repository: AirBnB_clone
- Directory: web_static
- File: 1-index.html

### 2. CSS files

Write an HTML page that displays a header and a footer by using CSS files (same as 1-index.html)

Requirements:

- You must use the header and footer tags
- No inline styling
- You must have 3 CSS files:
  - styles/2-common.css: for global style (i.e. the body style)
  - styles/2-header.css: for header style
  - styles/2-footer.css: for footer style

The layout must be exactly the same as 1-index.html

**Repo:**

- GitHub repository: AirBnB_clone
- Directory: web_static
- File: 2-index.html, styles/2-common.css, styles/2-header.css, styles/2-footer.css

### 3. Zoning done!

Write an HTML page that displays a header and footer by using CSS files (same as 2-index.html)

Layout:

- Common:
  - no margin
  - no padding
  - font color: #484848
  - font size: 14px
  - font family: Circular,"Helvetica Neue",Helvetica,Arial,sans-serif;
  - icon in the browser tab
- Header:
  - color: white
  - height: 70px
  - width: 100%
  - border bottom 1px #CCCCCC
  - logo align on left and center vertically (20px space at the left)
- Footer:
  - color white
  - height: 60px
  - width: 100%
  - border top 1px #CCCCCC
  - text Best School center vertically and horizontally
  - always at the bottom at the page

Requirements:

- No inline style
- You are not allowed to use the img tag
- You are not allowed to use the style tag in the head tag
- All images must be stored in the images folder
- You must have 3 CSS files:
  - styles/3-common.css: for the global style (i.e body style)
  - styles/3-header.css: for the header style
  - styles/3-footer.css: for the footer style

![101096090ff2b87a86083d61789d597774400d5d](https://user-images.githubusercontent.com/85451781/142459489-b4d1b2a5-7ee2-4acd-bc76-131787f90946.png)

**Repo:**

- GitHub repository: AirBnB_clone
- Directory: web_static
- File: 3-index.html, styles/3-common.css, styles/3-header.css, styles/3-footer.css, images/

### 4. Search!

Write an HTML page that displays a header, footer and a filters box with a search button.

Layout: (based on 3-index.html)

- Container:
  - between header and footer tags, add a div:
    - classname: container
    - max width 1000px
    - margin top and bottom 30px - it should be 30px under the bottom of the header (screenshot)
    - center horizontally
- Filter section:
  - tag section
  - classname filters
  - inside the .container
  - color white
  - height: 70px
  - width: 100% of the container
  - border 1px #DDDDDD with radius 4px
- Button search:
  - tag button
  - text Search
  - font size: 18px
  - inside the section filters
  - background color #FF5A5F
  - text color #FFFFFF
  - height: 48px
  - width: 20% of the section filters
  - no borders
  - border radius: 4px
  - center vertically and at 30px of the right border
  - change opacity to 90% when the mouse is on the button

Requirements:

- You must use: header, footer, section, button tags
- No inline style
- You are not allowed to use the img tag
- You are not allowed to use the style tag in the head tag
- All images must be stored in the images folder
- You must have 4 CSS files:
  - styles/4-common.css: for the global style (body and .container styles)
  - styles/3-header.css: for the header style
  - styles/3-footer.css: for the footer style
  - styles/4-filters.css: for the filters style
- 4-index.html won’t be W3C valid, don’t worry, it’s temporary

![0fc91d5d4d62955575dc65a93d9823cf4dc72133](https://user-images.githubusercontent.com/85451781/142459704-a73d4980-2d68-4819-b88d-512481a72f3e.png)

**Repo:**

- GitHub repository: AirBnB_clone
- Directory: web_static
- File: 4-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/4-filters.css, images/

### 5. More filters

Write an HTML page that displays a header, footer and a filters box.

Layout: (based on 4-index.html)

- Locations and Amenities filters:
  - tag: div
  - classname: locations for location tag and amenities for the other
  - inside the section filters (same level as the button Search)
  - height: 100% of the section filters
  - width: 25% of the section filters
  - border right #DDDDDD 1px only for the first left filter
  - contains a title:
    - tag: h3
    - font weight: 600
    - text States or Amenities
  - contains a subtitle:
    - tag: h4
    - font weight: 400
    - font size: 14px
    - text with fake contents

Requirements:

- You must use: header, footer, section, button, h3, h4 tags
- No inline style
- You are not allowed to use the img tag
- You are not allowed to use the style tag in the head tag
- All images must be stored in the images folder
- You must have 4 CSS files:
  - styles/4-common.css: for the global style (body and .container styles)
  - styles/3-header.css: for the header style
  - styles/3-footer.css: for the footer style
  - styles/5-filters.css: for the filters style

![63600f1cf5fad5711e6ebba03421fe980d498ec5](https://user-images.githubusercontent.com/85451781/142460141-b3166e1a-12e8-499d-9059-f2ac531e1ac2.png)

**Repo:**

- GitHub repository: AirBnB_clone
- Directory: web_static
- File: 5-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/5-filters.css, images/

### 6. It's (h)over

Write an HTML page that displays a header, footer and a filters box with dropdown.

Layout: (based on 5-index.html)

- Update Locations and Amenities filters to display a contextual dropdown when the mouse is on the filter div:
  - tag ul
  - classname popover
  - text should be fake now
  - inside each div
  - not displayed by default
  - color #FAFAFA
  - width same as the div filter
  - border #DDDDDD 1px with border radius 4px
  - no list display
  - Location filter has 2 levels of ul/li:
    - state -> cities
    - state name must be display in a h2 tag (font size 16px)

Requirements:

    * You must use: header, footer, section, button, h3, h4, ul, li tags
    * No inline style
    * You are not allowed to use the img tag
    * You are not allowed to use the style tag in the head tag
    * All images must be stored in the images folder
    * You must have 4 CSS files:
        * styles/4-common.css: for the global style (body and .container styles)
        * styles/3-header.css: for the header style
        * styles/3-footer.css: for the footer style
        * styles/6-filters.css: for the filters style

![2fc49432137a0f660dedf3fd4b3d86449a72bc53](https://user-images.githubusercontent.com/85451781/142460297-942b4ba3-b18c-4dc8-a59e-bcdb2a808ab6.png)
![5aa1d0291e579abd8fc9876af9b9d089147268e2](https://user-images.githubusercontent.com/85451781/142460392-6129baa1-0802-464b-83a6-3171928225b7.png)

**Repo:**

- GitHub repository: AirBnB_clone
- Directory: web_static
- File: 6-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, images/

### 7. Display results

Write an HTML page that displays a header, footer, a filters box with dropdown and results.

Layout: (based on 6-index.html)

- Add Places section:
  - tag: section
  - classname: places
  - same level as the filters section, inside .container
  - contains a title:
    - tag: h1
    - text: Places
    - align in the top left
    - font size: 30px
  - contains multiple “Places” as listing (horizontal or vertical) describe by:
    - tag: article
    - width: 390px
    - padding and margin 20px
    - border #FF5A5F 1px with radius 4px
    - contains the place name:
      - tag: h2
      - font size: 30px
      - center horizontally

Requirements:

- You must use: header, footer, section, article, button, h1, h2, h3, h4, ul, li tags
- No inline style
- You are not allowed to use the img tag
- You are not allowed to use the style tag in the head tag
- All images must be stored in the images folder
- You must have 5 CSS files:
  - styles/4-common.css: for the global style (i.e. body and .container styles)
  - styles/3-header.css: for the header style
  - styles/3-footer.css: for footer style
  - styles/6-filters.css: for the filters style
  - styles/7-places.css: for the places style

![4655b5086fc9b7832927f0a2ac6f04dc0b44775b](https://user-images.githubusercontent.com/85451781/142460489-84bfe677-0cce-4201-98c2-6cb810a81f5f.png)

**Repo:**

- GitHub repository: AirBnB_clone
- Directory: web_static
- File: 7-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, styles/7-places.css, images/

### 8. More details

Write an HTML page that displays a header, a footer, a filter box (dropdown list) and the result of the search.

Layout: (based on 7-index.html)

Add more information to a Place article:

- Price by night:
  - tag: div
  - classname: price_by_night
  - same level as the place name
  - font color: #FF5A5F
  - border: #FF5A5F 4px rounded
  - min width: 60px
  - height: 60px
  - font size: 30px
  - align: the top right (with space)
- Information section:
  - tag: div
  - classname: information
  - height: 80px
  - border: top and bottom #DDDDDD 1px
  - contains (align vertically):
    - Number of guests:
      - tag: div
      - classname: max_guest
      - width: 100px
      - fake text
      - icon
    - Number of bedrooms:
      - tag: div
      - classname: number_rooms
      - width: 100px
      - fake text
      - icon
    - Number of bathrooms:
      - tag: div
      - classname: number_bathrooms
      - width: 100px
      - fake text
      - icon
- User section:
  - tag: div
  - classname: user
  - text Owner: <fake text>
  - Owner text should be in bold
- Description section:
  - tag: div
  - classname: description

Requirements:

- You must use: header, footer, section, article, button, h1, h2, h3, h4, ul, li tags
- No inline style
- You are not allowed to use the img tag
- You are not allowed to use the style tag in the head tag
- All images must be stored in the images folder
- You must have 5 CSS files:
  - styles/4-common.css: for the global style (i.e. body and .container styles)
  - styles/3-header.css: for the header style
  - styles/3-footer.css: for the footer style
  - styles/6-filters.css: for the filters style
  - styles/8-places.css: for the places style

![f47a405fccad371100ff9665dae9b3a84a471e62](https://user-images.githubusercontent.com/85451781/142460601-898ae17e-9f2d-418b-b2ef-141b8ca07fa4.png)

**Repo:**

- GitHub repository: AirBnB_clone
- Directory: web_static
- File: 8-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, styles/8-places.css, images/
