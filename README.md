# Desafio 02 - Upload de imagens

<p align="center">
<img alt="ReactJS Rocketseat" src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fc2fd7c29-54f4-45c2-95fa-b9fa269109b8%2Freactjs.png?table=block&id=51e4099a-6e2f-4d4b-ae94-f9fe75bb769d&spaceId=08f749ff-d06d-49a8-a488-9846e081b224&width=250&userId=&cache=v2" width="200" hspace="50" align="center"/>
<img alt="Desafio 02 - Upload de imagens" src="src/assets/logo.png" align="center" width="400"/>

</p>

<br>

<p align="center"><em>Confira o resultado do desafio em: <a href="https://upfi-rocketseat-vitor.vercel.app" target="_blank">upfi-rocketseat-vitor.vercel.app</a></em></p>

## :computer: Sobre o desafio

<hr>

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS

Essa será uma aplicação onde o seu principal objetivo é adicionar alguns trechos de código para que a aplicação de upload de imagens funcione corretamente. Você vai receber uma aplicação com muitas funcionalidades e estilizações já implementadas. Ela deve realizar requisições para sua própria API Next.js que vai retornar os dados do FaunaDB (banco de dados) e do ImgBB (serviço de hospedagem de imagens). A interface implementada deve seguir o layout do Figma. Você terá acesso a 4 arquivos para implementar:

- Infinite Queries e Mutations com React Query;
- Envio de formulário com React Hook Form;
- Exibição de Modal e Toast com Chakra UI;
- Entre outros.

A seguir veremos com mais detalhes o que e como precisa ser feito 🚀

## Layout da Aplicação

|              Home              |
| :----------------------------: |
| ![home](./src/assets/home.png) |

<br>

|            Form            |
| :------------------------: |
| ![](./src/assets/form.png) |

<br>

|            Image            |
| :-------------------------: |
| ![](./src/assets/image.png) |

## Imagens

<div>
   <p>Home</p>
   <img src="./src/assets/image-1.png" />
   <br>
   <p>Form</p>
   <img src="./src/assets/image-2.png" />
   <br>
   <p>Imagem</p>
   <img src="./src/assets/image-3.png" />
</div>

## :rocket: Techs

<ul>
  <li> ReactJS </li>
  <li> TypeScript </li>
  <li> Next.js </li>
  <li> Chakra-UI </li>
  <li> React Query </li>
  <li> React Hook Form </li>
  <li> ImgBB </li>
  <li> FaunaDB </li>
  <li> API do Next.js </li>
</ul>

## Desenvolvimento

---

### Pré-requisitos

- Instalar [Node.js](https://nodejs.org)

- Instalar [Yarn](https://yarnpkg.com/)

### Clone o repositório

```bash
$ git@github.com:vitorgaletti/ignite-reactjs-upfi.git
```

### Executar Projeto

```bash
# Mudar para directório
$ cd ignite-reactjs-upfi/
```

- Instalar dependências

```bash
$ yarn
```

```bash
# Crie um arquivo .env.local e configure as váriaveis de ambiente
NEXT_PUBLIC_IMGBB_API_KEY=
FAUNA_API_KEY=
```

- Execute

```bash
$ yarn dev
```

```bash
$ yarn build
```

- Executar scripts

|          Ação          |  Utilização  |
| :--------------------: | :----------: |
|   Iniciar o servidor   |  `yarn dev`  |
|    Executar testes     | `yarn test`  |
| Compilar para produção | `yarn build` |

Acesse <http://localhost:3000> para ver o resultado.
