#5번째 과제: Sprite 활용하기

1. HTML 마크업 
section 태그로 전체 영역을 나눈 뒤 추천 사이트라는 제목 부분과 리스트 부분으로 
나누어 마크업 했습니다. 

헤더의 더보기 버튼은 button 태그로, +기호는 span태그로 마크업 하였습니다.

순서가 필요 없기 때문에 ul과 li요소로 추천 사이트 목록을 마크업 했습니다.



2. CSS 스타일링

text-decoration:none으로 하이퍼링크 효과를 없애고
list-style:none을 통해 리스트 요소의 기본 마커를 없앴습니다. 

그리고 기본 마커 대신 가상선택자 ::before을 이용하여 사이트 리스트의 각 요소를
넘버링 했습니다. 이때 content 속성을 사용하였습니다. content속성 중 숫자를
자동으로 생성하는 content: counter를 사용했습니다. 


화살표 이미지를 삽입하기 위해 sprite 기법을 활용하였습니다.
