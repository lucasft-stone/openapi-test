# 📚 OpenAPI Test - Documentação da API

Este repositório contém uma especificação completa e modular de uma API REST documentada utilizando OpenAPI 3.0.3. A documentação está organizada claramente por domínio e métodos, facilitando manutenção, escalabilidade e colaboração.

## 🚀 Estrutura do Projeto

A documentação está organizada da seguinte forma:

```
openapi-test/
├── openapi.json (arquivo raiz da especificação)
├── users/
│   ├── path.json
│   ├── get-users/
│   │   ├── schema.json
│   │   ├── responses.json
│   │   └── examples/
│   └── post-users/
│       ├── schema.json
│       ├── responses.json
│       └── examples/
└── orders/
    ├── path.json
    ├── get-orders/
    │   ├── schema.json
    │   ├── responses.json
    │   └── examples/
    └── post-orders/
        ├── schema.json
        ├── responses.json
        └── examples/
```

Cada rota possui exemplos práticos para facilitar testes e entendimento.

---

## 🔗 Como acessar a documentação?

A documentação completa pode ser facilmente visualizada utilizando o **Swagger UI Online**. Acesse diretamente pelo seguinte link:

➡️ [Visualizar Documentação OpenAPI (Swagger UI)](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/lucasft-stone/openapi-test/main/openapi.json)

---

## 📂 Detalhes dos Domínios

### Usuários (`users`)
- **GET** `/users`: Lista os usuários cadastrados.
- **POST** `/users`: Cria um novo usuário.

### Pedidos (`orders`)
- **GET** `/orders`: Lista os pedidos existentes.
- **POST** `/orders`: Cria um novo pedido.

---

## 🛠️ Ferramentas Utilizadas

- [OpenAPI Specification (Swagger)](https://swagger.io/docs/specification/about/)
- [Swagger UI Online](https://swagger.io/tools/swagger-ui/)

---

## 📌 Contribuições

Sinta-se à vontade para abrir issues ou pull requests para contribuir com melhorias ou correções.

---

©️ Desenvolvido por Lucas.

