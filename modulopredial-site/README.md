# GamificationAll MóduloPredial — site oficial

Site estático em HTML, CSS e JavaScript. Não exige npm ou dependências.

## Testar
Extraia o ZIP e abra index.html no navegador.

## Publicar na Vercel
1. Crie um repositório no GitHub e envie o conteúdo desta pasta (index.html na raiz).
2. Na Vercel, selecione Add New > Project e importe o repositório.
3. Use Framework Preset: Other. Deixe Build Command vazio e Output Directory padrão. Clique em Deploy.
4. A Vercel fornecerá o endereço do site.

## Inserir os links finais
Edite config.js. Preencha downloadUrl com o endereço público do arquivo do jogo, browserUrl com o endereço da build WebGL hospedada e gameplayUrl com um link do YouTube ou MP4. Para MP4, altere gameplayType para "mp4". Envie as alterações ao GitHub para atualizar a publicação.

A build Unity WebGL deve ser exportada e hospedada separadamente com a configuração de compressão e cabeçalhos adequada. Este site não inclui o executável nem a build WebGL. Para downloads grandes, prefira um serviço de distribuição de arquivos ou releases do GitHub. As capturas atuais são de desenvolvimento e podem ser substituídas na pasta assets mantendo os nomes.
