# AbspielenView

`AbspielenView` is a Vue.js view component that displays a list of saved programs and provides controls for playback and deletion.

## Props

- None.

## Data

- `programString`: A string containing the program data.
- `programs`: An array of objects representing saved programs.
- `text1`, `text2`: Text displayed on buttons for playback and deletion.
- `color1`, `color2`: Color variables for button styling.
- `checked`: A boolean variable to track program selection.
- `checkedprogram`: The currently selected program.
- `timer`: A timer to track program playback time.
- `currentTime`: The current playback time.
- `isPaused`: A boolean indicating if playback is paused.
- `keepLooping`: A boolean to control a data retrieval loop.
- `TimerProgram`: The total time of the selected program.

## Methods

- `primBtn()`: Handles the primary button action for playback control.
- `secBtn()`: Handles the secondary button action for pause/resume and deletion.
- `handleProgramClick(e)`: Handles the selection of a program from the list.
- `startTimer()`, `stopTimer()`, `pauseTimer()`, `resumeTimer()`: Timer control functions.
- `stopRunningProgram()`: Stops a running program.

## Created Hook

- Initializes MQTT communication.
- Retrieves the list of saved programs.

## Unmounted Hook

- Stops the data retrieval loop.

## BeforeUnmount Hook

- Stops a running program when the component is unmounted.

## Watchers

- Watches for changes in the `checked` property and updates button text and colors accordingly.

## Computed Property

- `formattedTime`: Formats the current playback time.

## Style

- The component uses CSS styles for positioning and styling elements.
- It has a container with a rounded border and a list of saved programs.
- The timer is displayed with a specific font and color.

This documentation provides an overview of the `AbspielenView` component, its data, methods, lifecycle hooks, watchers, computed property, and applied styles.