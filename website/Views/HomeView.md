# HomeView

`HomeView` is a Vue.js view component representing the home page of your project. It displays buttons using the `MainButton` component.

## Props

- `MainButton` Props:
  - `placement` (String, Default: "tl"): Button placement.
  - `color` (String, Default: "--fade-2"): Button background color.
  - `text` (String, Default: "BEWEGEN"): Button text.

## Methods

- `MoveButton()`: Toggles `MainButton` color and sends MQTT commands.

## Style

- `.container-button`: Button container styling.
- `.left-enable`, `.right-enable`: Element positioning.

This documentation offers a brief overview of the `HomeView` component, its props, methods, and applied styles.