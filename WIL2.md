# 2주차

1. analysis_options.yaml 파일 가서 Lint를 꺼줌(뭔지는 잘 모르겠음)
2. stless 단축키?로 긴 함수?를 빠르게 불러옴
3. 화면에 여러 가지 위젯을 띄움
  - return MaterialApp 함수 안에서 home: Text, Image.asset('경로'), Icon 등을 넣을 수 있음
  - 이미지는 asset에도 넣고 경로도 표시해줬는데 무슨 이유에서인지 나오지 않음
      -> 다시 시도해보니 pubspec.yaml 파일에서 이미지 이름까지 넣어줬어야 했는데 그걸 안해 나오지 않았던 것!
      ![예시](./<img width="501" alt="flutter study w2" src="https://user-images.githubusercontent.com/63771218/230058423-3c0af3de-b2ed-4722-b066-469e9a67aa9d.png">)
  - Image -> Container 로 바꿔서 넣어보는데 실행되고 있던 구글 크롬 페이지가 실시간으로 바뀌는 게 신기했음, xcode에서 ios 시뮬레이터를 돌릴 때는 그때마다 다시 실행해줘야 하기 때문
  - child 문법(?)을 이용해서 Container를 Center 안에 넣어줌




## 질문
1. 단순히 이미지나 아이콘, 박스를 띄우는 것보다 더 복잡한 화면을 구성하려면 어떻게 해야 할까?
2. 화면 구성뿐만 아니라 버튼 등 동적인 기능들을 추가하려면 어떻게 해야 할까?
3. 색깔을 RGB 형식으로 표현할 방법은 없을까?
