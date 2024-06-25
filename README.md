제스쳐 공부를 위한 데모 프로젝트입니다.

1. 클릭 감지 - 간단히 모디파이어에 clickable로 구현
2. 클릭 감지 - pointerInput으로 눌렀을 때, 떼었을 때, 두번, 길게 등 감지를 구현
3. 드래그 감지 - draggable로 구현
4. 드래그 해서 위치 조정 - pointerInput에 detectDragGesture 메서드를 사용해 구현
5. 스크롤 감지 - 모디파이어에 scrollable 메서드를 사용해 구현. 수평,수직 둘 중 하나만 사용하고 상태 감지를 rememberScrollableState로 한다
6. 다중 스크롤 감지 - 모디파이어에 verticalScroll과 horizontalScroll 둘 다에 rememberScrollState로 객체를 전달해 구현한다.
7. 다중 터치 감지 - 확대/축소, 회전, 변환(위치 조정) 제스처를 모디파이어 중
  transformable 메서드에 rememberTransformableState 객체를 전달 해 동작을 감지, graphicsLayer를 통해 해당 컴포저블의 크기, 회전, 변환을 구현한다.
