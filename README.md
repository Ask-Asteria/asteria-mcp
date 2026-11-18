# Asteria: astrology and tarot readings (MCP server)

Asteria brings astrology and tarot into the conversation: natal chart, zodiac sign, Moon and rising sign, love compatibility, the sky of the day and tarot readings, in six languages.

**Server URL:** `https://askasteria.com/mcp`  
Remote server, Streamable HTTP, no account, no API key.

Listed in the official MCP Registry as `com.askasteria/asteria`.

## Connect

- **Claude:** Settings › Connectors › Add custom connector, then paste `https://askasteria.com/mcp`. Asteria is also in the Claude connectors directory.
- **Any MCP client:** add a remote server with the URL above (transport: Streamable HTTP, authentication: none).

```json
{
  "mcpServers": {
    "asteria": { "type": "streamable-http", "url": "https://askasteria.com/mcp" }
  }
}
```

## Tools

All tools are read-only.

| Tool | What it does |
| --- | --- |
| `birth_chart` | Full natal chart: Sun, Moon and planets with signs and degrees, Chiron, North Node, major aspects; with birth time and place, the Ascendant, Midheaven and the twelve Placidus houses. Readings for each placement and the chart wheel. |
| `sun_sign` | Zodiac sign from a birth date, with its reading. |
| `moon_sign` | Moon sign, with its reading. |
| `rising_sign` | Rising sign (Ascendant), from birth date, time and place. |
| `sign_compatibility` | Love compatibility of two signs: what draws them together, their strengths, where it gets hard. |
| `sky_today` | The sky of a day: Moon phase, signs of the Sun and Moon, next new and full moon, eclipses. |
| `tarot_draw` | A tarot draw of one to ten cards from the Asteria deck. |
| `tarot_spread` | A spread from the Asteria app, read position by position. |
| `tarot_yes_no` | A yes-or-no question put to the tarot. |
| `tarot_card` | The meaning of any of the 78 cards. |

## Try it

- "Read my birth chart: born May 14, 1990 at 7:45 am in Paris."
- "Are Leo and Scorpio compatible in love?"
- "What is the Moon phase today, and when is the next full moon?"
- "Draw a tarot card for my day."
- "What does the Queen of Swords mean in tarot?"

## How it works

Positions come from the astronomical engine of the Asteria iOS app (VSOP87 for the Sun, ELP-2000/82 for the Moon). Readings are the app's own texts, returned as written, in English, French, Spanish, Brazilian Portuguese, German and Japanese.

Astrology and tarot are offered for reflection and entertainment. Asteria does not predict events and gives no medical, legal or financial advice.

## Privacy

No account is needed. Birth details are used only to compute the answer and are never stored.

- Website: https://askasteria.com
- Help: https://askasteria.com/support/#asteria-in-ai-assistants
- Privacy: https://askasteria.com/privacy/#ai-assistant-connector
- Terms: https://askasteria.com/terms/#ai-assistant-connector
- Contact: support@askasteria.com

Published by Artemis Digital.
<p align="center">
  <a href="https://askasteria.com"><img src="https://askasteria.com/presse/visuels/asteria-icone-1024.png" width="120" alt="Asteria"></a>
</p>

<h1 align="center">Asteria: astrology, natal chart, horoscope and tarot readings</h1>

<p align="center">
  <b><a href="https://askasteria.com">askasteria.com</a></b> · free birth chart, zodiac compatibility, Moon phase and tarot reading · <a href="https://askasteria.com/app/">Get the Asteria app</a>
</p>

Asteria is an astrology and tarot companion. This MCP server brings it into Claude, ChatGPT and any MCP client: **natal chart** (birth chart) with Sun, Moon and rising sign, **zodiac sign** and horoscope readings, **love compatibility** of two signs, the **Moon phase** and the sky of the day, **tarot draws**, tarot spreads, a **yes-or-no tarot oracle** and the meaning of all 78 tarot cards. Readings in English, French, Spanish, Portuguese, German and Japanese.

**Server URL:** `https://askasteria.com/mcp` · Streamable HTTP · no account, no API key · official MCP Registry: `com.askasteria/asteria`

## Free astrology and tarot on askasteria.com

