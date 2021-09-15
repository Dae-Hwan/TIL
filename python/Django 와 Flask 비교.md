![](https://images.velog.io/images/gigymi2005/post/e69e8d56-cd48-4cd9-88e4-a89d833d5020/image.png)
>참고자료
- https://tech95.kr/164
- https://dingrr.com/blog/post/%EC%96%B8%EC%A0%9C-django%EB%A5%BC-%EC%96%B8%EC%A0%9C-flask%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%B4%EC%95%BC-%ED%95%A0%EA%B9%8C
- https://bluese05.tistory.com/44
- https://wendys.tistory.com/172

## Django
### 특징
- 오픈소스, flask보다 사용자가 더 많아서 자료 찾기가 편리함
- flask보다 약 10배 많은 코드 라인으로 개발해서 더 무거움(full stack web framework)
- 프레임워크가 복잡하지만 틀에 맞추면 쉽게 큰 프로젝트도 가능(자유도가 적음)
- 속도가 더 빠름(근데 상관없다고함)
- RDBMS와의 상호 작용을 완전히 지원하는 기본 내장 ORM과 함께 제공.이 ORM은 마이그레이션 생성 및 관리도 지원. 내장 된 유효성 검사를 사용하여 데이터베이스 모델을 만드는 것이 상대적으로 더 편안함.
-유지 보수하기편함
- django는 자동으로 관리자 화면을 구성(admin 페이지를 말하는거 같다)

 ### Django를 사용하는 사이트
 Instagram, Spotify, YouTube, Dropbox, Bitbucket, Eventbrite...

---
## Flask
- 오픈소스, Django보단 상대적으로 사용자가 적음.
- Django의 1/10수준으로 가벼움
- 매우 가볍고 심플한 Framework를 지향하는 점이 특징(Micro framework)
- Flask는 기본 기능 제공에 다양한 확장 모듈을 이용할 수 있는 구조여서 자유도가 높음
- Flask에는 DB ORM 구조가 따로 존재 하지 않음. 개발자가 원한다면 ORM 지원 패키지를 선택해서 사용하면 된다. (보통 SQLAlchemy 를 사용한다)
- REST API 서버처럼 요청과 응답이 매우 확정적인 경우에는 가볍고 군더더기 없는 Flask 개발이 더 효율적


 ### Flask를 사용하는 사이트
Flask를 사용하는 회사 중 일부는 Reddit, Mailgun, Netflix, Airbnb 등입니다
 
 ---
 ## 결론
 찾아본 자료들에서 공통적으로 말하길 서로의 필요에 의해 적절히 사용하는것이 좋다고 했다. 
 가볍고, 자유로움은 Flask. 편리함과 생산성은 Django같다.


