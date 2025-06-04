# VISADigitalPagamentos

Esta aplicação gerencia dados de empenhos e faturamentos. Para habilitar a sincronização com o GitHub é necessário configurar algumas constantes no arquivo `index.html`:

- `GITHUB_OWNER` – usuário ou organização do repositório
- `GITHUB_REPO` – nome do repositório
- `GITHUB_FILE` – arquivo onde os dados serão salvos (padrão `data.json`)
- `GITHUB_TOKEN` – token pessoal de acesso (opcional). Se não definido, informe manualmente no campo **GitHub Token** ao abrir a página.

Após configurar, os dados serão carregados do GitHub automaticamente na inicialização e salvos sempre que forem alterados.
