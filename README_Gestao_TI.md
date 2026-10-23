# Gestão TI — Protótipo v0.1

## Arquivos
- `index.html`: estrutura da interface.
- `styles.css`: aparência e layout responsivo.
- `app.js`: navegação e comportamento demonstrativo.

## Como testar localmente
1. Extraia os arquivos para a mesma pasta.
2. Abra `index.html` no navegador.
3. Para desenvolvimento, é preferível usar a extensão Live Server no VS Code.

## Limitações importantes
Este pacote é um protótipo de frontend. Os dados ficam na memória do navegador e se perdem ao recarregar/fechar a página; não existe banco de dados compartilhado, login verdadeiro nem autorização segura. O seletor de perfil só simula a interface por papel. Não use para dados reais ou informações pessoais.

## Publicação
Pode ser publicado como demonstração estática em hospedagem de sites estáticos (por exemplo, GitHub Pages ou Netlify). Para uso real por várias pessoas, é necessário desenvolver e hospedar uma API/backend, banco de dados, autenticação, autorização por perfil, validação no servidor, HTTPS e estratégia de backups.
