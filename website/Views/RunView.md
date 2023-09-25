# RunView.vue

`RunView.vue` is a Vue.js component responsible for displaying the "AUTO MODUS" and providing a button to stop the automated process.

## Template

- The template consists of a title displaying "AUTO MODUS" and a button for stopping the automated process.

## Imports

- The component imports the `MainButton` component for the stop button, the `useMQTT` module for MQTT communication, and the Vuex store for managing application state.

## Data

- The component defines a data property to manage the text displayed on the stop button.

## Created Hook

- The `created` hook initializes MQTT communication and defines a method to send commands to the MQTT server.

## Methods

- `primBtn`: Handles the click event of the stop button. It navigates the user back to the home screen when the stop button is clicked.

## Style

- The component defines scoped styles for rendering the container, title, and other elements.
- It uses a linear gradient for the background color.
- The title is styled with large text, bold font, and centered alignment.

## Additional Information

- The component provides a simple user interface for stopping the automated process.
- It displays the "AUTO MODUS" title and a stop button.
- Users can click the stop button to halt the automation and return to the home screen.

## Screenshots

![RunView](../../assets/images/FlexRob%20Views/RunView.png)


This documentation provides an overview of the `RunView.vue` component, its template structure, imported components, data properties, created hook, methods, styles, and its role in displaying the "AUTO MODUS" and stopping the automated process within your application.


[![Button Shield]][Shield]


<!---------------------------------------------------------------------------->

[Button Shield]: ../../assets/images/FlexRob%20Views/logo.png

[Shield]: https://ihebmrabet0.github.io/FlexRob_Doc

