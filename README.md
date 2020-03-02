# Timple BS

## Un boost para Bootstrap 🤓

Versión de Boostrap: 4.3.1

En caso de querer hacer una actualización recordar salvar el archivo variables, para no perder los tamaños modificados de media querys.

<table>
  <thead>
    <tr>
      <th></th>
      <th class="text-center">
        Extra small<br>
        <small>&lt;768px</small>
      </th>
      <th class="text-center">
        Small<br>
        <small>≥768px</small>
      </th>
      <th class="text-center">
        Medium<br>
        <small>≥992px</small>
      </th>
      <th class="text-center">
        Large<br>
        <small>≥1260px</small>
      </th>
      <th class="text-center">
        Extra large<br>
        <small>≥1300px</small>
      </th>
      <th class="text-center">
        Requete large<br>
        <small>≥1820px</small>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th class="text-nowrap" scope="row">Max container width</th>
      <td>None (auto)</td>
      <td>720px</td>
      <td>960px</td>
      <td>1040px</td>
      <td>1140px</td>
      <td>1800px</td>
    </tr>
    <tr>
      <th class="text-nowrap" scope="row">Class prefix</th>
      <td><code>.col-</code></td>
      <td><code>.col-sm-</code></td>
      <td><code>.col-md-</code></td>
      <td><code>.col-lg-</code></td>
      <td><code>.col-xl-</code></td>
      <td><code>.col-xxl-</code></td>
    </tr>
    <tr>
      <th class="text-nowrap" scope="row"># of columns</th>
      <td colspan="6">12</td>
    </tr>
    <tr>
      <th class="text-nowrap" scope="row">Gutter width</th>
      <td colspan="6">30px (15px on each side of a column)</td>
    </tr>
    <tr>
      <th class="text-nowrap" scope="row">Nestable</th>
      <td colspan="6">Yes</td>
    </tr>
    <tr>
      <th class="text-nowrap" scope="row">Column ordering</th>
      <td colspan="6">Yes</td>
    </tr>
  </tbody>
</table>



### For forgetful Agos:

```
sass --watch scss/bootstrap.scss:dist/css/bootstrap.css
sass --watch scss/bootstrap.scss:dist/css/bootstrap.min.css --style compressed
```
