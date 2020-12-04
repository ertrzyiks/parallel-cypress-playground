# parallel-cypress-playground

## How to run test in parallel

1. Create a dashboard project
2. Set proper projectId in the cypress.json
3. Open 2 terminals and run the following command in both of them
```
yarn test --parallel --key <KEY> --group 2x-electron --ci-build-id 3
```
4. See parallel result in the dashboard
