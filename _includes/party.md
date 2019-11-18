<div class="well">
    <div class="row">
        <div class="col-md-12 christmas">
            <h1 class="text-center">
                <span>M</span>
                <span>i</span>
                <span>l</span>
                <span>e</span>
                <span>s</span>
            </h1>
            <p>
                {% capture intro_include %}{% include intro-text.md %}{% endcapture %}
                {{ intro_include | markdownify }}
            </p>
        </div>
    </div>
</div>
