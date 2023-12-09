# Guias de estilo do Google

Todo grande projeto de código aberto tem seu próprio guia de estilo: um conjunto de convenções
(às vezes arbitrário) sobre como escrever código para esse projeto. Isso é muito
mais fácil entender uma base de código grande quando todo o código nela contido está consistente
estilo.

“Estilo” cobre muito, desde “usar camelCase para nomes de variáveis” até
“nunca use variáveis globais” para “nunca use exceções”. Este projeto
([google/styleguide](https://github.com/google/styleguide)) links para o estilo
diretrizes que usamos para o código do Google. Se você estiver modificando um projeto que
originado no Google, você pode ser direcionado para esta página para ver os guias de estilo
que se aplicam a esse projeto.


*   [AngularJS Style Guide][angular]
*   [Common Lisp Style Guide][cl]
*   [C++ Style Guide][cpp]
*   [C# Style Guide][csharp]
*   [Go Style Guide][go]
*   [HTML/CSS Style Guide][htmlcss]
*   [JavaScript Style Guide][js]
*   [Java Style Guide][java]
*   [Objective-C Style Guide][objc]
*   [Python Style Guide][py]
*   [R Style Guide][r]
*   [Shell Style Guide][sh]
*   [Swift Style Guide][swift]
*   [TypeScript Style Guide][ts]
*   [Vim script Style Guide][vim]

Este projeto também contém [cpplint][cpplint], uma ferramenta para auxiliar no guia de estilo
conformidade e [google-c-style.el][emacs], um arquivo de configurações do Emacs para o Google
estilo.

Se o seu projeto exigir a criação de um novo formato de documento XML, o
[Guia de estilo de formato de documento XML][xml] pode ser útil. Além de real
regras de estilo, ele também contém conselhos sobre como projetar o seu próprio ou adaptar um
formato existente, na formatação de documentos de instância XML e em elementos vs.
atributos.

Os guias de estilo neste projeto são licenciados sob a licença CC-By 3.0, que
incentiva você a compartilhar esses documentos. Ver
[https://creativecommons.org/licenses/by/3.0/][ccl] para mais detalhes.

The following Google style guide lives outside of this project:
[Effective Dart][dart].

## Contributing

With few exceptions, these style guides are copies of Google's internal style
guides to assist developers working on Google owned and originated open source
projects. Changes to the style guides are made to the internal style guides
first and eventually copied into the versions found here. **External
contributions are not accepted.** Pull requests are regularly closed without
comment. Issues that raise questions, justify changes on technical merits, or
point out obvious mistakes may get some engagement and could in theory lead to
changes, but we are primarily optimizing for Google's internal needs.

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>

[cpp]: https://google.github.io/styleguide/cppguide.html
[csharp]: https://google.github.io/styleguide/csharp-style.html
[swift]: https://google.github.io/swift/
[objc]: objcguide.md
[go]: go/
[java]: https://google.github.io/styleguide/javaguide.html
[py]: https://google.github.io/styleguide/pyguide.html
[r]: https://google.github.io/styleguide/Rguide.html
[sh]: https://google.github.io/styleguide/shellguide.html
[htmlcss]: https://google.github.io/styleguide/htmlcssguide.html
[js]: https://google.github.io/styleguide/jsguide.html
[ts]: https://google.github.io/styleguide/tsguide.html
[angular]: https://google.github.io/styleguide/angularjs-google-style.html
[cl]: https://google.github.io/styleguide/lispguide.xml
[vim]: https://google.github.io/styleguide/vimscriptguide.xml
[cpplint]: https://github.com/google/styleguide/tree/gh-pages/cpplint
[emacs]: https://raw.githubusercontent.com/google/styleguide/gh-pages/google-c-style.el
[xml]: https://google.github.io/styleguide/xmlstyle.html
[dart]: https://www.dartlang.org/guides/language/effective-dart
[ccl]: https://creativecommons.org/licenses/by/3.0/
