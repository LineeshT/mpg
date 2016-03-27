This example is inspired by the mpg Shiny example.
It display the following components in the screen:
   Radio button & Checkbox

Based on your selection, the application displays charts in the middle section. The application can be used to display the following plots : mpg vs cylinders, mpg vs transmission, mpg vs gears, mpg vs weight.

Application uses "mpgData" global variable. It builds "formulaText" using renderText, and uses it for display and also to build the charts.

