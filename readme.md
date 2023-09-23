# Bloganore

## Local dev

-   `./bin/dev initial setup`
-   run the following commands AND append to your shell configs (ie. `~/.zshrc`
    or `~/.bashrc`/`~/.bash_profile`)

```bash
eval "$(rtx activate zsh)"
# or for bash
# eval "$(rtx activate bash)"
source "$HOME/.cargo/env"
```

-   (optionally) configure rtx: `~/.config/rtx/config.toml`

```toml
[settings]
missing_runtime_behavior = "autoinstall"
trusted_config_paths = ["~/Projects"] # where ~/Projects is wherever you clone your repos
```

-   `dev start`

###### Bootstrapped with [pentible/typescript-app-template](https://github.com/pentible/typescript-app-template)
