<h2 id="publications" style="margin: 30px 0px -15px;">Selected Publications <temp style="font-size:15px;">[</temp><a href="https://scholar.google.com/citations?hl=en&user=GzBuFCAAAAAJ&view_op=list_works&sortby=pubdate" target="_blank" style="font-size:15px;">Google Scholar</a><temp style="font-size:15px;">]</temp></h2>


<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
  <div class="pub-row">
    
    <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 20px;">
        <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
        <div class="author">{{ link.authors }}</div>
        <div class="periodical"><em>{{ link.conference }}</em>
        </div>
      <div class="links">
        {% if link.pdf %} 
        <a href="{{ link.pdf }}" class="btn btn-pdf btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">
          <i class="fa-solid fa-file-pdf"></i> PDF
        </a>
        {% endif %}
        {% if link.code %} 
        <a href="{{ link.code }}" class="btn btn-code btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">
          <i class="fa-brands fa-github"></i> Code
        </a>
        {% endif %}
        {% if link.page %} 
        <a href="{{ link.page }}" class="btn btn-ppage btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">
          <i class="fas fa-mouse"></i> Project Page
        </a>
        {% endif %}
        {% if link.bibtex %} 
        <a href="{{ link.bibtex }}" class="btn btn-bibtex btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">
          <i class="fas fa-book"></i> BibTeX
        </a>
        {% endif %}
        {% if link.notes %} 
        <strong> <i style="color:#ed8f87">{{ link.notes }}</i></strong>
        {% endif %}
        {% if link.others %} 
        {{ link.others }}
        {% endif %}
      </div>
    </div>
  </div>
</li>

<br>

{% endfor %}
</ol>
</div>


