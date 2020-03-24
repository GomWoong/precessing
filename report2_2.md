# Report 2-2
## 안동대학교 김대현

```

PFont f;
void setup(){
  size(470, 380);
  f = createFont("궁서", 40);
  textFont(f);
}

int i = 1, h=40, sp=1;
void draw(){
  fill(0);
  background(127, 127, 255);
  text("안동대 컴공 사랑합니다", 20, h = h + i * sp);
  if(h > 370) i--;
  if(h < 40) i++;
}

void keyPressed(){
  sp = key - '0';
}

```
### 소감
*한글 배너 제작
*그래픽스 너무 재밌습니다.
