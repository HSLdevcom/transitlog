# transitlog

Transitlog enables visual exploration of observed public transport and how it compares to the intended traffic.
The time scale is from years past until right now.
The focus is on the movement of individual vehicles.

The initial users will be HSL customer service, traffic reimbursement with public transport operators and traffic planners.

Development deployment: https://dev-transitlog.hsldev.com/

## Roadmap

The project roadmap is currently written as epics in [the issue list of the UI repository](https://github.com/HSLdevcom/transitlog-ui/issues).

## Components

- [transitlog-ui](https://github.com/HSLdevcom/transitlog-ui) - The web user interface
- [jore-history-graphql](https://github.com/HSLdevcom/jore-history-graphql) - The backend component for retrieving historical data
- [jore-history-graphql-import](https://github.com/HSLdevcom/jore-history-graphql-import) - The batch importer for jore-history-graphql
- transitlog-timescaledb-postgraphile - A PoC for the time series database and API for the historical vehicle locations

## Status

The project is quite young and in active development.

## Public review session

The next review session is on 2018-10-16 from 11:00 to 11:30 UTC.
Please name your avatar if you join us remotely at https://meet.jit.si/transitlog .
