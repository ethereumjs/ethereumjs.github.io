---
layout: default
title: EthereumJS — Ethereum execution layer in TypeScript
---

<section class="hero">
  <img class="hero-logo" src="https://user-images.githubusercontent.com/47108/78779352-d0839500-796a-11ea-9468-fd2a0b3fe1ef.png" alt="EthereumJS logo" width="120">
  <h1>Ethereum execution layer,<br>in TypeScript.</h1>
  <p class="hero-tagline">
    Modular, browser-ready protocol libraries — EVM, blocks, transactions, state —
    maintained by core contributors and open to the broader Ethereum dev community.
  </p>
  <div class="hero-cta">
    <a class="btn btn-primary" href="https://github.com/ethereumjs/ethereumjs-monorepo">Explore the monorepo</a>
    <a class="btn btn-secondary" href="https://discord.gg/TNwARpR">Join Discord</a>
  </div>
</section>

<hr class="section-divider">

<section class="section" id="community">
  <span class="section-label">Community</span>
  <h2>Built from the community</h2>
  <p>
    EthereumJS is one of the oldest JavaScript/TypeScript Ethereum stacks in the ecosystem —
    alongside Go Ethereum on the execution layer — with deep community roots going back to the early days of Ethereum.
  </p>
  <p>
    The project grew out of the community, was nurtured for years within the Ethereum Foundation JavaScript team,
    and has since transitioned back to an independent community effort: a small core of maintainers,
    diversely funded, actively shipping protocol updates.
  </p>
  <p>
    You don't need permission to get involved — open an issue, join a discussion, send a PR.
    Whether you're building dApps, researching EIPs, or just curious about how the protocol works in readable TypeScript,
    you're welcome here.
  </p>

  <div class="team-grid">
    <a class="team-member" href="https://github.com/gabrocheleau">
      <img src="https://github.com/gabrocheleau.png" alt="Gabriel Rocheleau" width="72" height="72">
      <span class="name">Gabriel Rocheleau</span>
      <span class="handle">@gabrocheleau</span>
    </a>
    <a class="team-member" href="https://github.com/scottypoi">
      <img src="https://github.com/scottypoi.png" alt="Scotty Poi" width="72" height="72">
      <span class="name">Scotty Poi</span>
      <span class="handle">@scottypoi</span>
    </a>
    <a class="team-member" href="https://github.com/holgerd77">
      <img src="https://github.com/holgerd77.png" alt="Holger Drewes" width="72" height="72">
      <span class="name">Holger Drewes</span>
      <span class="handle">@holgerd77</span>
    </a>
    <a class="team-member" href="https://github.com/jochem-brouwer">
      <img src="https://github.com/jochem-brouwer.png" alt="Jochem Brouwer" width="72" height="72">
      <span class="name">Jochem Brouwer</span>
      <span class="handle">@jochem-brouwer</span>
    </a>
  </div>
</section>

<hr class="section-divider">

