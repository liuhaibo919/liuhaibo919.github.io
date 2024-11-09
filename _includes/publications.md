<h2 id="publications" style="margin: 30px 0px -15px;">Selected Publications <temp style="font-size:15px;">[</temp><a href="https://scholar.google.com/citations?user=thYLaZgAAAAJ&hl=en" target="_blank" style="font-size:15px;">Google Scholar</a><temp style="font-size:15px;">]</temp></h2>


<div class="publications">
{% for link in site.data.publications.main %}
    <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 20px;">
        <div class="title">
      <abbr class="badge">{{ link.pub_short }}</abbr>{{ link.title }}
        </div>
        <div class="author">{{ link.authors }}</div>
        <div class="periodical"><em>{{ link.pub_detail }}</em></div>
    </div>
    <br>
{% endfor %}
</div>


