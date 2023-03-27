## REST API
- REST API는 특정 URL로 요청을 통해 이루어진다.

### HTTP 요청 메서드
- HTTP는 요청 메서드를 정의하여, 주어진 리소스에 수행하길 원하는 행동을 나타낸다.
- 간혹 요청 메서드를 "HTTP 동사"라고 부르기도 한다.
- https://developer.mozilla.org/ko/docs/Web/HTTP/Methods

### 자주 사용하는 HTTP 요청 메서드들
- GET: GET 메서드는 오직 데이터를 받기만 한다. (읽기 전용)
- POST: POST 메서드는 리소스를 생성할 때 사용한다.
- PUT: PUT 메서드는 리소스를 업데이트할 때 쓰인다.
- DELETE: DELETE 메서드는 틁정 리소스를 삭제할 때 쓰인다.
- PATCH: PATCH 메서드는 리소스의 부분만을 수정하는 데 쓰인다.

### REST API 설계
1. URL에서는 가급적 동사를 사용하지 않는다.
- 동사보다는 HTTP request method를 이용
- /seeMovies(GET) -> /movies(GET)
- /createMovie(POST) -> /movies(POST)

2. 검색이나 필터를 처리할 때는 query parameter를 이용하는 것이 좋다.
- /getTopRatedMovies -> /movies?min_rating=9
- /findMoviesFromThisYear -> /movies?release_date=2022
