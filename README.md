# Web Crawler para Extração de Dados de Ranking de Filmes

Este projeto consiste em um web crawler desenvolvido para coletar dados de ranking de filmes, buscar as capas dos filmes e elaborar um relatório para apresentar os dados obtidos.

## Nosso Objetivo

O objetivo principal deste projeto é automatizar a coleta de informações sobre o ranking de filmes disponíveis em determinadas fontes na web. Além disso, buscamos obter as capas dos filmes para enriquecer os dados coletados.

## Funcionalidades Principais

1. **Extração de Dados de Ranking de Filmes:** O web crawler é capaz de navegar por diferentes fontes de ranking de filmes na web e extrair informações como título, classificação, gênero, entre outros.

2. **Busca de Capas de Filmes:** Além de coletar informações textuais, o crawler busca as capas dos filmes para enriquecer os dados obtidos, proporcionando uma experiência visual mais completa.

## Tecnologias Utilizadas

 - **Python:** A linguagem de programação principal para o desenvolvimento do web crawler.

- **Beautiful Soup:** Uma biblioteca Python para extração de dados de documentos HTML e XML. É conhecida pela sua simplicidade e facilidade de uso. Trabalha bem com parsers como lxml e html5lib.
  
- **Selenium:** Embora seja comumente usado para automação de testes, o Selenium também pode ser utilizado para web scraping interativo. Ele permite a automação do navegador, possibilitando a extração de dados de páginas da web que usam JavaScript para renderização.

- **Requests-HTML:** Uma biblioteca simples e amigável para fazer solicitações HTTP e interagir com o conteúdo HTML de uma página. Oferece uma sintaxe intuitiva para navegar e extrair dados de páginas web.

## Como Utilizar

1. **Instalação das Dependências:** Antes de executar o projeto, certifique-se de ter todas as dependências instaladas. Você pode instalá-las executando `pip install -r requirements.txt`.

2. **Execução do Crawler:** Execute o script principal do crawler, que iniciará o processo de coleta de dados e busca de capas de filmes.

3. **Customização:** Caso deseje personalizar a fonte dos dados ou as configurações do crawler, você pode modificar os parâmetros no arquivo de configuração correspondente.

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema, tiver sugestões de melhorias ou quiser adicionar novos recursos, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Esperamos que este projeto seja útil para quem busca automatizar a coleta de dados de ranking de filmes e gerar insights a partir dessas informações. Divirta-se explorando e analisando os dados!

---

