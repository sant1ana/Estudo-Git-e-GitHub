# Anotações Git e GitHub 📝
 :pushpin: Repositório criado para armazenar meus resumos de estudo do Git e GitHub para sanar futuras dúvidas. <br> <br>

## O que é Git? <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg" width = "40px"/>

Git  é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, é uma ferramenta que ajuda a controlar e gerenciar todas as mudanças feitas nos seus projetos, permite que você trabalhe com outras pessoas de forma eficaz e fornece um histórico seguro das suas criações. E um de seus diferenciais é que, além de que cada diretório (chamado de
repositório) possuir um histórico completo das alterações realizadas, ele é capaz de sincronizar um
repositório local a um remoto, possibilitando que também seja acessado em outro computador e na nuvem
(internet). <br> <br>

- [Link para download do Git](https://git-scm.com/)  <br> <br>




## O que GitHub? <img src="https://github.com/duribeiro/duribeiro/blob/main/assets/GitHub.png?raw=true" width = "40px"/>



GitHub é um sistema de hospedagem para versionamento de projetos e de códigos para desenvolvedores. É
possível trabalhar em projetos colaborativos com desenvolvedores de todo o mundo, e ter todas as versões
do seu código disponíveis online. <br> <br>


# :dart: Comandos funcionais do Git e Github

## Comandos do Git:


1. ```git init```:  irá criar um repositório novo em branco e, a partir daí, será possível armazenar seu código fonte, alterar, salvar e gerenciar todas as alterações feitas nesse repositório..



2. `git add [nome do arquivo]`: Para incluir um arquivo especifico é preciso determinar o nome do arquivo novo/modificado


3. `git add .`: Para incluir todos os novos  arquivos modificados de uma unica vez ao stage para serem commitadas.

4. `git reset . `: remove todos os arquivos do palco


5. `git commit -m "descrição da alteração"`: realiza o commit dos rquivos modificados no repositório com uma mensagem descritiva.



6. `git status`: Lista as últimas modificações dentro do repositório



7. `git branch`: Lista todas as branches locais.



8. `git branch -M main`: troca o nome da branch de master para main



9. `git remote -v`: verifica o status do link do repositório



10. `git branch [nome  da branch]`: Cria uma nova branch.



11. `git checkout [nome da branch]`: entra na branch especificada.

12. `git checkout [nome da branch] [nome do arquivo]`: realiza o "merge" do arquivo específico na branch atual



13. `git pull`: Atualiza seu repositório local com as alterações do repositório remoto.
    

14. `git pull main`: puxa as últimas  versões da branch informada



15. `git push`: Envia suas alterações locais para o repositório remoto.





16. `git log`: lista o histórico de commits.



17. `git diff`: Mostra as diferenças entre os arquivos no stage e os arquivos no último commit.

18. `git rm [nome do arquivo]`: Remover arquivo

<br> 

- [Link comandos básicos do Git](http://comandosgit.github.io/)

<br> <br> 


## Comandos do GitHub:

1. `git remote add origin [URL]`: Conecta seu repositório Git local a um repositório remoto no GitHub.



2. `git push -u origin [branch]`: Envia a branch local para o repositório remoto pela primeira vez.



3. `git pull origin [ nome da branch]`: Atualiza sua branch local com as alterações da branch remota.



4. `git clone [URL]`: Clona um repositório GitHub para sua máquina local.



5. `git fork`: Cria uma cópia pessoal de um repositório GitHub em sua conta.



6. `git pull request`: Abre uma solicitação de pull (pull request) para sugerir alterações em um repositório.



7. `git merge [ nome da branch]` : Realiza o merge  da branch atual com a branch indicada .



8. `git blame [arquivo]`: Mostra quem fez cada alteração em um arquivo específico.



9. `git stash`: Salva temporariamente alterações não commitadas para trabalhar em outra tarefa.



10. `git tag [nome]`: Cria uma tag para marcar versões específicas do seu código.

<br> <br>





##  :bulb: Documentação para obter mais detalhes sobre cada comando e suas opções 
- [documentação do Git](https://git-scm.com/doc)
- [documentação do GitHub](https://docs.github.com/)
