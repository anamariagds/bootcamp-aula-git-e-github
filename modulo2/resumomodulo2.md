##Criando seu primeiro repositório e aprendendo os comandos mais utilizados
1 - crie o repositorio no github e preencha as informações solicitadas
2 - (na sua maquina) abra o repositorio local no terminal ou editor de codigo de preferencia,
    execute  **git init** - para o git configurar uma nova estrutura de controle de versão neste diretorio.
3 - Depois execute **git remote add origin < aqui você informa o link de conxão do repostorio no github, que é gerado quando você cria o repo lá >**

##Você também pode clonar um repositorio já existente.
**git clone url-do-repo**

***Neste módulo também praticamos alguns do comando mais usados no versioamento de software com git***
**git status** - informa os arquivos e pastas que não estão em conformidade, comparando seu
repositório local e remoto.
**git add .** ou **git add <seguido do nome do arquivo específico que você quer incluir.>**  - inclue todos os arquivos e modificações no diretório para o staging area do git.
**git commit** - cria um comentario no repositório git, registrando as mudanças que foram adicionadas ao staging.
**git push** - envia os commits locais para um repositório remoto. Ele sincroniza as alterações feitas no seu repositório local com o repositori remoto.
**git pull** - Atualiza o repositório local com as ultimas alterações do repositório remoto
