# Sumário

- [Sumário](#sumário)
- [Testes da API de Usuários](#testes-da-api-de-usuários)
  - [Como Testar](#como-testar)
  - [🚀 Endpoints para Teste](#-endpoints-para-teste)
    - [📍 Criar um Novo Usuário](#-criar-um-novo-usuário)
    - [📍 Buscar Todos os Usuários](#-buscar-todos-os-usuários)
    - [📍 Deletar um Usuário](#-deletar-um-usuário)
- [Testes da API de Posts](#testes-da-api-de-posts)
  - [Como Testar](#como-testar-1)
  - [🚀 Endpoints para Teste](#-endpoints-para-teste-1)
    - [📍 Criar um Novo Post](#-criar-um-novo-post)
    - [📍 Buscar Todos os Posts](#-buscar-todos-os-posts)
    - [📍 Deletar um Post](#-deletar-um-post)
- [Testes da API de Mensagens](#testes-da-api-de-mensagens)
  - [Como Testar](#como-testar-2)
  - [🚀 Endpoints para Teste](#-endpoints-para-teste-2)
    - [📍 Criar uma Nova Mensagem](#-criar-uma-nova-mensagem)
    - [📍 Listar Todas as Mensagens](#-listar-todas-as-mensagens)
    - [📍 Buscar uma Mensagem Específica](#-buscar-uma-mensagem-específica)
    - [📍 Deletar uma Mensagem](#-deletar-uma-mensagem)
- [Testes da API de Membros da Comunidade](#testes-da-api-de-membros-da-comunidade)
  - [Como Testar](#como-testar-3)
  - [🚀 Endpoints para Teste](#-endpoints-para-teste-3)
    - [📍 Criar um Novo Membro na Comunidade](#-criar-um-novo-membro-na-comunidade)
    - [📍 Listar Todos os Membros da Comunidade](#-listar-todos-os-membros-da-comunidade)
    - [📍 Buscar um Membro Específico da Comunidade](#-buscar-um-membro-específico-da-comunidade)
    - [📍 Deletar um Membro da Comunidade](#-deletar-um-membro-da-comunidade)
- [Testes da API de Curtidas](#testes-da-api-de-curtidas)
  - [Como Testar](#como-testar-4)
  - [🚀 Endpoints para Teste](#-endpoints-para-teste-4)
    - [📍 Criar uma Nova Curtida](#-criar-uma-nova-curtida)
- [Testes da API de Comunidades](#testes-da-api-de-comunidades)
  - [Como Testar](#como-testar-5)
  - [🚀 Endpoints para Teste](#-endpoints-para-teste-5)
    - [📍 Criar uma Nova Comunidade](#-criar-uma-nova-comunidade)
    - [📍 Listar Todas as Comunidades](#-listar-todas-as-comunidades)
    - [📍 Buscar uma Comunidade Específica](#-buscar-uma-comunidade-específica)
    - [📍 Deletar uma Comunidade](#-deletar-uma-comunidade)
- [Testes da API de Comentários](#testes-da-api-de-comentários)
  - [Como Testar](#como-testar-6)
  - [🚀 Endpoints para Teste](#-endpoints-para-teste-6)
    - [📍 Criar um Novo Comentário](#-criar-um-novo-comentário)
    - [📍 Deletar um Comentário](#-deletar-um-comentário)
    - [📍 Listar Todos os Comentários](#-listar-todos-os-comentários)
- [Testes da API de Classificações de Posts](#testes-da-api-de-classificações-de-posts)
  - [Como Testar](#como-testar-7)
  - [🚀 Endpoints para Teste](#-endpoints-para-teste-7)
    - [📍 Listar Todas as Classificações de Posts](#-listar-todas-as-classificações-de-posts)
    - [📍 Listar uma Classificação Específica de Post](#-listar-uma-classificação-específica-de-post)
    - [📍 Criar uma Nova Classificação de Post](#-criar-uma-nova-classificação-de-post)
- [Testes da API de Amizades](#testes-da-api-de-amizades)
  - [Como Testar](#como-testar-8)
  - [🚀 Endpoints para Teste](#-endpoints-para-teste-8)
    - [📍 Listar Todas as Amizades](#-listar-todas-as-amizades)
    - [📍 Criar uma Nova Amizade](#-criar-uma-nova-amizade)
    - [📍 Remover uma Amizade](#-remover-uma-amizade)

---

# Testes da API de Usuários

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar um Novo Usuário

- **Rota**:
  - `POST http://localhost:3000/usuario`

- **O que esperar**:
  - **201 Created** se o usuário for criado com sucesso.
  - **400 Bad Request** se faltar algum campo obrigatório.

### 📍 Buscar Todos os Usuários

- **Rota**:
  - `GET http://localhost:3000/usuario`

- **O que esperar**:
  - **200 OK** com uma lista de usuários cadastrados.
  - **404 Not Found** se não houver usuários cadastrados.

### 📍 Deletar um Usuário

- **Rota**:
  - `DELETE http://localhost:3000/usuario/:id`

- **Parâmetro**:
  - `id` (String) - O ID do usuário a ser removido.

- **O que esperar**:
  - **200 OK** se o usuário for deletado com sucesso.
  - **404 Not Found** se o usuário não existir.

---

# Testes da API de Posts

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar um Novo Post

- **Rota**:
  - `POST http://localhost:3000/Post`

- **O que esperar**:
  - **201 Created** se o post for criado com sucesso.
  - **400 Bad Request** se faltar algum campo obrigatório.

### 📍 Buscar Todos os Posts

- **Rota**:
  - `GET http://localhost:3000/Post`

- **O que esperar**:
  - **200 OK** com uma lista de posts cadastrados.
  - **404 Not Found** se não houver posts cadastrados.

### 📍 Deletar um Post

- **Rota**:
  - `DELETE http://localhost:3000/Post/:id`

- **Parâmetro**:
  - `id` (String) - O ID do post a ser removido.

- **O que esperar**:
  - **200 OK** se o post for deletado com sucesso.
  - **404 Not Found** se o post não existir.

---

# Testes da API de Mensagens

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar uma Nova Mensagem

- **Rota**:
  - `POST http://localhost:3000/mensagem`

- **O que esperar**:
  - **201 Created** se a mensagem for criada com sucesso.
  - **400 Bad Request** se faltar algum campo obrigatório.

### 📍 Listar Todas as Mensagens

- **Rota**:
  - `GET http://localhost:3000/mensagem`

- **O que esperar**:
  - **200 OK** com uma lista de mensagens.
  - **404 Not Found** se não houver mensagens cadastradas.

### 📍 Buscar uma Mensagem Específica

- **Rota**:
  - `GET http://localhost:3000/mensagem/:id`

- **Parâmetro**:
  - `id` (String) - O ID da mensagem a ser consultada.

- **O que esperar**:
  - **200 OK** com os detalhes da mensagem.
  - **404 Not Found** se a mensagem não existir.

### 📍 Deletar uma Mensagem

- **Rota**:
  - `DELETE http://localhost:3000/mensagem/:id`

- **Parâmetro**:
  - `id` (String) - O ID da mensagem a ser removida.

- **O que esperar**:
  - **200 OK** se a mensagem for deletada com sucesso.
  - **404 Not Found** se a mensagem não existir.

---

# Testes da API de Membros da Comunidade

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar um Novo Membro na Comunidade

- **Rota**:
  - `POST http://localhost:3000/MembroComunidade`

- **O que esperar**:
  - **201 Created** se o membro for adicionado com sucesso.
  - **400 Bad Request** se faltar algum campo obrigatório.

### 📍 Listar Todos os Membros da Comunidade

- **Rota**:
  - `GET http://localhost:3000/MembroComunidade`

- **O que esperar**:
  - **200 OK** com uma lista de membros da comunidade.
  - **404 Not Found** se não houver membros cadastrados.

### 📍 Buscar um Membro Específico da Comunidade

- **Rota**:
  - `GET http://localhost:3000/MembroComunidade/:id`

- **Parâmetro**:
  - `id` (String) - O ID do membro a ser consultado.

- **O que esperar**:
  - **200 OK** com os detalhes do membro.
  - **404 Not Found** se o membro não existir.

### 📍 Deletar um Membro da Comunidade

- **Rota**:
  - `DELETE http://localhost:3000/MembroComunidade/:id`

- **Parâmetro**:
  - `id` (String) - O ID do membro a ser removido.

- **O que esperar**:
  - **200 OK** se o membro for deletado com sucesso.
  - **404 Not Found** se o membro não existir.

---

# Testes da API de Curtidas

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar uma Nova Curtida

- **Rota**:
  - `POST http://localhost:3000/curtidas`

- **O que esperar**:
  - **201 Created** se a curtida for criada com sucesso.
  - **400 Bad Request** se a curtida já existir para o mesmo post.
  - **500 Internal Server Error** em caso de erro no servidor.

---

# Testes da API de Comunidades

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar uma Nova Comunidade

- **Rota**:
  - `POST http://localhost:3000/Comunidade`

- **O que esperar**:
  - **201 Created** se a comunidade for criada com sucesso.
  - **400 Bad Request** se algum campo obrigatório estiver faltando.

### 📍 Listar Todas as Comunidades

- **Rota**:
  - `GET http://localhost:3000/Comunidade`

- **O que esperar**:
  - **200 OK** com a lista de comunidades cadastradas.
  - **404 Not Found** se não houver comunidades cadastradas.

### 📍 Buscar uma Comunidade Específica

- **Rota**:
  - `GET http://localhost:3000/Comunidade/:id`

- **Parâmetro**:
  - `id` (String) - O ID da comunidade a ser consultada.

- **O que esperar**:
  - **200 OK** com os detalhes da comunidade.
  - **404 Not Found** se a comunidade não existir.

### 📍 Deletar uma Comunidade

- **Rota**:
  - `DELETE http://localhost:3000/Comunidade/:id`

- **Parâmetro**:
  - `id` (String) - O ID da comunidade a ser removida.

- **O que esperar**:
  - **200 OK** se a comunidade for deletada com sucesso.
  - **404 Not Found** se a comunidade não existir.

---

# Testes da API de Comentários

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar um Novo Comentário

- **Rota**:
  - `POST http://localhost:3000/comentario`

- **O que esperar**:
  - **201 Created** se o comentário for criado com sucesso.
  - **400 Bad Request** se faltar algum campo obrigatório.

### 📍 Deletar um Comentário

- **Rota**:
  - `DELETE http://localhost:3000/comentario/:id`

- **Parâmetro**:
  - `id` (String) - O ID do comentário a ser removido.

- **O que esperar**:
  - **200 OK** se o comentário for deletado com sucesso.
  - **404 Not Found** se o comentário não existir.

### 📍 Listar Todos os Comentários

- **Rota**:
  - `GET http://localhost:3000/comentario`

- **O que esperar**:
  - **200 OK** com uma lista de todos os comentários.
  - **404 Not Found** se não houver comentários cadastrados.

---

# Testes da API de Classificações de Posts

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Listar Todas as Classificações de Posts

- **Rota**:
  - `GET http://localhost:3000/classificacoes`

- **O que esperar**:
  - **200 OK** com uma lista de todas as classificações.
  - **404 Not Found** se não houver classificações.

### 📍 Listar uma Classificação Específica de Post

- **Rota**:
  - `GET http://localhost:3000/classificacoes/:id`

- **Parâmetro**:
  - `id` (String) - O ID da classificação a ser listada.

- **O que esperar**:
  - **200 OK** com a classificação específica.
  - **404 Not Found** se a classificação não for encontrada.

### 📍 Criar uma Nova Classificação de Post

- **Rota**:
  - `POST http://localhost:3000/classificacoes`

- **O que esperar**:
  - **201 Created** se a classificação for criada com sucesso.
  - **400 Bad Request** se faltar algum campo obrigatório.

---

# Testes da API de Amizades

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Listar Todas as Amizades

- **Rota**:
  - `GET http://localhost:3000/amigos`

- **O que esperar**:
  - **200 OK** com uma lista de todas as amizades.
  - **404 Not Found** se não houver amizades.

### 📍 Criar uma Nova Amizade

- **Rota**:
  - `POST http://localhost:3000/amigos`

- **O que esperar**:
  - **201 Created** se a amizade for criada com sucesso.
  - **400 Bad Request** se faltar algum campo obrigatório.

### 📍 Remover uma Amizade

- **Rota**:
  - `DELETE http://localhost:3000/amigos/:id`

- **Parâmetro**:
  - `id` (String) - O ID da amizade a ser removida.

- **O que esperar**:
  - **200 OK** se a amizade for removida com sucesso.
  - **404 Not Found** se a amizade não for encontrada.
