---

layout: sc5

style: |

    #Cover .main-logo__wrapper {
        width: 100%;
        text-align: center;
    }
    #Cover object.main-logo {
        z-index: 5;
        position: static;
        width: 200px;
        margin: 35px 50px;
    }

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
    }
    .no-title h2 {
      display: none;
    }
---

# React Hackathon {#Cover}

<div class="main-logo__wrapper">
    <object class="main-logo" data="themes/sc5/images/logo.min.svg#white" type="image/svg+xml"></object>
</div>

*Brought to you by&nbsp;[Varya&nbsp;Stepanova](http://varya.me/) and generated with&nbsp;[Jekyller](https://github.com/shower/jekyller)*
{: .credits }

## Material

[varya.me/reactjs-hackathon](http://varya.me/reactjs-hackathon)

## Test
{: .shout }

## THANK YOU!
{: .thanks }

Varya Stepanova, SC5 Online<br/>
[@varya_en](https://twitter.com/varya_en){: .twitter }

###[github://sc5/sc5-styleguide-visualtest](https://github.com/SC5/sc5-styleguide-visualtest)

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
