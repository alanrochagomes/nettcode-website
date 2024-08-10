<img src="assets/images/readme-images/cover.png">

<h1 align="center">Site HBO Max</h1>
<h4 align="center">Clone com modificações</h4>

<p align="center">
  O projeto é um clone do site <a href="https://www.hbomax.com/br/pt">HBO Max</a>, com o intuito de reproduzir a interface, com algumas modificações, aplicando os temas abordados ao longo das aulas de CSS da plataforma da <a href="https://dio.me">Digital Innovation One</a>.
</p>
<p align="center">
  O clone do site HBO Max serve como desafio para os alunos da plataforma testarem seus conhecimentos e colocarem em prática os recursos de HTML e CSS abordados nos cursos.
</p>

## 📎 Sumário

- [✨ Features](#features)
- [📦 Temas abordados](#topics)
- [ Demonstração](#demo)

<h2 id="features">✨ Features</h2>

- Menu de navegação
- Cabeçalho com animação gradiente
- Cards com os planos de assinatura animados
- Lista de filmes e séries disponíveis na plataforma
- Formulário de login
- Rodapé com links importantes
- UI Responsiva

_As features são visuais, não possuindo integração com nenhuma API. O intuito do projeto é reproduzir a interface do site original, com algumas modificações._

<h2 id="topics">📦 Temas abordados</h2>

O projeto possui como intuito aplicar os conceitos abordados na Trilha de CSS da <a href="https://dio.me">DIO</a>, ministrada pela instrutora <a href="https://github.com/micheleambrosio">Michele Ambrosio</a>.

Recursos CSS presentes no projeto:

- Fundamentos do CSS
- Grid Layout
- Flexbox
- Responsividade
- Pseudo-elementos
- Pseudo-classes
- Transformações 2D e 3D
- Transições e animações
- Tratamento de campos inválidos no formulário

_A propriedade `scroll-behavior: smooth` irá fazer com que os links que levam para uma outra sessão do site, da mesma página, faça uma transição suave ao realizar a rolagem._

Para implementar a barra de rolagem personalizada, como no exemplo, adicione na sua folha de estilos o seguinte trecho CSS:

```css
/* Custom Scroll */

::-webkit-scrollbar {
  width: 8px;
}

::-webkit-scrollbar-thumb {
  background: var(--tertiary-color);
  border-radius: 10px;
}

::-webkit-scrollbar-thumb:hover {
  background: var(--secondary-color);
}
```

O resultado final do projeto deve contemplar todas as [features](#features) presentes no <a href="">resultado final</a>.

As fontes utilizadas no projeto foram:

- [Raleway](https://fonts.google.com/specimen/Raleway)
- [Quicksand](https://fonts.google.com/specimen/Quicksand?query=quicksand)

```css
@import url("https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;500;600;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;700&display=swap");
```

_Para melhor orientação, assista ao vídeo de instruções do desafio, que está disponibilizado no Módulo 3 da Trilha de CSS._

<h2 id="demo">Demonstração</h2>

Você pode acessar ao resultado final do projeto [clicando aqui](https://alanrochagomes.github.io/clone-hbomax/).
