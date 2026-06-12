# Iniciar
git init                        # Cria um repositório novo na pasta

# Status e histórico
git status                      # Vê o que mudou
git log --oneline               # Histórico de commits resumido

# Salvando alterações
git add <arquivo>               # Seleciona um arquivo pra salvar
git add .                       # Seleciona TUDO
git commit -m "mensagem"        # Salva o que foi selecionado

# Branches
git branch                      # Lista as branches
git branch <nome>               # Cria uma branch nova
git checkout <nome>             # Muda pra uma branch
git checkout -b <nome>          # Cria e já muda pra ela

# Desfazendo
git restore <arquivo>           # Descarta mudança não commitada
git reset --soft HEAD~1         # Desfaz commit, mantém no stage
git reset HEAD~1                # Desfaz commit, mantém nos arquivos
git reset --hard HEAD~1         # Desfaz tudo, volta limpo

# Remoto (GitHub)
git remote -v                   # Vê os remotes
git push origin <branch>        # Envia pro GitHub
git pull origin <branch>        # Baixa do GitHub
git clone <url>                 # Copia um repositório existente

git diff                        # Mostra o que mudou e ainda não foi pro stage
git diff --staged               # Mostra o que já está no stage
git diff <branch1> <branch2>    # Compara duas branches

adicionar mais comandos aos poucos (teste pro push de git)
