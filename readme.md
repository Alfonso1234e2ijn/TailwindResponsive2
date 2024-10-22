# Responsivitat amb Tailwind

## Objectiu:

- Utilitzar Tailwind CSS per reproduir l'estil del model donat.

## Instruccions:

1. Tens un fitxer HTML sota public amb una estructura bàsica i sense estils aplicats.

Per executar el teu projecte necessites executar les següents comandes:

```bash
npm install
npm run dev
```

Això primer instal·larà les dependències necessàries i després executarà el projecte i comprovarà els canvis en el teu codi. Si obres el teu servidor en viu veuràs que els canvis de Tailwind s'apliquen.

Recorda que la [Documentació de Tailwind CSS](https://tailwindcss.com/docs/flex) és el teu millor amic!

## Disseny Responsive

Amb Tailwind CSS, la responsivitat és tan fàcil com afegir unes poques línies de codi. Imagina que tens un botó que vols que sigui més gran quan algú està mirant el teu lloc en una pantalla més gran. Només afegeix una classe com `lg:w-20` i mira com es transforma màgicament en un súper botó quan la pantalla és gran!

```html
<button class="bg-blue-500 text-white p-2 lg:w-40">Fes clic aquí</button>
```

#### Jugant amb els Breakpoints:

Els breakpoints són com nivells en un videojoc per a dissenyadors web. Defineixen quan les coses canvien. Amb Tailwind, tenim classes com `sm:`, `md:` i `lg:` que ens permeten canviar l'estil dels nostres components quan la pantalla passa a ser petita, mitjana o gran. Per exemple, si vols que el teu text sigui centrat en mòbils i a l'esquerra en pantalles més grans, pots fer servir `text-center sm:text-left`.

```html
<!-- Això centrarà el text en mòbils, i l'alinearà a l'esquerra en pantalles de 640px i més amples -->
<div class="text-center sm:text-left"></div>
```

Pots veure un bon exemple de com funciona això en el fitxer `index.html`.

> Important: els breakpoints defineixen la mida de la pantalla a partir del breakpoint i cap amunt. Així que `sm:` s'aplicarà a pantalles petites i cap amunt, `md:` s'aplicarà a pantalles mitjanes i cap amunt, i `lg:` s'aplicarà a pantalles grans i cap amunt. **Per això diem que és MOBILE FIRST**

Pots consultar la [Documentació Oficial de Disseny Responsive](https://tailwindcss.com/docs/responsive-design#overview) per a més informació.

Una bona explicació també en [aquest vídeo](https://www.youtube.com/watch?v=VYFjvMfVv2o&ab_channel=NetNinja).

### Exercici 1

Tens un fitxer HTML bàsic sota "public" (exercici.html) amb una estructura bàsica i sense estils aplicats. Necessites reproduir l'estil del model donat:

![Model](/assets/Demo_Responsive_Tailwind.gif)

I una instantània dels diferents resultats de breakpoints:

![Model](/assets/completa_petita.png)
![Model](/assets/completa_mitjana.png)
![Model](/assets/completa_gran.png)


Si vols pots substituir el contingut d'index.html pel contingut de l'exercici.html per veure com es comporta en diferents mides de pantalla.

### Exercici 2

Agafa el teu Portfoli (potser és millor que facis un altre projecte) i aplica Tailwind CSS.

## Entrega

Puja els 2 projecte a alguna de les plataformes que hem vist fins ara (Vercel, Netlify, GitHub Pages) i comparteix el link al full compartit del drive. 

