# Animations4LayersImg

Playing with a design I made for the movie witness for the prosecution 1957

I divided the image in 4 layers
and I bringing out one layer at the type.

The layers are overlaped with the container position relative and the 4 layers position absolute:

'''rd
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
'''

first animation is just opacity



second animation has movement and opacity
