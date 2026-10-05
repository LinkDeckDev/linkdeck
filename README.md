# LinkDeck

LinkDeck is a compact, touch-first digital identity and sharing device built around an ESP32-S3, a 1.64-inch AMOLED touchscreen and NFC.

This repository is the **public project overview** for LinkDeck.

> LinkDeck is still in prototype development. Hardware, software, specifications and product direction may change as physical validation progresses.

## Current phase

LinkDeck is currently in **digital preparation before hardware arrival**.

The mechanical direction, UI/UX planning, prototype validation criteria, branding, public documentation and project infrastructure are being prepared so physical validation can begin as soon as the first prototype components and enclosure are available.

The next major milestone is **first physical prototype validation**. Hardware-dependent behaviour will only be described as working after it has been observed on the real prototype.

## Product direction

LinkDeck is designed around a simple interaction model:

- NFC as the primary contactless sharing method
- QR as a universal fallback
- Swipe left/right for navigation
- Tap to select
- Long press for back/menu
- Multiple digital identity profiles over time

Current prototype direction:

- ESP32-S3
- 1.64-inch 280 × 456 AMOLED touchscreen
- Capacitive touch
- NFC
- USB-C operation during early validation
- Compact custom enclosure

## Public documentation

The public documentation set is maintained in [`linkdeck-docs`](https://github.com/LinkDeckDev/linkdeck-docs).

Start with:

- [Project Overview](https://github.com/LinkDeckDev/linkdeck-docs/blob/main/docs/project-overview.md)
- [Public Roadmap](https://github.com/LinkDeckDev/linkdeck-docs/blob/main/docs/public-roadmap.md)
- [Prototype Milestones](https://github.com/LinkDeckDev/linkdeck-docs/blob/main/docs/prototype-milestones.md)
- [UI/UX Overview](https://github.com/LinkDeckDev/linkdeck-docs/blob/main/docs/ui-ux-overview.md)
- [Public Architecture Overview](https://github.com/LinkDeckDev/linkdeck-docs/blob/main/docs/public-architecture-overview.md)
- [Software Architecture Overview](https://github.com/LinkDeckDev/linkdeck-docs/blob/main/docs/software-architecture-overview.md)
- [NFC & QR Sharing Concept](https://github.com/LinkDeckDev/linkdeck-docs/blob/main/docs/nfc-qr-sharing-concept.md)
- [Prototype Validation Overview](https://github.com/LinkDeckDev/linkdeck-docs/blob/main/docs/prototype-validation.md)
- [Brand Overview](https://github.com/LinkDeckDev/linkdeck-docs/blob/main/docs/brand-overview.md)
- [Glossary](https://github.com/LinkDeckDev/linkdeck-docs/blob/main/docs/glossary.md)
- [Devlogs](https://github.com/LinkDeckDev/linkdeck-docs/tree/main/devlog)

Public documents are curated product and engineering summaries. They are intentionally less detailed than the internal specifications.

## Public repositories

- [`linkdeck`](https://github.com/LinkDeckDev/linkdeck) — project overview and public status
- [`linkdeck-docs`](https://github.com/LinkDeckDev/linkdeck-docs) — public documentation and devlogs
- [`linkdeck-examples`](https://github.com/LinkDeckDev/linkdeck-examples) — future public examples and SDK/API samples

## Public project areas

We plan to share selected material such as:

- Development updates
- Devlogs
- Prototype milestones and validated results
- UI experiments
- Public documentation
- Screenshots and media
- Public examples when interfaces are stable enough to support them

## Not published here

Production-critical engineering remains private, including:

- Production CAD
- PCB/Gerbers
- Full manufacturing BOM
- Full production firmware
- Supplier-sensitive information
- Provisioning and security internals
- Credentials, keys and recovery material

See [`LICENSE-NOTICE.md`](LICENSE-NOTICE.md) for the current licensing position and [`SECURITY.md`](SECURITY.md) for security reporting guidance.

## Project links

- Documentation: https://github.com/LinkDeckDev/linkdeck-docs
- Examples: https://github.com/LinkDeckDev/linkdeck-examples
- YouTube: https://www.youtube.com/@LinkDeckDev
- Instagram: https://www.instagram.com/linkdeckdev/
- TikTok: https://www.tiktok.com/@linkdeckdev
- GitHub organization: https://github.com/LinkDeckDev

## Status

> Build in public where useful. Validate on real hardware before presenting prototype behaviour as confirmed.
