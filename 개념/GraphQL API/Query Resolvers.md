## Resolvers
- Resolvers 함수는 데이터베이스에 액세스한 다음 데이터를 반환한다.
```
// args는 GraphQL 쿼리의 필드에 제공된 인수입니다.
Query: {
human(obj, args, context, info) {
return context.db.loadHumanByID(args.id).then(
userData => new Human(userData)
)
}
}
```
- https://graphql.org/learn/execution/#root-fields-resolvers
