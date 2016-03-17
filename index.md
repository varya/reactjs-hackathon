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

###[varya.me/reactjs-hackathon](http://varya.me/reactjs-hackathon)

## Agenda

1. About the event
1. Choosing the projects
1. Introduction to React
1. Stub projects
1. Linking UI libraries
1. Coding

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

## Starter projects

Search: [andrewhfarmer.com/starter-project](http://andrewhfarmer.com/starter-project/)

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

## ES6 + builder

## React UI components

* [Bootstrap](https://react-bootstrap.github.io/)
* [Elemental](http://elemental-ui.com/)
* [Material UI](http://www.material-ui.com/#/)
* [TopCoat](https://github.com/kjda/react-topui)
* [React ToolBox](http://react-toolbox.com/#/)
* [Grommet](http://www.grommet.io/docs/)

## Coding time
{: .shout }

## THANK YOU!
{: .thanks }

###[varya.me/reactjs-hackathon](http://varya.me/reactjs-hackathon)

<style>
.thanks h3 {
  font-size: 50px;
}
.thanks .twitter
{
  text-decoration: none;
  color: currentColor;
  background: none;
}
.thanks .twitter::before
{
  content: "";
  display: inline-block;
  width: 1.5em;
  height: 1.5em;
  background-image:url('pictures/twitter-logo.png');
  background-size: cover;
  margin-right: 0.5em;
  margin-bottom: -0.5em;
}
</style>
