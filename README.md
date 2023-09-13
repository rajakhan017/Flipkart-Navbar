# Flipkart-Navbar
# Assignment

## [Live Website Link!]https://rajakhan017.github.io/Flipkart-Navbar/

### Structure of the web page

img src="./public/readme/webpage.png" width="700px" alt="structure of the webpage"  />

---![image](https://github.com/rajakhan017/Flipkart-Navbar/assets/135150598/685770bb-bb00-42d8-9c7c-8cf5b691cae3)


.

### In `style.css`


#### `:root`

| CSS Rule            | Explanation                                                                             |
| ------------------- | --------------------------------------------------------------------------------------- |
| `:root`             | Pseudo-class selector representing the root element (typically the HTML document).      |
| `--flipkart-blue`   | Custom CSS variable defining a color value (#3d71e7) and naming it '--flipkart-blue'.   |
| `--flipkart-yellow` | Custom CSS variable defining a color value (#ffc200) and naming it '--flipkart-yellow'. |

**Rule Explanation**: The `:root` selector sets custom CSS variables `--flipkart-blue` and `--flipkart-yellow` with specific color values, which can be used throughout the stylesheet.

#### `*`

| CSS Selector  | Explanation                                                          |
| ------------- | -------------------------------------------------------------------- |
| `*`           | Universal selector that targets all elements in the HTML document.   |
| `box-sizing`  | Sets the CSS box model to 'border-box' for all elements.             |
| `margin`      | Sets the margin of all elements to 0, removing any default margin.   |
| `padding`     | Sets the padding of all elements to 0, removing any default padding. |
| `font-family` | Sets the font family for all elements to 'Inter', a sans-serif font. |

**Selector Explanation**: The `*` selector with various properties sets global styling for all HTML elements, including box-sizing, margin, padding, and font-family.

### In `header.css`

#### `.header`

| CSS Property     | Value                | Explanation                                                                                            |
| ---------------- | -------------------- | ------------------------------------------------------------------------------------------------------ |
| height           | 55px                 | Sets the height of elements with the class `.header` to 55 pixels.                                     |
| width            | 100%                 | Sets the width of elements with the class `.header` to 100% of their container.                        |
| background-color | var(--flipkart-blue) | Sets the background color of elements with the class `.header` to a custom variable `--flipkart-blue`. |
| display          | flex                 | Configures elements with the class `.header` as flex containers.                                       |
| flex-direction   | row                  | Sets the flex direction of elements with the class `.header` to a row layout.                          |
| justify-content  | start                | Aligns content at the start of the main axis within elements with the class `.header`.                 |
| align-items      | center               | Centers content vertically within elements with the class `.header`.                                   |
| gap              | 20px                 | Adds a 20-pixel gap between child elements of elements with the class `.header`.                       |

**Selector Explanation**: The `.header` selector targets elements with the class `.header`, styling them with specific size, background color, flex layout, and alignment properties.
![image](https://github.com/rajakhan017/Flipkart-Navbar/assets/135150598/6994a352-bcb0-4453-b759-e9afb899c0b7)

#### `.branding`

| CSS Property   | Value  | Explanation                                                                        |
| -------------- | ------ | ---------------------------------------------------------------------------------- |
| display        | flex   | Configures elements with the class `.branding` as flex containers.                 |
| flex-direction | column | Sets the flex direction of elements with the class `.branding` to a column layout. |
| margin-left    | 7%     | Adds a left margin of 7% to elements with the class `.branding`.                   |

**Selector Explanation**: The `.branding` selector targets elements with the class `.branding`, styling them as flex containers with a column layout and specific margin.

#### `.sub-branding`

| CSS Property   | Value | Explanation                                                                            |
| -------------- | ----- | -------------------------------------------------------------------------------------- |
| display        | flex  | Configures elements with the class `.sub-branding` as flex containers.                 |
| flex-direction | row   | Sets the flex direction of elements with the class `.sub-branding` to a row layout.    |
| gap            | 10px  | Adds a 10-pixel gap between child elements of elements with the class `.sub-branding`. |
| margin-left    | 68px  | Adds a left margin of 68px to elements with the class `.sub-branding`.                 |

**Selector Explanation**: The `.sub-branding` selector targets elements with the class `.sub-branding`, styling them as flex containers with a row layout, specific gap, and margin.
![image](https://github.com/rajakhan017/Flipkart-Navbar/assets/135150598/a09bf7bc-9113-44ea-bc89-3d40310bfed4)

#### `.sub-branding p`

| CSS Property | Value  | Explanation                                                                                         |
| ------------ | ------ | --------------------------------------------------------------------------------------------------- |
| font-size    | 12px   | Sets the font size of `p` elements within elements with the class `.sub-branding` to 12 pixels.     |
| font-style   | italic | Sets the font style of `p` elements within elements with the class `.sub-branding` to italic.       |
| font-weight  | 600    | Sets the font weight of `p` elements within elements with the class `.sub-branding` to 600 (bold).  |
| color        | #fff   | Sets the text color of `p` elements within elements with the class `.sub-branding` to white (#fff). |

**Selector Explanation**: The `.sub-branding p` selector targets `p` elements within elements with the class `.sub-branding`, styling them with specific font properties and text color.

#### `p span`

| CSS Property | Value                  | Explanation                                                                                          |
| ------------ | ---------------------- | ---------------------------------------------------------------------------------------------------- |
| color        | var(--flipkart-yellow) | Sets the text color of `span` elements within `p` elements to a custom variable `--flipkart-yellow`. |

**Selector Explanation**: The `p span` selector targets `span` elements within `p` elements, styling them with a custom text color variable.

#### `.search-bar`

| CSS Property     | Value | Explanation                                                                               |
| ---------------- | ----- | ----------------------------------------------------------------------------------------- |
| display          | flex  | Configures elements with the class `.search-bar` as flex containers.                      |
| background-color | #fff  | Sets the background color of elements with the class `.search-bar` to white (#fff).       |
| border-radius    | 2px   | Rounds the corners of elements with the class `.search-bar` with a radius of 2 pixels.    |
| box-shadow       | ...   | Applies a box shadow to elements with the class `.search-bar` for a subtle shadow effect. |

**Selector Explanation**: The `.search-bar` selector targets elements with the class `.search-bar`, styling them as flex containers with a white background, rounded corners, and a box shadow.
![image](https://github.com/rajakhan017/Flipkart-Navbar/assets/135150598/1bb1f59c-98cf-4140-95eb-ea71f30bfaa0)

#### `input`

| CSS Property  | Value | Explanation                                                       |
| ------------- | ----- | ----------------------------------------------------------------- |
| height        | 35px  | Sets the height of `input` elements to 35 pixels.                 |
| width         | 480px | Sets the width of `input` elements to 480 pixels.                 |
| border        | none  | Removes the border of `input` elements.                           |
| padding-left  | 20px  | Adds left padding of 20 pixels to `input` elements.               |
| outline       | none  | Removes the outline (focus border) of `input` elements.           |
| border-radius | 2px   | Rounds the corners of `input` elements with a radius of 2 pixels. |

**Selector Explanation**: The `input` selector targets `input` elements, styling them with specific size, border properties, padding, and border-radius.

#### `input::-webkit-input-placeholder` and `input:-moz-placeholder`

| CSS Property | Value | Explanation                                                 |
| ------------ | ----- | ----------------------------------------------------------- |
| font-weight  | 500   | Sets the font weight of input placeholders to 500 (medium). |
| font-size    | 14px  | Sets the font size of input placeholders to 14 pixels.      |

**Selector Explanation**: These selectors target the input placeholders for webkit and Mozilla-based browsers, styling them with specific font properties.

#### `.icon`

| CSS Property     | Value   | Explanation                                                                                |
| ---------------- | ------- | ------------------------------------------------------------------------------------------ |
| background-color | #fff    | Sets the background color of elements with the class `.icon` to white (#fff).              |
| height           | 35px    | Sets the height of elements with the class `.icon` to 35 pixels.                           |
| width            | 40px    | Sets the width of elements with the class `.icon` to 40 pixels.                            |
| cursor           | pointer | Changes the cursor to a pointer (hand) when hovering over elements with the class `.icon`. |
| border-radius    | 2px     | Rounds the corners of elements with the class `.icon` with a radius of 2 pixels.           |

**Selector Explanation**: The `.icon` selector targets elements with the class `.icon`, styling them with specific size, background color, cursor behavior, and border-radius.

#### `.icon svg`

| CSS Property | Value | Explanation                                                                           |
| ------------ | ----- | ------------------------------------------------------------------------------------- |
| margin-top   | 5px   | Adds top margin of 5 pixels to `svg` elements within elements with the class `.icon`. |

**Selector Explanation**: The `.icon svg` selector targets `svg` elements within elements with the class `.icon`, styling them with a specific top margin.

#### `.login button`

| CSS Property  | Value                | Explanation                                                                                                                 |
| ------------- | -------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| height        | 30px                 | Sets the height of `button` elements within elements with the class `.login` to 30 pixels.                                  |
| width         | 130px                | Sets the width of `button` elements within elements with the class `.login` to 130 pixels.                                  |
| color         | var(--flipkart-blue) | Sets the text color of `button` elements within elements with the class `.login` using a custom variable `--flipkart-blue`. |
| font-weight   | 500                  | Sets the font weight of `button` elements within elements with the class `.login` to 500 (medium).                          |
| border        | none                 | Removes the border of `button` elements.                                                                                    |
| cursor        | pointer              | Changes the cursor to a pointer (hand) when hovering over `button` elements.                                                |
| font-size     | 15px                 | Sets the font size of `button` elements within elements with the class `.login` to 15 pixels.                               |
| border-radius | 1px                  | Rounds the corners of `button` elements with a radius of 1 pixel.                                                           |

**Selector Explanation**: The `.login button` selector targets `button` elements within elements with the class `.login`, styling them with specific size, color, font properties, border, cursor, and border-radius.

#### `.become-seller`, `.more`, `.cart`

| CSS Property | Value   | Explanation                                                                                                                 |
| ------------ | ------- | --------------------------------------------------------------------------------------------------------------------------- |
| color        | #fff    | Sets the text color of elements with the classes `.become-seller`, `.more`, and `.cart` to white (#fff).                    |
| font-weight  | 500     | Sets the font weight of elements with the classes `.become-seller`, `.more`, and `.cart` to 500 (medium).                   |
| cursor       | pointer | Changes the cursor to a pointer (hand) when hovering over elements with the classes `.become-seller`, `.more`, and `.cart`. |
| margin-left  | Varies  | Adds left margin to elements with the classes `.become-seller`, `.more`, and `.cart`.                                       |

**Selector Explanation**: The selectors `.become-seller`, `.more`, and `.cart` target elements with specific classes, styling them with text color, font-weight, cursor behavior, and varying left margins.

#### `.more`

| CSS Property | Value  | Explanation                                                                    |
| ------------ | ------ | ------------------------------------------------------------------------------ |
| display      | flex   | Configures elements with the class `.more` as flex containers.                 |
| gap          | 10px   | Adds a 10-pixel gap between child elements of elements with the class `.more`. |
| align-items  | center | Centers content vertically within elements with the class `.more`.             |

**Selector Explanation**: The `.more` selector targets elements with the class `.more`, styling them as flex containers with specific gap and vertical alignment properties.

#### `.cart`

| CSS Property | Value  | Explanation                                                                    |
| ------------ | ------ | ------------------------------------------------------------------------------ |
| display      | flex   | Configures elements with the class `.cart` as flex containers.                 |
| gap          | 10px   | Adds a 10-pixel gap between child elements of elements with the class `.cart`. |
| align-items  | center | Centers content vertically within elements with the class `.cart`.             |

**Selector Explanation**: The `.cart` selector targets elements with the class `.cart`, styling them as flex containers with specific gap and vertical alignment properties.

### In `sub-header.css`

#### `.sub-header`

| CSS Property    | Value  | Explanation                                                                          |
| --------------- | ------ | ------------------------------------------------------------------------------------ |
| margin-top      | 20px   | Adds top margin of 20 pixels to elements with the class `.sub-header`.               |
| display         | flex   | Configures elements with the class `.sub-header` as flex containers.                 |
| justify-content | center | Centers content horizontally within elements with the class `.sub-header`.           |
| gap             | 50px   | Adds a 50-pixel gap between child elements of elements with the class `.sub-header`. |

**Selector Explanation**: The `.sub-header` selector targets elements with the class `.sub-header`, styling them with a top margin, flex layout, horizontal centering, and specific gap.

#### `.sub-header p`

| CSS Property | Value   | Explanation                                                                                                          |
| ------------ | ------- | -------------------------------------------------------------------------------------------------------------------- |
| margin-top   | 10px    | Adds top margin of 10 pixels to `p` elements within elements with the class `.sub-header`.                           |
| font-size    | 13px    | Sets the font size of `p` elements within elements with the class `.sub-header` to 13 pixels.                        |
| font-weight  | 500     | Sets the font weight of `p` elements within elements with the class `.sub-header` to 500 (medium).                   |
| cursor       | pointer | Changes the cursor to a pointer (hand) when hovering over `p` elements within elements with the class `.sub-header`. |

**Selector Explanation**: The `.sub-header p` selector targets `p` elements within elements with the class `.sub-header`, styling them with specific margins, font properties, and cursor behavior.

#### `.sub-header img`

| CSS Property | Value   | Explanation                                                                                                            |
| ------------ | ------- | ---------------------------------------------------------------------------------------------------------------------- |
| height       | 70px    | Sets the height of `img` elements within elements with the class `.sub-header` to 70 pixels.                           |
| cursor       | pointer | Changes the cursor to a pointer (hand) when hovering over `img` elements within elements with the class `.sub-header`. |

**Selector Explanation**: The `.sub-header img` selector targets `img` elements within elements with the class `.sub-header`, styling them with specific height and cursor behavior.

#### `.item`

| CSS Property    | Value  | Explanation                                                                    |
| --------------- | ------ | ------------------------------------------------------------------------------ |
| display         | flex   | Configures elements with the class `.item` as flex containers.                 |
| flex-direction  | column | Sets the flex direction of elements with the class `.item` to a column layout. |
| justify-content | center | Centers content horizontally within elements with the class `.item`.           |
| align-items     | center | Centers content vertically within elements with the class `.item`.             |

**Selector Explanation**: The `.item` selector targets elements with the class `.item`, styling them as flex containers with specific layout and alignment properties.

#### `.desc`

| CSS Property    | Value   | Explanation                                                                                |
| --------------- | ------- | ------------------------------------------------------------------------------------------ |
| display         | flex    | Configures elements with the class `.desc` as flex containers.                             |
| justify-content | center  | Centers content horizontally within elements with the class `.desc`.                       |
| align-items     | center  | Centers content vertically within elements with the class `.desc`.                         |
| gap             | 5px     | Adds a 5-pixel gap between child elements of elements with the class `.desc`.              |
| cursor          | pointer | Changes the cursor to a pointer (hand) when hovering over elements with the class `.desc`. |

**Selector Explanation**: The `.desc` selector targets elements with the class `.desc`, styling them as flex containers with specific layout, alignment, gap, and cursor behavior.

#### `.desc svg`

| CSS Property | Value | Explanation                                                                            |
| ------------ | ----- | -------------------------------------------------------------------------------------- |
| margin-top   | 10px  | Adds top margin of 10 pixels to `svg` elements within elements with the class `.desc`. |

**Selector Explanation**: The `.desc svg` selector targets `svg` elements within elements with the class `.desc`, styling them with a specific top margin.
