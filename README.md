**Moved: https://github.com/intrinsisch/intrinsisch/commit/aaff5b458abb93264d07cc4fb08f27f9d7638e7c**

# intrinsisch/framework

## Prerequisites

* Node v16.17 or higher
* Yarn v1.22 or higher

### Run with Docker

To run the development environment in a container the `/.devcontainer/Dockerfile` can be used.

## Setup

Run `yarn` inside the root directory to install the npm packages needed.

## Development

Run `yarn dev` and SASS styles based on the `/src/index.scss` will be compiled to CSS into the directory `/dist` continuously.

## Build

Run `yarn build` and SASS styles based on the `/src/index.scss` will be compiled and compressed to CSS into the directory `/dist` once.
