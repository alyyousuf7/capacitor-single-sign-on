# Capacitor Custom Tabs

[![npm](https://img.shields.io/npm/v/capacitor-custom-tabs.svg)](https://www.npmjs.com/package/capacitor-custom-tabs)
[![npm](https://img.shields.io/npm/dt/capacitor-custom-tabs.svg?label=npm%20downloads)](https://www.npmjs.com/package/capacitor-custom-tabs)
[![Build Status](https://travis-ci.org/triniwiz/capacitor-custom-tabs.svg?branch=master)](https://travis-ci.org/triniwiz/capacitor-custom-tabs)

## Installation

* `npm i capacitor-custom-tabs`

## Usage

```ts
import { CustomTabs } from 'capacitor-custom-tabs';
const customTabs = new CustomTabs();

customTabs.show({url:'someUrl',customScheme:'customSchemeIfNeeded'},(data,err)=>{
    // data contains the info used to start the app e.g data from fb callback
});


customTabs.view({url:'someExternalUrl'}).then().catch();

```

## Api

| Method                                   | Default | Type                         | Description                                           |
| ---------------------------------------- | ------- | ---------------------------- | ----------------------------------------------------- |
| show(options: { url: string, customScheme: string }, response: Function) |         | `void`                     | Can be used for sso/oauth |
| view(options: { url: string }) |         | `Promise<any>`                     | Can be used to view any url |

## Example Image

| IOS                                     | Android                                     |
| --------------------------------------- | ------------------------------------------- |
| Coming Soon | Coming Soon |
