<div align="center">

<img src="https://img.shields.io/badge/versão-v0.2-blue?style=for-the-badge" alt="Versão"/>
<img src="https://img.shields.io/badge/plataforma-Windows%20%7C%20macOS-lightgrey?style=for-the-badge" alt="Plataforma"/>
<img src="https://img.shields.io/badge/licença-MIT-green?style=for-the-badge" alt="Licença"/>

# 📂 Nesta Pasta

**Organização inteligente de arquivos para Windows e macOS.**

Configure uma vez. Deixe o Nesta Pasta cuidar do resto.

[⬇️ Download Windows](#-instalação---windows) · [⬇️ Download macOS](#-instalação---macos) · [✨ Funcionalidades](#-funcionalidades) · [⚙️ Configurações](#️-configurações)

---

</div>

## Sobre o projeto

O **Nesta Pasta** é uma aplicação desktop que automatiza a organização dos seus arquivos através de regras personalizadas e monitoramento contínuo de pastas. Chega de perder tempo organizando Downloads, Área de Trabalho ou qualquer outra pasta manualmente.

---

## ✨ Funcionalidades

### 📋 Regras personalizadas

Crie regras para organizar arquivos com base em múltiplos critérios:

| Critério | Descrição |
|---|---|
| **Extensão** | `.pdf`, `.mp3`, `.jpg`, etc. |
| **Nome contém** | Qualquer trecho no nome do arquivo |
| **Nome começa com** | Prefixo específico |
| **Nome termina com** | Sufixo específico |
| **Tipo do arquivo** | Documento, imagem, vídeo, etc. |
| **Data de criação** | Intervalo de datas |
| **Tamanho do arquivo** | Menor ou maior que X MB |

Combine condições com operadores **QUALQUER (OU)** ou **TODAS (E)** para regras mais precisas.

---

### 📁 Pastas monitoradas

Monitore quantas pastas quiser simultaneamente:

- Downloads
- Área de Trabalho
- Documentos
- Projetos
- Compartilhamentos de rede
- Qualquer pasta personalizada

**Frequências de execução disponíveis:**

`5 min` · `15 min` · `30 min` · `1 hora` · `6 horas` · `12 horas` · `Diário` · `Manual`

---

### 🕓 Histórico de execuções

Acompanhe tudo o que aconteceu com seus arquivos:

- Arquivos movimentados
- Data e horário de cada operação
- Pasta de origem e destino
- Quantidade de arquivos processados
- Acesso rápido à pasta de destino com um clique

---

### 📄 Relatórios PDF automáticos

Cada execução pode gerar um relatório PDF completo contendo:

- Data da execução
- Arquivos processados
- Destinos aplicados
- Regras utilizadas
- Resumo da operação

---

### 🤖 Integração com IA *(Beta)*

Potencialize a organização com inteligência artificial. Integrações disponíveis:

| Provedor | Status |
|---|---|
| OpenAI | ✅ Disponível |
| Google Gemini | ✅ Disponível |
| Claude | ✅ Disponível |
| Ollama Local | ✅ Disponível |

> A integração com IA está em fase beta e continuará evoluindo nas próximas versões.

---

## 💻 Instalação - Windows

### 1. Baixe o arquivo ZIP

```
NestaPasta-win32-x64.zip
```

### 2. Extraia o conteúdo

Clique com o botão direito no arquivo ZIP e selecione **Extrair Tudo**.

### 3. Execute o aplicativo

Navegue até a pasta extraída e execute:

```
electron-transferize → NestaPasta-win32-x64 → NestaPasta.exe
```

### 4. Recomendação

Para facilitar o uso diário:

- Mova a pasta extraída para uma localização fixa (preferencialmente `C:\`)
- Crie um atalho do `NestaPasta.exe`
- Fixe o aplicativo na Barra de Tarefas ou crie um atalho na Área de Trabalho

> ⚠️ Isso evita problemas caso a pasta seja movida posteriormente.

---

## 🍎 Instalação - macOS

### 1. Baixe o arquivo ZIP

```
NestaPasta-darwin-x64-v21.zip
```

### 2. Extraia e mova para Aplicativos

Após extrair, arraste o arquivo `NestaPasta.app` para a pasta **Aplicativos (Applications)**.

### 3. Execute o aplicativo

Dê um duplo clique em `NestaPasta.app`.

### 4. Caso o macOS bloqueie a execução

Como o aplicativo é distribuído fora da App Store, pode aparecer um aviso de segurança na primeira execução. Para liberar:

**Opção 1 — Ajustes do Sistema:**
```
Ajustes do Sistema → Privacidade e Segurança → Segurança → Abrir Mesmo Assim
```

**Opção 2 — Atalho direto:**

Segure `Control (Ctrl)` + clique sobre o aplicativo → **Abrir** → Confirme.

> ℹ️ Essa etapa é necessária apenas na primeira execução. Após autorizado, o Nesta Pasta funcionará normalmente como qualquer outro aplicativo do macOS.

---

## ⚙️ Configurações

### Automação
- Iniciar com o sistema
- Iniciar minimizado
- Executar em segundo plano
- Monitoramento automático
- Execução programada

### Notificações
- Notificações discretas ao mover arquivos
- Alertas de execução
- Feedback das organizações realizadas

### Performance
- Modo de baixo consumo
- Operação otimizada em segundo plano

### Relatórios
- Geração automática de PDF
- Histórico local de execuções

---

## 🔒 Privacidade

O Nesta Pasta funciona **100% localmente** no seu computador.

- ✅ Nenhum arquivo é enviado para servidores externos sem autorização
- ✅ As integrações com IA são opcionais e só são ativadas quando configuradas manualmente
- ✅ Sem coleta de dados em segundo plano

---

## 🗺️ Roadmap

- [x] Regras personalizadas por extensão, nome e tamanho
- [x] Monitoramento contínuo de pastas
- [x] Histórico de execuções
- [x] Personalização do schedule de organização
- [ ] Integração com IA (Beta)
- [ ] Mais opções de automação
- [ ] Melhorias na experiência de uso

---

## ❤️ Desenvolvido por

<div align="center">

**Nesta Cloud**

*Organize. Encontre. Foque no que importa.*

<br/>

[![LinkedIn](https://img.shields.io/badge/Lucas%20Costa-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-vinicius-costa/)

</div>
