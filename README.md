## Visão Geral

Este repositório contém dois pequenos jogos criados durante o curso de Programação em Python (com uso da biblioteca Pygame):

* **Acerte o Alvo** – um jogo simples onde o jogador tenta acertar alvos que aparecem.
* **Pong** – uma versão clássica do jogo de tênis de mesa em duas dimensões (duas raquetes, bola e placar).

O objetivo é servir como exemplo para iniciantes conhecerem conceitos como: loop de jogo, eventos de teclado/mouse, colisões, placar, sprites simples, etc.

---

## 🖼️ Imagens

### Jogo “Acerte o Alvo”

<img width="802" height="626" alt="image" src="https://github.com/user-attachments/assets/95ee8057-63d7-40f5-97bc-d448b1aff505" />


### Jogo “Pong”

<img width="801" height="626" alt="image" src="https://github.com/user-attachments/assets/fa3504c5-cfbb-4398-bc13-f3e0d566847d" />

---

## Pré-requisitos

Para rodar os jogos, você precisará ter instalado:

* Python 3.x
* A biblioteca Pygame:

  ```bash
  pip install pygame
  ```

---

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/Viniart/Python-Jogos-Aula.git
   cd Python-Jogos-Aula
   ```

2. Para rodar cada jogo:

   * **Acerte o Alvo**

     ```bash
     python acertealvo.py
     ```
   * **Pong**

     ```bash
     python pong.py
     ```

3. Se desejar, ajuste variáveis (como velocidade da bola, tamanho da janela, cores, etc) diretamente nos scripts para treinar.

---

## Como funciona cada jogo

### Acertar o Alvo

* O alvo aparece em posições aleatórias.
* O jogador tenta “clicar” ou “atingir” o alvo (dependendo da implementação) dentro do tempo limite.
* Pontuação é registrada conforme acertos e erros.
* Talvez exista temporizador, efeitos visuais simples, etc.

### Pong

* Dois players controlam raquetes verticalmente.
* Uma bola se move e rebate nas raquetes ou paredes.
* Se a bola passar pela raquete, o oponente marca ponto.
* Jogo continua até um placar determinado ou indefinido.

---

## Dependências

* Python 3.x
* Pygame (versão utilizada no desenvolvimento: **X.X** — ajuste se souber a versão)
* Os scripts contêm comentários explicativos que ajudam a entender o fluxo.

---

## Contribuições

Contribuições são bem-vindas! Se quiser adicionar melhorias, novos jogos ou corrigi-los:

1. Fork este repositório.
2. Crie uma branch (ex: `melhoria-pong`).
3. Faça as modificações e adicione testes ou prints adequados.
4. Abra um pull-request explicando a melhoria.

---

## Contato

Desenvolvido por **[Viniart](https://github.com/Viniart)**
Se tiver dúvidas ou sugestões, abra uma *Issue* ou envie mensagem pelo GitHub.
