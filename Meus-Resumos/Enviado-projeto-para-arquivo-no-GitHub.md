
# Este guia fornece os passos necessários para enviar um repositório para o GitHub 

1. Instale o Git em sua máquina, caso ainda não tenha feito isso.

- Para utilizar o git e enviar seus arquivos para o github, é preciso configurar em sua máquina seu usuário e email do github com os comandos ``` git config --global user.name "yourname" ``` e  ``` git config --global user.email "youremail@email.com" ```

2. Crie um Repositório no GitHub
- Faça login na sua conta do GitHub 
- No canto superior direito da página inicial, clique no botão "+", e escolha "New repository".
- Preencha o nome do repositório, uma descrição opcional, escolha se ele será público ou privado e selecione a opção de criar um arquivo README.md, caso 
 deseje(isso é util para fornecer informações básicas sobre o seu projeto)
- Clique no botão "Create repository".

3. Abra o terminal ou prompt de comando e navegue até a pasta do projeto que deseja enviar para o GitHub.

4. Inicialize o Git dentro dessa pasta usando o comando ``` git init ```

5. Adicione os arquivos do projeto ao Git usando o comando  ``` git add . ``` 

6. Faça um commit dos arquivos adicionados usando o comando  ```git commit -m "Mensagem de commit" ``` 

7. Adicione o repositório remoto do GitHub como destino para enviar seus arquivos usando o comando ```git remote add origin <URL do repositório do github> ```  

8. Envie seus arquivos para o repositório remoto no GitHub usando o comando ```git push -u origin master ```  

Suas alterações agora foram enviadas para o repositório remoto no GitHub. Você pode verificar o GitHub para confirmar que seu projeto foi enviado com sucesso.
