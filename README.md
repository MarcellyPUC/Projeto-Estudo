# Sumário

- [API de Usuários](#testes-da-api-de-usuários)
- [API de Posts](#testes-da-api-de-posts)
- [API de Mensagens](#testes-da-api-de-mensagens)
- [API de Membros da Comunidade](#testes-da-api-de-membros-da-comunidade)
- [API de Curtidas](#testes-da-api-de-curtidas)
- [API de Comunidades](#testes-da-api-de-comunidades)
- [API de Comentários](#testes-da-api-de-comentários)
- [API de Classificações de Posts](#testes-da-api-de-classificações-de-posts)
- [API de Amizades](#testes-da-api-de-amizades)

---

# Testes da API de Usuários

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar um Novo Usuário

- **Rota**: `POST http://localhost:3000/usuario`

### 📍 Buscar Todos os Usuários

- **Rota**: `GET http://localhost:3000/usuario`

### 📍 Deletar um Usuário

- **Rota**: `DELETE http://localhost:3000/usuario/:id`
- **Parâmetro**: `id` (String) - O ID do usuário a ser removido.

---

# Testes da API de Posts

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar um Novo Post

- **Rota**: `POST http://localhost:3000/Post`

### 📍 Buscar Todos os Posts

- **Rota**: `GET http://localhost:3000/Post`

### 📍 Deletar um Post

- **Rota**: `DELETE http://localhost:3000/Post/:id`
- **Parâmetro**: `id` (String) - O ID do post a ser removido.

---

# Testes da API de Mensagens

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar uma Nova Mensagem

- **Rota**: `POST http://localhost:3000/mensagem`

### 📍 Listar Todas as Mensagens

- **Rota**: `GET http://localhost:3000/mensagem`

### 📍 Buscar uma Mensagem Específica

- **Rota**: `GET http://localhost:3000/mensagem/:id`
- **Parâmetro**: `id` (String) - O ID da mensagem a ser consultada.

### 📍 Deletar uma Mensagem

- **Rota**: `DELETE http://localhost:3000/mensagem/:id`
- **Parâmetro**: `id` (String) - O ID da mensagem a ser removida.

---

# Testes da API de Membros da Comunidade

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar um Novo Membro na Comunidade

- **Rota**: `POST http://localhost:3000/MembroComunidade`

### 📍 Listar Todos os Membros da Comunidade

- **Rota**: `GET http://localhost:3000/MembroComunidade`

### 📍 Buscar um Membro Específico da Comunidade

- **Rota**: `GET http://localhost:3000/MembroComunidade/:id`
- **Parâmetro**: `id` (String) - O ID do membro a ser consultado.

### 📍 Deletar um Membro da Comunidade

- **Rota**: `DELETE http://localhost:3000/MembroComunidade/:id`
- **Parâmetro**: `id` (String) - O ID do membro a ser removido.

---

# Testes da API de Curtidas

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar uma Nova Curtida

- **Rota**: `POST http://localhost:3000/curtidas`

---

# Testes da API de Comunidades

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar uma Nova Comunidade

- **Rota**: `POST http://localhost:3000/Comunidade`

### 📍 Listar Todas as Comunidades

- **Rota**: `GET http://localhost:3000/Comunidade`

### 📍 Buscar uma Comunidade Específica

- **Rota**: `GET http://localhost:3000/Comunidade/:id`
- **Parâmetro**: `id` (String) - O ID da comunidade a ser consultada.

### 📍 Deletar uma Comunidade

- **Rota**: `DELETE http://localhost:3000/Comunidade/:id`
- **Parâmetro**: `id` (String) - O ID da comunidade a ser removida.

---

# Testes da API de Comentários

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Criar um Novo Comentário

- **Rota**: `POST http://localhost:3000/comentario`

### 📍 Deletar um Comentário

- **Rota**: `DELETE http://localhost:3000/comentario/:id`
- **Parâmetro**: `id` (String) - O ID do comentário a ser removido.

### 📍 Listar Todos os Comentários

- **Rota**: `GET http://localhost:3000/comentario`

---

# Testes da API de Classificações de Posts

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Listar Todas as Classificações de Posts

- **Rota**: `GET http://localhost:3000/classificacoes`

### 📍 Listar uma Classificação Específica de Post

- **Rota**: `GET http://localhost:3000/classificacoes/:id`
- **Parâmetro**: `id` (String) - O ID da classificação a ser listada.

### 📍 Criar uma Nova Classificação de Post

- **Rota**: `POST http://localhost:3000/classificacoes`

---

# Testes da API de Amizades

## Como Testar

Utilize uma ferramenta como **Postman**, **Insomnia** ou **cURL** para enviar requisições ao servidor localmente.

---

## 🚀 Endpoints para Teste

### 📍 Listar Todas as Amizades

- **Rota**: `GET http://localhost:3000/amigos`

### 📍 Criar uma Nova Amizade

- **Rota**: `POST http://localhost:3000/amigos`

### 📍 Remover uma Amizade

- **Rota**: `DELETE http://localhost:3000/amigos/:id`
- **Parâmetro**: `id` (String) - O ID da amizade a ser removida.

---

# O que esperar

## API de Usuários

### Criar um Novo Usuário
- `201 Created` se o usuário for criado com sucesso.
- `400 Bad Request` se faltar algum campo obrigatório.

### Buscar Todos os Usuários
- `200 OK` com uma lista de usuários cadastrados.
- `404 Not Found` se não houver usuários cadastrados.

### Deletar um Usuário
- `200 OK` se o usuário for deletado com sucesso.
- `404 Not Found` se o usuário não existir.

---

## API de Posts

### Criar um Novo Post
- `201 Created` se o post for criado com sucesso.
- `400 Bad Request` se faltar algum campo obrigatório.

### Buscar Todos os Posts
- `200 OK` com uma lista de posts cadastrados.
- `404 Not Found` se não houver posts cadastrados.

### Deletar um Post
- `200 OK` se o post for deletado com sucesso.
- `404 Not Found` se o post não existir.

---

## API de Mensagens

### Criar uma Nova Mensagem
- `201 Created` se a mensagem for criada com sucesso.
- `400 Bad Request` se faltar algum campo obrigatório.

### Listar Todas as Mensagens
- `200 OK` com uma lista de mensagens.
- `404 Not Found` se não houver mensagens cadastradas.

### Buscar uma Mensagem Específica
- `200 OK` com os detalhes da mensagem.
- `404 Not Found` se a mensagem não existir.

### Deletar uma Mensagem
- `200 OK` se a mensagem for deletada com sucesso.
- `404 Not Found` se a mensagem não existir.

---

## API de Membros da Comunidade

### Criar um Novo Membro na Comunidade
- `201 Created` se o membro for adicionado com sucesso.
- `400 Bad Request` se faltar algum campo obrigatório.

### Listar Todos os Membros da Comunidade
- `200 OK` com uma lista de membros da comunidade.
- `404 Not Found` se não houver membros cadastrados.

### Buscar um Membro Específico da Comunidade
- `200 OK` com os detalhes do membro.
- `404 Not Found` se o membro não existir.

### Deletar um Membro da Comunidade
- `200 OK` se o membro for deletado com sucesso.
- `404 Not Found` se o membro não existir.

---

## API de Curtidas

### Criar uma Nova Curtida
- `201 Created` se a curtida for criada com sucesso.
- `400 Bad Request` se a curtida já existir para o mesmo post.
- `500 Internal Server Error` em caso de erro no servidor.

---

## API de Comunidades

### Criar uma Nova Comunidade
- `201 Created` se a comunidade for criada com sucesso.
- `400 Bad Request` se algum campo obrigatório estiver faltando.

### Listar Todas as Comunidades
- `200 OK` com a lista de comunidades cadastradas.
- `404 Not Found` se não houver comunidades cadastradas.

### Buscar uma Comunidade Específica
- `200 OK` com os detalhes da comunidade.
- `404 Not Found` se a comunidade não existir.

### Deletar uma Comunidade
- `200 OK` se a comunidade for deletada com sucesso.
- `404 Not Found` se a comunidade não existir.

---

## API de Comentários

### Criar um Novo Comentário
- `201 Created` se o comentário for criado com sucesso.
- `400 Bad Request` se faltar algum campo obrigatório.

### Deletar um Comentário
- `200 OK` se o comentário for deletado com sucesso.
- `404 Not Found` se o comentário não existir.

### Listar Todos os Comentários
- `200 OK` com uma lista de todos os comentários.
- `404 Not Found` se não houver comentários cadastrados.

---

## API de Classificações de Posts

### Listar Todas as Classificações de Posts
- `200 OK` com uma lista de todas as classificações.
- `404 Not Found` se não houver classificações.

### Listar uma Classificação Específica de Post
- `200 OK` com a classificação específica.
- `404 Not Found` se a classificação não for encontrada.

### Criar uma Nova Classificação de Post
- `201 Created` se a classificação for criada com sucesso.
- `400 Bad Request` se faltar algum campo obrigatório.

---

## API de Amizades

### Listar Todas as Amizades
- `200 OK` com uma lista de todas as amizades.
- `404 Not Found` se não houver amizades.

### Criar uma Nova Amizade
- `201 Created` se a amizade for criada com sucesso.
- `400 Bad Request` se faltar algum campo obrigatório.

### Remover uma Amizade
- `200 OK` se a amizade for removida com sucesso.
- `404 Not Found` se a amizade não for encontrada.
