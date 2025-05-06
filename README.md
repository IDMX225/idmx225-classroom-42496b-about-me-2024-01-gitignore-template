# README

**About me project** - Sahar Naz 

This project is an implementation of all the topics learned in web dev 1. Below are snapshots of code with descriptions. 

---
---
**Code Snapshots:**
Here are all the snipits of the project I enjoyed doing, this includes both html and css code.

Below is the code for navbar; also attached new logo 
```ruby 
            <div class="navbar">
                <div class="navbar-links">
                    <div class="logo">
                    <img src="Favicon/sn-rhodium.svg" alt="my initals logo"/>
                    </div>
                    <ul>
                        <li><a href="#bio" class="nav-links">Bio</a></li>
                        <li><a href="#gallery" class="nav-links">Gallery</a></li>
                        <li><a href="#lit" class="nav-links">Blog</a></li>
                        <li><a href="#contact" class="nav-links">Contact Me</a></li>
                    </ul>
                </div>
            </div>
```
---

Below is the code for the hamburger menu, this was taken from codepen.
``` ruby 
<div class="navbar2">
              <div class="container nav-container">
                  <input class="checkbox" type="checkbox" name="" id="" />
                  <div class="hamburger-lines">
                    <span class="line line1"></span>
                    <span class="line line2"></span>
                    <span class="line line3"></span>
                  </div>  
        
                <div class="menu-items">
                  <li><a href="#bio">Bio</a></li>
                  <li><a href="#gallery">Gallery</a></li>
                  <li><a href="#lit">Blog</a></li>
                  <li><a href="#contact">contact</a></li>
                </div>
              </div>
            </div>
```
---

Media queries were a concept unknown to me, learning about them changed my perspective on web dev. We really dont realize how a few lines of code can change the oveall structure of a site and can make it more pleasing for the user. Media queries nake a website more responsive according to the device used. Below are some of the media queries used in my project: 

```ruby
@media screen and (min-width: 60em){
    figure{
        display: grid;
        grid-template-columns: 2fr 1fr;
    }

    figcaption {
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: 2rem;
        margin-left: 1rem;
    }

    figure img {
        width: 100%;
    }

    #content div {
        max-width:100%;
        columns: 40rem;
    }

    #myVideo {
        width: 80%;
        height: auto;
    }

}

/* Large screen size */
@media screen and (min-width: 100em){
    #gallery {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
    }

    hr {
        display: none;
    }

    #gallery h2 {
        grid-column: 1 / -1;
    }

    figure {
        display: block;
    }

    #myVideo {
        width: 50%;
        height: auto;
    }
}


```

---
**Color Theme:**
![imagealt](https://github.com/IDMX225/about-me-shrnzz/blob/6bf22cbe3121263b9fccb807114b171a7d8b4ed7/color-theme.png)


HexCode for colors used:

-E3C8BD

-E4746E

-E0E000

-41A4E1

-B9E6E4


---
**Article:**

The topic I picked for my article was css animations.


---
**Citations:**
harmuger menu : https://codepen.io/sanketbodke/pen/qBXBOgb

Article sources: 

1. https://www.w3schools.com/css/css3_animations.asp

2. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animations/Using_CSS_animations

3. 