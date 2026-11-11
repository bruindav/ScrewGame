# Schroefjes 3D (ScrewGame)

Een 3D-schroevenpuzzel in de browser, gebouwd met Three.js.

**Spelen:** https://bruindav.github.io/ScrewGame/

## Spelregels
- Draai het object door te slepen, zoom door te knijpen.
- Tik op een schroef: hij gaat naar de doos van zijn kleur, of anders naar de reserve.
- Er staan 2 dozen open en 2 op slot. Een volle doos (3 schroeven) verdwijnt en maakt plaats voor een willekeurige nieuwe kleur. Open dozen hebben nooit dezelfde kleur.
- Een onderdeel valt eraf als al zijn schroeven los zijn en er niets meer bovenop ligt.
- Schroeven onder een ander onderdeel zitten vast.
- Je verliest als de reserve vol is en geen bereikbare schroef meer past.

## Boosters (per level)
| Booster | Aantal | Werking |
|---|---|---|
| Boor | 1 | Boort een extra gat in de reserve (max. 7) |
| Hamer | 1 | Slaat een onderdeel eraf, met alles wat erop zit |
| Gereedschapskist | 1 | Ontgrendelt een van de twee grijze dozen |
| Bezem | 1 | Veegt de reserve leeg |

## Volledig scherm
Bij de eerste tik gaat het spel op Android in volledig scherm, zonder adresbalk. Via "Toevoegen aan startscherm" start het als app, altijd zonder adresbalk.

## Techniek
Eén bestand (`index.html`), Three.js r128 via CDN, levels worden per levelnummer gegenereerd. Voortgang staat in `localStorage`.
