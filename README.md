<<<<<<< HEAD
My Pet Zone - Front-End 🐾
Uma plataforma completa para centralizar as informações do seu pet, encontrar serviços e cuidar de quem você ama. Este repositório contém o código-fonte do front-end da aplicação.

✨ Funcionalidades Principais
🏠 Landing Page: Página de apresentação do projeto, destacando seus benefícios e funcionalidades.

🐶 Cadastro de Pets: Formulário intuitivo para registrar seu animal de estimação, incluindo informações como nome, raça, idade e foto.

🩺 Carteira de Vacinação Digital: Visualize e gerencie o histórico de vacinas e vermífugos do seu pet de forma fácil e organizada.

🗺️ Mapa Interativo de Serviços: Explore um mapa ao estilo Google Maps para encontrar tudo o que o mundo pet oferece ao seu redor.

Busca por Localização: Encontre serviços próximos à sua localização atual.

Pesquisa e Filtros: Pesquise por serviços específicos (petshops, clínicas 24h, hotéis pet-friendly, etc.).

Visualização de Detalhes: Clique em um ponto no mapa para ver informações detalhadas sobre o estabelecimento.

🛠️ Tecnologias Utilizadas
Este projeto foi construído utilizando as mais modernas tecnologias para desenvolvimento web:

React: Biblioteca para construção de interfaces de usuário.

TypeScript: Superset do JavaScript que adiciona tipagem estática.

Vite: Ferramenta de build moderna e extremamente rápida para o desenvolvimento.

HTML5 & CSS3: Estruturação e estilização das páginas (pode ser usado com Módulos CSS, Styled-Components ou Tailwind CSS).

React Router DOM: Para gerenciamento de rotas na aplicação (navegação entre páginas).

Axios: Cliente HTTP para realizar requisições à API (back-end).

Google Maps API / Leaflet: Para a funcionalidade do mapa interativo.

🚀 Como Executar o Projeto
Para rodar este projeto localmente, siga os passos abaixo:

Clone o repositório:

Bash

git clone https://github.com/seu-usuario/nome-do-repositorio.git
Navegue até o diretório do projeto:

Bash

cd nome-do-repositorio
Instale as dependências:

Bash

npm install
# ou
yarn install
Configure as variáveis de ambiente:

Renomeie o arquivo .env.example para .env.

Insira suas chaves de API necessárias (por exemplo, a chave da API do Google Maps).

Snippet de código

# Exemplo de conteúdo para o arquivo .env
VITE_GOOGLE_MAPS_API_KEY="SUA_CHAVE_DE_API_AQUI"
VITE_API_BASE_URL="http://localhost:3333/api" # URL do seu back-end
Execute a aplicação em modo de desenvolvimento:

Bash

npm run dev
# ou
yarn dev
Abra seu navegador e acesse http://localhost:5173 (ou a porta indicada no seu terminal).

📂 Estrutura de Pastas
O projeto segue uma estrutura de pastas organizada para facilitar a manutenção e escalabilidade:

/src
|-- /assets           # Imagens, fontes e outros arquivos estáticos
|-- /components       # Componentes reutilizáveis (Button, Input, Map, etc.)
|-- /pages            # Componentes de página (Home, PetProfile, MapPage, etc.)
|-- /hooks            # Hooks customizados (useAuth, useApi, etc.)
|-- /services         # Lógica de comunicação com APIs (api.ts)
|-- /styles           # Estilos globais e configurações de tema
|-- /types            # Definições de tipos e interfaces TypeScript
|-- App.tsx           # Componente principal da aplicação
|-- main.tsx          # Ponto de entrada da aplicação
🖼️ Telas da Aplicação
(Esta seção está reservada para as imagens que você irá adicionar)

Adicione aqui screenshots da Landing Page, do formulário de cadastro, da carteirinha e do mapa.

Exemplo de como adicionar uma imagem:
![Descrição da Tela](caminho/para/sua/imagem.png)

🤝 Como Contribuir
Contribuições são sempre bem-vindas! Se você deseja contribuir com o projeto:

Faça um Fork deste repositório.

Crie uma nova Branch (git checkout -b feature/sua-feature).

Faça o Commit das suas alterações (git commit -m 'Adiciona nova feature').

Faça o Push para a sua Branch (git push origin feature/sua-feature).

Abra um Pull Request.

📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
=======
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default tseslint.config([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...

      // Remove tseslint.configs.recommended and replace with this
      ...tseslint.configs.recommendedTypeChecked,
      // Alternatively, use this for stricter rules
      ...tseslint.configs.strictTypeChecked,
      // Optionally, add this for stylistic rules
      ...tseslint.configs.stylisticTypeChecked,

      // Other configs...
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])
```

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default tseslint.config([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...
      // Enable lint rules for React
      reactX.configs['recommended-typescript'],
      // Enable lint rules for React DOM
      reactDom.configs.recommended,
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])
```
>>>>>>> 0b5c2f3 (start)
