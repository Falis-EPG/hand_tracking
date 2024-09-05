
# Projeto de Reconhecimento de Gestos com Mediapipe e OpenCV

Este projeto utiliza OpenCV, Mediapipe e outras bibliotecas Python para desenvolver uma interface de controle baseada em gestos. O sistema captura gestos da mão através de uma câmera e permite que o usuário digite texto virtualmente, desenhe na tela, e execute comandos, como abrir o Microsoft Word ou o Google Chrome. A interação com o sistema é feita com base nos movimentos e posições dos dedos, reconhecidos pelo modelo de mãos do Mediapipe.

## Funcionalidades

- **Teclado Virtual**: Permite a digitação de letras quando o indicador toca nos "botões" exibidos na tela.
- **Comandos de Aplicativos**: Baseado em diferentes combinações de dedos levantados, é possível abrir ou fechar o Microsoft Word e o Google Chrome.
- **Desenho**: Usando dois dedos, o usuário pode desenhar na tela com cores diferentes e espessuras variadas.
- **Reconhecimento de Mão Esquerda e Direita**: O sistema identifica se a mão reconhecida é a esquerda ou a direita, realizando diferentes ações com base nisso.

## Dependências

- OpenCV
- Mediapipe
- Pynput
- NumPy

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git
   ```
2. Instale as dependências:
   ```bash
   pip install opencv-python mediapipe pynput numpy
   ```
3. Execute o projeto:
   ```bash
   python main.py
   ```

## Como Usar

- Use a mão esquerda para interagir com o teclado virtual. O texto digitado será exibido na tela e salvo em um arquivo `texto.txt`.
- Para desenhar, utilize as duas mãos, onde a mão direita controla a cor e a mão esquerda o movimento.
- Para abrir o Word ou o Chrome, use a mão direita com as seguintes combinações de dedos:
  - **1 dedo (indicador)**: Abre o Microsoft Word.
  - **2 dedos (indicador e médio)**: Abre o Google Chrome.
- O gesto de fechar o punho com a mão direita fecha o Microsoft Word.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um _pull request_.

---

Essa estrutura ajuda a organizar o repositório, explicando claramente as funcionalidades e como usar o código.
