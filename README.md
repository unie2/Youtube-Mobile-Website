# Youtube-Mobile-Website
> Clone Coding
---------------------------

### 기본
- link 태그를 통해 https://fonts.googleapis.com/ 에서 Roboto 폰트를 사용할 수 있도록 하였다.
![image](https://user-images.githubusercontent.com/54324782/149303656-d6a88821-1f7c-4702-8a88-a81c9331f324.png) 
- 위 코드를 추가해줌으로써 영상 제목 텍스트가 2줄로 제한된다.

### 모바일 화면
![모바일](https://user-images.githubusercontent.com/54324782/149303941-751eabed-83db-4025-bb20-081e6169419f.png)
- 화면 너비가 768px 미만일 경우 flect-direction이 column으로 잡히도록 하여 'Up Next' 항목이 Channel Description 아래에 배치된다.

### 패드 혹은 데스크탑 화면
![데스크탑](https://user-images.githubusercontent.com/54324782/149304778-e1f7af10-5f84-4275-a6ef-d5ac2acc0abc.png)
- 화면 너비가 768px 이상일 경우 flex-direction이 row로 잡히도록 하여 'Up Next' 항목이 Channel Description 우측에 배치된다.

### 추가 (JavaScript)
![main.js](https://user-images.githubusercontent.com/54324782/149304936-e6d98cae-2a81-4885-9815-e09f16cfaf6a.png)
- 영상 타이틀이 2줄로 제한되어 있어 모두 보이지 않을 경우, 우측에 배치된 버튼 클릭 시 모두 보여진다.
