# AutoView.vue

`AutoView.vue` is a Vue.js component responsible for configuring and starting an automated process within your application.

## Template

- The template consists of two main sections, the left side for configuring "DEPALETTIERUNG" (depalletization) and the right side for configuring "PALETTIERUNG" (palletization).
- Each section contains input fields for configuring the process, a dropdown for selecting the process type, and a `SavedProgram` component for displaying selected programs.
- There's also a back button for navigation.

## Imports

- The component imports several custom components such as `MainButton`, `SavedProgram`, `Dropdown`, and `IncrementInput`.
- It also imports the `useMQTT` module for MQTT communication and the Vuex store.

## Data

- The component defines data properties to manage program information, dropdown options, selected options, input values, and button states.
- It initializes program data with a default "ERROR" program and retrieves the chosen program from the Vuex store.

## Created Hook

- The `created` hook initializes MQTT communication and retrieves the chosen program from the store.

## Methods

- `primBtn`: Handles the primary button click event for starting the automated process.
- `handleProgramClick`: Handles the click event on a saved program.
- `handleOptionSelectedDepalettierung` and `handleOptionSelectedPalettierung`: Handle dropdown option selection events.

## Computed Property

- `isButtonEnabledColor`: Computes the color of the primary button based on input values and selected options. If all required fields are filled, the button is enabled.

## Style

- The component defines scoped styles for rendering the container, left and right sides, titles, and other elements.
- It uses a linear gradient for the background color.

## Additional Information

- The component allows users to configure depalletization and palletization settings.
- Users can select a program for the automated process.
- The selected program and configuration settings are stored in the Vuex store for use in other views.
- The primary button is enabled when all required fields are filled.
- Users can navigate back to the previous view using the back button.



This documentation provides an overview of the `AutoView.vue` component, its template structure, imported components, data properties, created hook, methods, computed property, styles, and its role in configuring and starting an automated process within your application.


[![Button Shield]][Shield]


<!---------------------------------------------------------------------------->

[Button Shield]: ../../assets/images/FlexRob%20Views/logo.png

[Shield]: https://ihebmrabet0.github.io/FlexRob_Doc

