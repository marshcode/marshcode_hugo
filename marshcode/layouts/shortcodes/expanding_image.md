{{ $small := default "" (.Get "image_url") }}
{{ $large := default $small (.Get "image_url_large") }}
{{ $alt := default "Image" (.Get "alt_text") }}



{{ printf "[![%s](%s '%s')](%s)" $alt $small $alt $small }}
