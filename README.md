#부산_코로나와
2020.02.26. ~ 2020.03.05
자바스크립트, html, php, DB 및 웹 호스팅(cafe24)
2020년도에는 코로나가 한창 유행이었다.
원래는 부산지역에는 코로나 확진자가 나오지 않다가 늦게 나오기 시작했었다.
그래서 여러 가지 코로나 확진자의 동선을 지도에 알려주는 사이트들은 있었지만
전국 확진자의 수가 너무 많아서 업데이트가 느렸었다.
*20200328_071002.png
부산시의 공식홈페이지(http://www.busan.go.kr)에서는 업데이트가 빨랐으나
위와 같이 지도에 표시를 해주지는 않고 그냥 표에 글로 적혀있었다.
그래서 업데이트가 빠른 부산시 공식홈페이지에서 확진자 동선을 가져와서
다른 확진자 동선을 지도에 알려주는 사이트들처럼 지도에 표시를 해주는 사이트를 만들고 싶었다.
*busancoronawa2.png
처음에는 파이썬으로 웹크롤링을 해서 목록을 표시하는 코드를 짰었다.
파이썬의 BeautifulSoup이란 라이브러리를 사용하였다.
세부적으로 말하자면 확진자들이 표에서 마지막 확진자부터 표시가 되어있어서
마지막 확진자의 확진자 번호를 가져온다.
그러면 현재 모든 확진자의 인원은 몇 명인지
마지막 확진자의 인적사항에 적혀있으므로 그 인원수만 가져온다.
확진자들의 동선이 적혀있는 부분을 그 인원수만큼 반복시키면서
한명씩 구분하면서 가져와서 출력하는 코드가 위의 왼쪽의 코드이다.
오른쪽은 그에 따른 실행 결과이다.

이러한 것을 사이트로 만들어서 다른 사람들도 사용할 수 있게 만들려고
생각해 본 결과 작년에 앱을 만드는 대회가 있었는데,
그 때 DB가 필요해서 카페24의 웹호스팅 서비스를 신청해서 사용했었다.
그래서 카페24에서 기본적으로 제공해주는 나만의 도메인과 DB를 사용할 수 있었다.
이번에도 그것을 활용해보기 위해서 파이썬으로 된 위의 코드를 나의 도메인에 업로드 하였는데,
내가 신청한 것은 파이썬으로 코딩된 것을 지원하지 않는 것이었다.

(http://ted12333.cafe24.com/code_image/crawlphp.png)

그래서 php로 웹 크롤링을 해서 어느 정도 정리를 한 뒤에 DB에 저장시키는 코드를 짰었다.
위의 주소에 그 코드의 이미지를 업로드 해놓았다.
#스마트_미러
2018.10.26. ~ 2018.11.17
자바, 라떼판다(초소형 컴퓨터)
학교에서 주제탐구 대회를 하는데 IOT에 관해서 탐구하고 특정한 물건을 만들어 보자고 했었다.
그때 팀원들의 다양한 아이디어가 나왔었는데,
그중에서 우리의 힘으로 만들 수 있는 것을 만들어 보자고 해서 스마트 미러를 만들게 되었다.
스마트 미러를 만들게 되었을 때 라즈베리파이에 기존에 인터넷에 있는 코드를 넣고,
인공지능 비서처럼 작동이 되게 만들 수 있었다.
하지만 직접 만들어 보는 것이 더 유익할 것 같아서 직접 만들게 되었다.

우선 디스플레이에 디자인 된 창을 띄워야 하므로 가장 사용하기 쉬울 것 같은 자바를 사용하였다.
#비크
#HINF
#판다봇
