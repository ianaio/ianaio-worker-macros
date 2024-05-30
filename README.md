# ianaio-worker-macros
Convenience crate for working with Web Workers

<div align="center">

  <h1><code>ianaio-worker</code></h1>

  <p>
    <a href="https://crates.io/crates/ianaio-worker"><img src="https://img.shields.io/crates/v/gloo-worker.svg?style=flat-square" alt="Crates.io version" /></a>
    <a href="https://crates.io/crates/ianaio-worker"><img src="https://img.shields.io/crates/d/gloo-worker.svg?style=flat-square" alt="Download" /></a>
    <a href="https://docs.rs/ianaio-worker"><img src="https://img.shields.io/badge/docs-latest-blue.svg?style=flat-square" alt="docs.rs docs" /></a>
  </p>

  <h3>
    <a href="https://docs.iana.io/ianaio-worker">API Docs</a>
    <span> | </span>
    <a href="https://github.com/rustwasm/ianaio/blob/master/CONTRIBUTING.md">Contributing</a>
    <span> | </span>
    <a href="https://discordapp.com/channels/44/44">Chat</a>
  </h3>

  <sub>Built with 🦀🕸 by <a href="https://rustwasm.github.io/">The Rust and WebAssembly Working Group</a></sub>
</div>

IanaIO workers are a way to offload tasks to web workers. These are run concurrently using
[web-workers](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers).
It provides a neat abstraction over the browser's Web Workers API which can be consumed from anywhere.
