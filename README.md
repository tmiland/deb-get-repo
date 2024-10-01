## Supported Software

The software below can be installed, updated and removed using this repository:

```bash
wget -q https://github.com/tmiland/deb-get-repo/raw/refs/heads/main/manifest -O /etc/deb-get/77-tmiland.repo
```

<!-- [[[cog
import subprocess
import cog

pretty_list = subprocess.check_output(["./deb-get-repo", "prettylist", "", "--include-unsupported" ], encoding="utf-8")
cog.out(pretty_list)
]]] -->
| Source   | Package Name   | Description   |
| :------: | :------------- | :------------ |
| [<img src="./assets/github.png" align="top" width="20" />](https://github.com/badaix/snapcast) | `snapclient` | <i>Synchronous audio player</i> |
| [<img src="./assets/github.png" align="top" width="20" />](https://github.com/badaix/snapcast) | `snapclient-pulse` | <i>Synchronous audio player</i> |
| [<img src="./assets/github.png" align="top" width="20" />](https://github.com/badaix/snapcast) | `snapserver` | <i>Synchronous audio player</i> |
| [<img src="./assets/github.png" align="top" width="20" />](https://tabby.sh/) | `tabby-terminal` | <i>A terminal for the modern age</i> |
<!-- [[[end]]] -->


**Legend**

The icons above denote how `deb-get` installs/updates the packages.

- <img src="./assets/debian.png" align="top" width="20" /> apt repository
- <img src="./assets/github.png" align="top" width="20" /> GitHub releases
- <img src="./assets/launchpad.png" align="top" width="20" /> Launchpad PPA
- <img src="./assets/direct.png" align="top" width="20" /> Website/Direct
