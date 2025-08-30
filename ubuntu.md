# Atualiza o sistema
```bash
sudo apt update && sudo apt upgrade -y
```

# Instala Spotify, VS Code, Sublime Text e Insomnia via Snap
```bash
sudo snap install spotify
sudo snap install --classic code
sudo snap install sublime-text --classic
sudo snap install insomnia
```

# Instala Python 3, pip e Git (caso não estejam instalados)
```bash
sudo apt install python3 python3-pip git -y
curl -o- [https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh) | bash
```

# Carrega o NVM (necessário fechar e reabrir o terminal após a instalação)
```bash
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```

# Instala a versão LTS do Node.js
```bash
nvm install --lts
```

# Ativa o Corepack para gerenciar o Yarn
```bash
corepack enable
```

# Instala o Yarn
```bash
corepack prepare yarn@stable --activate
```
