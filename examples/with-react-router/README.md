## An example of using `react-async` with `react-router` (built with parcel)

The idea is to make fetching data for pages (components) configurable in a declarative way.

```
  <Router>
    ...
    <ApiRouter path="/repositories" fetchUrl="https://api.github.com/repositories" component={RepositoriesComponent} />
  </Router>
```

## Running the example

```
  npm install
  npm start
```

Then visit [http://localhost:1234](http://localhost:1234).
