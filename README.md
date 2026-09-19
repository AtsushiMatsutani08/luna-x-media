# LUNA X Media

Public image storage for the LUNA X publishing workflow.

- Only publish-ready SNS images belong in `media/`.
- Internal documents, customer information, addresses, secrets, drafts, and source code must never be stored here.
- `requests/*.json` can import an approved image from a temporary HTTPS source into stable GitHub-hosted media.
- Buffer should receive the stable raw URL as `assets[].image.url`; the URL is not appended to the X post text.

Stable raw URL pattern:
`https://raw.githubusercontent.com/AtsushiMatsutani08/luna-x-media/main/media/<filename>`
