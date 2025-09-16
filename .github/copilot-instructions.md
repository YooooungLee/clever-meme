<!-- Copilot instructions for the tradingView repository -->
# Repository Guidance for AI coding agents

This file contains concise, actionable guidance to help an AI coding assistant quickly become productive in this repository.

1. Purpose and big picture:
   - **Goal**: Educational TradingView indicator implementations and strategy notes (Chinese/English). Primary code lives in `Quant-code/` and documentation/learning content in `Quant-book/` and root READMEs (`README_zh.md`, `README_en.md`).
   - **Major components**: `Quant-code/indicator/` (indicator `.md` docs + `.pine` implementations), `Quant-code/strategy/` (strategy docs + `.pine`), `Quant-book/` (references).

2. Project structure and conventions:
   - **Documentation-first**: Each indicator has an `.md` with theory and a `.pine` file with TradingView Pine Script implementation. Example: `Quant-code/indicator/MACD.md` and `Quant-code/indicator/MACD.pine`.
   - **Pine Script versioning**: Pine files often start with `//@version=6` and author metadata. Keep the version directive and comment header when editing or adding scripts.
   - **Language**: Primary content is Chinese; preserve Chinese text in docs. Use English only for code identifiers and short inline comments unless adding a new English README.

3. Typical tasks for the assistant:
   - Add or update `.md` documentation to match `.pine` implementation (ensure formulas and parameter names align).
   - Implement or refactor `.pine` scripts preserving `indicator()` signature and `input.*` usage for user-configurable parameters.
   - Add images referenced in `.md` under the existing `others/png/` folders and keep relative paths (examples in `Quant-code/indicator/others/png/`).

4. Patterns and examples to copy:
   - Parameter handling: use `input.int(...)` / `input.source(close, title="Source")` as shown in `MACD.pine`.
   - Plotting style: `plot(..., color=..., style=plot.style_histogram)` is used for histogram bars (see `MACD.pine`).
   - Documentation link convention: inside `.md` files link the implementation using relative paths, e.g. [MACD](Quant-code/indicator/MACD.md)

5. Build / test / run guidance:
   - There is no automated build system. To test Pine scripts, copy the `.pine` file contents into TradingView’s Pine editor (https://www.tradingview.com/) and run on a chart.
   - For documentation preview, use any Markdown viewer. No CI is configured in this repo.

6. Edits and PR guidance:
   - Keep diffs focused: change the `.pine` script and the corresponding `.md` together.
   - Preserve original author comments and `//@version` lines in `.pine` scripts unless intentionally upgrading version — mention upgrade rationale in PR description.

7. Integration points and external dependencies:
   - External runtime: TradingView platform for executing Pine scripts.
   - PDFs in `Quant-book/` are static references — do not modify without intent.

8. When in doubt:
   - Match the style used in `Quant-code/indicator/*` files. Use existing examples (MACD, RSI, Bollinger-Bands) as templates.
   - Ask for clarification if a doc claims a calculation that doesn't match the `.pine` implementation.

If anything here is unclear or you'd like more rules (naming, formatting, PR checklist), tell me which area to expand.
