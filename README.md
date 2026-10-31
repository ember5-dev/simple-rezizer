# Simple Resizer

> Redimensione, converta e exporte imagens em lote — 100% no navegador,
> sem upload, sem servidor, sem cadastro.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![No Backend](https://img.shields.io/badge/backend-none-brightgreen)]()
[![Vanilla JS](https://img.shields.io/badge/JS-vanilla-yellow)]()

![Demo do Simple Resizer](docs/demo.gif)

Ferramenta web para **redimensionar, converter e exportar imagens** diretamente
no navegador. Suporta **lote**, **PNG/JPEG/WebP**, **controle de qualidade** e
**download em ZIP** — tudo processado localmente com **Canvas API**. Suas imagens
nunca saem do seu computador.

**[🔗 Demo online](https://gnu1672.github.io/simple-resizer)** ·
**[🐛 Reportar bug](https://github.com/gnu1672/simple-resizer/issues)** ·
**[💡 Sugerir feature](https://github.com/gnu1672/simple-resizer/issues)**

---

## 🤔 Por que existe

A maioria dos redimensionadores online faz **upload da sua imagem para um servidor**.
Isso significa espera, exposição de dados e, muitas vezes, cadastro obrigatório.

O **Simple Resizer** processa tudo **localmente** com a **Canvas API** do navegador:
- Suas imagens **nunca** são enviadas para servidor
- Funciona **offline** depois de carregar a página
- **Sem cadastro, sem anúncios, sem limite de uso**
- **Single-file HTML** (~X KB) — fácil de hospedar em qualquer lugar

## ✨ Funcionalidades

### Redimensionamento
- Redimensionar por **largura, altura ou porcentagem**
- **Múltiplas imagens** de uma vez
- **Preservar proporção** (com opção de desativar)
- Diferentes **modos de redimensionamento**
- **Presets** de dimensões comuns
- **Rotação** e **espelhamento**
- **Fundo transparente** para PNG/WebP

### Exportação
- **PNG, JPEG e WebP**
- Ajuste de **qualidade** (JPEG/WebP)
- **Download individual** ou **em lote**
- **Exportação em ZIP** de várias imagens de uma vez

### Pré-visualização
- **Antes e depois** lado a lado
- **Zoom** na pré-visualização
- **Interface responsiva** (desktop e mobile)
- **Modo escuro**

### Privacidade
- 🔒 **Processamento 100% local** — nada é enviado para servidor
- Sem cookies, sem analytics, sem rastreamento
- Funciona **offline** após o primeiro carregamento

<p align="center">
  <img src="docs/desktop.png" alt="Interface desktop" width="600">
  <br>
  <img src="docs/mobile.png" alt="Interface mobile" width="250">
</p>

## 🚀 Como usar

### Online (recomendado)
1. Abra o **[demo online](https://gnu1672.github.io/simple-resizer)**
2. Arraste imagens ou clique para selecionar
3. Ajuste dimensões, formato e qualidade
4. Baixe individualmente ou em **ZIP**

### Localmente
Não precisa instalar nada — é um único arquivo HTML.

```bash
git clone https://github.com/gnu1672/simple-resizer.git
cd simple-resizer
