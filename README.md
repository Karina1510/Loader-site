# Loader Animado ✨
Um projeto simples e elegante que demonstra a criação de um "loader" (indicador de carregamento) animado usando HTML e CSS. A animação simula múltiplos pontos girando em um círculo, criando um efeito visual de espera para o usuário.

## 💻 Tecnologias Utilizadas
HTML: Utilizado para a estrutura básica da página, incluindo a section e os spans que formam os pontos do loader.

CSS: Responsável por toda a estilização e, principalmente, pela animação. Foram usadas propriedades como transform, animation e variáveis CSS para criar o movimento e a distribuição circular dos pontos.

## ✨ Conceitos e Funcionalidades
Animação com @keyframes: A regra @keyframes foi usada para definir a animação de opacidade dos pontos, fazendo com que eles apareçam e desapareçam em um ciclo contínuo.

Variáveis CSS (--i): Cada <span> possui uma variável CSS (--i) que vai de 1 a 15. Essa variável é crucial para:

Posicionamento Circular: Calcular a rotação de cada ponto, garantindo que eles sejam distribuídos uniformemente em um círculo.

Atraso da Animação: Criar um atraso progressivo (animation-delay) que faz com que cada ponto anime em um momento diferente, gerando o efeito "em cascata".

Propriedades transform: O CSS usa as propriedades rotate() e translateY() para girar os pontos em torno de um eixo central, criando o efeito de movimento circular.

cálculo das bolinhas (span): Para formar o círculo dos círculos. Fazemos 360° / pela quantidade de span criação de bolinhas.

## ⚙️ Como Executar o Projeto
Clique no git page
Abra o arquivo:
Simplesmente abra o arquivo index.html em seu navegador para ver o loader em ação.

🧑‍💻 Autor
Nome: Karina Silva
