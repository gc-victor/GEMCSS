GEMCSS
======

El paradigma GEM (globals, elements and modules) está basado en conceptos como OOCSS y SMACSS.

Usamos tres tipos de clases en nuestros CSS, utilizando los prefijos para especificar el tipo al que nos referimos. Por lo tanto usaremos ‘.g-’ para las globales, ‘.e-’ para los elementos y ‘.m-’ para módulos.

Estos tienen un orden de mayor a menor en complejidad y de menor a mayor en repetición. Siendo los globales los más abstractos, los elementos la unidad mínima e independientes y los módulos una estructura más compleja que los anteriores.

Los prefijos para las clases hijas de modelos y elementos deben comenzar por el nombre de este, es decir, las clases hijas de .m-tabs serán ‘.m-tabs-element’ o ‘.m-tabs-inner’. Como en el ejemplo y ya que recomendamos no usar más de tres clases hijas proponemos usar la nomenclatura ‘.m-/.e-’ + ‘outer/element/inner’. Siendo ‘-element’ el elemento principal, ’-outer’ una clase que lo recubra e ‘-inner’ una clase hija del elemento principal.

**Referencias**

* [OOCSS](https://github.com/stubbornella/oocss/wiki)
* [BEM](http://bem.info/)
* [SMACSS](http://smacss.com/)
* [Session: Scalable and Modular CSS FTW!](http://oredev.org/2012/sessions/scalable-and-modular-css-ftw)
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
