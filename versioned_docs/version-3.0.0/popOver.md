---
id: popOver
title: Popover
---

import { ComponentTheme } from '../../src/components';

`Popover` is a non-modal dialog that floats around a trigger. It's used to display contextual information to the user, and should be paired with a pressable trigger element.

## Import

- `Popover`: The wrapper that provides props, state, and context to its children.
- `Popover.Arrow`: The popover arrow.
- `Popover.Body`: The body of the popover.
- `Popover.Content`: The popover itself.
- `Popover.CloseButton`: A button to close the popover.
- `Popover.Header`: The header of the popover.
- `Popover.Trigger`: Used to wrap the reference (or trigger) element.

```jsx
import { Popover } from 'native-base';
```

## Examples

### Basic

```ComponentSnackPlayer path=composites,Popover,Basic.tsx

```

### initialFocusRef

```ComponentSnackPlayer path=composites,Popover,RefEg.tsx

```

### Positions

```ComponentSnackPlayer path=composites,Popover,PopoverPositions.tsx

```

:::tip Tip
You can pass custom backgroundColor using `bg` or `backgroundColor`, `borderColor` and `borderWidth` to Popover.Content.
:::

## Props

```ComponentPropTable path=composites,Popover,Popover.tsx

```

### Popover.Arrow

`Popover.Arrow` composes the [`Box`](box.md) component.

### Popover.Content

`Popover.Content` composes the [`Box`](box.md) component.

### Popover.Header

`Popover.Header` composes the [`Box`](box.md) component.

### Popover.Footer

`Popover.Footer` composes the [`Box`](box.md) component.

### Popover.Body

`Popover.Body` composes the [`Box`](box.md) component.

### Popover.CloseButton 

`Popover.CloseButton` composes the [`Button`](button.md) component.

## Styling

<ComponentTheme name="popover" />
