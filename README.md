# Edie Homepage

Create a static page with HTML and CSS by using SCSS following the designs. To avoid complexity, I use parcel instead of watching the SASS to convert it into CSS. Because parcel convert a SASS style into a CSS automatically.

- Make the design by mobile view as a default device.

![image](./assets/edie.png)
This image is just a preview, the full design is on the figma file!


**Icon**: https://google.github.io/material-design-icons/

**Design**: https://www.figma.com/file/ahnGupP4JjTdVJDTRfMRF2

**Live app**: https://edie-homepage-noeline.netlify.app/

## Design structure:

 - I separated each element selection style into its own file to make it understandable. Also, it's not good to put all the styles in one file but instead I import each file into the index.scss the one I need to link in the html file.
 - I create a variable file for the variables that may be needed in multiple file and just import the file.
 - To get the fonts working, I didn't use google fonts. I create a file and create objects for the font and loop through them you can find the document for doing that [here](https://sass-lang.com/documentation/at-rules/control/each)


Template for your readme :

<!-- Please update value in the {}  -->

<h1 align="center">Edie Homepage</h1>

<div align="center">
  <h3>
    <a href="https://edie-homepage-noeline.netlify.app/">
      Demo
    </a>
    <span> | </span>
    <a href="https://github.com/vakodrazan/edie-homepage">
      Solution
    </a>
  </h3>
</div>

### Built With

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->

-   [React](https://reactjs.org/)
-   [SASS](https://sass-lang.com)
-   [Parcel](https://parceljs.org)


## How To Use

<!-- Example: -->

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/vakodrazan/edie-homepage

# Install dependencies
$ npm install

# Run the app
$ npm start or parcel index.html
```

## Contact

-   Website [edi-homepage.com](https://edie-homepage-noeline.netlify.app/)
-   GitHub [Noeline](https://github.com/vakodrazan/edie-homepage)
