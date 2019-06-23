[![Build Status][build-shield]]()
[![Contributors][contributors-shield]]()
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/edward-joseph/alertBox">
    <img src="https://img.techpowerup.org/190623/favicon.png" alt="Logo" width="100" height="100">
  </a>

  <h3 align="center">alertBox</h3>
  <p align="center">
    Create an AlertBox with no hassle!
    <br />
    <a href="https://github.com/edward-joseph/alertBox"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/edward-joseph/alertBox/issues">Report Bug</a>
    ·
    <a href="https://github.com/edward-joseph/alertBox/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github.com/edward-joseph/alertBox)

In fact, I needed a javascript library where I always wanted to create `alerts` and `popups` without losing any time. It's also really annoying to spend my time making different `popups` and `alerts` with different designs.

So I spent my time up:
* built a library just with javascript so libraries like jQuery no longer needed
* To make a warning message for myself and the users who are tired of writing long codes
* With just a few lines of code writing, you can create alerts and popups that even change their designs

Of course, your needs can not be addressed with this library alone, and maybe you need more than that, so I'm going to update this library to be able to meet the maximum needs.

In fact, I created this library alone, but I also asked some questions about the problem.

### Built With
This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Javascript](https://www.javascript.com)
* [Css3](http://www.css3.info)



<!-- GETTING STARTED -->
## Getting Started

To launch and use the alertBox in your project, follow the steps below.

### Prerequisites

You must first download the alertBox library from its GitHub and add it to your project.

### Installation

1. First, go to the [alertBox](https://github.com/edward-joseph/alertBox) page
2. Then download that package and add it to your project
3. To add the necessary CSS, you must first go to the [Css Folder](https://github.com/edward-joseph/alertBox/tree/master/) in the package and add the alertBox.min.css file to your css files.
4. Also, to add JS files, you must log in to the [Js Folder](https://github.com/edward-joseph/alertBox/tree/master/) and add the alertBox.js file to your js files.

<!-- USAGE EXAMPLES -->
## Usage

To work with this library, we already defined a constant variable and set it equal to the `alertBox`.

* Alert
1. To create an alert, you must first call the addAlert function. This function receives two parameters
2. The first parameter of this function is a string that contains the text inside the alert
3. The second parameter of this function is a multiplicity of objects (although giving these values is arbitrary because the defaults are predefined)


| Object Value     | Application   | Acceptable values |
| -------------    | ------------- | ----------------- |
| position         | set alert box position  | 'left', `'right'`, 'center' |
| status           | determine the status of the alert box  | `'simple'`, 'success', 'error'      |
| align            | set the text orientation of the alert box  | `'left'`, 'right', 'center'      |
| animateDelay     | delay for displaying alert box  | NUMBER (s) : `0`     |
| animateDuration  | When it will take time for the alert box to be in position  | NUMBER (s) : `1`      |
| boxDuration      | The amount of time the alert box is in position  | NUMBER (s) : `2`     |

```javascript
alertBox.addAlert('This is a message',{
  position:'left',
  status:'error',
  align:'center',
  animateDelay:0.1,
  animateDuration:1,
  boxDuration:3
});
```

* Popup
1. To create a popup, you must use the addPopup function
2. This function receives only one parameter, which is object. This object accepts various values for popup control

| Object Value     | Application   | Acceptable values |
| -------------    | ------------- | ----------------- |
| duration         | the amount of animation time              | NUMBER (s) : `1`                |
| title         | setting the subject              | STRING: `'Subject: title'`                  |
| message         | set text message              | STRING : `'message'`                  |
| headerAlign         | setting the subject orientation              | `'left'`, 'right', 'center' |
| textAlign         | setting the message orientation              | `'left'`, 'right', 'center' |
| buttonAlign         | setting the buttons orientation              | `'left'`, 'right', 'center' |
| buttonWidth         | setting the buttons width              | NUMBER : 85                 |
| visible         | black background display              | `true`, false                  |
| hideClose         | display the exit icon              | true, `false`                  |

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Edward Joseph (ALi Yaghoby) - [Edward_Joseph](https://t.me/Edward_Joseph) - alibigham3095@gmail.com

Project Link: [alertBox](https://github.com/edward-joseph/alertBox)


<!-- MARKDOWN LINKS & IMAGES -->
[build-shield]: https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat-square
[contributors-shield]: https://img.shields.io/badge/contributors-1-orange.svg?style=flat-square
[license-shield]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square
[license-url]: https://choosealicense.com/licenses/mit
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: https://img.techpowerup.org/190623/screenshot.png
