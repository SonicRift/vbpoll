# vbpoll
A polling system for Vestaboard
Currently in development

### Installation / setup
```sh
$ npm install
```

### Running in development
This repository uses environment variables to obscure the database connection settings.  This needs to be set prior running in development or production.
```sh
$ npm run build
$ npm run backend
```

### Testing
```sh
$ npm run test
```

### Next Steps
As Vestaboard's API continues to evolve, we are making a switch to PostgreSQL as a relational database is now closer to the shape of the interface Vestaboard makes available. Expect changes and most likely a pretty big overhaul in the coming days and weeks.