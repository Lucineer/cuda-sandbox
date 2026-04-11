# cuda-sandbox

Sandbox — execution isolation, resource limits, operation policies, fault containment (Rust)

Part of the Cocapn platform layer — infrastructure, configuration, and tooling.

## What It Does

### Key Types

- `ResourceLimits` — core data structure
- `ResourceUsage` — core data structure
- `SandboxConfig` — core data structure
- `OperationRecord` — core data structure
- `Fault` — core data structure
- `Sandbox` — core data structure
- _and 1 more (see source)_

## Quick Start

```bash
# Clone
git clone https://github.com/Lucineer/cuda-sandbox.git
cd cuda-sandbox

# Build
cargo build

# Run tests
cargo test
```

## Usage

```rust
use cuda_sandbox::*;

// See src/lib.rs for full API
// 11 unit tests included
```

### Available Implementations

- `Default for ResourceLimits` — see source for methods
- `ResourceUsage` — see source for methods
- `Default for SandboxConfig` — see source for methods
- `Sandbox` — see source for methods

## Testing

```bash
cargo test
```

11 unit tests covering core functionality.

## Architecture

This crate is part of the **Cocapn Fleet** — a git-native multi-agent ecosystem.

- **Category**: platform
- **Language**: Rust
- **Dependencies**: See `Cargo.toml`
- **Status**: Active development

## Related Crates

- [cuda-platform](https://github.com/Lucineer/cuda-platform)
- [cuda-config](https://github.com/Lucineer/cuda-config)
- [cuda-logging](https://github.com/Lucineer/cuda-logging)
- [cuda-metrics](https://github.com/Lucineer/cuda-metrics)
- [cuda-debugger](https://github.com/Lucineer/cuda-debugger)
- [cuda-test-harness](https://github.com/Lucineer/cuda-test-harness)
- [cuda-ffi](https://github.com/Lucineer/cuda-ffi)

## Fleet Position

```
Casey (Captain)
├── JetsonClaw1 (Lucineer realm — hardware, low-level systems, fleet infrastructure)
├── Oracle1 (SuperInstance — lighthouse, architecture, consensus)
└── Babel (SuperInstance — multilingual scout)
```

## Contributing

This is a fleet vessel component. Fork it, improve it, push a bottle to `message-in-a-bottle/for-jetsonclaw1/`.

## License

MIT

---

*Built by JetsonClaw1 — part of the Cocapn fleet*
*See [cocapn-fleet-readme](https://github.com/Lucineer/cocapn-fleet-readme) for the full fleet roadmap*
