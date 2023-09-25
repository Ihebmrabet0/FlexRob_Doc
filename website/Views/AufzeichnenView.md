# AufzeichnenView

`AufzeichnenView` is a Vue.js view component representing a recording interface in your frontend project. It consists of buttons using the `MainButton` component.

## Props

- `MainButton` Props:
  - `placement` (String): Button placement.
  - `color` (String): Button background color.
  - `text` (String): Button text.

## Data

- `color1`: Background color for the first button.
- `color2`: Background color for the second button.
- `color3`: Background color for the third button.
- `color4`: Background color for the fourth button.
- `text1`: Text for the first button.
- `text2`: Text for the second button.
- `text3`: Text for the third button.
- `text4`: Text for the fourth button.
- `mode`: Current mode of the view.
- `ptp`: PTP status.
- `finished`: Recording finished status.

## Methods

- `button1()`: Toggles PTP mode and button color.
- `button2()`: Controls recording mode, pause, and resume.
- `button4()`: Stops recording and navigates to the "Save" page.
- `stopRunningProgram()`: Stops the running program.

## Style

- `.container-button`: Button container styling.
- `.left-enable`, `.right-enable`: Element positioning.

## Screenshots

`First View`

![AufzeichnenView](../../assets/images/FlexRob%20Views/AufzeichnenView.PNG)

`Recording View`

![AufzeichnenRunView](../../assets/images/FlexRob%20Views/AufzeichnenRunView.PNG)


This documentation provides an overview of the `AufzeichnenView` component, its props, data, methods, and applied styles.


[![Button Shield]][Shield]


<!---------------------------------------------------------------------------->

[Button Shield]: ../../assets/images/FlexRob%20Views/logo.png

[Shield]: https://ihebmrabet0.github.io/FlexRob_Doc

