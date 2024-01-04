# belly-button-challenge

I worked on the code for Challenge 14 with Danielle Dubash over Slack. We relied on the in-class examples from Module 14 and the following sources.

## Sources

Bubble chart
- [Plotly Documentation](https://plotly.com/javascript/bubble-charts/)

Bar chart
- [Plotly Documentation](https://plotly.com/javascript/bar-charts/)
- [StackOverflow](https://stackoverflow.com/questions/20516473/d3-js-horizontal-bar-chart-and-data-from-json-file?rq=4)

Dropdown Menu
- https://devdocs.io/d3~5/d3-selection#select

I ran into issues with connecting the plot data to the values in the dropdown menu after the plots were initialized. I used the following sources for some debugging. I also asked AskBCS, and they helped me to reformat the order of our code to make the function optionChanged() work. I had originally nested all of the plotting functions under the d3 line calling the data, when instead that should be the first line of each function. 
- https://notesontech.com/javascript-selected-option-on-change/
- https://stackoverflow.com/questions/12621258/onchange-function-is-not-defined
