# Cactus Docs Hub

Site estático para centralizar documentações dos apps internos da Cactus Corp.

## Acesso local

Abra `docs-site/index.html` no navegador.

Credenciais iniciais:

- Login: `cactuscorp`
- Senha: `cactuscorp@&2026`

## Observação de segurança

Este login é apenas uma barreira visual em um site estático. Em GitHub Pages, qualquer pessoa com acesso ao código publicado consegue ver a senha no JavaScript. Para segurança real, use repositório privado, GitHub Pages privado/Enterprise ou uma camada com autenticação corporativa.

## Exportar PDF

Clique em `Exportar PDF` e escolha `Salvar como PDF` na impressão do navegador.

## Adicionar novos apps

O layout já está preparado para múltiplos apps. Para adicionar outro app:

1. Adicione um novo botão em `.app-nav`.
2. Crie novas seções dentro de `.docs-content`.
3. Ajuste a busca e textos em `app.js`, se necessário.
