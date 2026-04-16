# uia-mcp

Windows UI Automation shared library for CPC MCP servers.

## What it does

Provides Windows UI Automation (UIA) wrappers used by the `hands` MCP server for:

- Accessibility tree inspection — walk and query the UIA element tree
- Element focus control — set focus, bring windows to foreground
- Desktop input — keyboard events, mouse clicks via UIA patterns
- Window enumeration and state queries

Targets ARM64 and x64 Windows. Used as a path dependency by `hands`.

## Usage

```rust
use uia_lib;

// Walk accessibility tree, find elements, send input
```

## Platforms

| Platform | Status |
|---|---|
| Windows x64 | Supported |
| Windows ARM64 | Supported |
| macOS / Linux | Not supported (Windows-only UIA APIs) |

## Versioning

- v1.0.0 — Initial public release; extracted from `hands` as shared crate

## License

Apache-2.0
