![](https://badgen.net/bundlephobia/minzip/a11y-hooks)
![](https://badgen.net/npm/v/a11y-hooks)

# React a11y hooks 🎣♿

> A set of hooks to make it easy for everyone to make their site more accessible and improve their ux.

### table of contents:

- [useFocus](#useFocus)

## useFocus

- Programmatically focuses bound element on mount or, if shouldFocus is set to true.
- check [here](https://codesandbox.io/embed/usefocus-example-ttpys) for example usage.

`const bind = useFocus(shouldFocus?: boolean)`

### Arguments

| Name        | Type    | Required | Description                                                                |
| ----------- | ------- | -------- | -------------------------------------------------------------------------- |
| shouldFocus | boolean | false    | if provided the bound element will be focused whenever it switches to true |