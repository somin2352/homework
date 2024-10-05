- 각각의 이미지를 64px x 64px 크기로 지정하고 테두리를 둥글게 지정, padding을 10px로 주어서 이미지 사이의 간격이 20px이 되도록 함.

- 전체 margin과 padding을 0으로 지정하고 기본적으로 들어가 있는 margin과 padding을 없애줌.

- float을 이용하여 왼쪽에서부터 정렬되도록 배치하였고, 이미지 요소들 전체를 감싼 faces class에서 너비를 350px로 설정하여 너비가 350px이 넘어가면 2행으로 정렬되로록 함.

- margin: auto 0;을 주어 좌우로 중앙 정렬되도록 하고 중앙 정렬을 위해 margin-top을 350px로 줌.

- activate class로 활동중 표시 도형을 생성하여 색상과 모양을 지정하고 이미지마다 오른쪽 하단에 위치하도록 position값을 사용함.

- row라는 클래스의 div 태그를 이용하여 행마다 묶어주어 column-reverse 방향으로 flex 속성을 사용하여 1행과 2행의 이미지 묶음이 반전되도록 배치함.
