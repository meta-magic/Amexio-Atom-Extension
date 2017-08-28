# Amexio Angular Extensions for Atom

This extension will help the developers of Atom with quick code snippet for the Amexio Angular Markup as well as Angular TypeScript.

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
import { NgModule,FormsModule } from '@angular/core';

import { AppComponent } from './app.component';

// Import your library
import { AmexioWidgetModule,CommonHttpService } from 'amexio-ng-extensions';

@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    AmexioWidgetModule,
    FormsModule
  ],
  providers: [CommonHttpService],
  bootstrap: [AppComponent]
})
export class AppModule { }
```
Include this in your app's angular-cli.json file

``` json 
"styles": [
        "../node_modules/bootstrap/dist/css/bootstrap.min.css",
        "../src/assets/messenger-theme-air.css",
        "../src/assets/messenger.css",
        "../node_modules/bootstrap-datepicker/dist/css/bootstrap-datepicker.min.css",
        "../node_modules/bootstrap-timepicker/css/bootstrap-timepicker.min.css",
        "../node_modules/jquery-bootstrap-scrolling-tabs/jquery.scrolling-tabs.min.css",
        "styles.css"
      ],
      "scripts": ["../node_modules/jquery/dist/jquery.min.js",
        "../node_modules/jquery-bootstrap-scrolling-tabs/jquery.scrolling-tabs.min.js",
        "../src/assets/messenger.js",
        "../node_modules/bootstrap-datepicker/dist/js/bootstrap-datepicker.min.js",
        "../node_modules/bootstrap-datepicker/dist/locales/bootstrap-datepicker.en-GB.min.js",
        "../node_modules/bootstrap-timepicker/js/bootstrap-timepicker.min.js"],

```
If not using cli then simply add it to the index.html head.

Once your library is imported, you can use its components, directives and pipes in your Angular application:

```xml
<!-- You can now use your library component in app.component.html -->
<amexio-text-input></amexio-text-input>
```


## Installing Extension in Atom

In the install package section look for "MetaMagic-Amexio" (https://atom.io/packages/MetaMagic-Amexio) package

<img src ="https://github.com/meta-magic/Amexio-Atom-Extension/blob/master/installPackage.png"/>

## Known Issues

--

## Release Notes

### 1.X.X

Amexio Atom Extension supports Amexio Varanasi
    http://www.amexio.org/showcaseapp/v1/index.html#/home
Amexio Atom Extension supports Amexio Hampi
    http://www.amexio.org/showcaseapp/v2/index.html#/home

## License

[Apache 2.0](http://www.amexio.org/metamagic-showcase/license.html) © [MetaMagic Global Inc](http://www.metamagicglobal.com/), 2017. [Amexio Angular Extensions](http://www.amexio.tech)

**Enjoy!**