<section class="section" id="stack">
  <span class="section-label">Monorepo</span>
  <h2>The stack</h2>
  <p>
    The <a href="https://github.com/ethereumjs/ethereumjs-monorepo">ethereumjs-monorepo</a> holds modular
    building blocks of the Ethereum execution layer — each package installable via npm, composable,
    and kept in sync through a shared <code>@ethereumjs/common</code> hardfork engine.
  </p>

  <ul class="feature-strip">
    <li>Browser-ready</li>
    <li>Official test suite</li>
    <li>Tree-shakeable</li>
    <li>Osaka / Amsterdam in dev</li>
    <li>@noble crypto</li>
  </ul>

  <div class="package-group">
    <h3>Execution</h3>
    <div class="package-grid">
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/evm">
        <div class="pkg-name">@ethereumjs/evm</div>
        <p class="pkg-desc">Standalone EVM — run bytecode, custom precompiles, colored debug output.</p>
      </a>
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/vm">
        <div class="pkg-name">@ethereumjs/vm</div>
        <p class="pkg-desc">Full execution context — run transactions and blocks, update state.</p>
      </a>
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/statemanager">
        <div class="pkg-name">@ethereumjs/statemanager</div>
        <p class="pkg-desc">State abstraction — Merkle Patricia tries, RPC backends, binary tree (research).</p>
      </a>
    </div>
  </div>

  <div class="package-group">
    <h3>Protocol</h3>
    <div class="package-grid">
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/block">
        <div class="pkg-name">@ethereumjs/block</div>
        <p class="pkg-desc">Block header and body schema, validation, serialization.</p>
      </a>
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/blockchain">
        <div class="pkg-name">@ethereumjs/blockchain</div>
        <p class="pkg-desc">Chain management — block processing, reorgs, PoW/PoS helpers.</p>
      </a>
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/tx">
        <div class="pkg-name">@ethereumjs/tx</div>
        <p class="pkg-desc">All transaction types — legacy, EIP-1559, blobs, EIP-7702, and more.</p>
      </a>
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/genesis">
        <div class="pkg-name">@ethereumjs/genesis</div>
        <p class="pkg-desc">Genesis block and state initialization.</p>
      </a>
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/common">
        <div class="pkg-name">@ethereumjs/common</div>
        <p class="pkg-desc">Chain configs, hardfork scheduling, EIP activation — the glue.</p>
      </a>
    </div>
  </div>

  <div class="package-group">
    <h3>State &amp; encoding</h3>
    <div class="package-grid">
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/mpt">
        <div class="pkg-name">@ethereumjs/mpt</div>
        <p class="pkg-desc">Modified Merkle Patricia Trie — proofs, checkpoints, flexible backends.</p>
      </a>
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/binarytree">
        <div class="pkg-name">@ethereumjs/binarytree</div>
        <p class="pkg-desc">Binary tree trie implementation for statelessness research.</p>
      </a>
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/rlp">
        <div class="pkg-name">@ethereumjs/rlp</div>
        <p class="pkg-desc">Recursive Length Prefix encoding and decoding.</p>
      </a>
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/util">
        <div class="pkg-name">@ethereumjs/util</div>
        <p class="pkg-desc">Addresses, accounts, signatures, byte helpers, and shared types.</p>
      </a>
      <a class="package-card" href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/e2store">
        <div class="pkg-name">@ethereumjs/e2store</div>
        <p class="pkg-desc">Historical block data storage format (E2HS / Portal History).</p>
      </a>
    </div>
  </div>

  <p class="footnote">
    <sup>*</sup> <code>@ethereumjs/client</code> is deprecated — see the
    <a href="https://github.com/ethereumjs/ethereumjs-monorepo/tree/master/packages/client">monorepo README</a> for details.
  </p>
</section>

<hr class="section-divider">

<section class="section" id="code">
  <span class="section-label">Examples</span>
  <h2>See it in code</h2>

  <div class="code-row">
    <div>
      <div class="code-block-wrap">
        <h3>Run bytecode in the EVM</h3>
        <p class="code-caption">Five lines to instantiate an EVM and execute simple bytecode.</p>
        <pre><code>import { createEVM } from '@ethereumjs/evm'
import { hexToBytes } from '@ethereumjs/util'

const evm = await createEVM()
const res = await evm.runCode({
  code: hexToBytes('0x6001'), // PUSH1 01
})
console.log(res.executionGasUsed) // 3n</code></pre>
      </div>

      <div class="code-block-wrap">
        <h3>Run a transaction locally</h3>
        <p class="code-caption">Simulate an ETH transfer with the VM — no RPC node required.</p>
        <pre><code>import { Common, Hardfork, Mainnet } from '@ethereumjs/common'
import { createLegacyTx } from '@ethereumjs/tx'
import { createAccount, createAddressFromPrivateKey,
  createZeroAddress, hexToBytes } from '@ethereumjs/util'
import { createVM, runTx } from '@ethereumjs/vm'

const common = new Common({ chain: Mainnet,
  hardfork: Hardfork.Shanghai })
const vm = await createVM({ common })

const key = hexToBytes(`0x${'20'.repeat(32)}`)
const sender = createAddressFromPrivateKey(key)
await vm.stateManager.putAccount(sender,
  createAccount({ nonce: 0n, balance: 10n ** 18n }))

const tx = createLegacyTx({
  gasLimit: 21000n, gasPrice: 1_000_000_000n,
  value: 1n, to: createZeroAddress(),
}).sign(key)

