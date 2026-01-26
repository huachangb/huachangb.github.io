<!-- publications -->
{% include publication_list.html
  title="Publications"
  items=site.data.publications.main
%}

<!-- workhop papers --> 
{% include publication_list.html
  title="Workshop Papers"
  items=site.data.publications.workshop
%}

<!-- preprints -->
{% if site.data.publications.preprint %}
  {% include publication_list.html
    title="Preprints"
    items=site.data.publications.preprint
  %}
{% endif %}
