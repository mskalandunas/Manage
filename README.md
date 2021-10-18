# Manage
A lightweight application manager for runtime micro-frontends.

## Requirements:
- Simple interface
- Lifecycle methods
- Lazy loading modules
- Cross-app communication
  - Consider "plugins" prop
- Refetch and mount new versions of apps
  For example, app v1.0 is loaded but then want to dynamically replace it with app v1.1

## Implementation brainstorming:
- Middleware to communicate with subapps
- Most of the work depends on the router
- Internal state machine showing mounted apps

## References:
https://single-spa.js.org/docs/getting-started-overview
- Use multiple frameworks on the same page without page refreshing (React, AngularJS, Angular, Ember, or whatever you're using)
- Deploy your microfrontends independently
- Write code using a new framework, without rewriting your existing app
- Lazy load code for improved initial load time

https://netflixtechblog.com/how-we-build-micro-frontends-with-lattice-22b8635f77ea