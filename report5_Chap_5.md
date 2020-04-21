# Report 5-2 [돌아가기_버튼](https://github.com/GomWoong/processing/blob/master/README.md)
## 안동대학교 김대현
```

//5장. 원선도형
PShape circle;

void setup() {  
  size(640, 360, P2D);
  circle = createShape(ELLIPSE, 0, 0, 100, 50); // 원형 도형 생성
}

void draw() {
  background(51);
  circle.setStroke(color(255)); //색 설정
  circle.setStrokeWeight(4); //선 굵기
  circle.setFill(color(map(mouseX, 0, width, 0, 255))); //마우스 X값에 따라 색 적용
  translate(mouseX, mouseY); // 마우스 좌표값에 따라 도형 이동
  shape(circle); // 도형 생성
}

```
### 설명
* translate로 마우스의 좌표값에 따라 도형 이동
* 도형을 생성후 도형에 속성을 설정
* x 좌표의 값에 따라 도형의 색이 0~255값으로 설정
