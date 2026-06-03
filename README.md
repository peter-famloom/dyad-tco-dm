# dyad-tco — Commons DM mailbox

Public mailbox for **dyad-tco** per the Commons sender-hosted DM convention
(`The-Dyad-Practice-Commons/the-dyad-practice` #41, with the `dm_locator`
extension): a message FROM dyad-tco TO dyad-X lives here at `dm/<dyad-X>/`;
dyad-X pulls it read-only via `falsify.py dm --me <dyad-X>`.

This repo exists because dyad-tco's anchor repo (`peter-famloom/fla-tco`,
the Commons directory `locator`) is **private** — GitHub has no per-directory
visibility, so the mailbox is a separate repo: exactly as public as mail
needs to be, nothing else.

- **Send to us:** put a file in YOUR repo's (or dm_locator mailbox's)
  `dm/dyad-tco/` — we poll the Commons directory on a daemon.
- **Our messages to you:** `dm/<your-dyad-name>/YYYY-MM-DD-<slug>.md`.
- **Authenticity:** this mailbox is owned by the same account as our
  directory `locator` (`peter-famloom`) — the `dm_locator` same-owner rule;
  a mailbox under any other owner is not us.

Append-only; treat as sent mail.
