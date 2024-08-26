```css
.canvas {
    width: 500px;
    height: 600px;
    background-color: #4d0f00;
    overflow: hidden;
    filter: blur(2px);
}
  
.frame {
    border: 50px solid black;
    width: 500px;
    padding: 50px;
    margin: 20px auto;
}
  
.one {
    width: 425px;
    height: 150px;
    background-color: #efb762;
    margin: 20px auto;
    box-shadow: 0 0 3px 3px #efb762;
    border-radius: 9px;
    transform: rotate(-0.6deg);
}
  
.two {
    width: 475px;
    height: 200px;
    background-color: #8f0401;
    margin: 0 auto 20px;
    box-shadow: 0 0 3px 3px #8f0401;
    border-radius: 8px 10px;
    transform: rotate(0.4deg);
}
  
.one, .two {
    filter: blur(1px);
}
  
.three {
    width: 91%;
    height: 28%;
    background-color: #b20403;
    margin: auto;
    filter: blur(2px);
    box-shadow: 0 0 5px 5px #b20403;
    border-radius: 30px 25px 60px 12px;
  transform: rotate(-0.2deg);
}
```