## Resolver arguments
- Resolver 함수에는 parent(root or source), args, context, info 의 네 가지 인수가 순서대로 전달된다.
```
User: {
fullName: (parent, args, context, info) => {
return "hello";
},
},
```
- https://www.apollographql.com/docs/apollo-server/data/resolvers/#resolver-arguments
