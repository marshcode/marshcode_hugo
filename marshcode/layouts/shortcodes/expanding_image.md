{{ $small := default "" (.Get "image_url") }}
{{ $large := default $small (.Get "image_url_large") }}
{{ $alt := default "Image" (.Get "alt_text") }}



{{ printf "[![GitHub](%s 'Link to sourecode on GitHub')](%s)" $small $small}}
