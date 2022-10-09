<!-- Please update value in the {}  -->

<h1 align="center">{404-Error-Page}</h1>

<div align="center">
   Solution for a challenge from  <a href="http://devchallenges.io" target="_blank">Devchallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://petsamuel.github.io/error-page/">
      Demo
    </a>
    <span> | </span>
    <a href="https://github.com/Petsamuel/error-page">
      Solution
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenges/wBunSb7FPrIepJZAg0sY">
      Challenge
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
  - [Built With](#built-with)
- [Features](#features)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

<!-- OVERVIEW -->

## Overview

![screenshot](/127.0.0.1_3000_index.html.png)

A basic landing page design challenge by devchallenges using vanilla CSS and HTML.
Following the mobile first responsive design method, I developed the single webpage utilizing both semantic and non-semantic forms of element organization.

As seen here, the section element was wrapped in the main element (semantic).

``` html
 <main>
      <section class="intro-text-container">
        <p class="intro-text">404 NOT FOUND</p>
      </section>
      <section class="container">
        <div class="Scarecrow"></div>
        <div class="error-message-container">
          <p class="error-heading">I have bad news for you</p>
          <p class="error-text">The page you are looking for might be removed or is temporarily unavailable
          </p>
          <div class="button">
            <a href="#">Back to homepage</a>
          </div>
        </div>
      </section>
    </main>
```
using the root pseudo class i was able to defined required styles for the pages, the image is being passed directly to the Scarecrow class.

however the container class element the property of flex, makes the the image and the text to display on the same row.
as seen here in the Css.


``` css
/* pseudo class deceleration*/
:root {
    --Scarecrow: url("/assets/images/Scarecrow.png");
    --font1: "Inconsolata";
    --line-height: 36px;
    --letter-spacing: -0.035em;
    --text-color: #4F4F4F;
}

.container {
    display: flex;
    justify-content: space-between;
    gap:10%;
}
.Scarecrow {
    content: var(--Scarecrow);
    width: 50%;
}
.button {
    width: 216px;
    height: 68px;
    background: #333333;
    font-family: 'Space Mono';
    display:flex;
    justify-content: center;

}
a {
    color: white;
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 21px;
    letter-spacing: -0.035em;
    text-transform: uppercase;
    align-self: center;
     
}
```




### Built With

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->

- [html](https://reactjs.org/)
- [Css](https://vuejs.org/)


## Features

<!-- List the features of your application or follow the template. Don't share the figma file here :) -->

This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges) challenge. The [challenge](https://devchallenges.io/challenges/wBunSb7FPrIepJZAg0sY) was to build an application to complete the given user stories.



## Contact

- Medium [Post-link](https://{your-web-site-link})
- GitHub [Petsamuel](https://github.com/Petsamuel/)
- Twitter [@Bieefilled](https://twitter.com/Bieefilled)
