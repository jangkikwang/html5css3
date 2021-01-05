# html5css3
웹표준학습
<!doctype html>
<html lang="ko">
	<head>
		<title>문서의 제목</title>
		<meta charset="utf-8">
		<style>
		/*내부 스타일 : 현재 문서에만 적용되는 서식*/
		</style>
		<!--
		외부 스타일 : 여러 문서에 스타일을 적용할 때
		-->	
		<link rel="stylesheet" href="파일명">
		<script>
		/* 여기는 내부 스크립트 */
		</script>
	</head>
	<body>
		<h1>대제목1 입니다.</h1>
		<h2>대제목2 입니다.</h2>
		<h3>중제목1 입니다.</h3>
		<h4>중제목2 입니다.</h4>
		<h5>소제목1 입니다.</h5>
		<h6>소제목2 입니다.</h6>
		<p>여기는 문단입니다. 동해물과 백두산이 마르고 닳도록 하느님이

	</body>	
</html>
<!doctype html>
<html>
	<head>
	<tiltle>하이퍼링크 요소 연습</title>
	<meta charset="utf-8">
	<style>
	</style>
	<link href="" rel="stylesheet">
	</head> 
	<body>
		<h2>하이퍼링크 요소 연습</h2>
		<div id="header">
			<a href="ex1.html">연습1</a>
			<a href="ex2.html">연습2</a>
			<a href="http://www.naver.com"target="blank">네이버</a>
			<a href="#footer">네임앵커-푸터로이동</a>
			<a href="mailto:rlrhkd21@naver.com>이메일 확인</a>
			<a href="tel:010-2593-8934">전화걸기</a>
			<a href="sms:010-259-8934">문자보내기</a>
		</div>
		<div id="content">
			<h2>여기는 컨텐츠</h2>
			<img src="http://placehold.it/960x2000/333"/>
		</div>
		<div id="footer">
			<h2>여기는 푸터</h2>
			<a href="#">임시링크-맨 위로</a>
		</div>
	
	</body>
</html>

<!doctype html>		                        	            	       &nbsp =한글자 띄어쓰기
<html lang="ko">							      <br> 태그는 </br> 로 끝나지않는다				      
	<head>							      inline요소는 크기 조정이 가능하지않는다	
	<title>index</title>					      block요소는 크기 조정이 가능하며 밑에 내용이 공백이생긴다
	<meta charset="utf-8">						
	<style>
	.rtxt {color:deeppink;}
	</style>
	<link href="" rel="stylesheet">
	</head>
	<body>
                  <h2>문서 <span class="rtxt">연습</span>하기</h2>
                  <p>
		여기는 첫 번째 문단입니다. 그리고		
		<strong>굵게</strong>나옵니다.
		<em>기울임꼴</em>입니다.
		<ins>밑줄</ins>입니다.
		<del>취소선</del>입니다.
		<span class="rtxt">일반단어</span>입니다.
	      </p><br>
                  <p>
		여기는 두 번쨰 문단입니다. 그리고
		<b>굵게</b>나옵니다.
		<i>기울임꼴</i>입니다.
		<u>밑줄</u>입니다.
	       </p><br>
	
	</body>
</html>
