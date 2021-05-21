# happy
<!doctype html>
<html lang="ko">
<head>
	<title>온라인 프로필</title>
	<meta charset="utf-8">
  <link rel="stylesheet" href="css/style.css">
  <style>
    table {
      width:70%;  /* 표의 너비 */
      border:1px solid #222; /* 1픽셀짜리 표 테두리 */
      border-collapse: collapse; /* 중복되는 표와 셀의 테두리를 한 줄로 표시 */
    }
    thead {
      background:#eee;  /* 제목 행의 배경 색 */
    }
    th, td {
      border:1px solid #ccc; /* 1픽셀짜리 셀 테두리 */
      padding:5px;  /* 셀 테두리와 셀 내용 사이의 여백(패딩) */
      font-size:0.8em;  /* 셀의 글자 크기 */
    }
  </style>
</head>

<body>
    <div id="container">
        <!-- 사이드바 -->
        <aside>
            <div id="namecard">
                <img src="images/pf.jpg" alt="">
                <h1>Minju Kim</h1>    
                <p>오늘은 남은 인생이 시작되는 첫째날</p>
            </div>
            <div id="detail">
                <p>youngkwang, Korea</p>
                <p>aaa01085069857@gmail.com</p>                                 
            </div>
            <div id="sns">
                <h2>SNS</h2>
                <ul>                    
					<li>
						<a href="https://www.facebook.com/funnycom">github</a>
					</li>
					<li>
						<a href="https://www.google.com/search?q">google</a>
					</li>
				</ul>  
            </div>           
        </aside>
        <div id="main">
            <!-- 자기 소개 -->
            <section>
                <h2 class="subtitle">Who am I?</h2>
                <p><mark>나는 음악 듣는 것</mark>에 관심이 많습니다. <br>현재 영광의 한 시골 마을에서 코딩 중입니다.</p>
            </section>

            <!-- 경력 -->
            <section>
                <h2 class="subtitle">Experience</h2>
                <ul>
                    <li>요리하기
                        <ul>
                            <li>김치볶음밥 </li>
                            <li>콩나물 불고기</li>
                            <li>딸기 스무디</li> 
                        </ul>
                    </li>
                    <li>음악듣기
                        <ul>
                            <li>발라드 </li>
                            <li>팝송</li>
                        </ul>                        
                    </li>
                </ul>             
            </section>

            <!-- 숙련도 -->
            <section>
                <h2 class="subtitle">Skills</h2>

            </section>

            <!-- 학력 -->
            <section>
                <h2 class="subtitle">Education</h2>
                <table>
                  <caption>좋아하는 과일</caption>
                  <thead>
                      <tr>
                          <th>복숭아</th>
                          <th>딸기</th>
                          <th>멜론</th>
                          <th>자두</th>
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                          <td>6월</td>
                          <td>1월</td>
                          <td>7월</td>
                          <td>7월</td>
                      </tr>
                      <tr>
                          <td>연핑크</td>
                          <td>빨강</td>
                          <td>연두색</td>
                          <td>빨강</td>
                      </tr>
                  </tbody>
                </table>
            </section>
        </div>        
    </div>
</body>
</html>
