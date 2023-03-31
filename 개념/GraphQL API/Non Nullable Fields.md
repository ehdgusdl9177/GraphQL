## Lists and Non-Null
- 아래 Character에 name에 String 타입을 사용하고 느낌표 !를 추가하여 Non-Null로 표시한다.
- Non-Null로 표시하게 되면 서버가 항상 이 필드에 대해 null이 아닌 값을 반환할 것으로 예상한다.
- 그래서 null 값을 얻게 되면 클라이언트에게 문제가 있음을 알린다.

```
type Character {
name: String!
appearsIn: [Episode]!
}
```
- https://graphql.org/learn/schema/#lists-and-non-null

