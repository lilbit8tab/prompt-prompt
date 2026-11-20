# Prompt Prompt

A tiny, self-contained prompt builder. Fill in a few structured fields and it
assembles a clean, ready-to-paste prompt for any AI assistant.

## Purpose

Most people paste a one-line idea into an AI and get a mediocre result. Prompt
Prompt turns that idea into a structured prompt by separating the parts that
matter — role, task, context, constraints, output format, and tone — so the
model gets clear instructions every time.

## How to open it locally

No install, no build step, no server required.

1. Clone or download this repository.
2. Open `Index.html` directly in any modern browser (double-click the file, or
   drag it into a browser window).

## Supported fields

| Field           | Required | Description                                   |
| --------------- | -------- | --------------------------------------------- |
| Role            | No       | Who the AI should act as                      |
| Task            | Yes      | The core thing you want done                  |
| Context         | No       | Background, audience, or prior work           |
| Constraints     | No       | Length, must-haves, or things to avoid        |
| Output format   | No       | How the answer should be structured           |
| Tone            | No       | The voice or style of the response            |

As you type, the generated prompt appears live in the preview panel. Use
**Copy prompt** to copy it to your clipboard and **Clear** to reset everything.

## Privacy

Everything runs client-side in your browser. No data is sent anywhere: your
input never leaves the page. Field values are remembered locally in your
browser's `localStorage` (when available) so they survive a reload; clearing the
fields or using a private window removes them.
