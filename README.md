# Timple Bootstrap

## A boost for Bootstrap 💪

I improved Bootstrap media query sizes to cover all those screen resolutions that constantly give me a headache.

> Current Boostrap version: [4.3.1](https://getbootstrap.com/docs/4.3/getting-started/introduction/)

### Grid options

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
        Extra-extra large<br>
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

### Cooler collapse menu

Instead of the boring collapse Bootstrap offers I implemented a cool collapse from the left that closes when one clicks on the outside.

The html structure is very similar to the one BS uses, so be careful when implementing:

```
<nav class="navbar navbar-expand-lg navbar-off-canvas navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="offcanvas" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <div class="navbar-collapse--content">

      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Dropdown
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Something else here</a>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
        </li>
      </ul>
      <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>

```

---

En caso de querer hacer una actualización recordar salvar el archivo variables, para no perder los tamaños modificados de media querys.
