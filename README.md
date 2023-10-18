# Spotify clone

Create using Bun, Astro, React, Swelte and Tailwind.

To Try Astro's transitions. Only working on Chrome for now.

Inspired on this: 
https://github.com/igorm84/spotify-astro-transitions

But implementing an audio player

## Instalation

1. Instala las dependencias:
   `bun install`

2. Ejecuta el proyecto:
   `bunx --bun astro dev`

## Learning notes

When implementing no Astro components (React, Swelte) they are only rendered in the server, so if an user interaction is needed you have to
write 'client' in the directive of the component and use a load option (client:load, client:visible, client:only, client:media, client:idle)