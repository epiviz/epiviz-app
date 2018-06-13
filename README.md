Epiviz2 App is built using the epiviz component library and components available at http://webcomponents.org

This also uses the PRPL pattern in loading the app

The PRPL pattern, in a nutshell:

- **Push** components required for the initial route
- **Render** initial route ASAP
- **Pre-cache** components for remaining routes
- **Lazy-load** and progressively upgrade next routes on-demand

Setup

Install **polymer-cli** and **bower**

Run the app

```
polymer serve
```

To build the app

```
polymer build
```

The build actually generates both es5 and es6 compatible builds. Use the appropriate version that is supported by the libraries you plan to extend the app with.
