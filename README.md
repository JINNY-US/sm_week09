# sm_week09
스마트모바일프로그램설계 9주차

8주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week08

### 팀 구성   
스마트정보통신공학과 201621216 이준석   
스마트정보통신공학과 201921036 김경진   
스마트정보통신공학과 201921054 박유리   
스마트정보통신공학과 201921083 이혜정   
스마트정보통신공학과 201921104 홍수빈    
스마트정보통신공학과 201990009 미르자크메더브 사르더르    

   ***   
### 모든 항목은 변경되거나 삭제될 여지가 있습니다   
   ***   
      
### 가게주 가게 관리 페이지 UI 디자인 & 게시판 기능 (김경진, 홍수빈)   
>>1. 새로운 ui를 추가하였습니다.
>> - 각 사업주의 가게를 이름, 위치, 영업시간 정보등을 보여줄 페이지
>> - 이전에 등록한 가게의 정보를 수정할 수 있는 페이지
>> - 가게에서 판매하는 상품, 음식, 이용권 등의 정보를 추가하는 페이지(프레그먼트 사용)
>> - 이전에 등록된 상품들의 정보를 보여줄 페이지(프레그먼트 사용)
>> 

### 사용자 구분, 정보수정 (박유리, 이혜정)   
>진행과정   
> 이번주에는 저번주를 이어서 진행하였습니다. 
>
>> 1. 사용자 구분 (일반 사용자, 가게주)
>>
>> 사용자가 누구냐에 따라 필요한 기능이 다르기 떄문에 일반 사용자와 가게주가 보는 레이아웃과 엑티비티를 다르게 하기로 하였습니다.   
>> 회원가입 할 때 일반 회원인지 가게주인지 radioBox로 구분하여 가입할 수 있게 하였습니다.    
>> 이때 일반 회원으로 가입할 시 true가 가게주로 가입할 시 false가 DB에 저장됩니다.   
>> 로그인할때는 이 boolean값을 if조건문에 넣어 로그인한 사용자가 가게주인지 일반회원인지 구분하며 그에 맞는 레이아웃과 엑티비티를 출력합니다.   
>> 다은은 그 실행영상입니다.   

>>[사용자 구분](https://user-images.githubusercontent.com/79883808/116874926-0f127e80-ac55-11eb-8488-e38aaa38f396.mp4)   

>> 2. 정보 수정   

***   

### (이준석, 미르자크메더브 사르더르)   
>1. 튕김 오류   
>
>![KakaoTalk_20210501_205543346](https://user-images.githubusercontent.com/57963888/116868615-08cad500-ac4a-11eb-9758-05895716a0fe.jpg)
>![KakaoTalk_20210501_205638038](https://user-images.githubusercontent.com/57963888/116868617-09fc0200-ac4a-11eb-9982-85ffcf0bf483.jpg)   
>
>저번 주차에 구글 지도를 띄우는 것까지 성공했고,   
>장소를 검색하는 것에서 앱 튕김 현상이 발생하여 이를 고치는 작업을 했습니다.   
>특정한 장소를 검색하면 지도에 마커를 띄워 보여주는 것에 성공을 했습니다.   
>하지만 다른 장소를 검색하였을 때에 이전에 검색했던 기록이 지워지지 않아   
>여러 개의 마커가 지도상에 띄워지는 현상이 있어, 이를 수정 중에 있습니다.   
>


   
   
