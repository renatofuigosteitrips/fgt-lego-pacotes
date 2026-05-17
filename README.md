# Lego Pacotes FGT

Sistema modular de cadastro de peças e composição de pacotes da Fui Gostei Trips × Kantu Peru Tours.

## Arquivos

- `index.html` — Detector que redireciona automaticamente para a versão mobile ou desktop conforme o dispositivo.
- `desktop.html` — Versão completa para tela grande (tabela de peças, drag-drop, 3 abas).
- `mobile.html` — Versão otimizada para celular (cards, tab bar inferior, telas de detalhe).

Forçar versão específica:
- `?force=mobile` — abre versão mobile mesmo no computador
- `?force=desktop` — abre versão desktop mesmo no celular

## Dados

Persistência em `localStorage` do navegador. Cada dispositivo guarda seus próprios dados.

Para sincronizar:
1. No dispositivo origem: menu (≡ no mobile / botões no desktop) → Exportar JSON
2. Manda o arquivo `.json`
3. No dispositivo destino: Importar JSON

## Tecnologia

HTML + CSS + JS vanilla. Zero dependências externas, funciona offline depois do primeiro carregamento.
