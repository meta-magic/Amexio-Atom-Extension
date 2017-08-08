# Amexio Angular Extensions for Atom

This extension will help the developers of Atom with quick code snippet for the Amexio and Angular Markup as well as Angular TypeScript.

## Usage

### Demo

### Select the Amexio Ui Component
<img src="https://github.com/meta-magic/Amexio-Atom-Extension/blob/master/searchComponent.png"/>
### Fill up the required Component Params
<img src ="https://github.com/meta-magic/Amexio-Atom-Extension/blob/master/fillDetails.png"/>
## Requirements

Install Amexio to enhance your Angular Project.

## Amexio Angular Extension - Installation

To install this library, follow the steps given below:

```bash
$ cd your-angular-project
$ npm install amexio-ng-extensions --save
```

and then from your Angular `AppModule`:

```typescript
import { BrowserModule } from '@angular/platform-browser';
import { NgModule } from '@angular/core';

import { AppComponent } from './app.component';

// Import your library
import { AmexioWidgetModule } from 'amexio-ng-extensions';

@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    AmexioWidgetModule
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }
```

Once your library is imported, you can use its components, directives and pipes in your Angular application:

```xml
<!-- You can now use your library component in app.component.html -->
<amexio-text-input></amexio-text-input>
```


## Installing Extension in Atom

```bash
ext install amexio
```


## Known Issues

--

## Release Notes
Amexio Atom Extension supports Amexio Varanasi update 1
Amexio Atom Extension supports Amexio Hampi update 2

### 1.0.0


## License

[Apache 2.0](http://www.amexio.org/metamagic-showcase/license.html) © [MetaMagic Global Inc](http://www.metamagicglobal.com/), 2017. [Amexio Angular Extensions](http://www.amexio.tech)

**Enjoy!**
