# Projetojogo...

https://editor.p5js.org/rywiriol33/full/3r-05M85e

function setup() { 
    createCanvas (600, 600);
    background("black");
   }
   
   function draw() {
    stroke ("gold")
    fill ("red")
   
    if(mouseIsPressed) {
     rect (mouseX, mouseY, 20, 35);
    }
   
   }