const res = await runTx(vm, { tx })
console.log(res.totalGasSpent) // 21000n</code></pre>
      </div>

      <div class="code-block-wrap">
        <h3>Create a typed transaction</h3>
        <p class="code-caption">EIP-1559 fee-market transactions with a unified API across all tx types.</p>
        <pre><code>import { Common, Hardfork, Mainnet } from '@ethereumjs/common'
import { createFeeMarket1559Tx } from '@ethereumjs/tx'

const common = new Common({ chain: Mainnet,
  hardfork: Hardfork.London })

const tx = createFeeMarket1559Tx({
  gasLimit: 21000n,
  maxFeePerGas: 20_000_000_000n,
  maxPriorityFeePerGas: 1_000_000_000n,
  value: 1n,
  to: '0x000000000000000000000000000000000000dEaD',
}, { common })

console.log(tx.type) // 2</code></pre>
      </div>
    </div>

    <div>
      <img class="screenshot" src="{{ '/assets/images/evm_example.png' | relative_url }}" alt="EVM code example in an editor">
      <p class="screenshot-caption">EVM usage in TypeScript</p>
      <img class="screenshot" src="{{ '/assets/images/debug.png' | relative_url }}" alt="Colored EVM debug output" style="margin-top: 1.5rem;">
      <p class="screenshot-caption">Built-in colored EVM debugging</p>
    </div>
  </div>
</section>

<hr class="section-divider">

<section class="section" id="value">
  <span class="section-label">Why EthereumJS</span>
  <h2>Where it runs</h2>

  <div class="use-case-grid">
    <div class="use-case">
      <h3>dApp &amp; tooling developers</h3>
      <p>Protocol-correct primitives in TypeScript — no reimplementing RLP, transaction formats, or EVM edge cases yourself.</p>
    </div>
    <div class="use-case">
      <h3>Wallets &amp; browser apps</h3>
      <p>Small bundles, WASM-free by default, runs in Node.js and the browser. Tree-shake what you need.</p>
    </div>
    <div class="use-case">
      <h3>Researchers &amp; EIP authors</h3>
      <p>Early EIP integrations — PeerDAS, binary tree state, Amsterdam hardfork — plus contributions to execution-spec-tests.</p>
    </div>
    <div class="use-case">
      <h3>Educators &amp; learners</h3>
      <p>A readable TypeScript codebase to explore how Ethereum execution actually works under the hood.</p>
    </div>
  </div>

  <p style="margin-top: 1.75rem;">
    On the consensus side, <a href="https://github.com/ChainSafe/lodestar">Lodestar</a> complements this stack
    with a TypeScript consensus client and SSZ implementations.
  </p>
  <p>
    We've also helped close browser cryptography gaps in the ecosystem — BN254 for EVM precompiles,
    KZG for EIP-4844 and PeerDAS — with major contributions from
    <a href="https://github.com/paulmillr">@paulmillr</a> (noble-curves, micro-eth-signer). ❤️
  </p>
</section>

<hr class="section-divider">

<section class="section" id="join">
  <span class="section-label">Contribute</span>
  <h2>Join us</h2>
  <p>
    EthereumJS thrives on community contributions — bug reports, documentation, EIP prototyping,
    test cases, or a first PR. Come say hi.
  </p>

  <div class="join-box">
    <p><strong>You don't need permission.</strong></p>
    <div class="join-links">
      <a class="btn btn-primary" href="https://github.com/ethereumjs/ethereumjs-monorepo">GitHub — monorepo</a>
      <a class="btn btn-secondary" href="https://discord.gg/TNwARpR">Discord</a>
      <a class="btn btn-secondary" href="https://twitter.com/EFJavaScript">@EFJavaScript</a>
    </div>
    <p class="join-onramps">
      Start here:
      <a href="https://github.com/ethereumjs/ethereumjs-monorepo/blob/master/DEVELOPER.md">Developer docs</a>
      &middot;
      <a href="https://github.com/ethereumjs/ethereumjs-monorepo/blob/master/CODE_OF_CONDUCT.md">Code of Conduct</a>
      &middot;
      <a href="https://github.com/ethereumjs/ethereumjs-monorepo/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22">Good first issues</a>
    </p>
  </div>
</section>
