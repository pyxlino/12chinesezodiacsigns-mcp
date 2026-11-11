# 12 Chinese Zodiac Signs MCP app

Find your Chinese zodiac animal and element, read any sign and check how two signs match.

Give a birth date and get your animal, your element and the Chinese New Year boundary that decided them. Ask about a sign, a birth year, a pair of animals or today's reading. Answers come from the same calendar and traditional readings as 12chinesezodiacsigns.com.

- Website: https://12chinesezodiacsigns.com
- Documentation: https://12chinesezodiacsigns.com/app
- Privacy: https://12chinesezodiacsigns.com/privacy
- Terms: https://12chinesezodiacsigns.com/terms

This repository documents the hosted connector. It does not contain the
website or its code.

## Connect

- Endpoint: `https://12chinesezodiacsigns.com/api/mcp`
- Transport: Streamable HTTP
- Authentication: none (no account, sign-in or API key)

```json
{ "mcpServers": { "12-chinese-zodiac-signs": { "url": "https://12chinesezodiacsigns.com/api/mcp" } } }
```

In ChatGPT, add it as a custom MCP server with no authentication. In
Claude, open Customize, then Connectors, choose Add custom connector and enter the URL.

## Tools

All tools are read-only.

| Tool | What it does |
|---|---|
| `find_my_sign` | Returns the Chinese zodiac animal, element, polarity and zodiac year for a birthday, with the Chinese New Year boundary that decided it, or for a birth year alone. |
| `get_sign` | Returns a Chinese zodiac sign's years, personality, best and hardest matches, lucky numbers, colours and flowers, and its 2026 and 2027 outlook. |
| `get_birth_year` | Returns the animal, element and exact dates of a zodiac year from 1924 to 2032, with its personality, best and hardest matches, lucky things and 2026 and 2027 outlook. |
| `check_compatibility` | Returns how two Chinese zodiac animals sit together: the match level, why, and the traditional branch and element relations behind it. |
| `get_element` | Returns the Chinese zodiac element of a birth date or of a zodiac year, with what it means for that year's animal. |
| `get_daily_reading` | Returns a sign's reading for a date, worked out from the day's animal and the traditional relations: work, love, energy, the best and hardest signs that day and the next seven days. |

## Try asking

- "What Chinese zodiac animal and element am I if I was born on 15 March 1990?"
- "Are the Rat and the Dragon a good match?"
- "What does the Chinese daily horoscope say for the Tiger today?"

## Report an issue

Open an issue in this repository or email support@12chinesezodiacsigns.com.

## License

The documentation files in this repository are MIT licensed (see
[LICENSE](LICENSE)). The 12 Chinese Zodiac Signs website, its content, data and brand are
not covered by this license.
