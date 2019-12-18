![Rentancy](assets/logo.png)
# Rentancy ~ Inventory ReactJS Explorer

## What it should do
The application should connect to the following GraphQL endpoint https://rentancy-test.sourcestream.co.uk/graphql and
query it using `getInventories: [Inventory]` and display the list of Inventories (in rows) with the following information:

1) Property `streetAddress`
1) Property `city`
1) Tenant   `firstName`
1) Tenant   `lastName`

When clicking on an inventory row, it should then query the GraphQL endpoint using `getInventory(id: ID!): Inventory` 
and display the following information:

1) Inventory: `wallsAndCeilings` 
1) Inventory: `windows` 
1) Inventory: `doors` 
1) Inventory: `lights` 
1) Inventory: `furniture` 
1) Inventory: `skirting` 
1) Agreement: `signedDate`
1) Agreement: `contractStartDate`
1) Agreement: `contractEndDate`
1) Agreement: `deposit`
1) Tenant   `email`
1) Tenant   `firstName`
1) Tenant   `lastName`
1) Property `streetAddress`
1) Property `city`
1) Property `county`
1) Property `postcode`

The test application should be written using ReactJS, but can use any libraries to help. Using a component library, 
such as React [Material-UI](https://material-ui.com/) will be looked at very favourably. 

The GraphQL endpoint has been created using AWS' AppSync. There may be libraries that will aid you in connecting and 
querying the data.

_Note: credentials for the GraphQL endpoint will be provided separately._

## Rules
 
 1) All dependent libraries must be publicly available. 
 1) Clear and concise instructions for how to build and run the application should be included within the code, e.g. `README.md`
 1) The code must be your own work. If you have a strong case to use a small code snippet of someone else's e.g. a
 boilerplate function, it must be clearly commented and attributed to the original author.
 1) The GraphQL must be queried in real-time. 

## Summary
The aim of this test is to understand your coding style, skills and approach to solving problems. We understand that you
probably have plenty of other things that you'd rather be doing, so for that reason we estimate that the test should
take approximately 3 ~ 4 hours. If after that time you have an unfinished project, that's fine. Just document what you
would have done to complete it, and submit to us.

**_You should choose an approach that you feel demonstrates your expertise and suitability for the position._**

## How to submit your test
**PLEASE DO NOT TRY AND PUSH YOUR CODE INTO THIS REPOSITORY.** This project is merely a location to hold the description
 of the test.

Preferably you will submit your code via a public repository you own e.g. your own [Github](https://github.com/) or 
[Bitbucket](https://bitbucket.org/) account. However, you may also submit your code via email or file sharing mechanism 
- e.g. Dropbox - using an archive, such as zip file or tarball (please consider the size of the file before emailing).

### Problems
If you have any problems with accessing the GraphQL endpoint, or you find that it is not responding correctly, please 
let us know by emailing [declan.newman@sourcestream.co.uk](mailto:declan.newman@sourcestream.co.uk) so we can rectify it. 
