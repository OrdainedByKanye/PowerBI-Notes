
# Functions

## Custom Functions for PowerQuery

### Date Functions

#### Converting Unix Date Format to Useable Format

`(Column w/ 10 Digit Number/60/60/24,1) + DATE(1970,1,1)`

## Custom DAX Functions for Measures

### Total Functions

#### Totals with Filters

`Total Sales - Example
Calculate (
  [Total Sales],
  dimProduct[Product Category] = "Hair Care"
  )`
