# Ekaterina Mashinskaia 
![Ekaterina Mashinskaia](https://avatars.githubusercontent.com/u/111440157?s=400&u=fc4bd5e5728108295f3f0766534359103c1df354&v=4) \
**Frontend student** 
## Contacts 
City: Vilnius, Lithuania \
Email: ekaterina.mashinskayaa@gmail.com \
GitHub: EkaterinaMash \
Discord: EkaterinaMash#8912 \
Phone: +37066596599
 
## About myself
My name is Ekaterina, I'm 28 years old. I want to become a frontend developer, because I would like to create usable and friendly services. Frontend opens a lot of perspectives for development of skills and knowledge. It seems interesting for me to create something new or solve problems, finding different and the most optimal ways of solving tasks. Frontend is a new sphere for me and I'm excited to get new knowledge and apply them. 
   
## Knowledge and skills
* HTML basics - tags, headers, paragraphs, lists, links, images
* CSS basics - selectors, properties, fonts, colors, images
* JavaScript basics - classes, attributes, functions, loops
* Git basics 

## Example of code

HTML part:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>PetStory</title>
    <meta charset="utf-8">
    <link rel="stylesheet" href="style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1">
</head>

<body>
<header>
    <div class="logo">
        <a href="" class="disabled">
            <h1>PetStory online</h1>
            <img src="../../assets/icons/bamboo.png">
        </a>
    </div>
    <div class="hamb">
        <span></span><span></span><span></span>
    </div>
    <nav>
        <ul class="navigation">
            <li><a href="" class="disabled active">About</a></li>
            <li><a href="">Map</a></li>
            <li><a href="">Zoos</a></li>
            <li><a href="../donate/index.html">Donate</a></li>
            <li><a href="">Contact us</a></li>
        </ul>
    </nav>
    <div class="popup">
        <div class="close-btn">
            <span class="sp1"></span><span class="sp2"></span>
        </div>
    </div>
    <a href="https://www.figma.com/file/jfEFwkXVj1WRq7sUHDr8os/PetStory-online" class="designed">Designed by ©</a>
</header>

```

JS part:

```
const hamb = document.querySelector(".hamb");
const popup = document.querySelector(".popup");
const menu = document.querySelector(".navigation").cloneNode(1);
const logo = document.querySelector(".logo").cloneNode(1);
const design = document.querySelector(".designed");
const closeBtn = document.querySelector(".close-btn");

hamb.addEventListener("click", openMenu);

function toggleMenuClasses() {
    popup.classList.toggle("open");
    menu.classList.toggle("active");
    design.classList.toggle("active");
    logo.classList.toggle("active");
}

function openMenu(e) {
    
    e.preventDefault();
    toggleMenuClasses();
    addMenuElements()
}

function addMenuElements() {
    popup.appendChild(logo);
    popup.appendChild(menu);
    popup.appendChild(design);
}

closeBtn.addEventListener("click", closeMenu);

function closeMenu(e) {
    e.preventDefault();
    toggleMenuClasses();
}

```
## Experience
* Coding exercises at HTML Academy 
* Codewars tasks(arrays, objects, functions)

## Education 
* Ryazan State Radio Engineering University - bachelor of automation and control of production
* Self study of HTML, CSS, JavaScript

## English level
B1 