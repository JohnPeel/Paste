# Paste website

This is a simple implementation of an anonymous pasting website.

## Usage

See the [public website](https://paste.dgby.org).

---

## Getting started

This is instructions for getting started on development, not for usage. See above for usage.

### Prerequisites

For development, you will need node.js and either the Node Package Manager (npm) or Yarn.

The npm program is installed with node.js on most systems, and yarn will need to installed after.

#### Node

Install node for you system using <http://nodejs.org/>.

After installation you should be able to call both node and npm from your command line.

```bash
$ node --verison
v0.1x.xx

$ npm --version
1.x.xx
```

## Install

```bash
$ git clone --recurse-submodules https://github.com/JohnPeel/Paste.git
$ cd Paste
```

### Dependencies

Use one of the following package managers to install dependencies.

- npm: `npm install`
- Yarn: `yarn install`

#### Configuration

Copy the `.env.sample` file to `.env` and edit the file with your configuration.

---

## Start Dev Server

To star the local server use npm or yarn to run the `start` script.

- npm: `npm run start`
- Yarn: `yarn run-script start`

---

## Deployment

### Build

You can build the production static files using the `build` script.

- npm: `npm run build`
- Yarn: `yarn run-script build`

---

## Built With

- [Quasar](https://quasar-framework.org/) - The frontend web framework used
  - [Vue.js](https://vuejs.org/) - The underlying frontend web framework Quasar is built on
- [Express](https://expressjs.com/) - The backend web framework used

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

- **John Peel** - [JohnPeel](https://github.com/JohnPeel)

## License

This porject is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgements

- Everyone who uses this
- Merlijn Wajer for insperation
