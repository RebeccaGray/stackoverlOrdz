# Spark --Social Networking

> "Things are bound to ignite when sparks fly!"

## Team

  - Deniz Tetik
  - Andrew Leonardi
  - Bohee Park
  - Rebecca Gray

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Tasks](#tasks)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage

> Some usage instructions

## Requirements

- Node v6.2.2
- MongoDB 2.2.1

### Facebook Developer Profile

1. Register a new app on Facebook (https://developers.facebook.com/apps/)
1. Insert Facebook App ID and App Secret into app/server/server.js lines 58 and 59
1. In App Settings go to the bottom of the page and click "+ Add Platform" and set the Site URL to either http://localhost:3000/auth/facebook/callback or http://your-domain-name.com/auth/facebook/callback depending on whether you are in a development or production platform.
1. In App Domains above set the domain to localhost or your-domain-name.com

### Traitify Developer Profile

1. Go to https://developer.traitify.com/ and signup for a developer account. Set your public key as the value of all of the 'Authorization' keys in traitifyAPICalls.js.

## Development

### Installing Dependencies

From within the root directory:

```sh
sudo npm install -g bower
npm install
bower install
```

### Roadmap

View the project roadmap [here](https://github.com/stackoverlOrdz/stackoverlOrdz/blob/development/ROADMAP.md)


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.
