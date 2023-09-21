# App.vue

`App.vue` is the main Vue.js component that serves as the container for other views and components in your application.

## Template

- The template contains the following elements:
  - A top bar with a timer, home button, and logo.
  - A status bar displaying the connection status of various components.
  - A `<router-view>` that renders child views based on the current route.
  - An `AxisControl` component for controlling robot axes.

## Imports

- The component imports the following components:
  - `AxisControl`: A component for controlling robot axes.
  - `Timer`: A component displaying a timer.
  - `Status`: A component displaying connection status.

## Style

- The component defines scoped styles for the status bar.

## Additional Information

- The component uses Vue Router to render child views within the `<router-view>`.
- It includes a top bar with a timer, home button, and logo for navigation.
- The status bar displays the connection status of various components such as the computer, robot, and gripper.
- The `AxisControl` component is positioned at the bottom of the view, allowing users to control robot axes.

This documentation provides an overview of the `App.vue` component, its template structure, imported components, and applied styles.