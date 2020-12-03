# AgoraVai

## Telas do aplicativo
<p float="left">
<img src="https://user-images.githubusercontent.com/10439230/101016668-df493880-3547-11eb-8b33-14a0c7988d1f.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016676-e07a6580-3547-11eb-87a2-d3f184f2b7f3.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016679-e1ab9280-3547-11eb-99e5-92ed51392215.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016654-dbb5b180-3547-11eb-8d9e-c218761f0549.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016683-e1ab9280-3547-11eb-8d9c-3d019a04def9.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016666-deb0a200-3547-11eb-87cb-caaf956e0978.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016685-e2442900-3547-11eb-96f2-0f21dd088e7e.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016688-e2dcbf80-3547-11eb-962e-2c1797a8e030.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016692-e2dcbf80-3547-11eb-87fa-76c7905313d5.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016696-e3755600-3547-11eb-9d41-55c565a875be.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016701-e40dec80-3547-11eb-95ce-43fe4c92f3e8.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016703-e4a68300-3547-11eb-8aea-0726e2b86fe0.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016704-e53f1980-3547-11eb-8f5c-b05b9b097441.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016655-dce6de80-3547-11eb-873a-bf8924159728.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016657-dd7f7500-3547-11eb-8208-f7b5c321532e.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016662-de180b80-3547-11eb-8159-6ca19a64a16d.jpg" width="170">
<img src="https://user-images.githubusercontent.com/10439230/101016664-de180b80-3547-11eb-88da-1a56d0d31d91.jpg" width="170">
</p>

# Sobre o projeto

A ideia do projeto é:

Venda de bebidas para entrega em casa, com suporte a localização através do CEP e
cupons de desconto.

## Observações

O pedido é realizado conforme pode ser verificado na utilização do app como também no video
de apresentação e nas telas, porém não é possível confirmar o mesmo para ser entregue pois não está em produção
com lojas reais.

## Instalador

Para utilizar o aplicativo, basta baixar o apk no link abaixo:

[Android .apk installer](https://drive.google.com/file/d/1fB6Pw7TEKyFJOLPSXXlhcLIs5s7brhOo/view)

## Video de apresentação

[Video de apresentação](https://drive.google.com/file/d/1RRzBgTmP7HFdumk_-dHBbFN2s9sV-bpJ/view?usp=sharing)

## Funcionalidades

* O aplicativo possui um sistema de cadastro e login do usuário onde é inserido também o endereço.
* Existe a tela principal onde são vistas as novidades.
* Existe um cardápio de bebidas separadas por Cervejas, Refrigerantes, Vinhos, Vodkas e Whisky.
* Existe uma tela com as lojas cadastradas
* Existe a função de adicionar as quantidades manualmente no carrinho ou os valores pré-definidos ao adicionar produto.
* Existe a opção de cupons
* Existe a função de inserir o CEP para definir o valor de Frete e local a ser entregue
* Existe a funcionalidade de gerar número do pedido como também a de informar que está sendo preparado
para a entrega


## Iniciando

### Pré-requisitos

Para abrir o projeto em modo desenvolvedor,é necessário ter o flutter e Android Studio instalados.

### Instalando

**Clonando repositório**

```
$ git clone https://github.com/TiagoMotta7/AgoraVai.git

```
**Instalando Android Studio**
1 - Baixar através do site https://developer.android.com/studio
2 - Procedimento de instalação padrão Wizard
3 - Ao abrir a aplicação é necessário criar um Dispositivo Virtual

Para abrir o AVD Manager, siga um dos procedimentos a seguir:

- Selecione Tools > AVD Manager.
- Clique em Create Virtual Device na parte inferior da caixa de diálogo do AVD Manager.
- A página Select Hardware é exibida.
- Selecione um perfil de hardware e clique em Next.
- A página System Image é exibida.
- Selecione a imagem de sistema de um nível de API específico e clique em Next.(O aconselhado é a versão 4.0)
- A página Verify Configuration é exibida.
- Mude as propriedades do AVD conforme necessário e clique em Finish.

**Instalando Flutter no Windows**

1 - Baixar o flutter através do link https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_1.22.4-stable.zip
2 - Extrair o conteúdo do zip de preferência no disco local C. (Exemplo C:\flutter)
3 - Rodar o comando C:\src\flutter>flutter doctor no Prompt de comando como Administrador,
para verificar se existe algo faltando a ser instalado.

## Servidor Firebase

Através do link https://console.firebase.google.com/u/0/?pli=1 realizar login com conta Google
e importar o arquivo google-services.json localizado na pasta Android/app do projeto.


### Executando o aplicativo

Executar o Run dentro do Android com a configuração de emulador realizada, para que possa ver
o aplicativo rodando em tempo real, ou utilizar o apk já fornecido no campo Instalador.


Obrigado!
