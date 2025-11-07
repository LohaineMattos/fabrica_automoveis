# 🚗 Fábrica de Automóveis

O projeto **Fábrica de Automóveis** consiste em um sistema completo que permite visualizar áreas de estacionamento, gerenciar carros disponíveis e vendidos, e realizar o controle de vendas de forma prática e intuitiva.

---

## 🧩 Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando tecnologias modernas e de fácil integração, garantindo bom desempenho e manutenção simplificada.

### 🖥️ Frontend
- **HTML5** — utilizado para estruturar o conteúdo e os elementos principais da aplicação.  
- **CSS3** — responsável pela estilização da interface e criação de um layout responsivo e atraente.  
- **JavaScript (ES6+)** — linguagem usada para implementar a lógica de interação entre usuário e sistema.  
- **Fetch API** — permite a comunicação entre o frontend e o backend por meio de requisições HTTP assíncronas.

### ⚙️ Backend
- **API REST local** — responsável por processar as requisições e gerenciar os dados de veículos, clientes e concessionárias.  
- **MySQL** — banco de dados relacional utilizado para armazenar todas as informações do sistema.  
- **Prisma ORM** — ferramenta de mapeamento objeto-relacional que facilita a manipulação de dados e a integração entre o banco e a aplicação.

---

## 🧠 Como Executar o Projeto

Abaixo estão descritos os passos necessários para executar o sistema em ambiente local.

### ✅ Pré-requisitos
Antes de iniciar, certifique-se de possuir:
- Um **servidor de API local** configurado na **porta 3000**;  
- Um **navegador web moderno** (como Google Chrome, Edge ou Firefox);  
- (Opcional) **Python** ou **Node.js** instalados, caso queira rodar o servidor local para o frontend.

---

### 🚀 Instruções de Execução

1. **Iniciar o servidor da API**
  ```npm start ``` ou ```node server.js```

1. **Executar o Frontend:**

Método 1: Abrir index.html diretamente no navegador

Método 2: Usar servidor local - ```python -m http.server 8000```
ou
```npx http-server```

e 

Abrir: ```http://localhost:8000```

## ⚙️ Funcionalidades

- Visualização de **11 áreas de estacionamento** organizadas por status.  
- **Áreas azuis:** representam os carros alocados para venda.  
- **Áreas brancas:** indicam áreas livres (sem veículos cadastrados).  
- **Modal interativo:** exibe a lista completa de carros disponíveis em cada área.  
- **Sistema de vendas:** permite a seleção do cliente e o registro da entrega do veículo.  
- **Identificação visual:** carros vendidos são destacados com o status **"Vendido"**.  
- **Interface responsiva:** modais sobrepostos e design adaptável para diferentes tamanhos de tela.

### Desenvolvido por: LohaineMattos

