---
title: Tabla de las notas

---

# notas

<table>
  <thead>
    <tr>
      <th>Nombre</th>
      <th>Notas</th>
      <th>Sexo</th>
    </tr>
  </thead>
  <tbody>
    {% for nota in site.data.notas %}
      <tr>
        <td>{{ nota.nombre }}</td>
        <td>{{ nota.notas }}</td>
        <td>{{ nota.sexo }}</td>
      </tr>
    {% endfor %}
  </tbody>
</table>



