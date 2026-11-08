# Hi, I'm Jason

I'm based in Adelaide, Australia, currently studying medicine while exploring interdisciplinary combinations between technology and healthcare. I spent most of my career working at startups before making this shift.

I like digging.

## Open Source

I contribute to Node.js core, with merged work on worker threads, streams, and the runtime:

- Added [`worker_threads.markAsUncloneable()`](https://github.com/nodejs/node/pull/55234) for protecting objects from serialization
- Implemented [Web IDL dictionary converter for `structuredClone`](https://github.com/nodejs/node/pull/55489)
- Fixed [`WritableStream` undefined size algorithm validation](https://github.com/nodejs/node/pull/56067)
- Improved [watch-mode parent/child path handling](https://github.com/nodejs/node/pull/57425)
- Enhanced [`fs.realpath` for namespaced drive paths](https://github.com/nodejs/node/pull/65378)

I also contributed to [Undici](https://github.com/nodejs/undici), using `markAsUncloneable` to [protect web objects during serialization](https://github.com/nodejs/undici/pull/3709).

## Projects

**[Agentic React](https://github.com/jazelly/agentic-react)** helps coding agents find and change React source with fewer tokens and less search time, without requiring a multimodal model. Select elements in the browser and Agentic React turns each selection into structured context containing the React component, selector, source file, nearby code, and owner trace. It includes Vite, Webpack, and Next.js adapters plus local MCP integration for agent handoff.
