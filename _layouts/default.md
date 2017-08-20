<!DOCTYPE html>
<html lang="{{ page.lang | default: site.lang | default: "en" }}">

  {% include head.md %}

  <body>
    
    <main class="page-content container" aria-label="Content">
      <div class="wrapper">
        {{ content }}
      </div>
    </main>

    {% include footer.md %}

  </body>

</html>
