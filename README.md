## 이스트소프트 부트캠프 프론트엔드 첫번째 개인 프로젝트 - 사이트 구현

### 문제 해결
-----
* 처음으로 혼자 html 틀을 짜려고 하니 어려웠는데 구현 할 사이트를 큰 틀의 구간별로 나누고 다시 세부적으로 div 클래스를 지정해주었습니다.
* css를 할 때 이미지의 위치 이동이 되지 않았지만, 검색 후 position: relative 를 통해 해결했습니다.
* lorem 문단을 작성할 때 줄 바꿈이 마음대로 되지 않았지만, css에 white-space: nowrap 스타일을 주고 줄바꿈 하고 싶은 부분에 <br> 을 사용하여 해결하였습니다.
* 사이트의 최상단으로 이동하는 버튼은 검색을 통해 window.scrollTo 를 사용하여 x,y 좌표를 0으로 설정 해 주었고 behavior: 'smooth' 를 사용하여 효과를 부드럽게 해주었습니다.
* button 태그를 지정하니 버튼 이미지에 틀이 생기는 걸 발견해서 검색 후 틀을 지우는 border:none 을 적용 해봤지만 적용되지 않아 버튼 이미지의 background-color를 배경의 background-color와 동일한 색상으로 지정해주므로써 틀의 이질감을 조금이라도 없애기 위해 시도해봤습니다.
* modal 창은 검색을 통해 document.querySelector 를 사용하여 요소를 반환 해주고 addEventListener 를 사용하여 click 이벤트를 생성해 버튼을 클릭하면 display = "flex"를, 
  닫기 버튼을 클릭하면 display = "none"을 주어서 해결하였습니다.(modal)
### 프로젝트 회고
-----
* 다음 프로젝트엔 클래스 명을 겹치지 않고 알아보기 쉽게 지정해주기 위해 생각해봐야 할 것 같습니다.
* 처음 프로젝트의 전체적인 html 틀을 짜는 과정이 어려워서 대부분 div 태그로 지정을 해주었는데, 공부를 통해 상황에 맞는 태그를 쓰도록 노력해야겠습니다.
* 레이아웃 사이즈를 하나하나 지정하고 flex를 잘 사용하였으면 이미지들의 위치를 맞춰가기가 편했을텐데 justify-content, align-items 기능들을 잘 사용하지 못하고 어떻게든 완성은 시키자는 마음에 top, left를 이용하여 조금씩 위치를 맞추다 보니 효율적이지 않았던 것 같습니다.
* 위 회고의 연장선인 것 같은데 footer, modal 이미지들이 다른 부분에 어떠한 속성을 추가하면 맞춰 놓은 이미지들이 흐트러지는 현상이 있었습니다. 이것도 하나의 큰 틀을 잡고 가지 못해서 인 것 같습니다.
* 처음으로 해 본 프로젝트여서 많이 부족하다고 느꼈고, 많은 경험을 쌓아야겠다고 생각했습니다. 
### 결과물
------
#### pc
![pc](https://github.com/hyunjinSD/EST_soft_frontend_project/blob/main/pc.png)
#### mobile
![mobile](https://github.com/hyunjinSD/EST_soft_frontend_project/blob/main/mobile.png)
