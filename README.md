# 📌 API RESTful com Laravel

Este repositório contém um projeto de **API RESTful** desenvolvido em **Laravel**, com o objetivo de fornecer endpoints organizados e escaláveis para aplicações web e mobile.  
O projeto também pode incluir o **frontend** (como submódulo ou pasta separada).

---

## 📂 Estrutura do Projeto

- **`eduteka-course-apirest-backend/`** → Código-fonte do backend em Laravel  
- **`eduteka-course-apirest-frontend/`** → Frontend do projeto (pode estar como submódulo)  
- **`.gitmodules`** → Configuração de submódulos do Git (se houver)  
- **`README.md`** → Documentação do projeto  
- **`LICENSE`** → Licença do projeto  

---

## 🚀 Instalação e Uso (Backend - Laravel)

1. Clone este repositório:
   ```bash
   git clone https://github.com/mthxavier/api-restful-laravel.git

---

Entre na pasta do backend:

cd api-restful-laravel/eduteka-course-apirest-backend
Instale as dependências:

composer install
Crie o arquivo de ambiente .env:

cp .env.example .env
Configure as variáveis de ambiente no .env (banco de dados, chave de app etc).

Gere a chave da aplicação:

php artisan key:generate
Rode as migrations:

php artisan migrate
Inicie o servidor local:

php artisan serve
A API estará disponível em http://localhost:8000 (ou na porta configurada).

🌐 Frontend
Se o frontend estiver configurado como submódulo:

git submodule update --init --recursive
Depois entre na pasta eduteka-course-apirest-frontend, instale as dependências (npm install ou yarn install) e rode o servidor (npm run dev ou equivalente).

Se o frontend for apenas uma pasta comum, basta clonar normalmente e seguir as instruções da pasta.

📡 Exemplos de Endpoints
Alguns exemplos que você pode encontrar ou implementar:

GET /api/users → Lista todos os usuários

POST /api/users → Cria um novo usuário

GET /api/users/{id} → Exibe detalhes de um usuário

PUT /api/users/{id} → Atualiza os dados de um usuário

DELETE /api/users/{id} → Remove um usuário

(Adicione aqui os endpoints específicos do seu projeto)

🔐 Licença
Este projeto está licenciado sob a MIT License.
Veja o arquivo LICENSE para mais informações.

🤝 Contribuições
Contribuições são bem-vindas!
Para contribuir:

Faça um fork do projeto

Crie uma branch para sua feature (git checkout -b feature/nova-feature)

Commit suas mudanças (git commit -m "Adicionando nova feature")

Faça o push da branch (git push origin feature/nova-feature)

Abra um Pull Request
