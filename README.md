# Colony workflow assistant

Private source-package snapshot, prepared November 5, 2026. Independent lab-developed software for reviewed cage entry, minimal litter recording, and weaning into assigned cages through a visible SoftMouse browser.

## Get the application

Download [colony-workflow-assistant-2026-11-05.zip](colony-workflow-assistant-2026-11-05.zip), extract it, and open the README inside the colony-workflow-assistant folder. The archive contains the application source, input examples, operating guides, and tests. This repository stores a packaged snapshot rather than an expanded source tree.

On Windows with Node.js 22 or newer:

```powershell
npm.cmd ci
npx.cmd playwright install chromium
npm.cmd start
```

Run these commands from the extracted application folder. Open http://127.0.0.1:4317, open the app-owned browser, sign in, refresh profiles, and select the exact destination. Read the included input contract before preparing a job. Examples are placeholders, not approved colony instructions.

## What is included

- Three workflows: add new cage cards/mice with explicit new matings, add minimal litters, and wean whole litters.
- Validation, four official Excel list exports before an operation, review or optional Fast mode, saved-record verification, and operation history.
- Required helper code and 87 passing local test groups. Read [validation and limitations](VALIDATION.md).
- A [per-file SHA-256 manifest](PACKAGE-MANIFEST.json) and archive checksum in SHA256SUMS.txt.

Credentials, lab records, account-specific demonstration inputs, signed-in browser sessions, exports, runtime history and the live permanent-ID registry are intentionally excluded. A source package is not a migration of the existing installation. Never start an independent ID registry against an already managed colony; use an approved registry/history migration process.

This is a candidate for a supervised pilot. Confirm vendor automation policy, account edition, licensed features, IT controls, and multi-profile behavior before real-colony unattended use. Historical standalone helpers are blocked in this package; launch with npm start. No open-source license is granted by this private distribution.
