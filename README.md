# Obsidian Memory

Vault Obsidian para armazenamento e sincronização de notas em markdown puro.

## Propósito

Este repositório serve como um vault Obsidian remoto, permitindo:

- Armazenamento de notas em formato markdown puro
- Sincronização entre dispositivos via Git
- Edição programática de notas por IA
- Versionamento completo do conhecimento

## Estrutura

```
Obsidian-memory/
├── .obsidian/          # Configurações do Obsidian
├── notas/              # Notas principais
├── templates/          # Templates para novas notas
└── anexos/             # Imagens e arquivos anexados
```

## Como usar

### Clonar localmente

```bash
git clone https://github.com/LucasLimaDM/Obsidian-memory.git
cd Obsidian-memory
```

### Abrir no Obsidian

1. Abra o Obsidian
2. Selecione "Open folder as vault"
3. Navegue até a pasta clonada
4. Pronto! O vault está pronto para uso

## Convenções

- Todas as notas em markdown puro (.md)
- Frontmatter YAML para metadados quando necessário
- Links internos usando sintaxe Obsidian: `[[nome-da-nota]]`
- Tags usando sintaxe: `#tag`

## Sincronização

```bash
# Puxar alterações
git pull

# Enviar alterações
git add .
git commit -m "Atualização das notas"
git push
```

---

Vault mantido por Lucas Lima Dias Messias