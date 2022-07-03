{{ $github := default "" (.Get "github") }}
{{ if $github }}
{{ printf "[![GitHub](https://github.githubassets.com/favicons/favicon.png 'Link to sourcecode on GitHub')](%s)" $github }}
{{ end }}

{{ $wikipedia := default "" (.Get "wikipedia") }}
{{ if $wikipedia }}
{{ printf "[![GitHub](https://www.wikipedia.org/static/favicon/wikipedia.ico 'Link to subject on WikiPedia')](%s)" $wikipedia }}
{{ end }}





