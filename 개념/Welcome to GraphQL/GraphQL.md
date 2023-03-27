## GraphQL이 해결하는 문제점
1. Overfetching
- 필요한 데이터보다 더 많은 데이터를 fetch 하는 것을 말한다.
- GraphQL을 사용하면 API에 GraphQL 쿼리를 보내고 필요한 것만 정확히 얻을 수 있다.
- GraphQL 쿼리는 항상 예측 가능한 결과를 반환한다.

2. Underfetching
- 필요한 데이터보다 적은 데이터를 fetch 하는 것을 말한다.
- 일반적인 REST API는 여러 URL에서 로딩해야 하지만 GraphQL API는 앱에 필요한 모든 데이터를 단일 request로 가져온다.
- GraphQL을 사용하는 앱은 느린 모바일 네트워크 연결에서도 빠를 수 있다.
