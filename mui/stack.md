# Stack

<br />
<br />

* 간단한 레이아웃을 만들때 사용하는 `Stack` 컴포넌트
---

```
Stack 컴포넌트는 간단한 레이아웃을 만들 때 매우 유용하다.

Stack은 자식 요소를 수직 또는 수평으로 정렬하고 간격을 조절할 수 있다.
```

<br />
<br />
<br />
<br />

1. Import

```
import Stack from '@mui/material/Stack';

// 예시에 사용하기 위한 버튼 컴포넌트
import Button from '@mui/material/Button';
```

<br />
<br />
<br />

2. 예시

```jsx
function StackComponent() {
  return (
    // direction 속성을 column으로 설정하면, 수직 정렬된다.
    <Stack direction="row" spacing={2}>
      <Button>Button 1</Button>
      <Button>Button 2</Button>
      <Button>Button 3</Button>
    </Stack>
  );
}

export default StackComponent;
```
