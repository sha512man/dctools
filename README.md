# DC Tools

## Instalation

```
cd ~/.local/share
git clone git@github.com:sha512man/dctools.git
```

Add to your `~/.zshrc`:

```
profile_file="${HOME}/.local/share/dctools/.zshprofile"

if [[ -f "${profile_file}" ]]; then
    source "${profile_file}"
fi
```
