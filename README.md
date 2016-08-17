# Iniciando com Git

Apresentação sobre Git feita por [Felipe Pontes](//github.com/felipemfp) e [Francisco Bento](//github.com/chicobentojr). :octocat: :books:

### Para editar

Primeiro de tudo, instale as dependências do [Qualy-Presenter](//github.com/qualy-org/qualy-presenter):

- [NodeJS](//nodejs.org/)
- [GulpJS](//gulpjs.com/)

```sh
# Clone este repositório
$ git clone https://github.com/felipemfp/iniciando-com-git
$ cd new_project
# Instale as dependências
$ npm install
# Executar tarefas e servir
$ gulp
```

### Como usar o Qualy-Presenter

- Escreva os slides na pasta `src/slides` em arquivos separados usando a [sintexe Jade](//jade-lang.com/) e adicione eles em `templates/index.jade`.

- Se você quiser adicionar outros _scripts_ ou _css_, use a pasta `templates/inc/` e chame eles em `templates/index.jade`.

- Para alterar temas veja [src/styl/reveal-themes](src/styl/reveal-themes) e chame eles em [src/styl/main.styl](src/styl/main.styl).

- Para temas do _highlight_ veja [src/styl/highlight-themes](src/styl/highlight-themes/).

### Mais informações

Para mais informações sobre o __[Qualy-Presenter](//github.com/qualy-org/qualy-presenter)__ veja a documentação do mesmo no [próprio repositório](//github.com/qualy-org/qualy-presenter).

### Licença

Este projeto é licenciado sobre a licença MIT, veja [LICENSE](LICENSE) para mais detalhes.
