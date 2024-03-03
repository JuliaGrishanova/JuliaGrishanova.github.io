---
title: Tabla de los ibros

---

# LIBROS

<table>
  <thead>
    <tr>
      <th>Título</th>
      <th>Autor</th>
      <th>Páginas</th>
    </tr>
  </thead>
  <tbody>
    {% for libro in site.data.libros %}
      <tr>
        <td>{{ libro.titulo }}</td>
        <td>{{ libro.autor }}</td>
        <td>{{ libro.paginas }}</td>
      </tr>
    {% endfor %}
  </tbody>
</table>

[Regresar a Home](/)

