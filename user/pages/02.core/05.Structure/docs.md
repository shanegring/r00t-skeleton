---
title: Resonsive utilities
taxonomy:
    category:
        - docs
visible: true
---

Responsive utilities
For faster mobile-friendly development, use these utility classes for showing and hiding content by device via media query. Also included are utility classes for toggling content when printed.

Try to use these on a limited basis and avoid creating entirely different versions of the same site. Instead, use them to complement each device’s presentation.

Available classes:
<ul>
  <li>The <code class="highlighter-rouge">.hidden-*-up</code> classes hide the element when the viewport is at the given breakpoint or wider. For example, <code class="highlighter-rouge">.hidden-md-up</code> hides an element on medium, large, and extra-large viewports.</li>
  <li>The <code class="highlighter-rouge">.hidden-*-down</code> classes hide the element when the viewport is at the given breakpoint or smaller. For example, <code class="highlighter-rouge">.hidden-md-down</code> hides an element on extra-small, small, and medium viewports.</li>
  <li>There are no explicit “visible”/”show” responsive utility classes; you make an element visible by simply not hiding it at that breakpoint size.</li>
  <li>You can combine one <code class="highlighter-rouge">.hidden-*-up</code> class with one <code class="highlighter-rouge">.hidden-*-down</code> class to show an element only on a given interval of screen sizes. For example, <code class="highlighter-rouge">.hidden-sm-down.hidden-xl-up</code> shows the element only on medium and large viewports. Using multiple <code class="highlighter-rouge">.hidden-*-up</code> classes or multiple <code class="highlighter-rouge">.hidden-*-down</code> classes is redundant and pointless.</li>
  <li>These classes don’t attempt to accommodate less common cases where an element’s visibility can’t be expressed as a single contiguous range of viewport breakpoint sizes; you will instead need to use custom CSS in such cases.</li>
</ul>


<table class="table table-bordered table-striped responsive-utilities table-responsive">
  <thead>
    <tr>
      <th></th>
      <th>
        Extra small devices
        <small>Portrait phones (&lt;544px)</small>
      </th>
      <th>
        Small devices
        <small>Landscape phones (≥544px - &lt;768px)</small>
      </th>
      <th>
        Medium devices
        <small>Tablets (≥768px - &lt;992px)</small>
      </th>
      <th>
        Large devices
        <small>Desktops (≥992px - &lt;1200px)</small>
      </th>
      <th>
        Extra large devices
        <small>Desktops (≥1200px)</small>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row"><code>.hidden-xs-down</code></th>
      <td class="is-hidden">Hidden</td>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
    </tr>
    <tr>
      <th scope="row"><code>.hidden-sm-down</code></th>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
    </tr>
    <tr>
      <th scope="row"><code>.hidden-md-down</code></th>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
    </tr>
    <tr>
      <th scope="row"><code>.hidden-lg-down</code></th>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-visible">Visible</td>
    </tr>
    <tr>
      <th scope="row"><code>.hidden-xl-down</code></th>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
    </tr>
    <tr>
      <th scope="row"><code>.hidden-xs-up</code></th>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
    </tr>
    <tr>
      <th scope="row"><code>.hidden-sm-up</code></th>
      <td class="is-visible">Visible</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
    </tr>
    <tr>
      <th scope="row"><code>.hidden-md-up</code></th>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
    </tr>
    <tr>
      <th scope="row"><code>.hidden-lg-up</code></th>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
      <td class="is-hidden">Hidden</td>
      <td class="is-hidden">Hidden</td>
    </tr>
    <tr>
      <th scope="row"><code>.hidden-xl-up</code></th>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
      <td class="is-visible">Visible</td>
      <td class="is-hidden">Hidden</td>
    </tr>
  </tbody>
</table>