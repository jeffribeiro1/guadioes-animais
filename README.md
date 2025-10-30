PetShop Guardiões Dos Animais🐕‍🦺


Um sistema web interativo para gerenciamento de petshops, desenvolvido com foco educacional em TypeScript. Demonstra como usar interfaces, tipos e funções para prevenir erros comuns em JavaScript, simulando operações reais como cadastro de animais, agendamento de serviços e geração de estatísticas.

📋 Descrição
Este projeto é uma aplicação front-end simples que simula um petshop. Ele foi criado pelo grupo "Os Guardiões Dos Animais" para ensinar conceitos de TypeScript em um contexto prático. Em vez de um sistema de produção, o foco é educacional: mostrar como TypeScript evita bugs como tipos incorretos ou dados incompletos, que poderiam causar problemas em um petshop real (ex.: calcular idade errada ou somar preços como strings).

Objetivo Educacional: Ensinar TypeScript através de exemplos reais, prevenindo erros que aparecem em JavaScript puro.
Funcionalidades Básicas: Cadastro de animais, agendamento de serviços, cálculos de preços e relatórios.
Tecnologias: HTML5, CSS3, TypeScript (compilado para JavaScript).
Público-Alvo: Desenvolvedores iniciantes, estudantes e profissionais de petshops interessados em automação simples.
✨ Funcionalidades
Cadastro de Animais: Criar animais com nome, espécie, idade (calculada automaticamente), peso e status de vacinação.
Agendamento de Serviços: Adicionar serviços como banho, tosa ou vacinação, vinculados a animais, com preços e status.
Cálculos Automáticos: Calcular preço total de serviços, filtrar animais vacinados e buscar por nome.
Interface Interativa: Botões para testar funções, visualizar listas e demonstrar erros prevenidos pelo TypeScript.
Prevenção de Erros: Exemplos de bugs evitados, como tipos incorretos (ex.: let idade: number = "5" não compila).
Estatísticas: Relatórios de animais cadastrados, serviços agendados e faturamento total.
🛠️ Tecnologias Utilizadas
HTML5: Estrutura semântica da página (index.html).
CSS3: Estilização responsiva com variáveis, flexbox e pseudo-elementos (style.css).
TypeScript: Lógica principal com interfaces e tipos (script.ts.ts).
JavaScript: Versão transpilada para execução no navegador (script.js).
Ferramentas Extras: Google Fonts (Quicksand), imagens locais e console para debugging.
🚀 Instalação e Execução
Pré-requisitos
Navegador web moderno (Chrome, Firefox, etc.).
Editor de código (VS Code recomendado) para visualizar/editar.
Node.js e TypeScript Compiler (opcional, para compilar script.ts.ts manualmente).
Passos para Executar
Clone o Repositório:

bash

Copy code
git clone https://github.com/seu-usuario/petshop-guardioes-animais.git
cd petshop-guardioes-animais
Abra no Navegador:

Abra o arquivo index.html diretamente no navegador (não precisa de servidor local, pois é front-end puro).
Ou use um servidor simples: python -m http.server 8000 e acesse http://localhost:8000.
Compilar TypeScript (Opcional):

Instale TypeScript globalmente: npm install -g typescript.
Compile: tsc script.ts.ts --outFile script.js.
Isso gera script.js a partir de script.ts.ts.
Verificar Funcionamento:

Clique nos botões na página para testar funcionalidades.
Abra o console do navegador (F12) para ver logs como "Sistema PetShop carregado!".
📖 Uso
Como Interagir
Página Inicial: Exibe cards com estatísticas (animais e serviços) e botões numerados.
Botões Principais:
1. Tipos Básicos: Mostra tipos TypeScript (string, number, etc.).
2. Exemplo Animais: Lista animais cadastrados (ex.: Rex, cachorro).
3. Testar Funções: Cria um animal e agenda um serviço, exibindo resultados.
4. Ver Erros: Demonstra erros prevenidos (ex.: tipos incorretos).
5. Cadastrar Animal: Simula cadastro com delay (ex.: adiciona "Luna").
Área de Resultados: Atualiza dinamicamente com HTML gerado por JavaScript.

📁 Estrutura de Arquivos

Copy code
petshop-guardioes-animais/
├── index.html          # Página principal com layout HTML
├── style.css           # Estilos CSS para responsividade e tema
├── script.ts.ts        # Código TypeScript (fonte)
├── script.js           # JavaScript compilado (executável)
├── images/             # Imagens do projeto
│   ├── logo.png        # Logo do petshop
│   ├── fb-cover.jpg    # Fundo de capa
│   └── pegadas.jpg     # Overlay de pegadas
└── README.md           # Este arquivo
🎥 Demonstração
Abra index.html no navegador.
Clique em "3. Testar Funções" para ver um animal criado e serviço agendado.
Clique em "4. Ver Erros" para exemplos de bugs evitados pelo TypeScript.
Use o console para ver mensagens de inicialização.
Para uma apresentação visual, consulte o PDF da Apresentação ou assista a um vídeo demo.

🤝 Contribuição
Contribuições são bem-vindas! Siga estes passos:

Fork o repositório.
Crie uma branch: git checkout -b feature/nova-funcionalidade.
Faça commits: git commit -m 'Adiciona nova funcionalidade'.
Push: git push origin feature/nova-funcionalidade.
Abra um Pull Request.
Ideias para Melhorias: Adicionar formulários reais, integração com API ou versão mobile.
Relatar Bugs: Use Issues no GitHub com detalhes e screenshots.
