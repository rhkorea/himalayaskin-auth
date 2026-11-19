# himalayaskin-auth
히말라야스킨이 자사 쇼핑몰 운영 도구를 카페24에 연결할 때 인증 코드를 받는 페이지다. https://auth.himalayaskin.com 으로 열린다.

- `cafe24/callback.html`: 카페24가 돌려준 주소(인증 코드 포함)를 화면에 보여 주기만 한다. 어디로도 보내지 않고 저장하지 않는다.
- 비밀 값(Client Secret, 접속 키)은 이 저장소에 두지 않는다.
