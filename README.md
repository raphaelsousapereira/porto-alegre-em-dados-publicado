# Porto Alegre em Dados: caixa de saída para o WordPress

Conteúdo **já aprovado** do [Porto Alegre em Dados](https://portoalegreemdados.com.br), no formato pronto para o
WordPress. É gerado por `tools/publicar.py exportar` no repositório principal, que é privado. Não edite à mão.

- `pacote.json`: matérias publicadas (ID do post, slug, MD5 e conteúdo).
- No site, o snippet **PANDORA Ponte** (WPCode) busca este arquivo **por commit**, atualiza só os posts cujo MD5
  mudou e confere o resultado. Só administradores do site podem acionar a ponte.

Aqui não há dados brutos, rascunhos nem credenciais: só o que já é público no site ou foi aprovado para publicação.
