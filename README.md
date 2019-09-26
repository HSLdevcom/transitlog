# transitlog

Transitlog enables visual exploration of observed public transport and how it compares to the intended traffic.
The time scale is from years past until right now.
The focus is on the movement of individual vehicles.

The initial users will be HSL customer service, traffic reimbursement with public transport operators and traffic planners.



## Roadmap

The project roadmap is currently written as epics in [the issue list of the UI repository](https://github.com/HSLdevcom/transitlog-ui/issues).

## Components

- [transitlog-ui](https://github.com/HSLdevcom/transitlog-ui) - The web user interface
- [jore-history-graphql](https://github.com/HSLdevcom/jore-history-graphql) - The backend component for retrieving historical data
- [jore-history-graphql-import](https://github.com/HSLdevcom/jore-history-graphql-import) - The batch importer for jore-history-graphql
- transitlog-timescaledb-postgraphile - A PoC for the time series database and API for the historical vehicle locations

## Status

The project now in production as HSL deployment "Reittiloki" at https://reittiloki.hsl.fi/

## Public review session

-

## UI project maintainer skills

- Recent experience with React v16 is required.
- Experience with Javascript app state management is required, preferrably with MobX but with Redux or other libraries is also applicable.
- Experience with client-side GraphQL and Apollo is required.
- Familiarity with modern Javascript syntax (ES6+) is good to have.
- Experience with Webpack and modern Javascript build systems is good to have.
- Experience with Leaflet or maps in general is good to have.
- Experience with modern CSS is good to have. The UI uses styled-components.
