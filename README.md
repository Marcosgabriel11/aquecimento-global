# Nosso Planeta, Nosso Futuro — Aquecimento Global

Site educativo e responsivo sobre aquecimento global, suas causas, consequências e soluções. Construído apenas com **HTML5 e CSS3**, sem JavaScript, frameworks ou bibliotecas de interface.

## Arquivos

- `index.html` — apresentação do projeto
- `causas.html` — principais causas e explicação do efeito estufa
- `solucoes.html` — soluções e atitudes práticas
- `galeria.html` — galeria visual com legendas
- `contato.html` — formulário demonstrativo e contatos fictícios
- `style.css` — estilos compartilhados por todas as páginas

## Como executar

1. Baixe e extraia os arquivos do projeto.
2. Mantenha todos os arquivos na mesma pasta.
3. Abra `index.html` em um navegador moderno.

Não é necessário instalar nada ou iniciar um servidor. Para publicar no GitHub Pages, envie os arquivos para um repositório e habilite o GitHub Pages nas configurações.

## Imagens

As imagens usam URLs do Unsplash e, portanto, precisam de conexão com a internet. Para usar imagens locais, crie uma pasta `img/`, salve nela as fotografias e substitua os endereços `https://images.unsplash.com/...` nos arquivos HTML e no `style.css` pelos caminhos locais, por exemplo `img/floresta.jpg`.

## Formulário de contato

O formulário foi estilizado e inclui validação básica dos campos pelo próprio navegador. **Ele não envia mensagens de verdade** porque este projeto é estático e não possui JavaScript nem backend. Para receber mensagens, será necessário integrar um endpoint de servidor ou um serviço de formulários compatível e configurar o atributo `action` do formulário conforme a documentação desse serviço.

## Acessibilidade e responsividade

- HTML semântico, idioma `pt-BR`, rótulos nos campos e textos alternativos nas imagens.
- Link para pular diretamente ao conteúdo principal.
- Estados de foco visíveis para navegação por teclado.
- Layout adaptável a telas menores com media queries.
- Respeito à preferência do sistema por movimento reduzido.

## Paleta de cores

- Verde-escuro: `#12372A`
- Verde-natureza: `#2E8B57`
- Azul oceano: `#168AAD`
- Bege-claro: `#F5F1E8`
- Laranja solar: `#F4A261`
