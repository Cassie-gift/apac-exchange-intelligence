# ExchangePulse Update Rules

This file is the maintenance checklist for future ExchangePulse updates. Use it whenever adding or refreshing market updates, launch radar items, effective dates, or directory coverage.

## Default coverage scope

Each update should check the four global regions by default:

1. APAC
2. Americas
3. Europe
4. Middle East & Africa

Do not let a region appear empty unless a reasonable source check found no material update. If there is no high-quality new item, record the source check in the update summary or coverage notes, but do not create a fake market-update card.

## Required market streams

For each region, check at least three streams:

1. Cash / equities markets
2. Derivatives markets
3. Market infrastructure, CSD, clearing, regulators

The site should not only show infrastructure updates for a region. MEA, Americas and Europe should have visible equities and derivatives coverage when credible sources exist.

## Source hierarchy

Use sources in this order:

1. Exchange, clearing house, CSD or regulator official notices
2. Official exchange press releases, circulars, market notices or product pages
3. Core financial media as early signals
4. Secondary sources only when they point to a concrete exchange, product, rule or market-structure event

Do not bypass paywalls or copy article text. If an item relies on a paywalled or media source, mark it as media-sourced and phrase it as “reported by” or “pending official confirmation” where appropriate.

## Inclusion criteria

Include an item only when it has at least one of the following:

- A specific rule, circular, product, contract, index, listing, data service, clearing change or regulatory change
- A known publication date or effective / launch window
- A likely impact on trading, operations, risk, clearing, settlement, compliance, master data, market data or client communication

Avoid generic marketing, broad strategy pieces, or unnamed product pipelines unless they materially affect market structure.

## Exclusion rules for market-update cards

Do not include internal coverage notes as market updates. The “Market Updates” page should only show real market events, not ExchangePulse housekeeping.

Exclude items whose main message is only:

- A market, exchange, CSD or regulator has been “added to monitoring”
- A source has been “included in coverage”
- A venue is being “continuously tracked” or “under watch”
- ExchangePulse will “monitor” a market in future
- A country or region has no specific new announcement

These notes belong in the market directory, coverage status, update summary or this rules file. They should not appear as user-facing exchange-dynamic cards unless tied to a concrete external event such as a rule change, product launch, settlement change, system notice, market-data release, enforcement action, trading-volume record, index change, listing or regulator/CSD announcement.

## Time windows

- Market updates: normally published in the past 30 days, plus older high-impact items still relevant.
- Upcoming effective dates: forward six-month window.
- Launch Radar: from announcement day until six months after launch, unless there are follow-up notices, delays, early volume signals or rule changes.
- High-impact retention: keep major migrations, settlement reforms, regulatory shifts or material product changes visible beyond the normal window when still operationally relevant.

## Data fields

Each market update should support:

- region
- country / market
- exchange / venue
- type: equities, derivatives, infrastructure
- category
- title
- summary / brief
- impact
- source URL
- source type: official, exchange, regulator, CSD / clearing, media
- publication date
- effective date, if relevant
- impact level

## Quality standard

The card should be useful without forcing the reader to click the source link. Summaries should usually be a full brief, not a one-line headline.

## Manual update workflow

1. Scan APAC, Americas, Europe and MEA.
2. For each region, check equities, derivatives and infrastructure / regulatory sources.
3. Add or update specific items with source links.
4. Mark media-only items clearly.
5. Check Launch Radar separately for new products, contracts, securities, indices and data services.
6. Check Upcoming Effective Dates for items in the next six months.
7. Verify filters still show content in each region and stream.
8. Update `public/index.html`, copy it to `outputs/index.html`, then publish only when explicitly requested.
