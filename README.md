🚀 ServeRest API Testing Project
Este projeto contém uma suíte de testes automatizados de API para a plataforma gratuita ServeRest. O objetivo é validar o fluxo de ponta a ponta (E2E) de um e-commerce fictício, garantindo a qualidade e a integridade dos dados através da automação com Postman e JavaScript.

🛠️ Tecnologias Utilizadas
Postman: Ferramenta principal para criação e execução das requisições.

JavaScript: Utilizado para scripts de pré-processamento e validações.

🧪 Fluxo de Testes Implementado
O projeto cobre os seguintes cenários críticos de negócio:

*  Cadastro de Usuário: Criação dinâmica de usuários administradores (com e-mail aleatório para evitar duplicidade).

*  Autenticação: Realização de login e captura automática do Bearer Token.

*  Gerenciamento de Produtos: Cadastro de novos produtos utilizando o token de administrador.

*  Carrinho de Compras: Finalização de compra vinculando o produto criado ao usuário autenticado.

📁 Estrutura do Repositório

.
├── Postman/
│   ├── Collection.json   # Exportação da coleção de testes
│   │ 
│   └── Environment.json   # Variáveis de ambiente
└── README.md
