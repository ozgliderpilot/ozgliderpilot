## Hi, I'm Vitalik 👋

AI dropped the cost of writing software far enough that it's now worth building a thing just to solve a single person's problem. So that's what I do here. Every repo on this profile started as *"I wish something did this for me."* Some of my friends and family benefit from them too.

Most of the code is AI-written but I architect the apps and read the code, because I believe that's how it should be done, and it's fun.

Most of it traces back to a few things about my life: I fly gliders, live in Melbourne, love my wife, and she loves plants.

### What's on my mind currently

🛩️ **[instructa-mate](https://github.com/ozgliderpilot/instructa-mate)**
A co-pilot for gliding instructors that answers **only** from the official training manuals, cites the exact page, and refuses when the answer isn't in them. I'm a gliding instructor; an invented procedure is a safety failure, so *"not covered in the guides I have"* had to be a first-class answer.

🌱 **[plant-scanner](https://github.com/ozgliderpilot/plant-scanner)**
An offline-first Android app for the Royal Botanic Gardens volunteer nursery. Built with accessibility in mind (big buttons, big text) and built to never lose a sale, with every decision that's easy to get wrong unit-tested off-device.

☕ **[english-breakfast](https://github.com/ozgliderpilot/english-breakfast)**
A Telegram bot my wife and I use to study English. One Cloudflare Worker: the translation direction is detected deterministically and unit-tested; the LLM only does the part it's actually good at.

🌦️ **[burevestnik](https://github.com/ozgliderpilot/burevestnik)**
Posts Melbourne's forecast to Telegram twice a day. A pure, tested core with the side effects pushed out to the edges, flapping along on a GitHub Actions cron. (*буревестник*: "stormy petrel".)

🍃 **[quarkus-mongodb](https://github.com/quarkiverse/quarkus-mongodb)**
Quarkus extensions for MongoDB. I authored and maintain the `flyway-mongodb` extension, a simple way to keep a production MongoDB schema versioned in your repo and the database up to date.
