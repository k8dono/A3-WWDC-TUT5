int age = 34;
PImage img;

void setup (){
  img = loadImage("a3photos.jpg");
  img.resize(750,1000);
  size(750,1000);
}

void draw (){
 background(255); 
 
 fill(0);
 noStroke();
 
 float tiles = mouseX/10;
 float tileSize = width/tiles;
 
 translate(tileSize/2, tileSize/2);
 
 for (int x = 0; x < tiles; x++) {
   for (int y = 0; y < tiles; y++) {
     
     color c = img.get(int(x*tileSize),int(y*tileSize));
     float size = map(brightness(c),0,255,15,0);
    
     
     ellipse(x*tileSize, y*tileSize, size, size);
   }
 }
}
