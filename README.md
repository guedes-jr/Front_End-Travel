# Travel (Agência de Viagens)

Projeto front end de uma página web de uma agência de viagêns, com bolíssimo design e apresentação agradável. O projeto é baseado em uma versão do canal Mr. Web Desing no you tube com algumas alterações como idioma e outros pontos.

![exemplo](./src/img/gif/apresentacao.gif)

## Estrutura

O projeto é contituí de um menú fixo, contedo a logo e os links para cada sessão bem como um botão para agendamento (botão apenas ilustrativo), seis sessões e um rodapé.
Dentre as sessões temos `Início`, `Sobre`, `Serviços`, `Galeria` e `Blog`. Ao final um `Footer`, ou melhor, Rodapé da página, o qual é subdivido em quatro coluna, sendo redes sociais, links para cada sessão, dados para contatos e Boletim de ocorrências e/ou atualizações.

## Tecnologias e Ferramentas

- [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Sass](https://sass-lang.com/)
- [Ajax](https://developer.mozilla.org/pt-BR/docs/Web/Guide/AJAX)
- [font-awesom](https://fontawesome.com/)

## Motivação

Estudar e entender técnicas e conecitos relacionados a aprensentação de uma página web, neste projeto é notável a hamia como cada sessão se posicionam, bem como a escolha das cores e composição do site como um todo.

## Requerimentos

Instalar o Sass

- [Sass](https://sass-lang.com/)
- Conexão com a internet

**OBS.:** _Tanto o Ajax quando Font Awesom estão sendo linkados ao projeto por meio do links para CDNs, portanto se faz necessário a conexão com a internet para testes locais._

## Instalação e Executar

Basta clonar o projeto

```bash
git clone https://github.com/guedes-jr/Front_End-Travel.git
```

Caso ainda não tenha instalado o Sass será necessário

**npm:**

```bash
npm install -g sass
```

**Chocolatey:**

```bash
choco install sass
```

**Homebrew:**

```bash
choco install sass
```

Após instalar o sass basta compilá-lo através do seguinte comando no terminal:

```bash
sass input.scss output.css
```

Caso esteja fazendo alterações no projeto pode estar utilizando o seguinte comando:

```bash
sass --watch input.scss output.css
```

Diferentemente do anterior esse atualiza em tempo real não sendo necessário executar sempre que for feita uma nova alteração

## Reference

- [Sass](https://sass-lang.com/)
- [Ajax](https://developer.mozilla.org/pt-BR/docs/Web/Guide/AJAX)
- [font-awesom](https://fontawesome.com/)
- [Mr. Web Designer](https://www.youtube.com/c/MrWebDesignerAnas/videos)
