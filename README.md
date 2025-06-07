# JOGO DA VELHA - EXE
👨‍💻ESSE É PEQUENO JOGO QUE RODA NO CONSOLE DA IDE.

<img src="FOTO.png" align="center" width="400" height= "200"> <br>

## DESCRIÇÃO:
O aplicativo é um jogo da velha simples para dois jogadores. Suas principais funcionalidades são:

1. **Menu de Opções:**
   - Permite aos jogadores escolherem entre sair do jogo ou jogar novamente.

2. **Tabuleiro Interativo:**
   - Exibe um tabuleiro 3x3 na tela, onde os jogadores fazem suas jogadas alternadamente.

3. **Entrada de Jogadas:**
   - Solicita que os jogadores informem as coordenadas (linha e coluna) para realizar suas jogadas.

4. **Verificação de Vitória:**
   - Avalia se um jogador venceu o jogo ao completar uma linha, coluna ou diagonal com suas marcações.

5. **Empate:**
   - Identifica quando o jogo resulta em um empate (nenhum jogador venceu e o tabuleiro está cheio).

6. **Exibição do Tabuleiro Atualizado:**
   - Mostra o estado atual do tabuleiro após cada jogada.

7. **Loop de Jogo:**
   - Permite que os jogadores continuem jogando até que haja um vencedor ou empate.

## EXECUTANDO O JOGO:
1. Acesse o diretório `./CODIGO` e execute o arquivo Python com o seguinte comando:

   ```bash
   python CODIGO.py
   ```

2. Ao iniciar, o jogo exibirá um tabuleiro vazio no console.

3. Os jogadores farão suas jogadas alternadamente, usando os símbolos **X** e **O**.

4. Quando for sua vez, o jogo solicitará que você informe a posição da jogada:

   * Primeiro, insira o número da **linha** (1, 2 ou 3) e pressione Enter.
   * Em seguida, insira o número da **coluna** (1, 2 ou 3) e pressione Enter.

5. O tabuleiro será atualizado com a sua jogada.

6. O jogo continuará alternando entre os jogadores até que:

   * Um dos jogadores vença, **ou**
   * Todas as posições estejam preenchidas, resultando em um **empate**.

7. Ao final da partida, você poderá escolher entre **jogar novamente** ou **encerrar o jogo**.

## SOBRE O EXECUTAVEL:
### 1. EXECUTANDO:
   * O executável gerado está disponível apenas para sistemas **Windows x64** e pode ser encontrado no diretório: `./APP`.
   * Para executá-lo, basta dar dois cliques. Ele é especialmente útil em máquinas onde o **Python não está instalado**.
   * Trata-se da **mesma aplicação contida no arquivo `./CODIGO/CODIGO.py`**, porém empacotada de forma independente.
   * Se necessário, você pode recompilar o executável a qualquer momento.

### 2. GERANDO:
> **IMPORTANTE:** Antes de gerar o novo `executável`, certifique-se de excluir o arquivo `./APP/JOGO DA VELHA.exe`.

   **1. Instalação do [PyInstaller:](https://pyinstaller.org/en/stable/)**
   - Certifique-se de ter o PyInstaller instalado. Se não tiver, instale usando o comando abaixo:
   ```bash
   pip install pyinstaller
   ```

   **2. Gerando o Executável:**
   - No diretório `./CODIGO`, execute o comando abaixo para gerar o executável a partir do arquivo `.spec`:

   ```bash
   pyinstaller EXECUTAVEL.spec
   ```

   - O arquivo `JOGO DA VELHA.exe` será criado dentro da pasta `./CODIGO/dist`.

   - Após a geração, você pode mover o executável para `./APP` e remover as pastas temporárias `./CODIGO/build` e `./CODIGO/dist`.

   - Para executar o aplicativo, basta dar dois cliques no arquivo `.exe`.

## NÃO SABE?
- Entendemos que para manipular arquivos em muitas linguagens e tecnologias, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE PYTHON](https://github.com/VILHALVA/CURSO-DE-PYTHON)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)
