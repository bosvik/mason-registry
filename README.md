# Mason registry for netcoredbg-macOS-arm64

```lua
  {
    "williamboman/mason.nvim",
    opts = function(_, opts)
      opts.registries = opts.registries or {}
      table.insert(opts.registries, "github:bosvik/mason-registry")
      opts.ensure_installed = opts.ensure_installed or {}
      table.insert(opts.ensure_installed, "roslyn-macOS-arm64")
    end,
  },
```
