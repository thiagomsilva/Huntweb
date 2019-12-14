# Huntweb

Aplicação web que faz uma busca na API onde os dados estão em um banco na nuvem, e os mesmos são renderizados e páginados no frontend da aplicação web e mobile.

**Tecnologia da aplicação web Huntweb**

Tecnologias utilizadas foram NodeJS (Backend API), ReactJS (Frontend), React Native (Mobile Android e IOS) e Banco de dados [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) (AWS cloud)

- **Passo a passo para execução da aplicação via terminal:**

1. Start backend -> `./backend_node_api/yarn dev`
2. Start frontend -> `./frontend_react/yarn start`
3. Após o start do frontend acesso será local e automático em localhost:3000

**Dependências NodeJS:**</br>

```
    "cors": "^2.8.5",
    "express": "^4.17.1",
    "mongoose": "^5.6.11",
    "mongoose-paginate": "^5.0.3",
    "require-dir": "^1.2.0"
```

**Dependências ReactJS:**</br>

```
    "axios": "^0.19.0",
    "react": "^16.9.0",
    "react-dom": "^16.9.0",
    "react-router-dom": "^5.0.1",
    "react-scripts": "3.1.1"
```

**Dependências React Native:**</br>

(Em construção)
