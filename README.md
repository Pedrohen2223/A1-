
# API REST Padrão - Node.js & Express

![Node.js](https://img.shields.io/badge/Node.js-14%2B-green)
![License](https://img.shields.io/badge/license-MIT-blue)

Projeto base para criação de APIs REST utilizando Node.js com arquitetura em camadas (Controller, Service, Repository). Ideal para iniciar novos projetos com estrutura organizada e escalável.

---

## :clipboard: Funcionalidades

- CRUD de Produtos
- CRUD de Clientes
- Estrutura modular por responsabilidades
- Pronto para integração com banco de dados

---

## :file_folder: Estrutura do Projeto

```
api-rest-padrao-service/
├── server.js
├── db.js
├── routes/
│   ├── produtoRoutes.js
│   └── clienteRoutes.js
├── controllers/
│   ├── produtoController.js
│   └── clienteController.js
├── services/
│   ├── produtoService.js
│   └── clienteService.js
├── repositories/
│   ├── produtoRepository.js
│   └── clienteRepository.js
```

---

## :rocket: Como Executar

```bash
# Instale as dependências
npm install

# Inicie o servidor
node server.js
```

A aplicação ficará disponível por padrão em `http://localhost:3000`.

---

## :hammer_and_wrench: Endpoints

### Produtos
- `GET /produtos` - Lista todos os produtos
- `POST /produtos` - Cadastra um novo produto

### Clientes
- `GET /clientes` - Lista todos os clientes
- `POST /clientes` - Cadastra um novo cliente

---

## :handshake: Contribuindo

1. Faça um fork do repositório
2. Crie uma branch: `git checkout -b minha-feature`
3. Commit suas alterações: `git commit -m 'Adiciona nova feature'`
4. Push na sua branch: `git push origin minha-feature`
5. Abra um Pull Request

---

## :memo: Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
