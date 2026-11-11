# Schroefjes 3D (ScrewGame)

Een 3D-schroevenpuzzel in de browser, gebouwd met Three.js.

**Spelen:** https://bruindav.github.io/ScrewGame/

## Spelregels
- Draai het object door te slepen, zoom door te knijpen.
- Tik op een schroef: hij gaat naar de doos van zijn kleur, of anders naar de reserve.
- Een volle doos (3 schroeven) verdwijnt en maakt plaats voor een nieuwe kleur. De twee dozen hebben altijd verschillende kleuren.
- Een onderdeel valt eraf als al zijn schroeven los zijn en er niets meer bovenop ligt.
- Schroeven onder een ander onderdeel zitten vast.
- Je verliest als de reserve vol is en geen bereikbare schroef meer past.

## Boosters (per level)
| Booster | Aantal | Werking |
|---|---|---|
| Boor | 2 | Draait één schroef los, ook als hij vastzit |
| Hamer | 1 | Slaat een onderdeel eraf, met alles wat erop zit |
| Gereedschapskist | 1 | Extra reserveplek (max. 7) |
| Bezem | 1 | Veegt de reserve leeg |

## Techniek
Eén bestand (`index.html`), Three.js r128 via CDN, levels worden per levelnummer gegenereerd. Voortgang staat in `localStorage`.
