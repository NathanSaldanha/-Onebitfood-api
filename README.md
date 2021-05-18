# Projeto OneBitFood 🍔

O OneBitFood é um app expirado no Ifood utilizando outras tecnologias, aqui iremos trabalhar no servidor da aplicação.

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina 
as seguintes ferramentas:

- [Rails 6.1.3](https://rubyonrails.org/)
- [Ruby 3.0.1](https://www.ruby-lang.org/pt/)
- [Git](https://git-scm.com)

Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando o Back End (servidor)

```bash
# Ambiente de Desenvolvimento
$ rvm install 3.0.1 
$ rvm use 3.0.1
$ gem install bundler

# Clone este repositório
$ git clone <https://github.com/NathanSaldanha/Onebitfood-api.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd Onebitfood-api

# Instale as dependências
$ bundle install
$ rake db:create db:migrate db:seed

# Execute a aplicação
$ rails s

# O servidor inciará na porta:3000 - acesse <http://localhost:3000>
```

### 📃 Documentação dos endpoints
- Ferramenta: [Postman](https://www.postman.com/)
- Endpoints: [Routes](https://documenter.getpostman.com/view/10378249/TzRPk9yD)

### 🛠 Tecnologias

- [Rails](https://rubyonrails.org/)
- [Ruby](https://www.ruby-lang.org/pt/)
- [Postman](https://www.postman.com/)
