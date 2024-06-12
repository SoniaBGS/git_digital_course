## Curso Digital: Git/versionamento

### Gravando mudanças no repositório Diff e Commit

- Criamos o arquivo e comandamos `git add` para adicionálo ao estado modificado, na sequência ele vai ao estado `staged` através de `git diff` mostra o que fooi modificado no código e `git diff --staged` vai mostrar o arquivo que está agora na área de staged
- Vamos comitar com `git commit -m "modificação realizada"`.

### Git Log
- vai mostrar o histórico das modificações no código.

### Git restore
- o uso do comando `git restore` volta a uma versão anterior modificada, fazendo o arquivo voltar ao estado modified ou `git restore` pararetornar de modified.

### Git push 
- envia modificações do repositório local para o github.

### Git pull
- envia alterações no código da plataforma para o local.
  
### Git fetch
- verifica o que de fato está sendo enviado. Depoi usamos `git diff` para ver as modificaçoes e por fim atualizamos o código local com `git pull`,

### Git branch e raminficações do código

### Merging branches