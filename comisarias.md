---
title: Tabla de las comisarias

---

# Comisarias

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Nombre</th>
      <th>Direccion</th>
    </tr>
  </thead>
  <tbody>
    {% for comisaria in site.data.comisarias %}
      <tr>
        <td>{{ comisaria.id }}</td>
        <td>{{ comisaria.nombre }}</td>
        <td>{{ comisaria.direccion }}</td>
      </tr>
    {% endfor %}
  </tbody>
</table>



