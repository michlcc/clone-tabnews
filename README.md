# clone-tabnews
Projeto do curso.dev para ganhar base na experiência completa de um progamador.

### CodeSpace:
Vem com uma base de extensões/utilitarios já prontos para uso neste ambiente, listados abaixo verificação da versão:
- ``node -v``
- ``docker -v``
- ``docker-compose -v``
- ``nvm -v`` (Node Version Manager)

### Dúvidas frequentes:
>[AecioJose]: "codespace é de graça? em algum momento ele vai me cobrar algo? ou ele é de graça ate um certo tamnho ou quantidade de processamento?"
>[Andrei]: "Excelente pergunta, AecioJose! Ele é gratuito, mas possui um limite de uso mensal de 15 GB para armazenamento, e de 120 horas de núcleo de processamento. Você pode conferir mais informações nessa página. 🤝"

### Sobre o Projeto:
- Versão sincronizada do ambiente: (longo prazo de suporte) LTS/Hydrogen. ``nvm install lts/hydrogen`` em seguida ``nvm alias default lts/hydrogen``
- Uso do arquivo ``.nvmrc`` (Run commands -> instruções de inicialização) para deixar esta versão explicita. Assim, ao acessar este arquivo as pessoas que podem contribuir irão saber qual as versões recomendadas neste projeto.
- Criando commits:
. ``git log`` para ver um os commits com o seu hash completo, data, autor e titulo
. ``git log --stat`` para ver os arquivos de cada commits de forma detalhada na quantidade de modificações
. ``git log --oneline`` para ver os commits resumidamente, com inicial do hash e titulo
. ``git status`` para ver como estão os arquivos do repositorio atual indicando se é untracked, modified, staged e commited
. ``git commit --amend`` para voltar um commit anterior substitundo por um novo com seu novo hash

- Commit no repo remoto:
``git commit -m "clear"`` atalho para fazer novos commits.
``git push`` empurrar alterações locais para o origin.
``git push --force`` empurrar de forma forçada alterações locais para o origin.
``git push -f - a`` forma comprimida do comando anterior.
