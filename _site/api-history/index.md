# API History at Union Fashion

This is the overview of how Union Fashion got to where they realized they needed to go API-First.

## Web

**Carrie** has been the lead on the Union Fashion website since it was first built 20 years ago.

- Leverages direct database connections to access product and order data for website.
- Has built a handful of custom APIs over the years to meet website needs along the way.
- Still uses some FTP locations for data dumps with affiliates and partners of Union Fashion.
- Is increasingly using more 3rd party and partner APIs in the last 5-10 years on website.

**Carrie** sees the value of APIs, but sees the world through the lens of the evolution of the web.

## Mobile

**Don** has been the on the Union Fashion mobile application since it first developed the app in 2009.

- Leverages direct database connections to access product and order data for mobile applications.
- Has built many custom APIs over the years to meet the needs of the mobile application.
- Leverages many JSON files published to a variety of locations for various mobile features.

**Don** sees the value of APIs, but doesn't really care how they get used beyond the mobile application.

## Integrations

**Sheila** took over integration for partners and growing SaaS applications at Union Fashion in 2012.

- Saw the value of developing RESTful APIs for use by many different partners and developers.
- Only uses APIs for integrations and avoids database connections and FTP locations for integrations.
- Has lobbied Jeff the VP of Engineering to institute a more formal strategy for developing APIs.

**Sheila** feels the pain of having to make data available to multiple consumers and values APIs.

## API Strategy

**Mishka** was hired in 2016 to establish an API strategy and develop a single API platform for Union Fashion.

- Believes in API-first, understanding the value of thoughtfully planning APIs before any application.
- Has worked with the team to craft an API strategy and help evangelize and implement across the company.
- Has published a developer portal with resources for internal teams to use when delivering APIs.
- Is using OpenAPI and JSON Schema as the contracts for each Union Fashion API being developed in the future.
- Is using OpenAPI and JSON Schema to define each of the existing APIs that are found in use at Union Fashion.
- Is having trouble getting everyone across the company to follow the strategy when delivering applications.

**Mishka** is committed to getting Carrie and Don believing in her strategy, and Sheila is helping.

## Current State

**Mishka** has documented the current state of APIs at Union Fashion, trying to understand what is in place.

- It is difficult to always find what internal APIs are in use by web, mobile, and integration teams.
- It is difficult to always find what 3rd party APIs are being used by web, mobile, and integration teams.
- There is a mix of RESTish, XMLRPC, GraphQL, SOAP, and other design patterns in use at Union Fashion.
- There are many different levels of reliability when it comes to APIs that are available at Union Fashion.

**Mishka** has revealed that a lack of an API-first approach has led to a much higher overhead in operations.

## New Projects

**Terry** the project manager was directed by **Jeff** the VP of Engineering to make sure **Mishka** signs off on new projects.

### Commerce Widgets

**Taylor** has been tasked with creating a new suite of e-commerce widgets and will be working with **Mishka** to design.

- Identifying the OpenAPI definitions for each of the existing APIs that will be used to power widgets.
- Defining OpenAPI definitions for each of the new APIs that will be need to power widgets.
- Taylor works with **Mishka** to ensure there are mock APIs for every one of the widget being developed.

**Taylor** enjoys the new API design first approach and likes having mocks to develop her widget JavaScript libraries against.

### Rewards Mobile Application

**Tim** has been tasked with creating a new mobile rewards application and was asked to work with **Mishka** to design.

- Feels like **Mishka** is asking for extra work, and feels like he can still be API-First by developing an API.
- Would rather generate his OpenAPI definition from the code he has written to develop the API behind his app.
- Feels he can still deliver a quality mobile application and be API-first without designing his OpenAPI first.

**Tim** understands the need to reuse existing APIs and standardize APIs, but feels the process is getting in his way.

## Conclusion

**Mishka** and **Jeff** realize it will take time to get the existing web and mobile teams on-board with the new strategy but will keep working at it.
