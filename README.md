# hello-world
ideas and practice
I am a criminiology and criminal justice major and I hae 2 cats kirby and skitty
function setup() {
  createCanvas(800, 800);
}

function draw() {
if (mouseIsPressed){
  fill(0);
} else { 
fill(255);
}
  ellipse(mouseX, mouseY, 80, 80);
}
