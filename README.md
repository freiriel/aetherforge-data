# AetherForge - Static Data Server
Repositório público para distribuição de ativos via GitHub Pages.

## Arquivos Estruturados
- `aether_manifest.json`: Contém a versão atual e o link para o banco.
- `aether_core.db`: O banco de dados SQLite atualizado.

## Fluxo de Deploy
1. O pipeline gera os arquivos.
2. Os arquivos são commitados neste repositório.
3. O App Android consome via URL do GitHub Pages.