# parakuro
parakuro의 이름의 유래는 시계를 뜻하는 그리스어 παρακολουθώ(parakolouthó)에서 나온 단어이다.
parakuro는 원형 노트낙하형 리듬게임으로 게임패드를 사용하는 게임으로 시계를 이용하여 노트를 치는 컨셉이다.

# 플레이 방법

서클 노트

버튼을 이용하여 처리를 한다. 

슬라이드 노트

파란색 노트는 왼쪽 스틱, 빨간색 노트는 오른쪽 스틱을 이용하여 처리를 한다. 노트가 닿기전에 스틱을 노트에 향하여도 처리가 된다. 

# 판정
서클 노트 판정은 marv(±40ms), close(±75ms), far(±100ms), bad(±170), miss(miss)이다.
롱노트는 끝 지점-90ms부터 떼면 marv가 뜨고 그 전에 떼면 bad가 난다.

슬라이트 노트는 0~-80ms이다.
