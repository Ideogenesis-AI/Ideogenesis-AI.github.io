# Ideogenesis AI — Organization Landing Page

The official landing page for [Ideogenesis-AI](https://github.com/Ideogenesis-AI), hosted at [ideogenesis.ai](https://ideogenesis.ai).

## Overview

This repository contains the source for the Ideogenesis AI organization website. The site covers the organization's research on AI-driven discovery in quantum many-body physics, and the open-source simulation stack — [Yuzuha](https://github.com/Ideogenesis-AI/Yuzuha), [Nicole](https://github.com/Ideogenesis-AI/Nicole), and [Alice](https://github.com/Ideogenesis-AI/Alice) — that underpins it.

## Tech Stack

- [Astro v5](https://astro.build) — static site generator
- Vanilla CSS with custom properties — no framework overhead
- Canvas API — animated quantum lattice background
- Self-hosted fonts via [`@fontsource`](https://fontsource.org)
- Deployed via GitHub Actions to GitHub Pages

## Development

```bash
npm install
npm run dev       # local dev server at http://localhost:4321
npm run build     # production build → dist/
npm run preview   # preview production build locally
```

## License

Copyright © 2026 Changkai Zhang. All rights reserved.

This repository and its contents are proprietary. No part of this software may be reproduced, distributed, or transmitted in any form or by any means without the prior written permission of the copyright holder. See the [LICENSE](LICENSE) file for details.
