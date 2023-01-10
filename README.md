> _Fork_ deze leertaak en ga aan de slag. 
Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. 
De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Vervoerregio Amsterdam website volgens de huisstijl.

## Beschrijving
Ik heb voor deze opdracht een website (her)bouwt volgens de living styleguide die ik en mijn studiegenoten hebben opgesteld na aanleiding van de bestaande styleguide van Vervoerregio Amsterdam.

In de screenshot hieronder zie je hoe ik de hoofdkleur uit de styleguide, Magenta heb toegepast op meerdere plekken om de website aan de huisstijl te laten voldoen.
Op de tweede screenshot zie je dat ik ook gebruik heb gemaakt van de andere kleuren uit de huisstijl zoals de verschillende kleuren blauw.

![image](https://user-images.githubusercontent.com/112857487/211563084-351fb8f7-03e0-41d6-aa9a-9eed3348e8cc.png)
![image](https://user-images.githubusercontent.com/112857487/211563421-7c9f0e3f-f1e2-4cd1-b766-b75fb41906c2.png)


Link: https://wesley-vervoerregio.student.fdnd.nl/

## Kenmerken
De kleuren zijn opgenomen in custom propperties in mijn css:
```css
  /* styleguide colors */
  --c-white: #fff;
  --c-red: #E30059;
  --c-yellow: #FFD05F;
  --c-green: #25AE93;
  --c-teal: #46BECD;
  --c-blue: #606eb3;
  --c-magenta: #B9005F;
  --c-brown: #6A4955;
  --c-dirt: #C9B5B2;
  --c-black: #111;

  /* custom properties colors */

  --background: #f3f3f3;

  --global-text: #000;
  --link-hover: #E30059;

  --desktop-navbar: #fff;
  --mobile-navbar: #444444;

  --header-gradient: linear-gradient(332deg, rgba(185, 0, 95, 1) 0%, rgba(227, 0, 89, 1) 100%);

  --accordion: #606eb3;
  ;
  --accordion-hover: #46BECD;
  --accordion-active: #46BECD;

  --box-gradient: linear-gradient(to right, #B9005F, #E30059);
  --box-shadow: rgba(50, 50, 93, 0.25) 0px 6px 12px -2px, rgba(0, 0, 0, 0.3) 0px 3px 7px -3px;

  --footer: #444444;
}
```


