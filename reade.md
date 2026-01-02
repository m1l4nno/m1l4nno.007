# CleanCord

## Beschreibung / Description

**DE:**  
CleanCord ist ein Vencord / Betterdiscord Add-on für Discord, das die Oberfläche aufräumt, transparenter macht und unnötige Elemente entfernt. Es bietet vielseitige Anpassungsmöglichkeiten, damit du dein Discord-Erlebnis individuell gestalten kannst.

**EN:**  
CleanCord is a Vencord / Betterdiscord add-on for Discord that cleans up the interface, makes it more transparent, and removes unnecessary elements. It offers versatile customization options so you can personalize your Discord experience.

---

## Installation

**DE:**  
1. Stelle sicher, dass Vencord / Betterdiscord installiert ist.  
2. Importiere die CSS-Datei über den QuickCSS-Editor oder deinen bevorzugten Vencord / Betterdiscord -CSS-Loader.  
3. Fertig – das Theme wird automatisch aktiviert.

**EN:**  
1. Make sure Vencord / Betterdiscord is installed.  
2. Import the CSS file using the QuickCSS editor or your preferred Vencord / Betterdiscord CSS loader.  
3. Done – the theme will activate automatically.

---

## Anpassbare Variablen / Customizable Variables

Du kannst das Aussehen über die folgenden CSS-Variablen anpassen. Alle Variablen sind zweisprachig kommentiert (DE/EN):

```css
/**
 * @name CleanDiscord
 * @description 
 * DE: Vencord Add-on für eine klare, transparente und aufgeräumte Discord-Oberfläche mit vielseitigen Anpassungsmöglichkeiten
 * EN: Vencord add-on for a clean, transparent, and organized Discord interface with versatile customization options
 * @author Milanno
 * @version 1.0.0
 * @source https://m1l4nno.github.io/Cleancord/CleanCord.css
 * @website https://m1l4nno.com
 */

 
@import url("https://m1l4nno.github.io/Cleancord/CleanCord.css");

:root {
  --btn-color: #14e90d; /* Button color (top-right) / DE: Farbe für die Rechts-oben-Buttons */
  --btn-size: 40px;      /* Button size / DE: Größe der Buttons */
  --speaking-border-color: #4acf56; /* Call border color / DE: Farbe bei aktivem Sprechen */
  --main-color: #868585;  /* Main theme color / DE: Hauptfarbe */
  --hover-color: #6b6969; /* Hover color / DE: Farbe beim Überfahren */
  --success-color: #148552; /* Success color / DE: Erfolgsmeldungen */
  --danger-color: #982929;  /* Danger color / DE: Fehler/Alarm */
  --warning-color: #faa61a; /* Warning color / DE: Warnungen */
  --mute-color: #ff4d4d;   /* Mute / DE: Stumm */
  --mute-glow: #0c0c0c;    /* Mute glow / DE: Leuchteffekt bei stumm */
  --info-color: #5865f2;    /* Info color / DE: Informationsfarbe */
  --online-color: #43b581;  /* Online status / DE: Online */
  --idle-color: #faa61a;    /* Idle status / DE: Abwesend */
  --dnd-color: #982929;     /* Do Not Disturb / DE: Nicht stören */
  --streaming-color: #593695; /* Streaming status / DE: Streaming */
  --offline-color: #808080; /* Offline / DE: Offline */


  /* Images / DE: Bilder */
  --group-icon: url('https://i.postimg.cc/2yVntbLV/m1l4nno.jpg');
  --home-icon: url('https://i.postimg.cc/2yVntbLV/m1l4nno.jpg');
  --background-image: url('https://i.imgur.com/bC59zah.jpeg');

  --background-position: center;  /* DE: Hintergrundposition */
  --background-size: cover;       /* DE: Hintergrundgröße */
  --background-attachment: fixed; /* DE: Hintergrundfixierung */
  --background-filter: saturate(calc(var(--saturation-factor, 1) * 1)); /* DE: Sättigungsfilter */
  --background-shading-percent: 100%; /* DE: Hintergrund-Schattierungsgrad */

  /* Fonts / DE: Schriftarten */
  --main-font: "gg sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
  --code-font: Consolas, "gg mono", "Liberation Mono", Menlo, Courier, monospace;

  /* Channel colors / DE: Kanal-Farben */
  --channel-normal: var(--interactive-text-default); 
  --channel-muted: var(--interactive-muted);
  --channel-hover: var(--interactive-text-hover);
  --channel-selected: var(--interactive-text-active);
  --channel-selected-bg: var(--main-color);
  --channel-unread: var(--main-color);
  --channel-unread-hover: var(--hover-color);

  /* Focus color / DE: Fokusfarbe */
  --focus-color: var(--main-color);
}
