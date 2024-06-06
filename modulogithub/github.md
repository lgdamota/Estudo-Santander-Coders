
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