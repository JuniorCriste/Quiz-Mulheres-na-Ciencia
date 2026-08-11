# 🔬 Quiz: Mulheres na Ciência

Este é um projeto de quiz interativo e gamificado, desenvolvido com tecnologias web nativas, focado em educar e inspirar estudantes sobre o papel fundamental das mulheres na história da Ciência, Tecnologia, Engenharia e Matemática (STEM).
![Tela Inicial](img/prints/print1.png)

## 🚀 Sobre o Projeto
O quiz apresenta 16 questões dinâmicas sobre cientistas icônicas (como Marie Curie e Ada Lovelace) e brasileiras contemporâneas (como Jaqueline Goes de Jesus e Mayana Zatz).

### Funcionalidades:
*   **Gamificação:** Sistema de pontuação, barra de progresso e feedbacks imediatos.
*   **Hall da Fama (Top 3):** Sistema de ranking local que registra os maiores pontuadores, integrando **captura de fotos via webcam** para personalizar o pódio.
*   **Design Responsivo:** Interface moderna, adaptável a diferentes tamanhos de tela.
*   **Experiência do Usuário:** Integração de áudio para acertos, erros e estados de pontuação.
*   **Interatividade:** Botões estilizados, transições suaves e design visual focado em ciência.

## 🛠️ Tecnologias Utilizadas
*   **HTML5:** Estrutura da página.
*   **CSS3:** Estilização responsiva, animações e paleta de cores tecnológica.
*   **JavaScript:** Lógica do jogo, manipulação do DOM, controle de áudio e **API MediaDevices (Webcam)**.
*   **LocalStorage:** Persistência dos dados do ranking no navegador do usuário.

## 📂 Estrutura do Projeto
Para que o jogo funcione corretamente com os áudios e imagens, o projeto deve seguir esta estrutura:
```
/seu-projeto
│
├── index.html       # Arquivo principal do quiz
├── /aud
│   ├── acerto.ogg
│   ├── erro.ogg
│   ├── notabaixa.ogg
│   ├── notaboa.ogg
│   └── trilha.ogg
└── /img
    └── [suas imagens de apoio]
```

## ⚙️ Como Utilizar
1.  **Requisitos:** Certifique-se de ter os arquivos de áudio (.ogg) e imagens necessários nas pastas indicadas no código.
2.  **Execução:** Basta abrir o arquivo `index.html` em qualquer navegador web moderno.
3.  **Customização:** Você pode editar facilmente a constante `questoes` dentro do arquivo `index.html` para adicionar, remover ou modificar perguntas sem precisar alterar a lógica do jogo.

---
## 🔗 Projetos Relacionados
*   [Projeto Base: Gamificação da Cultura Capixaba](https://github.com/JuniorCriste/gamificacao-da-cultura-capixaba-como-estrategia-pedagogica)
*Projeto desenvolvido para fins educacionais.*