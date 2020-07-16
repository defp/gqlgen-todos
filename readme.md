
```
mutation create {
  createTodo(input: {userId: "xxx", text: "xxx"}) {
    id
    text
    user {
      id
      name
    }
  }
}

query list {
  todos {
    id
    user {
      id
      name
    }
    text
  }
}
```