# Estudos de Pseudo-Classes e Pseudo-Elementos em CSS

## Introdução
Este projeto explora o uso de pseudo-classes e pseudo-elementos em CSS para criar uma navegação estilosa e breadcrumbs dinâmicos. Pseudo-classes e pseudo-elementos são essenciais para a estilização avançada, permitindo manipular o estado de elementos e inserir conteúdo adicional.

## Estrutura do Projeto

### HTML
O HTML deste projeto possui uma header para simular a utilização de breadCrumbs

### CSS
O CSS utiliza pseudo-classes e pseudo-elementos para adicionar interatividade e conteúdo extra aos elementos.

## Explicação das Propriedades CSS Utilizadas
### Pseudo-Classes
- :hover: Aplica estilos quando o usuário interage com o elemento passando o mouse sobre ele. Utilizado para destacar links na navegação e breadcrumbs.

### Pseudo-Elementos
- ::after: Insere conteúdo após o conteúdo de um elemento. nesse projeto utilizado para adicionar setas (>) entre os itens de breadcrumb, exceto no último item.

```css
.breadCrumbs li:not(:last-child)::after {
    content: ">";
}
```

## Conclusão
Este projeto é uma introdução prática ao uso de pseudo-classes e pseudo-elementos em CSS, mostrando como eles podem ser utilizados para criar interfaces de usuário interativas e dinâmicas. Continuarei estudando e aprimorando minhas habilidades em CSS para construir layouts mais sofisticados e funcionais.

## Contribuição 

Este é um projeto de código aberto, então sinta-se à vontade para contribuir com sugestões, correções de bugs ou até mesmo novas funcionalidades. Todas as contribuições são bem-vindas!

## Licença 

Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo [LICENSE](LICENSE).

---
