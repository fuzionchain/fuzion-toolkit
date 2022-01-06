# 🥞 Fuzion UIkit

[![Version](https://img.shields.io/npm/v/@fuzionchain/uikit)](https://www.npmjs.com/package/@fuzionchain/uikit) [![Size](https://img.shields.io/bundlephobia/min/@fuzionchain/uikit)](https://www.npmjs.com/package/@fuzionchain/uikit)

Fuzion UIkit is a set of React components and hooks used to build pages on Fuzion's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add@fuzionchain/uikit`

## Setup

### Theme

Before using Fuzion UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@fuzionchain/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@fuzionchain/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://fuzionchain.github.io/fuzion-uikit/)
