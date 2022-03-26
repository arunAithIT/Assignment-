
## Getting started

1. Clone this repo `git clone git@github.com:Sindex42/gilded-rose-js.git`
2. Change directory `gilded-rose-js`
3. Run npm to install dependencies `npm install`

### Testing

1. Run tests with Jest `npm run test`

## Approach

- Created a text test as per the [suggestions](https://github.com/emilybache/GildedRose-Refactoring-Kata#text-based-approval-testing) in the original repository. With this in place I could be sure that I didn't change any of the original functionality

- Wrote separate unit tests for the individual items and circumstances

- Made a flowchart to solidify my understanding of the flow of data through the program before starting




### Refactoring

  - Made the iterator return early for Sulfuras as it is a legendary item that does not change
  - Simplified the nested if statements
  - Created classes for each category of item that inherits from the Item class
  - Integrated the classes back into the updateQuality function
  - Removed magic numbers and added a module to hold the constants
  - Modified NonUnique items to handle conjured items as an update to the system
  - Created a function that converts items into special or non special items
  - Split advanceDay into smaller functions

