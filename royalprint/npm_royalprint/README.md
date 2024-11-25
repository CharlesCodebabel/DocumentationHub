#  [![jackal-11-24-v2-32-inverted.png](https://i.postimg.cc/wBPhM5Lv/jackal-11-24-v2-32-inverted.png)]()  CODEBABEL

# royalprint: 1.0.3
## 📃 Description / Descrição
~~~
{EN}

royalprint is perfect for simplifying the information that needs to go to the console,
similar to printing in C++ command cout, PHP echo, log("Hi"), go("Hello ..."),
cout("whoami?"), puts("She Knows")... and more.

{PTBR}

royalprint é perfeita para simplificar as informações que precisam ir para o console,
com similaridade de impressão em C++ comando cout, PHP echo, log("Oi"), go("Olá ..."),
cout("whoami?"), puts("She Knows")... e mais.
~~~

![](https://shields.io/badge/JavaScript-F7DF1E?logo=JavaScript&logoColor=000&style=flat-square:)
![](https://img.shields.io/badge/license-MIT-blue)
![](https://img.shields.io/badge/Vue-3-green)
![](https://shields.io/badge/react-black?logo=react&style=for-the-badge:)
![](https://img.shields.io/badge/angular.js-DD0031?logo=angularjs&logoColor=white)
![](https://img.shields.io/badge/-Ember.js-E04E39?style=flat&logo=emberdotjs&logoColor=white)
![](https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte)


[![](https://i.postimg.cc/HLxCjz9S/royalprint.png)]()

## 🌐 Content / Conteúdo
* [Installation](#installation)
* [All print formats](#formats)
* [Basic use](#basic)
* [Complete use](#complete)
* [Change log](#changelog)

### installation
## 💻 Installation / Instalação:
> `npm i @codebabel/royalprint`

> `yarn add @codebabel/royalprint`

## ✅ Codebabel go
~~~js
// codebabel go minimum syntax
const { go } = require("@codebabel/royalprint");

const sayMyName = "SayMyName.";
go(sayMyName);

//> SayMyName.
~~~

## ✅ Codebabel show
~~~js
// codebabel show
const { show } = require("@codebabel/royalprint");

const seEuLargarOFreio = "Não diga que sou ruim!";
show(seEuLargarOFreio);

//> Não diga que sou ruim!
~~~

## ✅ PHP echo
~~~js
// Use PHP echo
const { echo } = require("@codebabel/royalprint");

const myNameIs = "What?";
echo(myNameIs);

//> What?
~~~

## ✅ Angular xPrint
~~~js
// Angular xPrint
const { xAngular } = require("@codebabel/royalprint");

const showThis = "Do your jumps!";
xAngular(showThis);

//> Do your jumps!
~~~
### formats
## 📊 All print formats / Todos os formatos
~~~
go
war
inf
ero
log
show
echo
puts
display
put_line
cout
printf
printin
println

xVue
xReact
xSvelte
xAngular
~~~
### basic
## 🔹 Basic use
~~~js
// easy pease fela / uso básico fela
const { log, war, inf, ero } = require("@codebabel/royalprint");

const msgBox = "I am tea pot!";
log(msgBox); // simple console message > ...
war(msgBox); // warning console message > ...
inf(msgBox); // info console message > ...
ero(msgBox); // error console message > ...
~~~
### complete
## 🔹🔹 Complete use
~~~js
// complete use
const {
    go, war, inf, ero, log, show, echo, puts,
    display, put_line, cout, printf, printin, println, xVue, xReact, xSvelte, xAngular
    } = require("@codebabel/royalprint");

const msgBox = "I am tea pot!";

// basic...
log(msgBox); // [scm] simple console message > ...
war(msgBox); // warning console message > ...
inf(msgBox); // info console message > ...
ero(msgBox); // error console message > ...

// Aesthetic Print...
go(msgBox);       // codebabel go
show(msgBox);     // codebabel show
echo(msgBox);     // php echo
puts(msgBox);     // Ruby puts
display(msgBox);  // cobol display
put_line(msgBox); // ada putline
cout(msgBox);     // c++ cout <
printf(msgBox);   // c printf
printin(msgBox);  // scala printin
println(msgBox);  // java println

// Aesthetic xPrint Thematic
xVue(msgBox);     // Vue xPrint
xReact(msgBox);   // React xPrint
xSvelte(msgBox);  // Svelte xPrint
xAngular(msgBox); // Angular xPrint
~~~
### changelog
## 🚨 Change Log
|Version| Version Name | Upgrade Latency |
|-------|--------------|-----------------|
| 1.0.0 |  royalprint  |    START LIB    |
| 1.0.1 |  royalprint  | VERSION VIEWER  |
| 1.0.2 |  royalprint  | README REWRITE  |
| 1.0.3 |  royalprint  | README REWRITE  |

## 💜 Thank's 🧡
~~~
{EN}
Thank you for using the royalprint library.
see ya!

{PTBR}
Valeu por usar a biblioteca royalprint.
tmj!
~~~
© Copyright 2024, Codebabel royalprint cross-language library.