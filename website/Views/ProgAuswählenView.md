# ProgAuswählenView.vue

`ProgAuswählenView.vue` is a Vue.js component responsible for selecting and managing programs within your application.

## Template

- The template contains the following elements:
  - A container for displaying saved programs.
  - A list of saved programs rendered using the `SavedProgram` component.
  - Main buttons for selecting and deleting programs.

## Imports

- The component imports the following components and modules:
  - `MainButton`: A custom button component.
  - `SavedProgram`: A component for displaying saved programs.
  - `useMQTT`: A module for handling MQTT communication.
  - `store`: Vuex store for managing application state.

## Data

- The component defines data properties for managing program information, buttons, timers, and other states.

## Created Hook

- The `created` hook initializes MQTT communication and retrieves program data.
- It subscribes to MQTT topics and processes received program data.
- It also manages program selection, deletion, and navigation to the program view.

## Methods

- `primBtn`: Handles the primary button click event for program selection and navigation.
- `secBtn`: Handles the secondary button click event for program deletion.
- `handleProgramClick`: Handles the click event on a saved program, allowing program selection.
- Various utility methods for sending MQTT commands, formatting time, and controlling timers.

## Watchers

- Watches for changes in the `checked` property to update button text and colors based on program selection.

## Style

- The component defines scoped styles for rendering the list of programs and the container.

## Additional Information

- The component interacts with MQTT to receive program data and send commands.
- It allows users to select and delete programs.
- The selected program is stored in the Vuex store (`store.state.chosenProg`) for use in other views.
- Users can navigate to the program view when a program is selected.

This documentation provides an overview of the `ProgAuswählenView.vue` component, its template structure, imported components, data properties, created hook, methods, watchers, styles, and its role in managing programs within your application.