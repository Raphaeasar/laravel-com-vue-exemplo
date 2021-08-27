# Laravel-com-Vue.js
Projeto Prático de Laravel + JWT + Vue JS + Axios + Vuex + VueRouter + Boas Práticas

Primeiro passo, clonar o projeto:

# Clonar
git clone https://github.com/carlosfgti/laravel-com-vue-exemplo.git

# Acessar
cd laravel-com-vue-exemplo

Configuração - Backend
# Instalar dependências do projeto
composer install

# Configurar variáveis de ambiente
cp .env.example .env
php artisan key:generate

# Configuração do JWT
php artisan jwt:secret

# Criar migrations (tabelas e Seeders)
php artisan migrate --seed

# Criar link simbólico storage/app/public para public/storage/
php artisan storage:link
Login
O usuário de teste é:

email:    carlos@especializati.com.br
password: 123456
Configuração - Frontend
# Atualizar dependências
npm install

# Rodar em ambiente local localhost:8080
npm run dev

# Rodar em ambiente de produção
npm run build
