# VISADigitalPagamentos

Esta aplicação gerencia dados de empenhos e faturamentos. Já está configurada para sincronizar automaticamente com este repositório no GitHub. As seguintes constantes em `index.html` definem essa integração:

- `GITHUB_OWNER` – usuário ou organização do repositório (atualmente `leonardomverona`)
- `GITHUB_REPO` – nome do repositório (atualmente `VISADigitalPagamentos`)
- `GITHUB_FILE` – arquivo onde os dados serão salvos (padrão `data.json`)
- `GITHUB_TOKEN` – token pessoal de acesso com permissão de escrita. O token já está definido no código para sincronização automática.

Se o arquivo configurado não existir no repositório, ele será criado automaticamente na primeira gravação. Após configurar, os dados serão carregados do GitHub na inicialização e salvos sempre que forem alterados.

### Passos rápidos

1. Abra a aplicação no navegador; os dados serão carregados automaticamente do arquivo `data.json` deste repositório.
2. Ao salvar, as alterações são enviadas automaticamente ao GitHub usando o token configurado.
