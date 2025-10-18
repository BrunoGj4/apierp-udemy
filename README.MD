[alias]
co = checkout
br = branch
cm = commit -m
st = status
lg = log --oneline --graph --all


git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.cm 'commit -m'
git config --global alias.st status
git config --global alias.lg 'log --oneline --graph --decorate'
___
main            # Produção (release estável)
develop         # Integração de funcionalidades em desenvolvimento
feature/*       # Novas funcionalidades
bugfix/*        # Correções específicas
hotfix/*        # Correções urgentes em produção