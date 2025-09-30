📱 Frontend - Celulares

Este projeto é um frontend simples desenvolvido em HTML, CSS e Bootstrap, com integração via JavaScript (fetch API) para consumir a API REST de celulares.

🚀 Funcionalidades

📌 Cadastro de celulares com imagem.

📌 Listagem de celulares com exibição padronizada das imagens.

📌 Busca por marca utilizando @RequestParam.

📌 Edição de celulares via modal, com preenchimento automático dos dados ao buscar por ID.

📌 Exclusão de celulares com atualização automática da lista.

🛠️ Tecnologias Utilizadas

HTML5

CSS3

Bootstrap 5

JavaScript (fetch API)

📂 Estrutura do Projeto
frontend/
│── index.html   # Página principal com listagem, formulário e modal
│── style.css    # Estilos customizados

🔗 Integração com a API

Este frontend se comunica com a API de celulares através dos seguintes endpoints:

POST /celulares → Cadastrar celular

GET /celulares → Listar todos os celulares

GET /celulares/{id} → Buscar celular por ID

GET /celulares/buscarMarca?marca=XYZ → Buscar celulares por marca

PUT /celulares/{id} → Atualizar celular

DELETE /celulares/{id} → Excluir celular
![most](https://github.com/user-attachments/assets/d3f9c45c-1cdb-4cce-8ebf-edc3480c9d44)
