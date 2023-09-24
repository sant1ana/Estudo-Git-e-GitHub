
Este guia fornece os passos necessários para enviar um projeto para um repositório no GitHub 

## Passo 1: Crie um Repositório no GitHub
1. Faça login na sua conta do GitHub 
2. No canto superior direito da página inicial, clique no botão "+", e escolha "New repository".
3. Preencha o nome do repositório, uma descrição opcional, escolha se ele será público ou privado e selecione a opção de criar um arquivo README.md, caso deseje(isso é util para fornecer informações básicas sobre o seu projeto)
4. Clique no botão "Create repository".

## Passo 2:  Inicialize um Repositório Git Local 

1. vá no arquivo (pasta) do seu computador que você quer enviar para o repositório e abra o git basch 
2. e digite o comando ``` git init ``` para inicializar um novo repositório Git local.
3.Depois digite o comando ``` git status ``` para ver  se aparece todos os aquivos que vc quer enviar

## Passo 3: Adicione e Confirme suas Alterações Locais
1- Use o comando ``` git add . ``` para adicionar os arquivos ao controle de versão. 
2- Depois dê o comando ``` git status ``` para confirmar se todos os arquivos foi adcionado (se ficou todos verdes tá ok)
3- Faça um commit das alterações com uma mensagem descritiva usando o comando ``` git commit -m "Mensagem descritiva das alterações" ```

## Passo 4: Conecte seu Repositório Local ao Repositório Remoto no 

Agora, você precisa configurar seu repositório local para se conectar ao repositório remoto no GitHub que você criou no Passo 1. Use o seguinte comando ``` git remote add origin <URL do repositorio no github>  ```

## Passo 5: Envie suas Alterações para o Repositório Remoto

Finalmente, envie suas alterações para o repositório remoto usando o comando  ``` git push -u origin main  ```

Suas alterações agora foram enviadas para o repositório remoto no GitHub. Você pode verificar o GitHub para confirmar que seu projeto foi enviado com sucesso.