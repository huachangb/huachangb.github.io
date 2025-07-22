<!-- publications -->
{% include publication_list.html
  title="Publications"
  id="publications"
  items=site.data.publications.main
%}

<!-- preprints -->
{% if site.data.publications.preprint %}
  {% include publication_list.html
    title="Preprints"
    id="publications"
    items=site.data.publications.preprint
  %}
{% endif %}
