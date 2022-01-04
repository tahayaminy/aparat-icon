# aparat Font Awesome

- use this in head tag for FontAwesome :

```
<link rel="stylesheet" href="https://parswebdesigners.github.io/icon/css/all.min.css"/>
```

- use this template for aparat icon:
```
<section class="aparat-container">
    <div class="fas fa-square corner"></div>
    <div class="fas fa-circle border"></div>
    <div class="fas fa-circle cont-circles">
    <i class="fas fa-circle center-circle"></i>
    <i class="fas fa-circle circles"></i>
    <i class="fas fa-circle circles"></i>
    <i class="fas fa-circle circles"></i>
    <i class="fas fa-circle circles"></i>
    </div>
</section>
aparat
```

- use this style for aparat icon:

```
.aparat-container {
    position: relative;
    transform: rotate(15deg);
    display: inline-block;
    padding: 1em;
    font-size: 1em;/*size in em*/
    color: black;/* color */
}         
.circles,.center-circle,.border {
    color:white;/* bgcolor */
}   
/* dont change */
.cont-circles {
    font-size: 1.6em;
    position: absolute;
}
.center-circle {
    position: absolute;
    font-size: 0.1em;  
}
.circles {
    position: absolute;
    font-size: 0.3em;
    transform: translate(-50%, -50%);
}
.center-circle,.cont-circles,.border,.corner{
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    position: absolute;
}
.corner,.border {
    font-size: 1.7em;
}
.circles:nth-child(2) {
    top: 30%;
    left: 30%;
}
.circles:nth-child(3) {
    top: 30%;
    left: 70%;
}
.circles:nth-child(4) {
    top: 70%;
    left: 70%;
}
.circles:nth-child(5) {
    top: 70%;
    left: 30%;
}
```
