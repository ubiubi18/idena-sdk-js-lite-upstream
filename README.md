# idena-sdk-js

### Reliability and consensus

Please treat the software in this repository as potentially unreliable. To the best of my knowledge, concerns relevant to Idena’s consensus security remain unresolved upstream.

As long as the chain continues to operate under its current rules, I will not change those rules on my own. I welcome working with upstream maintainers, node operators, and the wider Idena community to review any proposed consensus change and coordinate its adoption.

## Research disclaimer

This is experimental research software. I cannot guarantee its security, correctness, or fitness for any purpose. Use it at your own risk, take responsibility for your decisions, independently verify changes, and stay vigilant.

![Build status](https://github.com/idena-network/idena-sdk-js/actions/workflows/ci/badge.svg)
[![License](https://badgen.net/github/license/ridenaio/idena-network/idena-sdk-js)](./LICENSE)
[![Library minified size](https://badgen.net/bundlephobia/min/idena-sdk-js)](https://bundlephobia.com/result?p=idena-sdk-js)
[![Library minified + gzipped size](https://badgen.net/bundlephobia/minzip/idena-sdk-js)](https://bundlephobia.com/result?p=idena-sdk-js)

## Installation

This library is published in the NPM registry and can be installed using any compatible package manager.

```sh
npm install idena-sdk-js --save

# For Yarn, use the command below.
yarn add idena-sdk-js
```

### Installation from CDN

This module has an UMD bundle available through JSDelivr and Unpkg CDNs.

```html
<!-- For UNPKG use the code below. -->
<script src="https://unpkg.com/idena-sdk-js"></script>

<!-- For JSDelivr use the code below. -->
<script src="https://cdn.jsdelivr.net/npm/idena-sdk-js"></script>

<script>
  // UMD module is exposed through the "idenaSdkJs" global variable.
  console.log(idenaSdkJs);
</script>
```

## Documentation

[Documentation generated from source files by Typedoc](./docs/README.md).

## License

Released under [MIT License](./LICENSE).
