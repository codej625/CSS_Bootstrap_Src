# GRID

<br />
<br />

* MUI의 Grid를 알아보자
---

```
Grid2는 Material-UI의 유연한 그리드 시스템으로,
다양한 레이아웃을 쉽게 구현할 수 있도록 도와준다.
(기본적으로 Flex으로 작동)
```

<br />
<br />
<br />
<br />

1. Import

```
import Grid2 from '@mui/material/Grid2';

or

import { Grid2 } from '@mui/material';
```

<br />
<br />
<br />

2. 예시

```tsx
<Grid container spacing={2}>
  <Grid size={8}>
    <Box>size=8</Box>
  </Grid>
  <Grid size={4}>
    <Box>size=4</Box>
  </Grid>
  <Grid size={4}>
    <Box>size=4</Box>
  </Grid>
  <Grid size={8}>
    <Box>size=8</Box>
  </Grid>
</Grid>
```
