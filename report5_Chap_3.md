# Report 5-2
## 안동대학교 김대현
```

//3장.Mouse 1D

void setup() {
  size(640, 360);
  noStroke(); // 선 없음
  colorMode(RGB, height, height, height);
  rectMode(CENTER);
}

void draw() {
  background(0.0);

  float r1 = map(mouseX, 0, width, 0, height);
  float r2 = height-r1;
  
  fill(r1);
  rect(width/2 + r1/2, height/2, r1, r1);
  
  fill(r2);
  rect(width/2 - r2/2, height/2, r2, r2);
}

```
### 설명
* 2개의 사각형이 프로그램 background 중심을 기준으로 x의 값에 따라서
  좌로 이동시 좌측 사각형이, 우로 이동시 우측 사각형이 커진다.
