---
id: button
title: Button
---

The `Button` component is used to trigger an action or event.

## Implements

- [`TouchableOpacity`](https://reactnative.dev/docs/touchableopacity) form [`React Native`](https://reactnative.dev)

## Import

```jsx
import { Button, ButtonGroup } from 'native-base';
```

- **Button** : The button component with support for custom icons, spinners, etc.
- **ButtonGroup** : Used to group buttons whose actions are related, with an option to flush them together.

## Examples

### Basic

```ComponentSnackPlayer path=primitives,Button,basic.tsx

```

### Sizes

```ComponentSnackPlayer path=primitives,Button,sizes.tsx

```

### Variants

```ComponentSnackPlayer path=primitives,Button,variants.tsx

```

### Loading

```ComponentSnackPlayer path=primitives,Button,loading.tsx

```

### Icons

```ComponentSnackPlayer path=primitives,Button,icons.tsx

```

### ButtonGroup

```ComponentSnackPlayer path=primitives,Button,ButtonGroup.tsx

```

### Basic (With Ref)

```ComponentSnackPlayer path=primitives,Button,WithRef.tsx

```

## Props

### Button

```ComponentPropTable path=primitives,Button,Button.tsx

```

### ButtonGroup

```ComponentPropTable path=primitives,Button,ButtonGroup.tsx

```

## Accessibility

- Button has `role` set to `button`
- When Button has focus, Space or Enter activates it.
