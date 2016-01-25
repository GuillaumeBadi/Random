<br>
<p align="center"><a href="#" target="_blank"><img width="250"src="https://raw.githubusercontent.com/GuillaumeBadi/Random/master/Logo.png?token=AGQURhfvBXfb5WB8lp3rMwSfsNhfuj0Yks5WqMwuwA%3D%3D"></a></p>

<p align="center">
  <a href="https://travis-ci.org/mailjet/mailjet-apiv3-python"><img src="https://travis-ci.org/mailjet/mailjet-apiv3-python.svg?branch=master" alt="travis"></a>
</p>

<p align="center">
<br>
|
<b><a href="#introduction"> Introduction </a></b>|
<b><a href="#installation"> Installation </a></b>|
<b><a href="#usage"> Usage </a></b>|
<b><a href="#tryitlive"> Plugins </a></b>|
<b><a href="#contribute"> Contribute </a></b>|

</p>
<br>

---

# Introduction

MJML is a markup language designed to reduce the pain of coding a responsive email. Its semantic syntax makes it easy and straightforward while its rich standard components library fastens your development time and lightens your email codebase. MJML’s open-source engine takes care of translating the MJML you wrote into responsive HTML.

<br>
<p align="center">
  <a href="#" target="_blank">
    <img width="75%" src="https://cloud.githubusercontent.com/assets/6558790/12450760/ee034178-bf85-11e5-9dda-98d0c8f9f8d6.png">
  </a>
</p>

<br>

# Installation

<p>
  <a href="#" target="_blank">
    <strong align="left">Via NPM: </strong>
    <img align="right" width="30" src="https://www.npmjs.com/static/images/npm-logo.svg">
  </a>
</p>


```

npm install -g mjml

```

<p>
  <a href="#" target="_blank">
    <strong align="left">Via Bower: </strong>
    <img align="right" width="30"src="http://bower.io/img/bower-logo.svg">
  </a>
</p>

```

bower install mjml

```

<a href="#" target="_blank">
  <strong align="left">Via... click: </strong>
</a>

<p align="center">
  <a href="#" target="_blank">
    <img width="100" src="https://cloud.githubusercontent.com/assets/6558790/12175323/cdc78a78-b561-11e5-99e2-23abd893879a.png">
  </a>
</p>


# Show me the code!

### Command line

> Compile the file and output the result in `a.html`

``` bash

$> mjml input.mjml

```

> Redirect the result to a file

``` bash

$> mjml input.mjml -o output.html

```

> Watch a file and compile every time the file changes

``` bash

$> mjml -w input.mjml -o output.html

```

<br>
### Inside NodeJs

``` javascript

import mjml, { watch, compile } from 'mjml'

/*
  Takes a file and compile it using the provided options
*/
compile('input.html', {output: 'output.html', minify: true})

/*
  Takes a file and call compile on each change
*/
watch('input.mjml', {output: 'output.html'})

/*
  Compile an mjml string
*/
const outputString = mjml('mjml code')

```

### Create your component

> Issue the following in your terminal

``` bash

$> mjml --register <name of your component>

# If your component cannot contain anything else than text:
$> mjml --register <name of you component> -e

```

It will create an basic component template in a `.js` file. Follow the instructions provided in the file
and read more about custom components in the documentation (TODO: link)

<br>

# Try it live

Get your hands dirty by trying the MJML online editor! Write awesome code on the left side an preview your email on the right

<p align="center">
  <a href="#"><img src="https://cloud.githubusercontent.com/assets/6558790/12195421/58a40618-b5f7-11e5-9ed3-80463874ab14.png" alt="try it live" width="75%"></a>
</p>
<br>

# Contributors

<table cellpadding="0">
  <tr>
    <th><a href="#"><img src="https://avatars2.githubusercontent.com/u/570317?v=3&s=192" alt="Maxime" width="100px"></a></th>
    <th><a href="#"><img src="https://avatars0.githubusercontent.com/u/116530?v=3&s=192" alt="Robin" width="100px"></a></th>
    <th><a href="#"><img src="https://avatars1.githubusercontent.com/u/582703?v=3&s=192" alt="Loeck" width="100px"></a></th>
    <th><a href="#"><img src="https://avatars3.githubusercontent.com/u/6558790?v=3&s=192" alt="Guillaume" width="100px"></a></th>
    <th><a href="#"><img src="https://avatars1.githubusercontent.com/u/315259?v=3&s=192" alt="Meriadec" width="100px"></a></th>
  </tr>
  <tr>
    <td><a href="https://github.com/iRyusa">Maxime</a></td>
    <td><a href="https://github.com/robink">Robin</a></td>
    <td><a href="https://github.com/lohek">Loeck</a></td>
    <td><a href="https://github.com/GuillaumeBadi">Guillaume</a></td>
    <td><a href="https://github.com/meriadec">Meriadec</a></td>
  </tr>
</table>

# Contribute

 - [ ] Fork the repository
 - [x] Code an awesome feature (we are confident about that)
 - [ ] Make your pull request
 - [ ] Add your github profile here
