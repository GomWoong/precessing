# Report 2-1
## 안동대학교 김대현
```

void setup(){
  size(800, 300);
  textSize(80);
}

int i, dir=1, sp=1, bg=255;
void draw(){
  fill(255,0,0);
  background(bg=bg-2);
  if(bg<1) bg=255;
  
  text("I love Graphics", i=i+dir*sp, 180);
  if (i>width-570) dir=-1;
  if (i<0) dir =1;
}

void keyPressed(){
  sp = key - '0';
}

```
### 소감
*그래픽스는 공부할수록 행복합니다.

*끝까지 열심히 하겠습니다.
