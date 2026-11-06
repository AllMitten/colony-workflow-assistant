# Package validation - November 5, 2026

**87 packaged test groups passed; zero failed.** npm ci completed from the included lockfile, then npm test ran from the isolated package directory on Windows. Synthetic data and local fixtures were used; no live SoftMouse operation was run. The source workspace and its real registry were not changed.

The first package check exposed four legacy litter tests that referenced an excluded site-specific fixture. A synthetic equivalent was supplied and the same count, date, rack, sex, identity and confirmation assertions were retained. The packaged suite then passed. Reconstruction tests that depend on real mouse/export datasets are not part of this distribution. This count applies to the packaged suite, not the larger historical development suite.

Checks include calendar boundaries, malformed inputs, duplicate/collision handling, permanent-ID behavior, uncertain saves, history integrity, local load, and simulated browser errors. Actual account features, licensed protocol assignment, multi-profile permissions and end-to-end remote saves still need supervised acceptance. No production-readiness guarantee or vendor approval is implied.

Packaging uses an explicit source allowlist. Credentials, browser state, lab-data, input batches, exports, screenshots, operation journals, and the live ID registry are excluded. Historical helper command entry points are disabled. Placeholder labels replace the original example profile labels. A SHA-256 manifest and archive checksum accompany this copy.
