# NOTICE — License & Attribution

This repository is a **fork** of
[`yArna/isChinaUser`](https://github.com/yArna/isChinaUser), maintained at
<https://github.com/Antisubmissivist/isChinaUser> as part of the deployment
to **ischinauser.antisubmissivist.com** via Cloudflare Pages.

## Upstream

| Field | Value |
| --- | --- |
| Original author | [yArna](https://github.com/yArna) |
| Upstream repo | https://github.com/yArna/isChinaUser |
| Original demo | https://yarna.github.io/isChinaUser/ |
| Description (zh) | 判断当前浏览器环境是否更像中国用户 / 中国地区设备。 |
| Latest release | 1.2.0 (npm: `is-china-user`) |

## License status (as of 2026-07-02)

The upstream repo currently ships **without a LICENSE file** and the
`package.json` does not declare a `license` field. GitHub therefore
treats the source as "All rights reserved" by default.

Because the author publishes an npm package, hosts a GitHub Pages demo,
and accepts PRs / issues openly, this fork treats the project as
**implied-OSS for demo purposes** with attribution preserved. If the
author clarifies the license in the future, this NOTICE will be updated
to mirror upstream's terms.

Until then, **no production-critical use** of this code should be made
without contacting the original author first.

## What this fork adds

- A Cloudflare Pages deployment at
  `ischinauser.antisubmissivist.com` (configured at the Cloudflare
  dashboard, not via `wrangler`).
- A weekly GitHub Actions sync workflow at
  `.github/workflows/sync-upstream.yml`.
- This NOTICE and an attribution footer in the upstream README.

## What this fork does NOT change

- `src/`, `docs/`, `test/`, `package.json`, `rslib.config.ts`,
  `tsconfig.json` — **untouched**.
- All commits merged from upstream keep their original author and
  metadata.
