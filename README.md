Chuchina-Moving
===============
int x; 
int y;

void setup() {      
  size ( 500, 500);     
  size ( 500, 500);
  x=150;
  y=160;  
} 


void draw() {  
  background ( #66CDAA  );  
  noStroke ();
  fill(#FFE47B);
  //ellipse ( x, y, Width, Height)//
  ellipse( x, y, 110, 95 ); 
  //sombrero//

  noStroke ();
  fill(#000000);
  ellipse( x, 170, 70, 60 ); 
  //pelo cabeza//

  noStroke ();
  fill(#E8AF82);
  ellipse( x+25, 350, 20, 25 ); 
  //pie derecho//

  noStroke ();
  fill(#E8AF82);
  ellipse( x-20, 350, 20, 25 ); 
  //pie derecho//


  noStroke ();
  fill(#FF434B);
  arc(x, 200, 300, 300, radians(35), radians(145)); 
  //arc(x,y, witdth, height, start, stop)//
  // start  = 3 o'cloock =0 )//
  //stop 0 PI.0.5= un quarto  pero PI= semicirculo) //
  // Falda Roja//

  noStroke ();
  fill(#627DFF);
  arc(x, 200, 260, 260, radians(35), radians(145)); 
  //arc(x,y, witdth, height, start, stop)//
  // Falda azul//

  noStroke ();
  fill(#FFE47B);
  arc(x, 200, 210, 210, radians(35), radians(145)); 
  //arc(x,y, witdth, height, start, stop)//
  // Falda amarilla//

  noStroke ();
  fill(#E8AF82);
  ellipse( x+97, 206, 20, 15 ); 
  //manita derecha//

  noStroke ();
  fill(#E8AF82);
  ellipse( x-96, 206, 20, 15 ); 
  //manita izquierda//

  noStroke ();
  fill(#FFE47B);
  rect(x-93, 198, 185, 16); 
  //brazos//

  noStroke ();
  fill(#ffffff);
  arc(x, 190, 150, 140, 0, PI); 
  //arc(x,y, witdth, height, start, stop)//
  // start  = 3 o'cloock =0 )//
  //stop 0 PI.0.5= un quarto  pero PI= semicirculo) 
  //camisa//

  //-------------trenza-----------------//
  noStroke ();
  fill(#000000);
  ellipse( x+27, 189, 12, 12 ); 
  //trenza1//
  noStroke ();
  fill(#000000);
  ellipse( x+29, 197, 10, 8 ); 
  //trenza2//
  noStroke ();
  fill(#000000);
  ellipse( x+28, 204, 10, 8 ); 
  //trenza3//
  noStroke ();
  fill(#000000);
  ellipse( x+27, 210, 10, 8 ); 
  //trenza4//
  noStroke ();
  fill(#000000);
  ellipse( x+26, 217, 10, 8 ); 
  //trenza5//
  noStroke ();
  fill(#000000);
  ellipse( x+27, 224, 10, 8 ); 
  //trenza 6//
  noStroke ();
  fill(#000000);
  ellipse( x+28, 230, 10, 8 ); 
  //trenza7//
  noStroke ();
  fill(#000000);
  ellipse( x+29, 237, 10, 8 ); 
  //trenza8//
  //-----------------------Trenza----------------------//

  //noStroke ();
  fill(#E8AF82);
  ellipse( x, 200, 16, 10 ); 
  //cuellito//

  noStroke ();
  fill(#E8AF82);
  ellipse( x, 176, 60, 50 ); 
  //cabeza//

  noStroke (); 
  fill(#FF434B);
  arc(x, 190, 12, 9, 0, PI); 
  //arc(x,y, witdth, height, start, stop)//
  // start  = 3 o'cloock =0 )//
  //stop 0 PI.0.5= un quarto  pero PI= semicirculo) 
  //boquita//

  noStroke ();
  fill(#000000);
  ellipse( x-12, 172, 7, 6 ); 
  //ojo izquierdo////

  noStroke ();
  fill(#000000);
  ellipse( x+16, 172, 7, 6 ); 
  //ojo derecho////

x= x+1;  
 }
