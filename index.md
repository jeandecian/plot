---
layout: default
title: Python Plotting Libraries Comparison
---

<div class="container" style="margin-top: 1em">
  <h1>Python Plotting Libraries Comparison</h1>
  <h2>Libraries</h2>
  <table class="table table-hover">
    <thead>
      <tr class="table-light">
        <th scope="col">Library</th>
        <th scope="col">Ressources</th>
      </tr>
    </thead>
    <tbody>
      {% for library in site.data.libraries %}
      <tr>
        <th scope="row">{{ library.name }}</th>
        <td>
          [<a href="{{ library.website }}" target="_blank">Website</a>]
          [<a href="{{ library.gallery }}" target="_blank">Gallery</a>]
        </td>
      </tr>
      {% endfor %}
    </tbody>
  </table>
</div>
