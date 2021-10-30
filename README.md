# Animations4LayersImg

Playing with a design I made for the movie witness for the prosecution 1957

![image](https://user-images.githubusercontent.com/22336407/139516908-882165c7-527e-454f-8837-f07baf6aefb0.png)

I divided the image in 4 layers, overlaped them
and I bringing in one layer at the time using CSS animations.

![image](https://user-images.githubusercontent.com/22336407/139517136-2a349ca2-2a0c-464a-a2de-94a33e048d84.png)

The layers are overlaped with the container position relative and the 4 layers position absolute:

```rd
  .animation-container{
    position: relative;
    max-width: 900px;
    width: 100%;
    height: auto;
    margin:auto;
  }
  .animation-container > div{
    position: absolute;
    top:0;
    left:0;
  }
````

first animation is just opacity: Animation 1
https://codepen.io/marchesinlorena/pen/OJjjBjv

second animation has movement and opacity: Animation 2
https://codepen.io/marchesinlorena/pen/wvqqYqX
