GEMCSS
======

El paradigma GEM (globals, elements and modules) está basado en conceptos como OOCSS y SMACSS.

GEM son las siglas, y prefijos, de los tres tipos de clases utilizadas para crear nuestros CSS. Por lo tanto, usaremos ‘.g-’ para las globales, ‘.e-’ para los elementos y ‘.m-’ para módulos.

Estos tienen un orden de mayor a menor en complejidad y de menor a mayor en repetición. Siendo los globales los más abstractos, los elementos la unidad mínima y los módulos una estructura más compleja que los anteriores.

Las clases globales también llamadas en otras arquitecturas 'base' o 'utils', son aquellas que usamos en innumerables ocasiones, normalmente con una única propiedad. Sirven para extender, pudiéndolo hacer entre ellas, elementos y módulos. Ejemplo de clases globales: .g-floatL,  .g-inlineBlock, .g-colorA, .g-column1 o .g-gutter.

Los prefijos para las clases hijas de modelos y elementos deben comenzar por el nombre de este. Por lo que, las clases hijas de ‘.m-tabs’ serán ‘.m-tabs-element’ o ‘.m-tabs-inner’. Ya que recomendamos no usar más de tres clases hijas, siendo ideal una especificidad de 10, es decir un único selector de clase para cada una de ellas, proponemos usar la nomenclatura ‘.m-/.e-’ + ‘outer/element/inner’. Siendo ‘-element’ el elemento principal, ’-outer’ una clase que lo recubra e ‘-inner’ una clase hija del elemento principal.

El uso de este paradigma no solo afecta al CSS. Es la arquitectura que debe marcar el camino en el desarrollo del templating. Utilizando una estructura modular, independientemente del lenguaje que se utilice. Reutilizando los módulos y elementos tantas veces como sea necesario, teniendo siempre presentes principios como [DRY](http://es.wikipedia.org/wiki/No_te_repitas) (Don't Repeat Yourself) o [KISS](http://es.wikipedia.org/wiki/Principio_KISS) (Keep It Simple, Stupid!).


**Referencias**

* [OOCSS](https://github.com/stubbornella/oocss/wiki)
* [BEM](http://bem.info/)
* [SMACSS](http://smacss.com/)
* [Architecting Scalable CSS](http://vimeo.com/70041549) (Vídeo)
* [Session: Scalable and Modular CSS FTW!](http://oredev.org/2012/sessions/scalable-and-modular-css-ftw)
* [SUITCSS](https://github.com/suitcss/suit)
* [OOCSS Code Standards](https://github.com/stubbornella/oocss-code-standards)
* [CSS-Guidelines](https://github.com/csswizardry/CSS-Guidelines)
* [Google General Style Rules](http://google-styleguide.googlecode.com/svn/trunk/htmlcssguide.xml#General_Style_Rules)
* [html5-boilerplate](https://github.com/h5bp/html5-boilerplate)
* [normalize.css](https://github.com/necolas/normalize.css)
* [CSS Tools: Reset CSS](http://meyerweb.com/eric/tools/css/reset/)
* [Browserhacks](http://browserhacks.com/)

**Autor**

* GitHub: [Víctor García](https://github.com/gc-victor)
* Twitter: [@gcv](http://twitter.com/gcv) 

**Licencia**

Public domain: [http://unlicense.org/](http://unlicense.org/)
