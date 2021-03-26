The css grid have been started to have the css-grid property being added to the container
------------------
```
  .container{
      display: grid;
      grid-template-columns: 1fr 1fr 2fr;
      grid-gap: 10px;
      grid-template-rows: 1fr 2fr;
  }
```
  - The template columns division will be used to have the 2 columns 1column and the 1column division

  - grid-gap the property has been changed to the gap property to provide the space between the "divs"
 
  - Here 1fr refers to 1fraction of the entire fractions mentioned
  - We have an alternate way of defining `grid-template-columns: 1fr 1fr 1fr` by means of the repeat(3, 1fr).

  - Like the way we have dimensionated the columns we can even do the same for the rows as well but of this format using the property 
  `grid-template-rows: 1fr 1fr 1fr`

  - There is an another property in the css grid system called 
  `grid-template-rows: repeat(auto-fill, minmax(200px, 3fr))` this is used to produce a responsive layout with max of the 3 columns and a minimum of the 200px.

  - The other properties are `grid-column-start: 1; grid-column-end: 3`

=========================



interesting sites to solve examples
- [cssgridexamples](https://gridbyexample.com/examples/)
- [anothersiteforcssgridexamples](https://grid.malven.co/)

Visit [caniuse.com](Browsers Compatibiltiy) for the sake checking compatitbiltiy across various browsers