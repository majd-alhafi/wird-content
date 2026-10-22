# Selected Quran translations — 2026-10-22

Only the nine editions explicitly requested by the owner are offered. These are
published translations, not generated translations of religious content.

| Source book ID | Edition (source title) | App/content code |
|---|---|---|
| 1947 | الإنجليزية — صحيح انترناشونال | en |
| 1949 | الفرنسية — المنتدى الإسلامي | fr |
| 1951 | الإسبانية — المنتدى الإسلامي | es |
| 1952 | الإسبانية (أمريكا اللاتينية) — المنتدى الإسلامي | es |
| 1959 | التركية — مجمع الملك فهد | tr |
| 1962 | الإندونيسية — وزارة الشؤون الإسلامية | id |
| 1964 | الفارسية — دار الإسلام | fa |
| 1968 | الكردية — محمد صالح باموكي، بحسب وصف المصدر | ckb |
| 1979 | الكازاخية — مجمع الملك فهد | kk |

## Provenance, permission and limitations

- Official index: https://quranpedia.net/dumps
- Official archive: https://quranpedia.net/dumps/translations-all.zip
- Applicable source licence: https://quranpedia.net/dumps/LICENSE.md
  (licence version 2026-10-19).
- API policy: https://quranpedia.net/api-docs#usage-policy . No bulk API scraping
  is performed. The source expressly directs bulk users to versioned dumps.
- The source permits free application use, and republication of downloadable
  datasets with a Quranpedia.net link and dump version. Those notices are retained
  in every catalogue entry and `sources/quranpedia/editions.json` on the content site.
- This is permission under Quranpedia's published data terms, **not** a claim
  of public domain, Creative Commons licensing, or independent permission from
  each translation's author/publisher. Their intellectual property remains theirs,
  as the source licence explicitly states. Recheck source terms for subsequent
  commercial distribution or if a rights-holder objects.
- The archive's server Last-Modified date was 2026-10-22. Saved source documents
  have no individual `license` or `version` field despite the index describing
  such fields; do not fabricate one. Catalogue source version identifies the
  retrieved archive snapshot; each original JSON is pinned by SHA-256.
- The nine individual links on the index were broken `http://localhost/...`
  links. `tool/quranpedia_selected.py` reads the official ZIP central directory
  and retrieves **only the nine selected compressed members using HTTP ranges**.
  It never requests localhost or downloads all 138 editions. Each selected member
  is checked against its ZIP size and CRC32 before parsing.
- All nine contain 6,236 records, split into 114 original surah sequences. Original
  translation strings, embedded notes/HTML, book identity and description are
  retained unchanged. The reader only strips markup for display. Original source
  page numbers are retained as source metadata and are not used as unverified
  navigation mappings for the app's Mushaf images.
- The Kurdish text is Sorani in Arabic script. Source `locale_code: ku` and
  `direction: ltr` are retained in edition metadata; app presentation uses `ckb`
  and RTL. This is a presentation correction, not a change to published text.
- Upstream corrections must be reviewed and selected editions regenerated with
  `tool/quranpedia_selected.py`, then `tool/prepare_quranpedia.py`. The static
  mirror does not silently promise automatic upstream correction synchronization.

## Embedded archive licence

The ZIP's actual `LICENSE.md` was separately retrieved by byte range and its
CRC32 verified. It states version **2026-10-22**, whereas the live licence URL
reviewed above states **2026-10-19**. Both carry the same operative application
and credited-dataset republication conditions, with the same author/publisher
rights reservation and third-party-source exclusions. The archive licence is
preserved as `sources/quranpedia/archive-LICENSE.md` on the content site. The
catalogue's 2026-10-19 licence label identifies the reviewed live policy, not
an invented per-translation licence. The actual dump/source snapshot is 2026-10-22.

## App changes (included in 3.5)

The offered interface languages are Arabic, English, French, Spanish, Turkish,
Indonesian, Persian, Sorani Kurdish and Kazakh. Both Spanish translation editions
share one Spanish interface option. Source religious text keeps its own language.
Spanish and Sorani primary interface labels were added; secondary labels without
a supplied translation retain the existing explicit English fallback. Flutter
does not supply Sorani stock Material/Cupertino strings; those use English while
the app's Sorani labels and overall writing direction remain Sorani/RTL.

Shared dropdown styling, edition volume/page labels, removal of the content
language filter and a 2,000 ms native splash were implemented. Native splash
duration includes the existing final 150 ms fade. The owner subsequently
authorized release 3.5 with three additional hadith books. See VERIFICATION_3_5.md
for actual build, install and verification results; the previous APK is backed up.
