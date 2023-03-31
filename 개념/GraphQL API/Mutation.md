## Mutation
- GraphQL에 대한 대부분은 데이터 fetching이지만, 서버 측 데이터를 수정할 수 있는 방법이 필요하다.
- 서버 측 데이터를 수정하는 모든 작업은 mutation을 통해 보내야 한다는 규칙을 설정하는 것이 유용하다.

```
mutation CreateReview($ep: Episode!, $review: ReviewInput!) {
  createReview(episode: $ep, review: $review) {
  stars
  commentary
  }
}
```

- https://graphql.org/learn/queries/#mutations

