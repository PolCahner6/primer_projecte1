# primer_projecte1
void setup() {
  
size(500,500);
background(250);

fill(255,255,255);
ellipse(250,350,150,150);

}

void draw() {
  
fill(150,50,0);
rect(90,70,50,50);

fill(0,150,0);
rect(200,70,50,50);

fill(0,0,255);
rect(300,70,50,50);
  
}  
  
void mousePressed() {
if(mouseX<140 && mouseX>90 && mouseY<120 && mouseY>70){
fill(255,0,0);
ellipse(250,350,150,150);
}
if(mouseX<250 && mouseX>200 && mouseY<120 && mouseY>70){
fill(0,150,0);
ellipse(250,350,150,150);
}
if(mouseX<350 && mouseX>300 && mouseY<120 && mouseY>70){
fill(0,0,255);
ellipse(250,350,150,150);
}

}
