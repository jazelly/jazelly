# Hi, I'm Jason

I'm based in Adelaide, Australia. Most of my work experience has been with startups, and I'm currently studying medicine. I'm especially interested in bringing different disciplines together, including software, AI, and medicine.

I like digging.

## Open Source

I contribute to Node.js core, with merged work on worker threads, streams, and the runtime:

- Added [`worker_threads.markAsUncloneable()`](https://github.com/nodejs/node/pull/55234) for preventing structured cloning of objects
- Implemented [Web IDL dictionary converter for `structuredClone`](https://github.com/nodejs/node/pull/55489)
- Fixed [`WritableStream` undefined size algorithm validation](https://github.com/nodejs/node/pull/56067)
- Improved [watch-mode parent/child path handling](https://github.com/nodejs/node/pull/57425)
- Enhanced [`fs.realpath` for namespaced drive paths](https://github.com/nodejs/node/pull/65378)

I also contributed to [Undici](https://github.com/nodejs/undici), using `markAsUncloneable` to [prevent structured cloning of web objects](https://github.com/nodejs/undici/pull/3709).

## Projects

**[Agentic React](https://github.com/jazelly/agentic-react)** connects selected elements in a React app to the source code behind them, without requiring a multimodal model. Select elements in the browser and Agentic React turns each selection into structured context containing the React component, selector, source file, nearby code, and owner trace. It includes Vite, Webpack, and Next.js adapters plus local MCP integration for agent handoff.
