# {{ .Parameter.ProjectName }}

## Contributors

{{range .Parameter.Authors}}
1. {{ . -}} 
{{end}}

## Database

{{ .Parameter.SqlDialect }}
