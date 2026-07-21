# Project information
This is source code of the form registration landing page, for a [virtual
YouTuber](https://www.youtube.com/@RirisyaMusic) [Ririsya](https://x.com/Ririsya_music)
to celebrate 6th anniversary.

# Boring technicial stuff

## CSS magic
This project uses tailwind, see
[https://tailwindcss.com/docs/installation/tailwind-cli](https://tailwindcss.com/docs/installation/tailwind-cli) 
for details about instalation.


When using the portable cli, it is recommended to put it under `./vendor/bin` directory.
Start with 
`.\vendor\bin\tailwindcss.exe -i ".\tailwind.in.css" -o ".\theme.css" -w`
to make it watch for changes in live mode and rebuild `theme.css` as needed.


Use `.\vendor\bin\tailwindcss.exe -i ".\tailwind.in.css" -o ".\theme.css" -m`
to make optimized and minified version (production-ready).
