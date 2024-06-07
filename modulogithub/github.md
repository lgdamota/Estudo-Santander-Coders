
# Santander Coders
# Versionamento com Git

O *Git* é um sistema de controle de versão distribuído. Ele permite que você registre alterações em seus arquivos ao longo do tempo. Cada alteração é registrada como um “snapshot” (ou “foto”) do estado do projeto naquele momento. Esses snapshots são armazenados em um histórico, permitindo que você recupere versões anteriores do código.

# GitHub

O *GitHub* é uma plataforma de hospedagem de repositórios Git na nuvem. Ele facilita a colaboração entre desenvolvedores, permitindo que várias pessoas trabalhem no mesmo projeto. Além disso, o GitHub oferece recursos como controle de acesso, gerenciamento de problemas e integração contínua.

# Comandos Básicos do Git

- git status: Verifica o status dos arquivos no seu repositório local. Ele mostra quais arquivos foram modificados, adicionados ou excluídos.
- git add nome-do-arquivo: Adiciona um arquivo específico para ser rastreado pelo Git.
- git commit -m "Mensagem descritiva": Cria um snapshot (commit) com as alterações feitas. A mensagem deve descrever o que foi feito.
- git push origin main: Envia suas alterações para o repositório remoto no GitHub.

# Dicas Adicionais

- Use git log para ver o histórico de commits.
- Crie branches para desenvolver recursos separadamente.
- Resolva conflitos usando git merge ou git rebase.
- Comando CMD
- CD - entrar

- Git status (verifica se o arquivo ja foi rastreado pelo git)
- Git add (finalizar e salvar no git) 
- Git log (traz o histórico dos commits)
- Git fetch (busca as alterações)
- Git pull busca e mescla as alterações
- Ctrl L - limpar terminal
- ctrl j - abrir terminal

# Criando e Subindo um Novo Repositório no GitHub

1. *Crie um novo repositório no GitHub*
   - Vá para GitHub e faça login na sua conta.
   - Clique em New repository no menu à esquerda.
   - Dê um nome ao seu repositório, adicione uma descrição (opcional), escolha se deseja torná-lo público ou privado e clique em Create repository.

2. *Clone o repositório para sua máquina local*
   - Copie a URL do repositório que você acabou de criar.
   - Abra o terminal no seu computador.
   - Navegue até o diretório onde deseja clonar o repositório.
   - Digite git clone [URL do repositório] e pressione Enter.

3. *Adicione arquivos ao repositório*
   - Navegue até o diretório do repositório clonado.
   - Adicione arquivos ou faça alterações nos arquivos existentes.
   - Quando terminar, digite git status para ver quais alterações foram feitas.

4. *Faça commit das suas alterações*
   - Digite git add . para adicionar todas as alterações feitas.
   - Em seguida, digite git commit -m "Sua mensagem de commit" para criar um novo commit com suas alterações.

5. *Suba suas alterações para o GitHub*
   - Digite git push origin main para enviar suas alterações para o repositório remoto no GitHub. 
   .

# Git Restore
O comando git restore é usado para restaurar arquivos no diretório de trabalho ou na área de preparação (índice) para o estado em que estavam no último commit. Aqui estão os detalhes:

Restauração do diretório de trabalho (working tree):
Quando você executa git restore <caminho>, o Git restaura o arquivo especificado no diretório de trabalho para o estado do último commit.
Por exemplo, se você fez alterações em um arquivo e deseja desfazê-las, use git restore <caminho>.
Restauração da área de preparação (index):
Para restaurar arquivos apenas na área de preparação (index), use git restore --staged <caminho>.
Isso remove as alterações do índice, mas mantém as alterações no diretório de trabalho.
Restauração de um commit específico:
Você pode usar git restore --source=<commit> <caminho> para restaurar arquivos do commit especificado.
Substitua <commit> pelo hash do commit desejado.

# Git Branch

## O que é um Branch no Git?
Um branch no Git é como um ramo de uma árvore. Ele é um ponteiro móvel para um commit específico no histórico do seu projeto. Aqui estão os pontos principais:

Utilidade do Branch:
Permite que você trabalhe em diferentes partes do projeto sem afetar o branch principal (geralmente chamado de “master” ou “main”).
Útil para adicionar novos recursos, corrigir erros ou experimentar sem comprometer o código estável.
Criando um Branch Local:
Para criar um novo branch local, use o comando:
git branch nome-do-branch

Isso cria um novo branch chamado nome-do-branch apontando para o mesmo commit atual.
Acessando um Branch Criado:
Para alternar para o novo branch, use:
git checkout nome-do-branch

Agora você está trabalhando no novo branch.
Mesclando Branches:
Quando terminar de trabalhar no branch, você pode mesclá-lo de volta ao branch principal (master ou main) usando:
git merge nome-do-branch

Isso incorpora as alterações do branch no principal.

<img src="https://media.discordapp.net/attachments/1087815765010415748/1248436193054429329/a469b294-42e1-45c6-a020-7523b4dbc041.png?ex=6663a84f&is=666256cf&hm=55aad6341ec1f1c9ccf1d8b9430ed936ede813919c2ef4825b47137a507a7c00&=&format=webp&quality=lossless" alt="Árvore Branch">