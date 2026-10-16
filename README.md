# SDD-pomodoro


🚀 Guia de Setup: OpenCode & GitHub Spec-Kit no Codespaces

Este guia orienta passo a passo como configurar o ambiente de desenvolvimento no GitHub Codespaces utilizando o OpenCode com modelos de IA gratuitos, dispensando configurações locais ou cartões de crédito.

🛠️ 1. Acessando o Ambiente no Codespaces

No repositório do workshop no GitHub, clique no botão verde < > Code.

Selecione a aba Codespaces.

Clique em Create codespace on main (ou utilize o botão direto de criação se fornecido pelo instrutor).

Aguarde a inicialização da máquina virtual no navegador.

Abra o terminal integrado do VS Code (Ctrl + ' no Windows/Linux ou Cmd + ' no macOS).

## 2. Instalação do OpenCode e Dependências

Caso as ferramentas não tenham sido instaladas automaticamente pelo .devcontainer, execute os comandos abaixo no terminal:

### Instalar o Bun e Node.js (caso não estejam presentes)

```bash
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
```

### Instalar o OpenCode CLI
```bash
curl -fsSL https://opencode.ai/v2/install | bash
```

Verifique a instalação do OpenCode:
```bash
opencode --version
```



## 3. GitHub Spec-Kit

Instale o github spec-kit
```bash
uv tool install specify-cli
```
Crie um novo projeto
```bash
specify init <NOME DO PROJETO> --integration copilot
```

entre na pasta do projeto
```bash
cd <NOME DO PROJETO>
opencode
```

