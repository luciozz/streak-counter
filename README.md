# streak-counter
a streak counter for the browser, inspired by Duolingo

# `@siuol/streak-counter` - a basic streak counter

This is a basic streak counter - inspired by duolingo - written in typescript and meant for the browser (uses ``localstorage`).

## Install

```shell
yarn add @siuol/streak-counter
```

npm install @siuol/streak-counter

Usage

import {streakCounter} from '@siuol/streak-counter'

const today = new Date()
const streak = streakCounter(localStorage, today)
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/11/2021",
//    startDate: "11/11/2021",
// }
//