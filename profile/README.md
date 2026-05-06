# 42ROWS

### Production-ready creative APIs in a single call.

No mockups. No mesh cleanup. No designer-in-the-loop.
Ad creatives that ship straight from the API response.

[Website](https://42rows.com) · [Playground](https://42rows.com/tools) · [Docs](https://42rows.com) · [Pricing](https://42rows.com)

</div>

---

## What we build

| Product | What it does | Status |
|---|---|---|
| **Image API** | Ad creatives with legible text, contrast-checked like an art director | Live |
| **Video API** | Motion graphics ad videos with readable typography | Live |
| **3D Artistic API** | Text or image → 3D asset | Live |
| **3D CAD** | Precise CAD for industrial machines | Coming soon |
| **Polars AI** | Data transformer (Apify $1M Challenge submission) | Coming soon |
| **42rows 1** | Prompt automation | Coming soon |

## Try it in 30 seconds

```bash
curl -X POST https://42rows.com/api/v1/image \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "prompt": "energy drink ad, slim Scandinavian aesthetic, headline FLOW STATE",
    "format": "1080x1080"
  }'
```

Get an API key at [42rows.com](https://42rows.com).

## Who it's for

Developers, agencies, e-commerce teams, ops/automation pipelines — anyone shipping creative assets at volume who'd rather make one API call than chain a model + a template renderer + a typography fixer.

## Open source we maintain

We open-source utilities we build for our own stack. MIT-licensed, zero dependencies where possible.

- **[MailStream](https://github.com/42ROWS/MailStream)** — Browser-based Gmail automation. Bulk send from CSV, smart rate limiting, ZIP export. 100% client-side, no server needed.
- **[vanilla-performance-patterns](https://github.com/42ROWS/vanilla-performance-patterns)** — High-performance JavaScript patterns. WeakRef memory management, GPU-accelerated virtual scrolling, auto-scaling worker pools, circuit breakers.

## Company

Built by [42rows S.r.l.](https://42rows.com) in Rome, Italy.

[42rows.com](https://42rows.com) · [support@42rows.com](mailto:support@42rows.com)
