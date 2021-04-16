# bbv Web Community Tech-Stack

The bbv web tech stack embraces the use of frameworks, libraries and tools which rely on the Jamstack.
Traditional web stacks (e.g. ServerSideRendering) should be avoided whenever possible.

## Desicion factors

The choice of frameworks, libraries and tools is based upon the following factors:
- Usage in bbv projets
- Personal experience
- [StateOfJs 2020](https://2020.stateofjs.com/en-US/)


## Frameworks

### Should use:
- **React**

    very popular, fast, huge community, huge ecosystem, easy to learn

- **Angular**

    still popular (at least in Switzerland), customer choice, huge community, batteries included, framework by Design, not as slim as React, most suited for huge applications

### Can use:
- **Vue.js** (<span style="background:yellow; color: green">opinions?</span>)
- **Razor/Blazor** (<span style="background:yellow; color: green">opinions?</span>)

### Explore:
- **Svelte**

    seems to be the next big thing, very promising, (very) fast since there is no virtual DOM, tooling support is still growing, easy to learn

### Don't use:
- **jQuery** (not suitable for mid-sized to large applications)
- **Angular.js** (outdated)
- **ASP.NET MVC** (only SSR on its core, limited possibilities, most data centric)
- **Aurelia** (not popular enough)

## Languages

### Use:
- **TypeScript**
- **ES6**

### Don't use:
- **Dart**

## Mobile / Desktop

### Use:
- **ReactNative**
- **NativeScript**
- **Ionic**
- **Progressive Web App (PWA)**
- **Electron**

### Dont use:
- **Flutter** (<span style="background:yellow; color: green">too eraly?</span>)


## Unit Testing Frameworks

### Use:
- **Jest**

    Very popular, almost no config, fast, snapshot support, huge community, mock support out of the box, brings its own JavaScript runtime, no support for real browsers, lack of support for browser APIs like fetch or LocalStorage

### Don't use:
- **Jasmine**

    Needs an extra runtime (Karma), needs a browser instance which can be headless, supports multiple browsers, comes preconfigured with the Angular default stack, lack of snapshot testing and mocking support


## e2e Testing Frameworks

### Use:
- **cypress.io**

### Don't use
- **Protractor**

## Code Quality

### Use:
- **prettier**
- **EsLint**

### Don't use:
- **TsLint** (Deprecated)

## Styling

### Use
- **SASS/SCSS**
- **Bootstrap**
- **MaterialDesign**
- **TailwindCSS**
