# Projeto de Relógio Digital

Este é um projeto simples de relógio digital utilizando HTML, CSS e JavaScript. O relógio exibe as horas, minutos e segundos atuais e possui uma borda animada colorida.

## Tecnologias Utilizadas

- HTML: Estrutura do relógio.
- CSS: Estilização do relógio e animação da borda.
- JavaScript: Atualização dinâmica do horário.

## Funcionalidades

- Exibição de horas, minutos e segundos em tempo real.
- Animação de borda colorida ao redor do relógio.

## Como Funciona

### JavaScript

O arquivo JavaScript (`script.js`) é responsável por atualizar o horário exibido no relógio a cada segundo. A função principal `updateClock` faz o seguinte:

1. Seleciona os elementos do DOM onde as horas, minutos e segundos serão exibidos.
2. Obtém o horário atual usando o objeto `Date`.
3. Formata as horas, minutos e segundos para que sempre tenham dois dígitos.
4. Atualiza o conteúdo dos elementos do DOM com os valores formatados.

A função `updateClock` é chamada a cada segundo utilizando `setInterval`, garantindo que o relógio esteja sempre atualizado.

### CSS

O arquivo CSS (`styles.css`) define a aparência do relógio, incluindo a animação da borda. A borda é criada utilizando gradientes e animações CSS para criar um efeito de movimento contínuo e colorido.

## Como Executar

1. Clone o repositório para o seu ambiente local.
2. Abra o arquivo `index.html` em um navegador web.

## Autor

Jose Neilson dos Santos

## Licença

Este projeto é licenciado sob a MIT License.
