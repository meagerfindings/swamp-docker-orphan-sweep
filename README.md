# swamp-docker-orphan-sweep

[swamp](https://swamp.club) extension `@mgreten/docker-orphan-sweep` — find
and remove orphaned Docker Compose containers from dead git worktrees.

## Extension documentation

See [extensions/models/README.md](extensions/models/README.md) for full usage,
method documentation, global arguments, matching heuristic details, and common
use cases.

## Install

```bash
swamp extension pull @mgreten/docker-orphan-sweep
```

## Repository layout

```
.
├── README.md                          # This file
├── extensions/
│   └── models/
│       ├── docker_orphan_sweep.ts     # Model implementation
│       ├── manifest.yaml              # Extension manifest
│       ├── README.md                  # Extension documentation
│       └── LICENSE.txt                # MIT license
└── .swamp/                            # Swamp repository data
```

## License

MIT — see [extensions/models/LICENSE.txt](extensions/models/LICENSE.txt).
