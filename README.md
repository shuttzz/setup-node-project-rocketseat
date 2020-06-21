### Passos

- yarn init -y
    - Inicia cria o arquivo package.json
- yard add typescript -D
    - Instala o typescript como pacote de desenvolvimento
- yarn tsc --init
    - Cria o arquivo tsconfig.json arquivo de configuração do TypeScript
- yarn add express
    - Microframework para se trabalhar com rotas e outras coisas
    - yarn add @types/express -D
        - Adiciona as tipagem do express para que o TypeScript utilize
- yarn tsc
    - Transpila o código em TypeScript para javascript puro
- yarn add ts-node-dev -D
    - Dependência que faz a parte da transpilção automática do código TypeScript e também já deixa o servidor de desenvolvimento em modo watch
- yarn ts-node-dev {caminho-do-arquivo-server.ts}
    - Executa o servidor em modo watch e também já faz a transpilação do código TypeScript
- yarn add tsconfig-paths -D
    - Precisa ter esse pacote para que o ts entenda como se trabalhar com os paths que criamos
