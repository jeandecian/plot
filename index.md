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
          [<a href="{{ library.website }}" target="_blank">Website</a>] [<a
            href="{{ library.gallery }}"
            target="_blank"
            >Gallery</a
          >]
        </td>
      </tr>
      {% endfor %}
    </tbody>
  </table>
  <h2>Data</h2>
  <p>
    The following mock data is used for the examples:
    <code>mock_data.csv</code>. [<a
      href="{{ site.baseurl }}/files/mock_data.csv"
      >Download</a
    >]
  </p>
  <p>
    It contains a mixture of categorical and numerical variables, including
    date-based entries, suitable for demonstrating a wide range of plot types
    such as bar charts, line plots, scatter plots, pie charts, histograms, box
    plots, and heatmaps.Each row represents a fictional observation with
    attributes like category, subcategory, numerical values, group
    classification, and 2D coordinates—ideal for comparing how different Python
    plotting libraries handle diverse data types.
  </p>
</div>
