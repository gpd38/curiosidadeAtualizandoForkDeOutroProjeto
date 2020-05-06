# Atualizando Fork de um Projeto 
Os comandos a seguir devem ser utilizados quando você realiza um fork de outro projeto que possui atualizações novas.

#### Configurando um remote
- Listar remotes existentes: <code>git remote -v</code>

- Criar novo remote chamado upstream apontando para o repositório de origem: <code>git remote add upstream "endereço do projeto de origem"</code>

#### Sincronizando Fork
- Baixe as atualizações do repositório de origem: <code>git fetch upstream</code>

- Mudar para a branch master: <code>git checkout master</code>

#### Realizar o merge
- Unir as atualizações com o projeto local: <code>git merge upstream/master</code>
