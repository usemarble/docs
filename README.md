# Marble Documentation

Documentation for Marble and its API built with [Mintlify](https://mintlify.com).

## Project Structure

```
docs/
├── content/                   # Documentation content
│   ├── api-reference/         # API endpoint documentation
│   │   ├── endpoint/          # Individual endpoint docs
│   │   ├── introduction.mdx   # API overview
│   │   └── pagination.mdx     # Pagination guide
│   └── guides/                # Integration guides and tutorials
│       ├── integrations/      # Framework-specific guides
│       ├── introduction.mdx   # Getting started
│       └── quickstart.mdx     # Quick setup guide
├── images/                    # Documentation images and assets
├── logo/                      # Brand assets
├── snippets/                  # Reusable content snippets
├── docs.json                  # Mintlify configuration
└── README.md                  # This file
```

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify):

```bash
npm i -g mintlify
```

Start the development server:

```bash
mintlify dev
```

---

Built with ❤️ using [Mintlify](https://mintlify.com)
