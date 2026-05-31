# Vim configuration
## Quick Start

1. Install without cloning the repo
```bash
tmpdir="$(mktemp -d)" && \
curl -fsSL https://raw.githubusercontent.com/Erdnaxela3/vim_config/master/setup.sh -o "$tmpdir/setup.sh" && \
curl -fsSL https://raw.githubusercontent.com/Erdnaxela3/vim_config/master/vim_config -o "$tmpdir/vim_config" && \
(cd "$tmpdir" && bash setup.sh)
```

2. (Alternative) Clone this repo
```bash
git clone https://github.com/Erdnaxela3/vim_config.git
```

3. Run the install script
```bash
cd vim_config
bash setup.sh
```

4. Open vim
```bash
# Ignore the error and press enter to continue
nvim
```

5. Run the following command in vim, to install the plugins (NERDTree, gruvbox theme, etc.)
```
:PlugInstall
```