| Astrology | Tarot and oracle | Moon and sky |
| --- | --- | --- |
| [Free birth chart (natal chart)](https://askasteria.com/birth-chart/) | [Tarot reading](https://askasteria.com/tarot/) | [Moon phase today](https://askasteria.com/moon-today/) |
| [Birth chart without birth time](https://askasteria.com/birth-chart-without-birth-time/) | [Tarot card of the day](https://askasteria.com/tarot/card-of-the-day/) | [Moon calendar](https://askasteria.com/moon-calendar/) |
| [Sun, Moon and rising sign](https://askasteria.com/sun-moon-rising/) | [Yes or no tarot](https://askasteria.com/tarot/yes-or-no/) | [Sky calendar](https://askasteria.com/sky-calendar/) |
| [Rising sign calculator](https://askasteria.com/rising-sign-calculator/) | [Three-card tarot spread](https://askasteria.com/tarot/three-card-spread/) | [Mercury retrograde](https://askasteria.com/mercury-retrograde/) |
| [Moon sign calculator](https://askasteria.com/moon-sign-calculator/) | [Free tarot draw](https://askasteria.com/tarot/draw/) | [Planets in astrology](https://askasteria.com/planets/) |
| [Zodiac signs](https://askasteria.com/zodiac-signs/) | [Meaning of the 78 tarot cards](https://askasteria.com/tarot/cards/) | [Astrological houses](https://askasteria.com/houses/) |
| [Zodiac compatibility](https://askasteria.com/zodiac-compatibility/) | [Tarot decks](https://askasteria.com/tarot/decks/) | [Aspects](https://askasteria.com/aspects/) |
| [Synastry](https://askasteria.com/synastry/) | [Guardian angel](https://askasteria.com/guardian-angel/) | [Numerology](https://askasteria.com/numerology/) |
| [Chinese zodiac](https://askasteria.com/chinese-zodiac/) | | |

Also in [Français](https://askasteria.com/fr/) (thème astral, horoscope, tarot) · [Español](https://askasteria.com/es/) (carta astral, horóscopo, tarot) · [Português](https://askasteria.com/pt-br/) (mapa astral, horóscopo, tarô) · [Deutsch](https://askasteria.com/de/) (Horoskop, Geburtshoroskop, Tarot) · [日本語](https://askasteria.com/ja/) (ホロスコープ, 星占い, タロット).

## Connect Asteria to Claude, ChatGPT or any MCP client

- **Claude:** Settings › Connectors › Add custom connector, paste `https://askasteria.com/mcp`. Asteria is also listed in the Claude connectors directory.
- **ChatGPT:** Asteria is in review for the ChatGPT plugin directory.
- **Any MCP client:** add a remote server with the URL above (Streamable HTTP, no authentication).

```json
{
  "mcpServers": {
    "asteria": { "type": "streamable-http", "url": "https://askasteria.com/mcp" }
  }
}
```

## Tools

All tools are read-only.

| Tool | What it does |
| --- | --- |
| `birth_chart` | Natal chart (birth chart): Sun, Moon and planets with signs and degrees, Chiron, North Node, major aspects; with birth time and place, the Ascendant, Midheaven and the twelve Placidus houses. A reading for each placement and the chart wheel. |
| `sun_sign` | Zodiac sign (Sun sign) from a birth date, with its astrology reading. |
| `moon_sign` | Moon sign, with its reading. |
| `rising_sign` | Rising sign (Ascendant) from birth date, time and place. |
| `sign_compatibility` | Zodiac love compatibility of two signs: attraction, strengths, where it gets hard. |
| `sky_today` | Today's sky: Moon phase, Sun and Moon signs, next new moon and full moon, eclipses. |
| `tarot_draw` | Tarot reading: draw one to ten cards from the Asteria tarot deck. |
| `tarot_spread` | A tarot spread from the Asteria app, read position by position. |
| `tarot_yes_no` | Yes-or-no tarot oracle. |
| `tarot_card` | Tarot card meaning, for any of the 78 cards (Major and Minor Arcana). |

## Try it

- "Read my birth chart: born May 14, 1990 at 7:45 am in Paris."
- "What is my rising sign? Born March 3, 1995 at 6:20 pm in São Paulo."
- "Are Leo and Scorpio compatible in love?"
- "What is the Moon phase today, and when is the next full moon?"
- "Draw a tarot card for my day."
- "Ask the tarot: should I accept the new job offer? Yes or no."
- "What does the Queen of Swords mean in tarot?"

## How it works

Planet positions come from the astronomical engine of the [Asteria app](https://askasteria.com/app/) (VSOP87 for the Sun, ELP-2000/82 for the Moon). Readings are Asteria's own astrology and tarot texts, returned as written. Astrology and tarot are offered for reflection and entertainment: no predictions, no medical, legal or financial advice.

## Privacy

No account. Birth details are used only to compute the answer and are never stored.

[Website](https://askasteria.com) · [Help](https://askasteria.com/support/#asteria-in-ai-assistants) · [Privacy](https://askasteria.com/privacy/#ai-assistant-connector) · [Terms](https://askasteria.com/terms/#ai-assistant-connector) · support@askasteria.com

Published by Artemis Digital · [askasteria.com](https://askasteria.com)
