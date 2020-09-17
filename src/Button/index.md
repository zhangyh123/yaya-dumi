## default
Demo:
```tsx
import React from 'react';
import Button from './index';

export default () => <Button onClick={()=>alert('onClick')} >default</Button>;

```
## primary
Demo:
```tsx
import React from 'react';
import Button from './index';

export default () => <Button onClick={()=>alert('onClick')} type={'primary'}>primary</Button>;

```
## secondary
Demo:
```tsx
import React from 'react';
import Button from './index';

export default () => <Button onClick={()=>alert('onClick')} type={'secondary'}>secondary</Button>;

```

## disabled
Demo:
```tsx
import React from 'react';
import { Button } from 'dumi-oni';

export default () => <Button onClick={()=>alert('onClick')} type={'secondary'} disabled={true}>disabled</Button>;

```

More skills for writing demo: https://d.umijs.org/guide/demo-principle
