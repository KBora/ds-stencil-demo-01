# Stencil Web Component Library with Tailwind Starter

This is a demo web component library that uses StencilJS and Tailwind CSS. 

- Tailwind CSS is installed via npm and unused class are purged via Stencil configuration
- A global style sheet is used, that contains the base tailwind styles and any styles used in the components
- Shadow DOM is turned off (for now)

## Todo
- Expand components
- Compose higher level components from base components
- Experiment with Stencil output options:
  - configure 'bundles' so that when lazy loading a higher level component, all child components are loaded too, in order to improve performance / avoid delays
  - consuming application installs stencil library using 'tagNameTransform' https://stackoverflow.com/questions/59712809/stencil-namespacing-custom-elements-names-to-avoid-collisions