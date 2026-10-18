# Return — A Reconciliation Companion

A personal companion for the Sacrament of Reconciliation: prepare in prayer, examine your conscience by the Ten Commandments and the Precepts of the Church, review your list, walk through the rite step by step, and keep a journal of the mercy received.

**Live:** https://keithintrinidad.github.io/Return/

## Privacy

- The examination is held in memory only. It is kept only if you choose **Record this confession** afterward.
- Journal entries are stored in this browser on this device (`localStorage`). Nothing is ever sent to a server.
- An optional passcode encrypts the journal (AES-GCM, key derived with PBKDF2-SHA-256). It relocks after two minutes in the background. A forgotten passcode cannot be recovered.
- Any entry, any item within an entry, or the whole journal can be deleted at any time.
- **Export backup** saves an unencrypted JSON file; keep it somewhere private. **Import backup** merges one back in.
- Built for low-connectivity spaces: the app opens instantly from cache with no network wait, updates quietly in the background, caps every network attempt with a timeout, and falls back to system fonts if web fonts are unavailable. The service worker caches only the app itself.

## Sources

- Scripture: Douay-Rheims (public domain)
- Act of Contrition: traditional form (public domain)
- Examination questions and thanksgiving prayer: original wording
- The words of absolution are described, not quoted, as the English translation of the rite is copyrighted.

## Install

Open the live link on your phone and choose *Add to Home Screen*.

## Credits and licence

Built by Claude using material provided by and under the guidance of Keith Francis.

Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
