# Mentoria Dropshipping - Landing Page

Este projeto é uma landing page desenvolvida para promover uma **mentoria de Dropshipping**. O objetivo da página é gerar conversões ao atrair usuários interessados em aprender sobre o modelo de negócios de Dropshipping, destacando os benefícios e os resultados que podem ser alcançados em apenas 14 dias de dedicação.

A página apresenta um design moderno, com uma combinação de cores impactantes e um layout limpo e responsivo. Ela contém uma introdução clara sobre a mentoria, campos de formulário para inscrição e um botão de ação para garantir a vaga, tudo isso em um formato que se adapta a diferentes tamanhos de telas.

![pagina](https://github.com/user-attachments/assets/ba34e6b4-05be-42bd-996f-ca2f52d7e589)


## Descrição

A página é composta por um layout simples, mas eficaz, que visa fornecer uma experiência clara e objetiva para o usuário. A interface é intuitiva, com foco em conversões. Ela contém:

1. **Título chamativo**: Atraindo a atenção do usuário para o principal benefício da mentoria.
2. **Texto explicativo**: Detalha rapidamente o que o usuário pode esperar da mentoria e o impacto de apenas 14 dias de dedicação.
3. **Campos de inscrição**: O usuário insere seu nome e e-mail para garantir sua vaga.
4. **Botão de ação**: O botão "Garantir minha vaga agora" incentiva o usuário a se inscrever na mentoria.
5. **Imagem do mentor**: Uma imagem que representa visualmente o mentor do curso, aumentando a credibilidade do projeto.

### Estilo e Design

O design visual foi construído com base em uma paleta de cores verde e preta, que visa transmitir uma sensação de confiança, profissionalismo e ação. As principais características do estilo são:

- **Gradientes de fundo**: O fundo é composto por um gradiente linear que mistura as cores verde escuro e preto.
- **Tipografia**: O uso de fontes sem serifa garante boa legibilidade e um visual moderno.
- **Responsividade**: O layout foi otimizado para funcionar bem em telas de diferentes tamanhos, desde desktops grandes até dispositivos móveis. O conteúdo se reorganiza em uma estrutura de coluna em telas menores, garantindo que a página seja sempre acessível e fácil de navegar.

### Estrutura do Layout

A página é dividida em duas seções principais:

- **Box Content**: Contém o título, a descrição e os campos de entrada de dados (nome e e-mail), junto com o botão de ação.
- **Box Image**: Exibe uma imagem do mentor ou da imagem representativa do curso, com efeitos de sombra e borda arredondada para destacar visualmente a imagem.

A estrutura do layout foi projetada para ser simples e eficiente, com foco em gerar conversões de forma direta.

### Prototipagem no Figma

O protótipo desta página foi desenvolvido no **Figma**, uma ferramenta de design colaborativo, onde as interações e o layout visual foram definidos. O protótipo ajudou a visualizar a página de forma mais clara antes da implementação, garantindo que os elementos estivessem bem organizados e que a experiência do usuário fosse intuitiva.

![prototipo](https://github.com/user-attachments/assets/6c4d09ef-5e7a-4c73-910f-36e4cb671bfd)


### Responsividade

A página foi projetada para ser totalmente responsiva, adaptando-se a diferentes tamanhos de tela:

- **Telas grandes** (acima de 1250px): O layout permanece com a imagem do mentor em seu tamanho original (500px x 500px).
- **Telas médias** (até 1250px): A imagem é redimensionada para 400px x 400px.
- **Telas pequenas** (até 850px): O layout é reorganizado em formato de coluna, onde o conteúdo se empilha verticalmente para facilitar a navegação em dispositivos móveis.

### Código CSS

O arquivo CSS utiliza variáveis para definir a paleta de cores e adota um estilo de design simples, com foco na clareza e usabilidade. O uso de **gradientes** e **efeitos de hover** nos botões adiciona um toque moderno à interface.

### Exemplo de código CSS:

```css
:root{
    --primary:  #006400;
    --secundary:#91FA46;
    --secundary-ligth: #1c4102;
    --black:    #022602;
    --white:    #F9FFF9;
}

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    outline: none;
    border: none;
}

body{
    background-color: var(--white);
    font-family: Arial, Helvetica, sans-serif;
}

/* Estilo do conteúdo e dos botões */
.container main .box-content .box-button button:hover{
    background-image: linear-gradient(to left, var(--primary), var(--secundary));
}
