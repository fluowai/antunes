# Antunes Imóveis

Site responsivo da Antunes Imóveis, com catálogo de imóveis, filtros, favoritos salvos no navegador e contato pelo WhatsApp.

## Executar localmente

O site é estático e não exige instalação de dependências.

```sh
python3 -m http.server 8080
```

Abra http://localhost:8080. Use um servidor HTTP para carregar `properties.json` corretamente.

## Estrutura

- `index.html`: página principal e janela de detalhes.
- `style.css`: layout responsivo e identidade visual.
- `app.js`: filtros, favoritos, catálogo e links de contato.
- `properties.json`: dados dos imóveis consultados no site oficial.
- `assets/`: fotografias e logos SVG, incluindo versão para fundo escuro.

## Atualizar imóveis

Edite `properties.json` e coloque as fotos correspondentes em `assets/`. O catálogo não possui sincronização automática com o site original. Valores e disponibilidade devem ser confirmados com a imobiliária.

## Publicação

Publique os arquivos da raiz em qualquer hospedagem de sites estáticos. O projeto não usa backend, credenciais ou variáveis de ambiente. As imagens de ambientação do banner e do atendimento são ilustrativas; as fotos dos anúncios foram obtidas do catálogo oficial.
