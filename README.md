This repository showcases an implementation of the micro frontends architecture.

Key technologies utilized include React for the Container app, Marketing, and Auth microfrontends, while Vue powers the Dashboard microfrontend.

Webpack is employed for building individual apps, with the addition of Webpack's ModuleFederationPlugin for creating modules that the Container can seamlessly consume.

Continuous Integration and Continuous Deployment (CI/CD) are facilitated through Github Workflows.

This microfrontend application adheres to the following design principles:

- Decoupling between child projects is maintained at zero.
- Coupling between the Container and child apps is kept minimal, relying on straightforward callbacks for communication.
- Assumptions about frameworks used by child apps are avoided.
- CSS styles from one project are isolated and do not affect another.
