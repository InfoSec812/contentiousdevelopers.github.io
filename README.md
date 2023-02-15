# Contentious Developers vite-press static site generator

## Running Locally

### Prerequisites

* NodeJS >= 16
* NPM >= 8.6

### Setup

1. Clone this repository
2. Change to the repo directory
3. Execute `npm install`

### Running In Dev Mode
1. Execute `npm run docs:dev`

### Building The Static Site
1. Execute `npm run docs:build`

## Publishing

There is a file `.github/workflows/deploy.yml` which will automatically run on the `main` branch to publish the site when updates are merged.