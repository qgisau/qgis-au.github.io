{{ range ( first 3 ( where .Site.Pages "Type" "blog" ).ByDate ) }}
  <li><a href="{{ .Permalink }}">{{ .Title }}</a></li>
{{ end }}
