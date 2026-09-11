# Deployment

## GitHub Pages

Este projeto está configurado para ser deployado automaticamente no GitHub Pages via GitHub Actions.

### URL de Acesso

🌐 **[https://maisondev.github.io/roadmap-contact-form/](https://maisondev.github.io/roadmap-contact-form/)**

### Como Funciona

1. **Repositório**: https://github.com/maisondev/roadmap-contact-form
2. **Branch**: master
3. **Workflow**: `.github/workflows/pages.yml`
4. **Deployment**: Automático a cada push para master

### Histórico de Deployment

- ✅ Repositório criado e configurado como público
- ✅ GitHub Pages habilitado
- ✅ Workflow do GitHub Actions configurado
- ✅ Primeiro deploy disparado automaticamente

### Como Fazer Deploy

Qualquer push para a branch `master` dispara automaticamente o workflow de deployment. Para fazer alterações:

```bash
# Fazer alterações nos arquivos
# ...

# Fazer commit
git add .
git commit -m "Descreva suas alterações"

# Fazer push (dispara deployment automático)
git push origin master
```

### Verificar Status do Deployment

```bash
# Ver histórico de workflows
gh run list -R maisondev/roadmap-contact-form

# Ver detalhes de um workflow específico
gh run view <run-id> -R maisondev/roadmap-contact-form
```

### Troubleshooting

Se o deployment falhar:

1. Verifique os logs do workflow: https://github.com/maisondev/roadmap-contact-form/actions
2. Verifique se GitHub Pages está habilitado nas configurações do repositório
3. Verifique se todos os arquivos estão no branch master
