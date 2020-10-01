# Mock bug report

Steps to reproduce:

1. Type a valid US city in the "Weather Search" box
1. Press {enter}

Expected results
User should see the current weather results for that city

Actual Results:
App crashes

## Things to do:

1. Fix the bug as you would if given the above bug ticket
1. Write a short description about what was the underlying cause of the bug and how you fixed it

## Additional tasks:

1. Make the tests better! There was a test written for this feature but it clearly didn't catch this bug, make the test better (you can open a new terminal in the bottom right of code sandbox and `yarn test`)
1. Make this application more accessible. Ensure that clicking on the label "Weather Search" puts focus into the text-input. Make sure any loading states are correctly announced to a screen reader
1. Refactor the city-weather.tsx component to use react hooks rather than React.Component
1. Match the attached design (design.png) (tailwindcss is installed and configured for you)
1. Note to match the design you may need to use different fields that are returned from the openweathermap API. The weather condition three digit code can be [mapped to the icons here](https://openweathermap.org/weather-conditions)
