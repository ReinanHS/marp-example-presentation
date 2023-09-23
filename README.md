<div align="center">
   <img src="https://marp.app/assets/marp.svg" alt="Marp Logo" width="40%">
</div><br>

# Marp Example Presentation

Este é o meu primeiro experimento com a ferramenta Marp, que permite gerar slides usando Markdown. Neste repositório, você encontrará as configurações básicas para começar a criar suas próprias apresentações usando Marp. 

## Objetivo

Meu principal objetivo com este repositório é aprender como usar a ferramenta e compartilhar uma apresentação sobre as Maravilhas Naturais do Nordeste Brasileiro.

## Apresentação

A apresentação contém informações sobre as seguintes tópicos:

- Praias Deslumbrantes
- Formações Rochosas
- Cânions e Cachoeiras
- Biodiversidade Rica
- Sabores do Nordeste
- Artesanato e Cultura

Este projeto utiliza automações de CI/CD para processar as informações automaticamente sempre que houver alterações na branch `main`. Isso significa que, ao fazer push das alterações para a branch principal, o sistema irá automaticamente exportar a apresentação para o formato HTML.

![Google Chrome - Light](https://github.com/ReinanHS/marp-example-presentation/assets/28494067/e46db1e1-0f1c-4f13-b669-5775227bfa6c)

Para visualizar a apresentação no seu navegador, [clique neste link](https://reinanhs.github.io/marp-example-presentation/). 

## Como Usar

1. Clone este repositório para a sua máquina local usando o comando abaixo:

```bash
git clone https://github.com/ReinanHS/marp-example-presentation.git
```

2. Abra o arquivo `slide-deck.md` em um editor de texto ou Markdown de sua escolha.
3. Personalize o conteúdo da apresentação de acordo com suas necessidades. Você pode usar Markdown para formatar os slides.
4. Depois de personalizar sua apresentação, você pode gerar os slides em formato PDF.
5. Execute o comando abaixo para gerar os slides no formato PDF:

```bash
docker run --rm --init -v "${PWD}:/home/marp/app/" marpteam/marp-cli slide-deck.md --pdf
```

6. No final da execução, será gerado o arquivo `slide-deck.pdf` na raiz do seu projeto.

## Software stack

Esse projeto roda nos seguintes softwares:

- Git 2.33+
- Marp 2.7.0
- Docker

## Changelog

Por favor, veja [CHANGELOG](CHANGELOG.md) para obter mais informações sobre o que mudou recentemente.

## Seja um dos contribuidores

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou adicionar recursos a este repositório. Basta criar um fork do projeto, fazer as alterações e enviar um pull request. Suas contribuições serão bem-vindas!

Quer fazer parte desse projeto? leia [como contribuir](CONTRIBUTING.md).

## Licença

Este projeto é licenciado sob a Licença MIT. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.
