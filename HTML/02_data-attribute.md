# Q : HTML의 'data-' 속성은 무엇인가요?

```html
<button data-user-id="123" data-role="admin">Edit</button>
```

<br />

# A :

- `data-` 속성은 HTML 요소에 사용자 정의 데이터를 저장할 수 있는 속성입니다. `data-*` 형태로 정의하며, JavaScript에서는 `element.dataset`을 통해 쉽게 접근할 수 있습니다.
- 이는 DOM 요소와 관련된 데이터를 코드에 깔끔하게 연결하고, 복잡한 구조 없이 필요한 정보를 저장할 수 있어서 유용합니다.
