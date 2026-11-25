# Changelog

## V36.3 "finds his own books" (Nov 25, 2026)
- **Rollo looks for books himself:** he can search a catalog of free, copyright-expired books, choose one (or decline), add it to his shelf, and start reading it.
- **Limits:** public-domain only, two self-added books per day, and downloads from official Project Gutenberg mirrors.

## V36.2 "library choices" (Nov 25, 2026)
- **Rollo plans his own library visits:** he picks which book to read, or writes his own web search, as part of his decision.
- **Fixed:** removed machine-made template searches. Live data showed every search had been the same fixed phrase, while his memories asked for a real book.
- **Book memories:** written from the passage he actually read.

## V36.1 (Nov 24, 2026)
- **Fixed:** the web-history page returned HTTP 404 because of route order.
- **Automatic deploys:** code is tested and deployed by GitHub Actions after approval.

## V36 "real decisions" (Nov 24, 2026)
- **Fixed:** the AI model's thinking mode had used up every answer budget. Live tally before the fix: decisions 0/229, thoughts 0/264.
- **AI planner:** Rollo's free time is now chosen by the AI from his memories, and every choice is logged with its reason and source.
- **No scripted experiences:** the prewritten "discoveries" are gone. New information now comes only from real sources.
- **Memories with sources:** new memories record where they came from. A built-in test checks whether a memory changes his choices.
- **Drawings:** caption text that older versions baked into drawings is removed when shown. The originals are preserved.
- **Website:** shows why Rollo is doing what he's doing.

Screenshots: [screenshots/v36](screenshots/v36)

## Earlier (V1–V35, Nov 3–23, 2026)
- **Built:** the town of North Quay, the rooftop garden, a library with real public-domain books, the forum with owner moderation, the art archive, Knot's grove, and a print shop (kept disabled).
- **Moved to the cloud:** the simulation went from running in a browser tab to an always-on Cloudflare Worker with a database.
