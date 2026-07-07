<!-- spiderbrain:start v=1 fp=1f404798b35b8113 commit=cc111d3aef17 -->
## Repo understanding (SpiderBrain)

This repo carries a committed brain in `.spiderbrain/`: a deterministic, source-free map of its
structure, dependencies, and blast radius (38 files, 2 edges). Consult it before
reading files, to know what matters and what a change reaches.

Fastest use (an MCP server for this repo, no SpiderBrain install, no account):
    npx spiderbrain mcp
One-off:
    npx spiderbrain blast <path>     # what a change to <path> reaches
    npx spiderbrain keystones        # the load-bearing files

Keystones (top by reach):
- CONTRIBUTING.md  (reaches 1 files)
- LICENSE  (reaches 1 files)

The why (decisions, reasoning, always-fresh scores) is the cloud layer. Set SPIDERBRAIN_API_KEY
(https://spiderbrain.ai/dashboard?tab=keys) and any command above also returns fresh scores and `why <path>`.

Deterministic: regenerates byte-identically from commit cc111d3aef17 (fingerprint 1f404798b35b8113). Do not hand-edit between the markers.
<!-- spiderbrain:end -->
