# 🥞 MoonKat UIkit

[![Version](https://img.shields.io/npm/v/moonkat_uikit)](https://www.npmjs.com/package/moonkat_uikit) [![Size](https://img.shields.io/bundlephobia/min/moonkat_uikit)](https://www.npmjs.com/package/moonkat_uikit)

MoonKat UIkit is a set of React components and hooks used to build pages on MoonKat's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add moonkat_uikit`

## Setup

### Theme

Before using MoonKat UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from 'moonkat_uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from 'moonkat_uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://github.com/StarsIdea/MOONKAT_uikit)
