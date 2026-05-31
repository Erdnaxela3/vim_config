# Vim configuration
## Quick Start

1. Install without cloning the repo
```bash
curl -fsSL https://raw.githubusercontent.com/Erdnaxela3/vim_config/master/vim_config -o vim_config
curl -fsSL https://raw.githubusercontent.com/Erdnaxela3/vim_config/master/setup.sh -o setup.sh
bash setup.sh
rm -f setup.sh vim_config
```

2. (Alternative) Clone this repo
```bash
git clone https://github.com/Erdnaxela3/vim_config.git
```

3. If you used the clone method, run the install script
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
