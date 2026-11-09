# Dra. Resumos — site gratuito

## Como testar
Na pasta do projeto, execute `python -m http.server 8000` e abra `http://localhost:8000`.

## Como publicar gratuitamente
1. Crie uma conta no GitHub e um repositório público, por exemplo `dra-resumos`.
2. Envie todos os arquivos desta pasta para a raiz do repositório (inclusive `assets/`).
3. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e salve.
4. Aguarde o GitHub mostrar o endereço publicado. Links individuais ficam como `https://SEU-USUARIO.github.io/dra-resumos/#mapa/fibromialgia`.

## Como adicionar mapas
1. Coloque a imagem PNG/JPG na pasta `assets`.
2. Abra `mapas.json` e adicione um novo objeto, com ID único (sem espaços), título, especialidade, descrição, caminho da imagem e referências.
3. Para oferecer PDF, coloque o arquivo em `assets/` e preencha `pdf` com `assets/nome-do-arquivo.pdf`.
4. Defina `publicado: true` e publique as alterações. O novo mapa aparecerá automaticamente.

## Observações
- A imagem inicial é uma versão de trabalho: revise o conteúdo médico antes de divulgar, especialmente os critérios ACR 2016 que aparecem simplificados na arte.
- O site é 100% estático e não possui login, pagamentos ou armazenamento de dados pessoais.
- Para premium, não publique arquivos pagos no mesmo repositório público: será necessária proteção por autenticação e armazenamento privado.
