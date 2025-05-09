O repositório [Guilherme-Dev-Java/jogo\_tutorial\_gosu](https://github.com/Guilherme-Dev-Java/jogo_tutorial_gosu) contém um jogo chamado **"Jogo Space"**, desenvolvido em **Ruby** utilizando a biblioteca gráfica **Gosu**.

### 📁 Estrutura do Projeto

* **`jogo.rb`**: Arquivo principal que inicia o jogo.
* **`player.rb`**: Define o comportamento do jogador.
* **`star.rb`**: Gerencia os objetos estrela no jogo.
* **`zorder.rb`**: Provavelmente define a ordem de renderização dos elementos.
* **Assets**:

  * **`beep.wav`**: Arquivo de som.
  * **`space.png`**, **`star.png`**, **`starfighter.bmp`**: Imagens utilizadas no jogo.

### 🚀 Como Executar o Jogo

1. **Pré-requisitos**:

   * Certifique-se de ter o **Ruby** instalado em seu sistema.
   * Instale a gem **Gosu**:

     ```bash
     gem install gosu
     ```

2. **Clone o repositório**:

   ```bash
   git clone https://github.com/Guilherme-Dev-Java/jogo_tutorial_gosu.git
   cd jogo_tutorial_gosu
   ```

3. **Execute o jogo**:

   ```bash
   ruby jogo.rb
   ```

O jogo deve iniciar em uma janela separada, permitindo que você interaja com os elementos gráficos e sonoros definidos.
