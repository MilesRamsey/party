<div class="well">
    <div class="row">
        <div class="col-md-12 christmas">
            <h1 class="text-center">
                <span>M</span><span>i</span><span>l</span><span>e</span><span>s</span><span>'</span>
                <span>A</span><span>n</span><span>n</span><span>u</span><span>a</span><span>l</span>
                <span>H</span><span>o</span><span>l</span><span>i</span><span>d</span><span>a</span><span>y</span>
                <span>B</span><span>a</span><span>s</span><span>h</span><span>!</span>
            </h1>
            <p>
                {% capture intro_include %}{% include intro-text.md %}{% endcapture %}
                {{ intro_include | markdownify }}
            </p>
        </div>
    </div>
</div>
