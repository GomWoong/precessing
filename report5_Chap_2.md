# Report 5-2
## 안동대학교 김대현
```

// 2장. 배너 만들기
PFont f;

void setup(){
  size(600, 400);
  f = createFont("바탕", 40);
  textFont(f);
}
int bg = 255, h = 40, i = 1, sp = 3;
void draw(){
  background(bg-=2);
  if(bg==1) bg = 255;
  text("2장. 배너 만들기", 160, h = h + i * sp);
  if(h > 385) i--;
  if(h < 40) i++;
}

```
### 설명
* 한글 배너를 출력해주는 프로그램이다.
* 배너가 화면 상단에서 시작하여 하단으로의 움직임을 반복한다.
