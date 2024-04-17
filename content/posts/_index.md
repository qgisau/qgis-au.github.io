{{ define "posts" }}
  {{ with (index (where site.RegularPages "Type" "posts").ByDate.Reverse 0) }}
    <h1>{{ .Title }}</h1>
    {{ .Content }}
  {{ end }}
{{ end }}
