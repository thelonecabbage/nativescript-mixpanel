[![npm](https://img.shields.io/npm/v/nativescript-mixpanel.svg)](https://www.npmjs.com/package/nativescript-mixpanel)
[![npm](https://img.shields.io/npm/dt/nativescript-mixpanel.svg?label=npm%20downloads)](https://www.npmjs.com/package/nativescript-mixpanel)


# NativeScript Mixpanel
A NativeScript plugin to provide the ability to integrate with Mixpanel.

## Installation
From your command prompt/terminal go to your app's root folder and execute:

`tns plugin add nativescript-mixpanel`

## Usage


### Angular Native (NativeScript Angular) Usage

In main.ts add the following before you bootstrap

``` TS

import {MixpanelHelper} from "nativescript-mixpanel";
MixpanelHelper.init(YOUR_KEY_HERE);

```


## API
``` TS
import {MixpanelHelper} from "nativescript-mixpanel";
```
- **MixpanelHelper.init(token: any)**
- **MixpanelHelper.track(eventName: any, props?: any)**
- **MixpanelHelper.timeEvent(eventName: any)**
- **MixpanelHelper.identify(id: any, extraAtributes?: any)**
- **MixpanelHelper.registerSuperProperties(props: any)**
- **MixpanelHelper.addPushDeviceToken(token: any)**
- **MixpanelHelper.alias(alias: string)**
- **MixpanelHelper.reset()**
- **MixpanelHelper.flush()**

### Contributors

- Antonio Cueva Urraco
- Blake Nussey
- Demetrio Filocamo
