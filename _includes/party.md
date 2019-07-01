<div class="well">
    <div class="row">
        <div class="col-md-12">
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
