# Projeto Cidade do Café

Este projeto foi construído com Nuxt.js. Trata-se de um site estático e fictício de uma cafeteria, gerado utilizando o JAMSTACK.

## Como Começar

Siga as instruções a seguir para clonar o projeto e executá-lo localmente.

### Pré-requisitos

Certifique-se de ter o *Node.js* e o *npm* instalados em sua máquina. Você pode baixá-los em [nodejs.org](https://nodejs.org/).

### Clonar o Repositório

git clone https://github.com/DanielUnifil/TRABALHO-GIT-WORKFLOW.git

cd TRABALHO-GIT-WORKFLOW

### Instalar Dependências

npm install

### Executar o Projeto

npm run dev

O projeto estará disponível em http://localhost:3000.

## Fluxo de Trabalho do GitHub Actions

Este projeto utiliza o GitHub Actions para automação de CI/CD. O fluxo de trabalho está configurado da seguinte forma:

### Build and Deploy

Este workflow é acionado em duas situações:
- Quando há um push na branch principal (main).
- Quando é criado um pull request para a branch principal.

### Etapas do Workflow

1. **Checkout do Código:** Isso garante que o código mais recente seja recuperado do repositório.

2. **Configuração do Node.js:** Configura o ambiente Node.js necessário para o projeto. A versão 18 é usada neste caso.

3. **Instalação de Dependências:** Instala todas as dependências do projeto usando o npm.

4. **Lint com ESLint:** Executa o ESLint para verificar a qualidade do código e garantir que esteja em conformidade com os padrões definidos.

5. **Formatar com Prettier:** Utiliza o Prettier para formatar o código de acordo com as regras de estilo definidas.

### Variáveis de Ambiente

- `CI: true`: Essa variável de ambiente é definida como `true` para garantir que o projeto seja executado no modo CI.