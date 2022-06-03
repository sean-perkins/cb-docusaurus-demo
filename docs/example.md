---
title: Example
---

This is an example docusaurus markdown page.

```tsx
import { useState } from "react";

const Main = () => {
  const [isOpen, setOpen] = useState(true);
  return (
    <div>
      <button onClick={() => setOpen(true)}>Open</button>
    </div>
  );
};
```
