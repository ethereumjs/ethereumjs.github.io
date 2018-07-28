
<div class="intro-text">
  The <a href="https://github.com/ethereumjs/">EthereumJS</a> community builds Javascript tools implementing core <a href="https://ethereum.org">Ethereum</a>
  technologies, protocols and APIs for helping developers to interact with the Ethereum network and build
  their own applications.
</div>

<h1>Projects</h1>

<div class="repo-group">
  <h3><i class="fa fa-cogs"></i> VIRTUAL MACHINE</h3>
  <p>Implementation of the Ethereum virtual machine supporting the latest fork rules.</p>
  {% include repository.html name="ethereumjs-vm" %}
</div>

<div class="repo-group">
  <h3><i class="fa fa-sitemap"></i> MERKLE TREE / RLP</h3>
  <p>Implementation of the core Ethereum data structure.</p>
  {% include repository.html name="merkle-patricia-tree" %}
  {% include repository.html name="rlp" %}
</div>

<div class="separator"></div>

<div class="repo-group">
  <h3><i class="fa fa-lightbulb-o"></i> DAPP DEVELOPMENT</h3>
  <p>Libraries and tools to support Dapp development.</p>
  {% include repository.html name="ethrpc" %}
  {% include repository.html name="ethereumjs-util" %}
  {% include repository.html name="ethereumjs-units" %}
  {% include repository.html name="ethereumjs-abi" %}
  {% include repository.html name="ethereumjs-tx" %}
</div>

<div class="repo-group">
  <h3><i class="fa fa-key"></i> KEY MANAGEMENT</h3>
  <p>Tools for Ethereum key management and wallet interaction.</p>
  {% include repository.html name="ethereumjs-wallet" %}
  {% include repository.html name="keythereum" %}
  {% include repository.html name="ethereumjs-icap" %}
  {% include repository.html name="helpeth" %}
</div>

<div class="separator"></div>

<div class="repo-group">
  <h3><i class="fa fa-cube"></i> BLOCKCHAIN</h3>
  <p>Implementations of the main building blocks of the Ethereum blockchain.</p>
  {% include repository.html name="ethereumjs-client" %}
  {% include repository.html name="ethereumjs-blockchain" %}
  {% include repository.html name="ethereumjs-block" %}
  {% include repository.html name="ethereumjs-account" %}
  {% include repository.html name="ethereumjs-blockstream" %}
</div>

<div class="repo-group">
  <h3><i class="fa fa-wrench"></i> UTILITIES / BINDINGS</h3>
  <p>Utilities libraries and bindings to third-party libraries.</p>
  {% include repository.html name="geth.js" %}
  {% include repository.html name="ethashjs" %}
  {% include repository.html name="node-ethash" %}
  {% include repository.html name="rustbn.js" %}
</div>

<div class="separator"></div>

<div class="repo-group">
  <h3><i class="fa fa-globe"></i> NETWORK</h3>
  <p>Implementation of the Ethereum network communication layer.</p>
  {% include repository.html name="ethereumjs-devp2p" %}
</div>

<div class="separator" style="height:0px;"></div>

<h1>Use Cases</h1>

### Creating an Online Wallet?

Check out [keythereum](https://github.com/ethereumjs/keythereum) or [ethereumjs-wallet](https://github.com/ethereumjs/ethereumjs-wallet) (with HD wallet support) for managing keys and [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx) for creating transactions with them.
[ethereumjs-icap](https://github.com/ethereumjs/ethereumjs-icap) might also come handy for dealing with the ICAP (Ethereum in IBAN) format.

### Creating a Dapp?

You will need to interface with the Ethereum network. [web3.js](https://github.com/ethereum/web3.js) provides a complete Javascript API to interact with the RPC interface. If looking for a more lightweight option, [ethereumjs-abi](https://github.com/ethereumjs/ethereumjs-abi) or [solidity.js](https://github.com/ethereumjs/solidity.js) can handle the ABI encoding.

### Build for the Web?

Most of the EthereumJS libraries can be transpiled with [babel](https://babeljs.io/) to be used in web context.
We provide [browser-builds](https://github.com/ethereumjs/browser-builds) for some EthereumJS libraries, be
warned though that these might often be slightly out of date.

# Projects not Tracked Here

There are various high-quality Ethereum infrastructure Javascript projects outside the EthereumJS scope.
Some worth mentioning:

* [web3.js](https://github.com/ethereum/web3.js): the complete API as seen in the [wiki](https://github.com/ethereum/wiki/wiki/JavaScript-API)
* [solidity.js](https://github.com/ethereum/solidity.js): ABI encoding and decoding (the relevant code split out from web3.js)
* [eth.js](https://github.com/ethjs): Simple JS modules for the Ethereum ecosystem

# Contributing and Contact

Contributing to each of the projects is preferably done via pull requests. To start you can watch out for
"help wanted" issues on the organization [GitHub page](https://github.com/ethereumjs/) or have a look for
suitable issues on the various repos.

<div class="intro-text">
  You can reach out to us on 
    <a href="https://gitter.im/ethereum/ethereumjs-lib">Gitter</a> or 
    <a href="https://webchat.freenode.net/?channels=ethereumjs">#ethereumjs</a> on freenode.
</div>

<p class="attribution">
Courtesy of <a href="http://fontawesome.io/">Font Awesome</a> for the icons used.
</p>
