# Glassmorphism - Game Profile Page 
Using CSS to create a glassmorphism card-like profile page for a gamer.  
**2021 UI Design Trend.**  
A learning project from Dev Ed. 

### CSS code for creating glassmorphism background:

#### Linear gradient
```
background: linear-gradient(
        to right bottom, 
        rgba(255, 255, 255, 0.6), 
        rgba(255, 255, 255, 0.25)
    );
```
Note: we are using the background shorthand property.To be more specific, we can replace ```background``` with ```background-image``` to create the effect of gradient-colored background.

#### RGBA 
To create a glassy effect on a glass card or background, we shall use the rgba porperty in CSS. 

```
rgba(255, 255, 255, x)
```
- rgb(255, 255, 255) = white  
- the ```a``` in ```rgba``` stands for alpha which is layman term: opacity. You can set the alpha from 0.0 (lowest opacity) to 1.0 (highest opacity). 

<br>

## Project Preview

![project_preview](https://github.com/lihuicham/game-profile-glassmorphism/blob/main/assets/images/project_preview.PNG)

**Click here to view the Glassmorphism Game Profile Page: 
[Project Demo](https://lihuicham.github.io/game-profile-glassmorphism/)**

Note:  
This project focuses on using CSS to create a glassy background effect on a card design. Hence, responsive feature and media queries is ommited from the development phase.   
The project is best viewed in 50% of browser (e.g. Google Chrome, Microsoft Edge) screen size. 



