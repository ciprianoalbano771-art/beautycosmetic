# Beauty Cosmetic

Página estática em inglês, adaptada para computador e telemóvel.

## Ficheiros

- `index.html`: página completa, com CSS e imagem incorporados.
- `vercel.json`: configuração da Vercel.
- `README.md`: instruções de publicação.

## Publicar na Vercel

1. Extrai o ZIP. Não envies o ZIP como se fosse o site.
2. Coloca estes três ficheiros na raiz de um repositório Git e importa o repositório na Vercel, ou publica a pasta através da Vercel CLI.
3. Seleciona Framework Preset: Other.
4. Deixa Build Command e Output Directory sem override; este projeto não precisa de compilação.
5. Em Root Directory, seleciona a pasta que contém diretamente index.html.
6. Faz Deploy e abre o endereço do deployment concluído com sucesso.

Se surgir 404, confirma que index.html existe na raiz selecionada, que o deployment terminou com sucesso e que estás a abrir o domínio associado a esse deployment.

## Editar

Abre index.html num editor de texto para alterar conteúdo, contactos e estilos. A imagem está incorporada no HTML; não é necessária uma pasta de imagens.
