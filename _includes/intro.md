<div class="well">
    <div class="row">
        <div class="col-md-4">
<!--             ![Profile Picture](/assets/miles.jpg?raw=true){:class="img-responsive"} -->
            <img class="img-responsive" src="/assets/miles_ramsey.jpg" alt="Profile Picture">
        </div>
        <div class="col-md-8">
            <h3>
                {{ site.title }}
            </h3>
            <p>
                {% capture intro_include %}{% include intro-text.md %}{% endcapture %}
                {{ intro_include | markdownify }}
            </p>
        </div>
    </div>
</div>
