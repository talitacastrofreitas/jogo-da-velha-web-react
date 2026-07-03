# ❌ Jogo da Velha Web - React ⭕
Este repositório contém a estrutura base e o template inicial para a criação de um clássico **Jogo da Velha** (Tic-Tac-Toe) web desenvolvido em **React**.
O projeto foi inicializado utilizando o scaffold do *Create React App* e passou por uma etapa de limpeza de arquivos e estilos sobressalentes, deixando o ambiente preparado com o ponto de entrada limpo para o desenvolvimento da lógica e interface do jogo.

---
## 📂 Estrutura Atual do Projeto
Os arquivos de código fundamentais estão estruturados da seguinte forma:
```bash
jogo-da-velha-web-react/
├── public/
│   ├── favicon.ico          # Ícone da aba do navegador
│   ├── index.html           # Documento HTML raiz da aplicação
│   └── manifest.json        # Manifesto PWA padrão do React
├── src/
│   ├── App.css              # Regras de centralização e alinhamento do container principal
│   ├── App.js               # Componente principal contendo o cabeçalho "Jogo da Velha"
│   ├── index.css            # Estilos gerais e fontes padrão do corpo do documento
│   └── index.js             # Arquivo inicializador que injeta a aplicação no DOM do navegador
├── package.json             # Registro de dependências e scripts de desenvolvimento
└── README.md                # Documentação do projeto
```
---
## 🛠️ Tecnologias Utilizadas
- [React v18](https://react.dev/) (Biblioteca para interfaces dinâmicas)
- **CSS3 (Vanilla):** Estilos básicos de renderização.
- **Create React App:** Estruturador e empacotador de scripts.
  
---

### 4. Status de Jogo & Reinício
- Exiba no topo do tabuleiro o status da partida: *"Próximo Jogador: X"*, *"Vencedor: O"* ou *"Empate (Deu Velha!)"*.
- Crie um botão de resetar para recriar o array do tabuleiro preenchido com `null` e reiniciar as rodadas.
---
## 💻 Como Rodar o Projeto
### Requisitos:
Certifique-se de ter o [Node.js](https://nodejs.org/) instalado na sua máquina.
### Execução:
1. Abra o terminal na pasta do projeto.
2. Instale os pacotes do npm:
   ```bash
   npm install
   ```
3. Inicialize o servidor local de desenvolvimento:
   ```bash
   npm start
   ```
4. Acesse: [http://localhost:3000](http://localhost:3000)
