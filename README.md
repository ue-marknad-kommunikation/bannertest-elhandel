# Skisser: Always-on Banners Elhandel 2026

Detta projekt innehåller HTML5-mockupar för Umeå Energis "always-on" banners för Elhandel. Syftet är att utforska olika animationstyper ("åkningar") och format för att hitta den mest effektiva lösningen för löpande digital annonsering.

## Format
Varje mockup innehåller två standardformat som körs synkroniserat:
- **Panorama:** 980x240 px
- **Kvadrat:** 320x320 px (inkluderar en loopande startskärm med rubrik)

## Animationsvarianter
Vi har tagit fram fem olika varianter på hur produkterna (Rörligt månadspris, Rörligt kvartspris, Fast elpris) presenteras:

1.  **Original (Bounce):** En mjuk vertikal åkning med en elastisk landningseffekt.
2.  **Push:** En vertikal "rullbandseffekt" där nästa produkt fysiskt knuffar ut den föregående.
3.  **Slide:** En modern horisontell åkning från höger till vänster.
4.  **Reveal:** En sofistikerad variant med mjuk fade-in och subtil zoom för en premiumkänsla.
5.  **Pop:** En energisk variant där produkterna "poppar" fram med kraftig bounce direkt i fokus.

## Hur man förhandsgranskar
Öppna någon av följande filer direkt i din webbläsare:

- [index.html](index.html) - Original (Bounce)
- [variant_push.html](variant_push.html) - Push-effekt
- [variant_slide.html](variant_slide.html) - Horisontell slide
- [variant_reveal.html](variant_reveal.html) - Mjuk reveal
- [variant_pop.html](variant_pop.html) - Pop-up effekt

*Använd navigationsmenyn uppe till vänster i förhandsgranskningen för att enkelt hoppa mellan de olika stilarna.*

## Tekniska detaljer
- **Teknik:** HTML5, CSS3 (Animations/Keyframes), Vanilla JavaScript.
- **Färger:**
    - Vår svart: `#012d2f` (Bakgrund & Vänster sektion)
    - Typografi: `#004042` (Höger sektion)
- **Interaktivitet:** Hela bannerytan är klickbar och leder till [umeaenergi.se/elavtal](https://www.umeaenergi.se/elavtal).
- **Loop:** Animationerna loopar oändligt med en paus på 1.5 sekunder per produktvy.
