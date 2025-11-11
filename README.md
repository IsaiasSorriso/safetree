# 🌳 Safe Tree — Plataforma de Sustentabilidade Digital

**Safe Tree** é uma plataforma web que transforma árvores reais em **ativos digitais rastreáveis (RWA)**.  
Cada árvore plantada é representada por um **SAFET Token**, garantindo transparência, rastreabilidade e certificação imutável de sequestro de carbono na blockchain **XRPL**.

---

## 🚀 Visão Geral

A Safe Tree foi criada para unir tecnologia e sustentabilidade, permitindo que **usuários e vendedores** interajam de forma simples e confiável.

Com ela, é possível:
- Registrar árvores e visualizar seus dados.
- Consultar módulos com informações sobre plantações e áreas verdes.
- Realizar simulações de compra de árvores via **token SAFET** ou **Pix**.
- Acompanhar a rastreabilidade através de **QR Codes** únicos.

---

## 🧩 Funcionalidades Principais

### 👥 Telas e Fluxo de Navegação
- **Início:** introduz o conceito do projeto e permite escolher o tipo de acesso (usuário ou vendedor).  
- **Login e Cadastro:** telas de autenticação simuladas com campos de entrada e tipo de usuário.  
- **Painel do Vendedor:** exibe árvores cadastradas e permite incluir novas espécies.  
- **Módulos:** apresenta detalhes técnicos sobre áreas, quantidade de árvores e informações gerais do projeto.  
- **Área do Usuário:** oferece acesso à leitura de QR Code e detalhes dos lotes.  
- **Compra Simulada:** seleção de moeda, quantidade e pagamento via Pix.  
- **Finalização:** gera um QR Code representando a árvore adquirida.

---

## 💻 Tecnologias Utilizadas

- **HTML5** — estrutura semântica das páginas  
- **CSS3** — estilização com variáveis, sombras e responsividade  
- **JavaScript (Vanilla)** — manipulação de DOM e controle de telas  
- **Google Fonts (Poppins)** — tipografia moderna e legível  

---

## 🧱 Estrutura do Projeto
├── index.html # Página principal (todo o projeto está contido aqui)
├── logo.png # Logotipo da Safe Tree (exemplo)
├── image.png # Imagem ilustrativa usada nos módulos
└── README.md # Documentação do projeto


---

## 📱 Responsividade

A interface é totalmente adaptável:
- Menu mobile com botão de alternância (☰)
- Layout reorganizado para telas menores
- Cards e seções ajustáveis em largura

---

## 🔒 Lógica de Navegação (JavaScript)

O sistema utiliza funções simples para controlar a exibição de telas sem recarregar a página:

- `abrirTela(id)` → alterna entre seções (adiciona e remove a classe `.hidden`)  
- `armazenarMoeda()` → guarda a moeda escolhida pelo usuário  
- `armazenarQuantidade()` → salva a quantidade inserida  
- Atualiza dinamicamente os dados de pagamento e resumo de compra  

---

## 🪙 Conceito do SAFET Token

Cada **1 SAFET Token** representa **1 árvore geolocalizada e auditada**.  
O token contém:
- **Proof of Tree** — prova de existência e localização da árvore  
- **Auditoria de sequestro de CO₂**  
- **Certificação imutável** na blockchain **XRPL**

---

## 🎨 Design e Estilo

Paleta de cores:
| Nome | Cor | Descrição |
|------|------|-----------|
| Verde Escuro | `#1b5e20` | Confiança e natureza |
| Verde Médio | `#2e7d32` | Equilíbrio e sustentabilidade |
| Verde Claro | `#81c784` | Vitalidade e crescimento |
| Cinza Claro | `#f4f7f4` | Fundo suave |
| Branco | `#fff` | Limpeza e contraste |

---

## 🔧 Como Executar Localmente

1. Baixe o repositório ou copie o conteúdo do arquivo `index.html`.
2. Coloque os arquivos (`logo.png`, `image.png`) na mesma pasta.
3. Abra o arquivo **index.html** em qualquer navegador moderno.
4. Navegue entre as telas clicando nos botões e links do menu.

---

## 🧠 Melhorias Futuras 

- Implementar autenticação real (com backend).
- Conectar ao banco de dados para cadastro de árvores e usuários.
- Integração real com XRPL e geração de tokens.
- Módulo de leitura real de QR Code via câmera.
- Dashboard de estatísticas ambientais.

---

## 📜 Licença

Este projeto é de uso livre para fins educacionais e de demonstração.  
© 2025 Safe Tree — Todos os direitos reservados.

---
