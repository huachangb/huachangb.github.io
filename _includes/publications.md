<!-- publications -->
{% include publication_list.html
  title="Publications"
  items=site.data.publications.main
%}

<!-- preprints -->
{% if site.data.publications.preprint %}
  {% include publication_list.html
    title="Preprints"
    items=site.data.publications.preprint
  %}
{% endif %}
