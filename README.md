# Hey, I'm Paul

AI engineer in **Miami** who likes building things that leave the laptop — production web apps, LLM/agent tooling, and hardware that talks to the real world.

I'm bilingual (**English / Spanish**) and also speak **Portuguese**. I came up through Miami Dade College (A.S. Computer Science, **GPA 4.00**, Jan–Dec 2024), then transferred to **Florida International University** for a B.S. in CS (**GPA 3.76**, expected Apr 2028). Clubs: INIT, Google Developer Group, AAVE, CASHI.

I'm looking for **Software Engineering**, **AI / ML**, and **Forward Deployed Engineer** internships — roles where I can ship with users, not just demos.

### Find me
🌐 [Personal site](https://paulpio.com) · [LinkedIn](https://www.linkedin.com/in/paul-pio/) · [Devpost](https://devpost.com/paulrpiotrowski) · [Resume](https://github.com/PaulPio/Personal_Website/blob/master/Paul_Piotrowski_Resume.pdf)

---

## What I care about

- **Shipping > slides** — dashboards and PWAs people actually use at work; AI tools students open before exams
- **AI that sits on real systems** — Gemini vision pipelines, agent providers, edge installs, not prompt toys in isolation
- **Hardware + software** — ESP32 / Raspberry Pi labs at home, and a city-facing AI kiosk on a Pi 5
- **Open source when it helps** — contributed an OpenRouter provider leaf to [nous-core](https://github.com/orthogonalhq/nous-core)

---

## Currently building / recently shipped

| Project | What it is |
|--------|------------|
| [**ProfSummarizer**](https://prof-summarizer.vercel.app/) | AI lecture tool — Cornell notes, flashcards, quizzes (Supabase + Gemini). Used by FIU classmates. |
| [**ResumeFit**](https://starter-hackathon-project.vercel.app) | Gemma health-check + ranked SWE internship matching + listing-specific tailoring ([repo](https://github.com/PaulPio/ResumeFit)) |
| [**PlateSpotter**](https://plate-spotter.vercel.app) | Gemini Vision PWA for auto shops — plate scan → Sheets; cut logging time ~80% across 2 offices |
| [**FreeFall**](https://frefall.vercel.app) | Sunjam endless-faller — desktop host + phone tilt over QR / WebRTC |
| [**OpenRouter → nous-core**](https://github.com/orthogonalhq/nous-core/pull/410) | Certified OpenRouter provider for the open-source agent OS |

Hackathon trail on [Devpost](https://devpost.com/paulrpiotrowski): ResumeFit, MaRe Signal, FinanceFlow, GradTrack, Senior Helper.

---

## IoT & edge (this is the fun desk clutter)

I keep a personal **ESP32 + Raspberry Pi** lab: blink-and-breathe LEDs, Wi-Fi web UIs, sensors, and a Pi that stores history so the hardware isn't a one-off serial-monitor demo.

**Home lab** — [`PaulPio/IOT`](https://github.com/PaulPio/IOT)

- **ESP32**
  - Button + LED (hold / toggle state machines)
  - PWM **breathing light** on a Freenove GPIO board
  - **WebServerBlinkLight** — control an LED from any browser on the LAN
  - **WebServerTempHumidity** — DHT11 on GPIO 13, HTML page + `/api` JSON for other devices to poll
- **Raspberry Pi**
  - **temp-humidity-dashboard** (Flask) — polls the ESP32 API, SQLite history, charts, °C/°F, date filters
  - Remote access experiments with **Tailscale** subnet routing so the LAN sensors stay reachable off-site

**City / FDE flavor** — Software Engineer Intern, **City of Coral Gables** (May–Jun 2026): AI smart-city kiosk POC on a **Raspberry Pi 5** in ~3 weeks. State-driven **Pygame** avatar lifecycle with **Gemini Veo** video states (Idle / Listening / Speaking) — hardware + generative video in a public-facing install.

That's the through-line I like: wires on the bench → APIs on the LAN → something a person can walk up to and use.

---

## Stack I reach for

`TypeScript` · `Python` · `React 19` · `Next.js` · `Node` · `Supabase` · `MongoDB` · `Gemini` · `Claude` · `Mistral` · `Hermes` · `ESP32` · `Raspberry Pi` · `Docker` · `Vercel` · `GitHub Actions` · `Puppeteer` / `Playwright`

---

## Outside the IDE

Miami-based · bilingual EN/ES (+ Portuguese) · happy talking FDE / AI agents / IoT edge · always down for a hackathon or an open-source review cycle.

If you're hiring interns who already ship — [say hi](mailto:paulrpiotrowski@gmail.com).

---

<p align="center">
  <img src="https://ghchart.rshah.org/22c55e/PaulPio" alt="Paul's GitHub contribution chart" />
</p>

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=PaulPio&show_icons=true&hide_border=true&bg_color=0d1117&title_color=39ff88&text_color=c9d1d9&icon_color=58a6ff" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PaulPio&layout=compact&hide_border=true&bg_color=0d1117&title_color=ffe600&text_color=c9d1d9" alt="Top languages" />
</p>
