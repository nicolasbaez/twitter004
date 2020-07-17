## twitter004 | #つぶやきProcessing 
![twitter](https://github.com/nicolasbaez/twitter004/blob/master/twitter004.gif)
```processing
float m=999;float x=-m;int w=255;void setup(){size(512,256,P3D);}void draw(){background(random(w),0,random(w));translate(w,128,x);rotateX(radians(x));rotateY(radians(x/2));stroke(w);strokeWeight(random(map(x,-m,0,1,64)));fill(0);box(128);x+=map(x,-m,0,2,8);}
```
