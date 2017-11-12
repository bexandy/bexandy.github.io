---
title: "Mi Primer Post"
layout: post
date: 2017-02-08 11:51
tag:
- tips
blog: true
---
## Sumario:

Acá mostraremos un indice del post.

### Indice
- [Introducción](#introducción)
- [Crear Una Cuenta](#crear-una-cuenta)

---

## Introducción

En este primer post vamos a ver como crear una página estática con GitHub Pages

## Crear Una Cuenta

1 .Primero, ingresamos a la página de [GitHub][1] y nos creamos una cuenta,suministrando los datos necesarios.

En mi caso voy a configurar una organizacion. Para ello transformare mi cuenta en una organizacion.

2. Creamos un repositorio con y lo nombramos de la siguiente manera: nombre-usuario.github.io

3. Clonamos el repositorio a local.

{% highlight raw %}
git clone https://github.com/bexandy-rodriguez/bexandy-rodriguez.github.io directorio/local/
{% endhighlight %}

4. Añadimos un index.html

|Encabezado 1   |Encabezado 2    |
|---------------|----------------|
|probemos       |algo            |
|probemos alguna|otra cosa       |

5. Realizamos un add, commit y push a los cambios.

<div>
  <table frame="void" rules="cols" width="100%">
    <caption>Esta es una Tabla en HHTML</caption>
    <thead >
      <tr bgcolor="gray">
        <th>header</th>
        <th>header</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>data</td>
        <td>data</td>
      </tr>
    </tbody>
  </table>
</div>

6. En Github Pages podemos montar paginas estaticas, es decir, sitios diseñados con html, css y javascript.

## Hacer un Fork de un template Jekyll

Entrar a la configuracion del repositorio

escoger un template en templete choose
o buscar un template que te guste en
http://themes.jekyllrc.org/
https://jekyllthemes.io/



    Download or clone repo git clone git@github.com:nandomoreirame/end2end.git
    Enter the folder: cd end2end/
    Install Ruby gems: bundle install
    Start Jekyll server: jekyll serve
localhost:4000/end2end

Deploy in Github pages in 2 steps

    Change the variables GITHUB_REPONAME and GITHUB_REPO_BRANCH in Rakefile
    Run rake or rake publish for build and publish on Github



[1]: https://github.com/
