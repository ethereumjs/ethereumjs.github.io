
<div class="intro-text">
  <a href="https://github.com/ethereumjs/">EthereumJS</a> is an implementation of the core <a href="https://ethereum.org">Ethereum</a> Execution Layer (EL) Protocol stack in TypeScript.
</div>

<div class="intro-text">
  <a href="https://github.com/ethereumjs/ethereumjs-monorepo">https://github.com/ethereumjs/ethereumjs-monorepo</a> 
  &nbsp;{% include repository_small.html name="ethereumjs-monorepo" %}
</div> 

<h1>Projects</h1>

<div class="repo-group">
  <h3><i class="fa fa-cogs"></i> VIRTUAL MACHINE (EVM)</h3>
  <p>Implementation of the Ethereum Virtual Machine in TypeScript supporting
  all hardforks and allowing for easy integration of the EVM in web applications.</p>
</div>

<div class="repo-group">
  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/vm" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      @ethereumjs/vm
    </div>
    <div class="repo-description">
      <ul>
        <li>All hardforks until Pectra</li>
        <li>Preliminary Cancun support (incl. EIP-4844)</li>
        <li>Basic tracing and debug support</li>
        <li>Flexible EIP on/off engine</li>
        <li>Modular EVM core</li>
      </ul>
    </div>
</div>
</div>

<div class="separator"></div>

<div class="repo-group">
  <h3><i class="fa fa-cogs"></i> Execution Layer Client</h3>
  <p>Execution Layer client similar to Go-Ethereum or Nethermind in TypeScript with support for
  full sync and most of the JSON RPC endpoints.</p>
</div>

<div class="repo-group">
  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/client" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      @ethereumjs/client
    </div>
    <div class="repo-description">
      <ul>
        <li>Full sync support</li>
        <li>Engine API</li>
        <li>JSON-RPC via HTTP or Websocket</li>
        <li>Syncs small and mid-size test networks</li>
        <li>Used for protocol development (EIP-4844)</li>
      </ul>
    </div>
</div>
</div>

<div class="separator"></div>

<div class="repo-group">
  <h3><i class="fa fa-cogs"></i> Ultralight</h3>
  <p>Portal Network client implementation in TypeScript (in Development).</p>
</div>

<div class="repo-group">
  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ultralight" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      Ultralight
    </div>
    <div class="repo-description">
      <ul>
        <li>History Network Support</li>
        <li>State Network (in development)</li>
        <li>Beacon Chain Network (in development)</li>
      </ul>
    </div>
</div>
</div>

<div class="separator"></div>

<div class="repo-group">
  <h3><i class="fa fa-cube"></i> Blockchain</h3>
  <p>Core building blocks for an Ethereum blockchain including a transaction library supporting all existing 
  transaction types.</p>
</div>

<div class="repo-group">
  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/tx" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      @ethereumjs/tx
    </div>
    <div class="repo-description">
      Implementation of the various transaction types.
    </div>
  </div>

  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/block" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      @ethereumjs/block
    </div>
    <div class="repo-description">
      Block representations for all hardforks.
    </div>
  </div>

  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/blockchain" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      @ethereumjs/blockchain
    </div>
    <div class="repo-description">
      Ethereum mainnet-compatible blockchain.
    </div>
  </div>
  
</div>

<div class="separator"></div>

<div class="repo-group">
  <h3><i class="fa fa-cogs"></i> Protocol</h3>
  <p>Implementations of protocol components and data structures.</p>
</div>

<div class="repo-group">
  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/trie" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      @ethereumjs/trie
    </div>
    <div class="repo-description">
      Implementation of a Merkle Patricia Tree.
    </div>
  </div>

  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/rlp" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      @ethereumjs/rlp
    </div>
    <div class="repo-description">
      RLP encoding and decoding.
    </div>
  </div>

  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/util" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      @ethereumjs/util
    </div>
    <div class="repo-description">
      Utilities for 4844, bytes, signatures, withdrawals, addresses and other.
    </div>
  </div>

  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/wallet" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      @ethereumjs/wallet
    </div>
    <div class="repo-description">
      Wallet implementation with key management and various import formats.
    </div>
  </div>
</div>

<div class="separator"></div>


<div class="repo-group">
  <h3><i class="fa fa-globe"></i> Network</h3>
  <p>Implementation of the Ethereum network communication layer.</p>
</div>

<div class="repo-group">
  <div class="repo-box">
    <div class="repo-header">
      <div class="repo-header-right">
        <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/devp2p" alt="GitHub URL">
          <i class="fa fa-github"></i>
        </a>
      </div>
      @ethereumjs/devp2p
    </div>
    <div class="repo-description">
      Devp2p implementation with support for Discovery (DPT), RLPx transport, ETH protocol, LES and SNAP.
    </div>
</div>
</div>

<div class="separator"></div>


<h1>Contact</h1>

The EthereumJS libraries are maintained and developed by the Ethereum Foundation JavaScript Team
together with the wider Ethereum JavaScript developer community.

<div class="intro-text">
  You can reach out to us on 
    <a href="https://discord.gg/TNwARpR">Discord</a>,  
    <a href="https://github.com/ethereumjs">GitHub</a> or 
    <a href="https://twitter.com/EFJavaScript">Twitter</a>.
</div>

<p class="attribution">
Courtesy of <a href="http://fontawesome.io/">Font Awesome</a> for the icons used.
</p>
