# 💻 [iFE-code-snippets](https://github.com/zyj1022/ife-code-snippets)

This extension provides you React/TS/JS snippets for [VS Code](https://code.visualstudio.com/)

## 📚 Supported languages (file extensions)

* JavaScript (.js)
* JavaScript React (.jsx)
* TypeScript (.ts)
* TypeScript React (.tsx)

## 📖 Snippets

Below is a list of all available snippets and the triggers of each one. The `⇥` means the `TAB` key.

## 📦 Import package
| Trigger  | Content | Description |
| -------: | ------- | ------- |
| `imr`   | `import React from 'react';` |  |
| `imfc`  | `import React, { Fragment, Component } from 'react';` |   |
| `imhs`  | `import React, { useState, useContext, useEffect, useCallback, useMemo } from 'react';` |   |

**imall**

```
import React, { Fragment, Component } from 'react';
import { observer, inject } from 'mobx-react';
import { toJS } from 'mobx';
import styled from 'styled-components';
import { Button } from 'antd';
```

## 🪝 React hooks
| Trigger  | Content | Description |
| -------: | ------- | ------- |
| `uses`   | `const [, set] = useState();` | useState |
| `usee`   | `useEffect(() => { }, []);` | useEffect |
| `usec`   | `const  = useContext();` | useContext |
| `usecb`  | `const memoizedCallback = useCallback(() => {doSomething(a, b)},[a, b],);` | useCallback |
| `user`   | `const  = useRef();` | useRef |
| `usem`   | `const memoizedValue = useMemo(() => computeExpensiveValue(a, b), [a, b]);` | useMemo |

## 🍚 Basic methods
| Trigger  | Content |
| -------: | ------- |
| `clog`   | `console.log()` |

## 📒 React components

**Class Component**

`cc`

```
export default class  extends Component {
    state = {  }
    render() { 
        return (  );
    }
}
```

**Function Component**

`fc`

```
export interface Props {
    
}
 
const : React.FC<Props> = () => {
    return (  );
}
 
export default ;
```

**render**

`render`

```
render() {
    return (
         
    );
}
```

## License

[MIT](./LICENSE.txt)