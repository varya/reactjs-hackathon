---

layout: sc5

style: |

    #Cover h2 {
        margin:80px 0 0;
        color:#FFF;
        text-align:center;
        font-size:60px;
        line-height: 1.5em;
        }
    #Cover p {
        margin:10px 0 0;
        text-align:center;
        color:#FFF;
        font-size:20px;
        }
        #Cover p a {
            color:#FFF;
            }
    #Picture h2 {
        color:#FFF;
        }
    #SeeMore h2 {
        font-size:100px
        }
    #SeeMore img {
        width:0.72em;
        height:0.72em;
        }
    body {
      font-family: 'PT Sans', sans-serif;
      font-size: 24px;
    }
    .slide h2 {
      font-size: 52px; /* for cyrilic */
    }
    .slide>div {
      font-size: 32px;
      padding-top: 50px;
    }
    .slide ol li,
    .slide ul li {
      text-indent: -1em;
    }
    .slide pre {
        background-color: #efefef;
        padding: 15px;
    }
    .slide pre code {
        line-height: 1.5em;
        font-size: 26px;
    }
    .slide pre code:before {
        content: "";
    }
    .shout.slide {
      background-color: #ef4942;
    }
    .shout.slide h2 {
      color: #fff;
      font-size: 100px;
    }
    .no-title h2 {
      display: none;
    }
---

# React Hackathon {#Cover}

*Brought to you by&nbsp;[Varya&nbsp;Stepanova](http://varya.me/) and generated with&nbsp;[Jekyller](https://github.com/shower/jekyller)*
{: .credits }

<style>
#Cover {
  background-image:url('pictures/cover.png');
  background-size: cover;
  background-position: -75px 0, center;
}
#Cover h2 {
   display: none;
}

#Cover .credits {
 position: absolute;
 bottom: 0;
 right: 2em;
}
</style>

## Material
{: .material }

### [varya.me/reactjs-hackathon](http://varya.me/reactjs-hackathon)

<style>
.material h3 {
  font-size: 2.15em;
}
</style>

## Agenda
{: .agenda }

1. About the event
1. Choosing the projects
1. Introduction to React
1. Stub projects
1. Linking UI libraries
1. React Native
1. Relay&QraphQL
1. Coding

<style>
.agenda ol {
    columns: 2;
    -webkit-columns: 2;
    -moz-columns: 2;
    list-style-position: inside;//this is important addition
}
</style>

## Next big app
{: .shout }

## App to write

<table><tr>

<td markdown="1">
* Instagram-like
* Twitter dashboard
* Shopping list
* [Bars on map](http://kipp.is/map)
</td>

<td markdown="1">
* [2048](https://claudiopro.github.io/2048-react/)
* Tetris
* [Snake game](https://reake-react-snake.firebaseapp.com/)
* Your own idea
</td>

</tr></table>

## React
{: .shout }

## Introduction to React

* [Official React website](https://facebook.github.io/react/index.html)
* [17 short video lessons](https://egghead.io/series/build-your-first-react-js-application)

## What is so great about React?
{: .what-is-so-great }

<textarea class="insert">
</textarea>

<style>
.what-is-so-great .insert {
  width: 100%;
  height: 325px;
  font-size: 25px;
}
</style>

<script>
var textArea = document.querySelector('.what-is-so-great .insert');
textArea.addEventListener('keydown', function(e){
  e.stopPropagation();
});
</script>

## Buzz words

* ES2015 (ES6)
* React
* webpack
* Flux / Redux
* Relay & GraphQL

## Starter projects
{: .starter-projects }

###Search

[andrewhfarmer.com/starter-project](http://andrewhfarmer.com/starter-project/)

<style>
.starter-projects h3 {
  font-size: 1.65em;
}
.starter-projects a {
  font-size: 1.65em;
}
</style>

## Plain JavaScript
{: .plainjs }

[https://facebook.github.io/react/downloads.html](https://facebook.github.io/react/downloads.html)

    <script src="https://fb.me/react-0.14.7.js"
        integrity="sha384-xQae1pUPdAKUe0u0KUTNt09zzdwheX4VSUsV8vatqM+t6X7rta01qOzessL808ox"
        crossorigin="anonymous"></script>
    <script src="https://fb.me/react-dom-0.14.7.js"
        integrity="sha384-A1t0GCrR06cTHvMjaxeSE8XOiz6j7NvWdmxhN/9z748wEvJTVk13Rr8gMzTUnd8G"
        crossorigin="anonymous"></script>

<style>
.slide.plainjs pre code {
  font-size: 0.45em;
}
</style>

## ES5 + builder

* [with webpack](https://github.com/petehunt/ReactHack)
* [with gulp](https://github.com/artyomtrityak/react-hackathon)

## ES2015 + builder

* [Essential](https://github.com/pheuter/essential-react)
* [varya/react-stub](https://github.com/varya/react-stub)
  * ES2015, BEM, PostCSS, webpack

## React UI components

* [React ToolBox](http://react-toolbox.com/#/) -
  [react-stub@with-react-toolbox](https://github.com/varya/react-stub/tree/with-react-toolbox)
* [Material UI](http://www.material-ui.com/#/) -
  [react-stub@with-material-ui](https://github.com/varya/react-stub/tree/with-material-ui)
* [Belle](http://nikgraf.github.io/belle/#/?_k=xvldj2) -
  [react-stub@with-belle](https://github.com/varya/react-stub/tree/with-belle)

## Dummy JSONs

Dummy JSONs:

* [Twitter JSON response](https://gist.github.com/search?l=json&q=twitter+json&utf8=%E2%9C%93)
* [Instagram JSON response](https://gist.github.com/mgcm/4d4ddf687b1399b87de4)

## React Native
{: .shout }

## Relay and GraphQL
{: .shout }

## Coding time
{: .shout }

## THANK YOU!
{: .thanks }

###[varya.me/reactjs-hackathon](http://varya.me/reactjs-hackathon)

<style>
.thanks h3 {
  font-size: 2.15em;
}
</style>
