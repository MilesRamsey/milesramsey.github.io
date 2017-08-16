<header class="site-header" role="banner">

  <div class="wrapper">
    {% assign default_paths = site.pages | map: "path" %}
    {% assign page_paths = site.header_pages | default: default_paths %}
    <a class="site-title" href="{{ "/" | relative_url }}">{{ site.title | escape }}</a>
  
    <nav class="navbar navbar-default navbar-inverse navbar-fixed-top" role="navigation">
        <div class="navbar-header">
          <a class="navbar-brand" href="#">Miles Ramsey</a>
        </div>
        <div class="collapse navbar-collapse navbar-ex1-collapse pull-right">
          <ul class="nav navbar-nav">
            <li class="active">
              <a class="scrollable" href="#about">About</a>
            </li>
            <li>
              <a class="scrollable" href="#portfolio">Portfolio</a>
            </li>
            <li>
              <a class="scrollable" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </nav>
  </div>
</header>
