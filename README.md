# Git e Github Beatsolu

Repositório para o curso git e github da Beatsolu

## Exemplo: contribuindo para um repositório existente
``` 
# Faça o download deste repositório para sua máquina
clone git git@github.com:beatsolu/gitgithub.git

# Mude para o diretório `gitgithub`
cd gitgithub

# Crie uma nova branch para armazenar novas alterações
git branch `seu-nome`

# Alternar para essa branch (linha de desenvolvimento)
git checkout `seu-nome`

Faça mudanças, por exemplo, edite `file1.md` e` file2.md` usando o editor de texto

# Adicionar em stage os arquivos alterados
git add file1.md file2.md

# Tirar um snapshot da área de stage (qualquer coisa que tenha sido adicionada)
git commit -m "Meu primeiro commit"

# Suba as mudanças para github
git push --set-upstream origin `seu-nome``
```

