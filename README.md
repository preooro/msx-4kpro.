# Projeto MSX 4KPRO

Estrutura inicial para publicar um menu Media Station X no GitHub Pages.

## Arquivos
- `start.json`: ponto de entrada do Media Station X.
- `data/menu.json`: menu inicial da 4KPRO.

## Antes de publicar
1. Crie um repositório público no GitHub chamado `msx-4kpro`.
2. Envie o conteúdo desta pasta para a raiz do repositório (não envie a pasta `msx-4kpro` como subpasta).
3. No GitHub, abra Settings > Pages.
4. Em Build and deployment, selecione Deploy from a branch, escolha `main` e `/ (root)`, e salve.
5. Aguarde o GitHub Pages publicar o site.
6. Edite `start.json`: troque `SEU-USUARIO` pelo seu nome de usuário do GitHub e salve.
7. Confirme que os arquivos abrem por HTTPS:
   - `https://SEU-USUARIO.github.io/msx-4kpro/start.json`
   - `https://SEU-USUARIO.github.io/msx-4kpro/data/menu.json`

## Configuração no Media Station X
No app, vá a Settings > Start Parameter > Setup e informe a URL completa do arquivo `start.json` quando o assistente solicitar o endereço do servidor/arquivo. Se a versão do app solicitar apenas hostname, use `SEU-USUARIO.github.io` e siga o caminho `/msx-4kpro/start.json` quando solicitado.

O menu atual é apenas uma base demonstrativa. Substitua os itens de exemplo por links públicos e autorizados dos aplicativos que você deseja divulgar. Não publique credenciais, listas privadas ou dados de clientes.
