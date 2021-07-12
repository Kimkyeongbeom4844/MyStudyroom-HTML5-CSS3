# 중간요약(5장 ~ 8장)
*  css연동법 -> 〈head〉부분에
    
    〈link rel="stylesheet" href="css/style.css"〉작성

    :hover -> 마우스를 올렸을때 이벤트 발생
 #
 * 1 . 웹 폰트사이트에서 @import부분을 〈style〉코드안에 작성 
 
    2 . 웹에서 폰트를 다운받아서 사용

     @font-face {


       font-family: "ABCD";
       src: url(ABCD.ttf) format(truetype);
   }

   이후 둘다 font-family:"ABCD"; 작성
 #
 * font-variant: small-caps -> 작은 대문자로 표시
 #
 *
    letter-spacing: 0em -> 글자 사이 간격조절(가능하면 em단위로)

    word-spacing: 0em -> 단어 사이 간격조절(거의 사용 안함)
 #
 * text-indent: 15px -> 15픽셀만큼 들여쓰기

    line-height -> 줄 사이 간격조절
 #
 * list-style-type: none; -> 목록의 불릿모양 설정

    list-style-image: url(""); -> 목록의 불릿을 이미지로 대체

 #
 * background-image: url(""); -> 배경화면 불러오기

    background-size: 100% 100% , cover , contain

    background-repeat: no-repeat;

    background-attachment: fixed -> 스크롤을 내려도 배경화면이 고정
 #
 * display: inline-block; -> 인라인이면서 블록속성을 가지는 것(너비나 높이 float등 적용가능)

    border: 1px solid #ccc;(width style color)

    border-radius: 5px -> border 꼭짓점 부분을 둥그랗게 만듬