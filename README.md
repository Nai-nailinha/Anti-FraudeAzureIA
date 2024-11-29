# **Análise de Documentos Anti-fraude com AzureAI**

## **Criar um Storage Account:**

- No marketPlace, pesquisar storage account e criar na opção abaixo:

![image](https://github.com/user-attachments/assets/568bdc2c-94bb-4bb2-9765-99dbb4bd9d13)

- Criar o recurso como Azure Files - Standard - LRS 
Após configurar conforme tela abaixo, clicar em Revisar + Criar

![image](https://github.com/user-attachments/assets/d336b3a3-8960-4ccf-a689-1e38ddffc8a9)

- Na próxima tela, no final da página, clicar em CRIAR:

![image](https://github.com/user-attachments/assets/923db8cc-7e43-4b37-b856-797c048806f0)

## **Criar um document intelligence:**

- Volte ao MarketPlace e escreva na busca ***document intelligence*** e escolha o recurso abaixo para criar:

![image](https://github.com/user-attachments/assets/a8a380f9-4e4f-4806-bdb3-7835d633f800)

- Nomei e selecione Standard
- Clique em Examinar e criar no menu superior e em seguida em criar no inferior da página:
![image](https://github.com/user-attachments/assets/4eeea7bb-bc21-4f08-a168-f0200fd30715)
![image](https://github.com/user-attachments/assets/1f9e4545-7b06-4e56-9991-59a50cf7d18a)

## **Configurar Storage Account:** 

- 1- Selecione no grupo de recursos o Storage account criado.
- 2- Clique em navegador de armazenamento
- 3- Clique em adicionar um contêiner
- 4- Escolha o nome do Containêr
- 5- Clique em CRIAR

![image](https://github.com/user-attachments/assets/d410c42f-0e7f-474a-9d0e-ef5a20432b35)

- Após criado, clique no menu esquerno na opção visão geral do Blob e, no serviço blob, clique em desabilitado ao lado de acesso anônimo ao blob:

![image](https://github.com/user-attachments/assets/929c8fd9-6a0f-48f6-9ee0-ae926f09ba6a)

 - Habilite a opção ***Permitir acesso anônimo ao Blob*** e clique em salvar

![image](https://github.com/user-attachments/assets/0ef92b99-e9c0-4c97-8e34-e1a5d8634586)

- No menu esquerdo da tela, vá até segurança + rede e clique em *Chave de acesso* e copie a chave e o nome da storage account para usar posteriormente.

![image](https://github.com/user-attachments/assets/1caca0c7-ecba-47c1-8a73-681ba73de04a)

- No menu esquerdo vá até navegador de armazenamento e selecione o container de blog criado, vá em alterar nível de acesso e selecione acesso de leitura anonimo para blogs:

![image](https://github.com/user-attachments/assets/3bba6a9c-ab15-455d-ae16-e0c4dfa9042d)

- Clique em Carregar e adicione uma imagem baixada ne web de cartão

![image](https://github.com/user-attachments/assets/b114f439-7fce-4eeb-8347-49e9bbc3036a)

## **Configurar document intelligence:** 

- Abrir o document e selecionar no menu esquerdo *Gerenciamento de recurso* -> *Chaves de ponto de acesso*.
- Salvar o ENDPOIN e a KEY

![image](https://github.com/user-attachments/assets/ceb9d9f6-de4f-4db7-af41-ab90bf13df11)









