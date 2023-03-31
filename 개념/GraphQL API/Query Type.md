## GraphQL 스키마 정의
- 모든 GraphQL 서버(Apollo Server 포함)는 스키마를 사용하여 클라이언트가 쿼리할 수 있는 데이터 구조를 정의한다.
- 스키마는 type definitions의 모음이다.
```
// 예시
const typeDefs = gql`
type Book {
title: String
author: String
}

type Query {
books: [Book]
}
`;
```
- https://www.apollographql.com/docs/apollo-server/getting-started/#step-3-define-your-graphql-schema
