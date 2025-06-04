# VISADigitalPagamentos

Esta aplicação gerencia dados de empenhos e faturamentos. Para habilitar a sincronização com o GitHub é necessário configurar algumas constantes no arquivo `index.html`:

- `GITHUB_OWNER` – usuário ou organização do repositório
- `GITHUB_REPO` – nome do repositório
- `GITHUB_FILE` – arquivo onde os dados serão salvos (padrão `data.json`)
- `GITHUB_TOKEN` – token pessoal de acesso com permissão de escrita. Pode ser definido no código ou informado uma única vez; ele será armazenado no navegador para acessos futuros.

Se o arquivo configurado não existir no repositório, ele será criado automaticamente na primeira gravação. Após configurar, os dados serão carregados do GitHub na inicialização e salvos sempre que forem alterados.

### Passos rápidos

1. Edite `index.html` e defina `GITHUB_OWNER`, `GITHUB_REPO` e opcionalmente `GITHUB_TOKEN`.
2. Abra a aplicação no navegador; o token informado será salvo no armazenamento local e a caixa de texto desaparecerá nos próximos acessos.
3. A cada alteração, os dados serão enviados automaticamente ao arquivo `data.json` do repositório.
