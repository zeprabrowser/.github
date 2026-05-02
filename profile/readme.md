<div align="center">
  <img src="https://raw.githubusercontent.com/zeprabrowser/Zepra/main/resources/icons/zepra.svg" width="96" alt="Zepra" />

  # Zepra Browser

  A browser engine built from scratch. No Chromium. No WebKit. No V8.

  Built by [KetiveeAI](https://ketivee.com)
</div>

---

This organization hosts the source code and tooling for **Zepra** — an independent browser engine written in C++.

Every subsystem is original:

| Subsystem | What it does |
|---|---|
| **ZepraScript** | JavaScript engine — multi-tier JIT, custom GC, ES2022+ |
| **NXRender** | Graphics rendering pipeline |
| **NXHttp** | HTTP/HTTPS networking stack |
| **NXCrypto** | Cryptography layer |
| **NXSVG** | SVG rasterizer |
| **WebCore** | HTML & CSS parser |

Zepra runs natively on [NeolyxOS](https://neolyx.ketivee.com) and is part of the broader KetiveeAI ecosystem alongside [Reox](https://github.com/ketiveeai/reox), [PixaML](https://opensource.ketivee.com), and [KetiveeSearch](https://ketivee.com).

**License:** [KetiveeAI Public License 2.0](https://github.com/zeprabrowser/Zepra/blob/main/LICENSE.md) ·
**Contact:** license@ketivee.com
