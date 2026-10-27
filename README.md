# RustDesk Setup

Client-facing setup page for test and assessment sessions. It covers the
self-hosted RustDesk build only: the ZIP from WhatsApp, the `.bat` file, the
Install and Accept prompts, and sending the machine code back.

Live: https://meghabollapalli.github.io/rustdesk-setup/

## Editing

Everything is in `index.html` — one file, no build step. The design tokens at
the top of the `<style>` block match `meghabollapalli/interview-setup`, so
colour, type and spacing stay in step with the interview page.

Push to `main` and GitHub Pages republishes within a minute.

## Checklist behaviour

The eight checklist items save to `localStorage` under
`rustdesk-setup-checklist`. Task keys live in `data-task` attributes; the
"Next:" label map is the `labels` object in the script at the bottom.
