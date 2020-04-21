# Report 5-2 [이전으로](https://github.com/GomWoong/processing/edit/master/report5_Chap_1.md)
## 안동대학교 김대현
```

// 1장, 펜 만들기

void setup(){
  size(600, 400);
  stroke(255, 0, 0);
  strokeWeight(15);
}

void draw(){
  if(mousePressed)
    line(pmouseX, pmouseY, mouseX, mouseY);
}

```
### 설명
* 마우스 클릭시에 x, y에 값에 따라 점을 찍어주는 프로그램
