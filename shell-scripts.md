# Shell scripts

## Shebang

Please use `#!/usr/bin/env bash` instead of directly linking bash.

## Unofficial strict mode

Add this right after the shebang.

```sh
set -euo pipefail
```

- any failure will end the script
- any unitialized variable will end the script
- any failure in a pipe will end the script

See <http://redsymbol.net/articles/unofficial-bash-strict-mode/> for more information.


## Linting

Use shellcheck (either locally or online with <https://www.shellcheck.net/>).