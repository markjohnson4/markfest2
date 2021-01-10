# Update the Base Theme:

```
{{ range $elem_key, $elem_val := $map }}
   {{ $elem_key }} -- {{ $elem_val }}
{{ end }}
```

= good as a snippet

```
{{ range $elem_index, $elem_val := $logo_letters }}
            {{ $elem_index }} -- {{ $elem_val }}
        {{ end }}
```
and that

{{ delimit .Params.tags ", " }}


Does a part of your html seem ignorant of a hugo variable like the useful ".Site.IsServer" var, which checks if the site is being served through hugo server (its local) or not (its live)

base > add "schedule reflection period"