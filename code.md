size(1280,720);

// head and body
fill(#0D0901); // shirt color
rect(400,500,480,300); // shirt
fill(#EDC87F); // skin color
rect(603,400,75,100); // neck
ellipse(640,250,370,420);// face
arc(640,500,100,100,0,PI); // neck line on the shirt

//glasses
line(610,240,670,240); // creates the bridge
strokeWeight(3); // makes it so that the lines creating the glasses frames are thicker and more visible
stroke(#FFD900); // my glasses have a gold trim
rect(500,200,110,85);
rect(670,200,110,85);
fill(0,0,0);
stroke(0,0,0);
rect(500,200,110,10);
rect(670,200,110,10);

//hat
strokeWeight(1);
arc(640,150,320,320,PI,2*PI); // the first arc creates the hat itself
noStroke();
fill(255,255,255);
triangle(620,75,595,60,620,90); // i made the nike logo by combining 2 triangles
triangle(620,75,690,40,620,90);
fill(#212120);
arc(640,150,320,140,PI,2*PI);

//chain
stroke(#FFD900);
noFill();
beginShape();
vertex(540,500);
vertex(640,670);
vertex(740,500);
endShape();
fill(#FFD900);
ellipse(640,680,20,20);
