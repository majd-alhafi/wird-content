# Asset and content credits — Wird 2.0 private audio build

Reviewed 2026-10-17. Following the user's explicit request, all twelve validated original MP3s replace the old three full Adhan options inside this private APK. Public redistribution rights remain unverified; inclusion does not create a licence. No voice was generated and no recording was re-encoded. Source caller names are publisher/uploader labels, not independent biometric authentication. No copyright/access restriction was bypassed.

Archive collection source: https://archive.org/details/Athan_Mawsoa_mp3 ; actual metadata: https://archive.org/metadata/Athan_Mawsoa_mp3 . The eight requested numbered files have their real suffixes and published sizes/SHA-1 checked. Neither the item nor the file metadata establishes an explicit redistribution grant. Islam Sobhi item https://archive.org/details/203.-mp-3 and its metadata likewise supply no such grant.

Publisher pages https://tilawatalharamain.com/miscellanies/11848 (Ibrahim Fajr), https://tilawatalharamain.com/miscellanies/11831 (Ibrahim Asr/general), and https://tilawatalharamain.com/miscellanies/1222 (Osama Al-Akhdar Dhuhr) link the actual MP3 URLs recorded in the versioned manifest. Publisher footer reserves rights; linked audio metadata supplies no overriding APK redistribution licence. No attribution/permission terms were invented. Evidence HTML/JSON is retained locally. Obtain the relevant rights holders' permission before public distribution.

| Variant | Original source filename | Bundled asset | Bytes | Measured seconds | Rights |
| --- | --- | --- | ---: | ---: | --- |
| makkah_fajr | 008.mp3 | assets/audio/makkah_fajr.mp3 | 446592 | 223.232 | Unverified; private test only |
| makkah_regular | 009.mp3 | assets/audio/adhan_makkah.mp3 | 405632 | 202.752 | Unverified; private test only |
| jerusalem_fajr | 015.mp3 | assets/audio/jerusalem_fajr.mp3 | 305280 | 152.576 | Unverified; private test only |
| jerusalem_regular | 016.mp3 | assets/audio/jerusalem_regular.mp3 | 364672 | 182.272 | Unverified; private test only |
| abdulbasit | 043-1.mp3 | assets/audio/abdulbasit.mp3 | 4536824 | 189.312 | Unverified; private test only |
| alafasy_regular | 050-1.mp3 | assets/audio/alafasy_regular.mp3 | 1929297 | 240.753 | Unverified; private test only |
| alafasy_fajr | 052-1.mp3 | assets/audio/alafasy_fajr.mp3 | 1501518 | 187.274 | Unverified; private test only |
| qatami | 076-3.mp3 | assets/audio/qatami.mp3 | 2174807 | 135.904 | Unverified; private test only |
| sobhi | 203. الأذان بصوت القارئ اسلام صبحي  حصريا  - صوتي   mp3 .mp3 | assets/audio/sobhi.mp3 | 2770004 | 173.058 | Unverified; private test only |
| madani_fajr | My Audio17.mp3 | assets/audio/adhan_madinah.mp3 | 3503706 | 219.43 | Unverified; private test only |
| madani_regular | m_23495amgy1.mp3 | assets/audio/madani_regular.mp3 | 4416983 | 173.337 | Unverified; private test only |
| ibrahim_regular | My Audio7.mp3 | assets/audio/adhan.mp3 | 3319809 | 207.91 | Unverified; private test only |

The independent short alert, assets/audio/adhan_short.wav, remains CC0 (Adam-synagda, 17.5-second opening excerpt). It is explicitly labelled as a separate generic excerpt, never as a shortened version by a requested named caller. All twelve full MP3s and the WAV have matching native raw resources. Exact source URLs, roles and original hashes are in assets/data/curated_adhan.json; per-download SHA-256 and retrieval timestamps in local_audio/manifest.json. AUDIO_BATCH_REPORT.md records batch validation and caveats.

## Quran pages (unchanged)
Publisher: King Fahd Glorious Quran Printing Complex. Madinah Hafs, official 1441 archive.
Source: https://dm.qurancomplex.gov.sa/
Terms: https://dm.qurancomplex.gov.sa/rights/
The official Arabic terms permit free use in software, websites, publishing and institutional
and personal work inside and outside Saudi Arabia. Commercial physical printing/import
restrictions remain reserved. Rights evidence is retained in quran-rights.html and .txt.
The original 604 PDF-compatible Illustrator pages were rendered at 2600px, with blank outer
margins trimmed and a 40px border retained, then stored as lossless WebP. No Quran text was
reconstructed or generated. All 604 hashes are in quran-manifest.json; the enhancement does
not change them. Original archive SHA-256:
280c5d71ca16aaeeb3a343be1b92c76fa6df71d0671e202c026fde12402d9eef.

## Quran navigation metadata
Tanzil Quran Metadata v1.0 — (C) 2008–2009 Tanzil.info.
Documentation: https://tanzil.net/docs/Quran_Metadata
Original XML: https://tanzil.net/res/text/metadata/quran-data.xml
License: CC BY, explicitly declared as license="cc-by" in the publisher XML; the XML does
not specify a version. Attribution is retained here and in the app's Sources screen.
Original publisher XML is retained as Tanzil-quran-data.xml. Derived quran_navigation.json
contains Arabic surah names and page starts for 114 surahs and 30 Juz, calculated from the
publisher's verse/page boundaries. The documentation identifies its pages as Medina Mushaf.
Compatibility: exactly 604 pages; anchors include Al-Fatiha 1, Al-Baqara 2, Aal-Imran 50,
Al-Kahf 293, Ya-Sin 440, Juz 30 at 582, and the final surahs at 604. No verse text was added.

## Offline countries and cities
GeoNames countryInfo and cities15000, retrieved 2026-10-17:
https://download.geonames.org/export/dump/
https://download.geonames.org/export/dump/countryInfo.txt
https://download.geonames.org/export/dump/cities15000.zip
License: Creative Commons Attribution 4.0 International.
https://creativecommons.org/licenses/by/4.0/
GeoNames-readme.txt preserves the publisher's license and column descriptions.
Adaptation: retain IDs, native/ASCII names, country, coordinates, timezone and population;
combine with localized country names. 252 country/territory records, 34,166 city records.
This covers cities over 15,000 inhabitants and selected capitals, not every settlement.
Some territories have no city in this extract. Manual coordinate/timezone entry is available.
Data is provided by GeoNames as-is, without a completeness or accuracy warranty.

Arabic country names: Unicode CLDR, Unicode License v3 (Unicode.txt).
https://github.com/unicode-org/cldr-json
Source: cldr-json/cldr-localenames-full/main/ar/territories.json
https://www.unicode.org/license.txt
Flags are Unicode regional-indicator sequences derived from country codes; no flag image
artwork or third-party flag-font asset is bundled. Rendering depends on Android's font.

## Adhkar and transmitted supplications
1. Seen-Arabic/Morning-And-Evening-Adhkar-DB, MIT (Seen-Adhkar-MIT.txt).
https://github.com/Seen-Arabic/Morning-And-Evening-Adhkar-DB
Source ar.json supplies Arabic content, prescribed counts/count descriptions, references,
and source-provided notes/hadith context. Morning includes type 0/1; evening type 0/2.
26 morning and 24 evening items are bundled. Arabic content, source references and counts
are retained verbatim; remote audio URLs are not fetched or redistributed.

2. asellam/HisnElMuslim, MIT (Hisn-MIT.txt).
https://github.com/asellam/HisnElMuslim
Original hisn.json is a documented transcription of Hisn al-Muslim by Sa'id ibn Ali ibn Wahf
al-Qahtani, compared by the repository author against a second copy. Includes source references.
15 sleep items, 4 waking items and a curated set of 12 transmitted supplications are bundled.
Text, Count and Reference are retained verbatim. This is a selection, not every dua in the book.
No independent authenticity grade is invented. Grading text present in a source reference is
shown as part of that reference; unavailable structured grading stays null. Scholarly differences
are not resolved by the app. Both datasets permit offline redistribution under their MIT licenses;
the complete applicable license notices are included in assets/licenses/.

## Earlier licensed recordings and retained short excerpt
- adhan.ogg: Beautiful adhan, Adam-synagda, 2022-04-29, CC0 1.0.
  https://commons.wikimedia.org/wiki/File:Beautiful_adhan.ogg
  https://creativecommons.org/publicdomain/zero/1.0/
  Unmodified original; 154.018 seconds. SHA-1 a1fa4fd942401922c5c3301816384aae86956522.
- adhan_short.wav: opening 17.5-second excerpt of the above, converted to PCM WAV and
  cut during the quiet gap. No words added, reordered or presented as a full/Fajr call.
  The earlier zero-sample Ogg excerpt was discovered during enhancement inspection and
  preserved in the backup rather than redistributed. The replacement has 771,750 frames.
- adhan_madinah.ogg: Call to prayer from the prophet mosque, ejaz215, CC BY 3.0 Unported.
  https://commons.wikimedia.org/wiki/File:33937_ejaz215_call-to-prayer-from-the-prophet-s-mo.ogg
  Original source: http://www.freesound.org/people/ejaz215/sounds/33937/
  https://creativecommons.org/licenses/by/3.0/
  Unmodified original, 186.553 seconds. SHA-1 4aa432b9e44804e7d72af4429bd743aa5fa9e3a4.
- adhan_makkah.ogg: Adhan, Great Mosque of Mecca - Jan 21, 2013, Seyfula Islam,
  CC BY 3.0 Unported. Wikimedia source license reviewed by MZaplotnik on 2018-07-19.
  https://commons.wikimedia.org/wiki/File:Adhan,_Great_Mosque_of_Mecca_-_Jan_21,_2013.webm
  Original authorship source: https://www.youtube.com/watch?v=KYi-PuOqVnA
  https://creativecommons.org/licenses/by/3.0/
  Audio extracted and transcoded to Ogg Vorbis, 197.087 seconds. No words reordered.
  Original video SHA-1 818becd553dde887095641bd1c86549db44060bc. Video is not bundled.

CC BY recordings may be redistributed/adapted, including commercially, with attribution,
license link and change disclosure; credits above satisfy those requirements in the app and
this distribution. No endorsement by the recordists or mu'adhins is implied.
Both locations are source-described field recordings, not identity claims about a named reciter.
All four audio files were completely decoded and checked for nonzero sample count and signal.
See audio-validation.json for durations, peaks and SHA-256 values. Device playback is unverified.
Only adhan_short.wav remains bundled from this earlier set. The three full Ogg files are preserved outside the current APK in local_audio/legacy_licensed/. The new requested MP3 files and native resources are listed above.

## Historical named-recording research (before the requested private build)
Nasser Al Qatami, Yasser Al Dosari, and Mishary Alafasy were researched, including AlAdhan's
public downloads and Islamic Network licensing discussions. No recording-specific permission
and sufficiently verified identity was established for those requested voices. A forum statement
calling files public domain while reserving copyright to mu'adhins was not treated as a clear
license for every named recording. No named-voice placeholder is presented as playable.
No dedicated Fajr recording with verified rights is bundled. To add these, provide a specific
recording with explicit APK redistribution rights and verifiable attribution. The recording
catalog is extensible without changing the per-prayer UI.

## Branding and software
The mosque vector, colors, layout, and Arabic Wird wordmark are original code-generated
branding. The wordmark is rendered from a system font; no font file is redistributed.
Dependency licenses are available in the app's Software Licenses screen:
adhan_dart — MIT; shared_preferences — BSD-3-Clause; geolocator — MIT;
timezone — BSD-2-Clause; flutter_local_notifications — BSD-3-Clause;
audioplayers — MIT; intl — BSD-3-Clause; workmanager — MIT;
home_widget 0.10.0 — BSD-3-Clause; AndroidX WorkManager 2.11.2 — Apache-2.0.


## Historical Wird 2.0 photography and Arabic typography (2026-10-19)

The following real photographs were bundled in 2.0 and replaced in 2.1 by the user-requested artwork. The original files remain in the source backup, and their metadata is retained in splash-photographs-2.0.json. These are historical attributions, not descriptions of the active 2.1 splash images. CC BY-SA derivatives remain under the same stated licence; app code is not relicensed by this asset attribution.

- makkah: M sh شراونة محمد. CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0). Source: https://commons.wikimedia.org/wiki/File:%D8%A7%D9%84%D9%83%D8%B9%D8%A8%D8%A9_%D8%A7%D9%84%D9%85%D8%B4%D8%B1%D9%81%D8%A9_%D9%81%D9%8A_%D9%85%D9%83%D8%A9.jpg. File: assets/branding/makkah.webp, 1500 × 2000. SHA-256 59081af5d3c20519ffd7dfddf3e956602b62b936f31254156adb1408be31692d.
- madinah: Radosław Botev. CC BY 3.0 pl (https://creativecommons.org/licenses/by/3.0/pl/deed.en). Source: https://commons.wikimedia.org/wiki/File:Masjid_al-Nabawi_2024_%2811%29.jpg. File: assets/branding/madinah.webp, 1600 × 1200. SHA-256 0dd86a71a17b436c7babcd8501573aae0618779c75fcd2fd9dd4d9fd6cbceee5.
- aqsa: Virtutepetens. CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0). Source: https://commons.wikimedia.org/wiki/File:Al-Aqsa_Mosque_%282018%29_front_and_cupola.jpg. File: assets/branding/aqsa.webp, 1600 × 1200. SHA-256 81a6ccfba9a697acdfdf96bc6b4264277a9d1e1e4a7dde61f34444bdace313f9.

Makkah shows the Kaaba; Madinah shows the Prophet’s Mosque courtyard/Green Dome; the Al-Aqsa source shows its interior cupola. All three were visually inspected; no sacred structure or text was generated. The requested rotating experience uses these photographs, not generated depictions.

Noto Sans Arabic: Copyright 2022 The Noto Project Authors (https://github.com/notofonts/arabic). SIL Open Font License 1.1, unchanged variable TTF obtained from the official google/fonts/ofl/notosansarabic repository. Complete licence: assets/licenses/NotoSansArabic-OFL.txt. Font file assets/fonts/NotoSansArabic.ttf. The earlier system-font wordmark remains in the native initial icon; the branded photo transition and Flutter interface use the bundled font.

The normal application UI no longer exposes developer-oriented source/licence menus, as requested. These notices and machine-readable asset metadata remain bundled in the APK and supplied with the project. The twelve requested Adhan recordings retain the previously documented unverified redistribution status; the build continues as a private-user audio build, not a claim of public-distribution clearance.

## Wird 2.1 reference identity (2026-10-19)

The user supplied «صفحة ورد في رحاب الحرم.png» and «ثلاثة معالم وروح واحدة.png» as the requested visual identity. The first supplied portrait is packaged losslessly as assets/branding/makkah.webp. Madinah and Jerusalem variants were derived with the built-in image-generation tool from that reference, changing the lower scene only. They are illustrative generated artwork, not documentary photographs. No independent third-party licence or authorship of the supplied references is asserted.

The native renderer draws the original upper 52% over every variant. Thus the exact original verse calligraphy, wordmark and citation remain identical across the three splash screens; no generated Quran page or replacement verse is used. All three complete artworks have identical dimensions, 838×1877; native copies match the Flutter asset hashes. Source/provenance, prompt and common-region metadata: assets/licenses/splash-images.json and reference-brand.json. In 3.1 the splash is shown for at least 3000ms after its native presentation becomes visible, then fades out for 240ms after Flutter is ready.

Amiri Regular/Bold, copyright 2010–2022 The Amiri Project Authors (https://github.com/aliftype/amiri), unmodified official TTFs from https://github.com/google/fonts/tree/main/ofl/amiri. SIL Open Font License 1.1; full licence assets/licenses/Amiri-OFL.txt. Amiri is a compatible classical Arabic interface choice, not a claim that the font in the supplied artwork has been identified. The original splash wordmark stays as supplied. Noto Sans Arabic remains for readable time numerals and retained components. Code-drawn leaf/arch and quiet geometric motifs follow the supplied identity.


## Wird 3.0 on-demand content (2026-10-20)

Quran page images are now prepared in content_site/quran/pages/ rather than bundled in the APK. All 604 bytes/checksums remain unchanged from the prior licensed source; source files remain in assets/quran/pages for verification and backup. Published payload/source notices: CONTENT_SOURCES.md and content_site/SOURCE_NOTICES.md. The APK contains only the verified catalogue, navigation metadata and existing fonts/branding/audio.

The prepared site includes eleven Arabic tafsirs and Arabic Sahih al-Bukhari/Muslim from OpenITI release v2025.1.9 under CC BY-NC-SA 4.0. Each JSON preserves its edition header; the catalogue preserves original URI, SHA-256, attribution and licence. Derived book payload files retain CC BY-NC-SA 4.0. QuranEnc English Rowwad, English Noor International and Urdu Junagarhi retain all original rows, footnotes, publisher metadata and version information under QuranEnc republication terms (https://quranenc.com/en/home/api); this is not a CC licence claim. No unverified English/Urdu tafsir or hadith book translations were copied. Corpus transcription quality varies; the text is verified against its digital source, not independently proofread religious scholarship.

Urdu country names: official Unicode CLDR, Unicode License v3, assets/licenses/CLDR-LICENSE.txt. Arabic/English/Urdu interface labels are original UI text, distinct from religious source text. crypto (BSD-3-Clause), path_provider (BSD-3-Clause) are used directly for integrity checks and app-private caching. Existing audio recordings retain their earlier unverified redistribution status; none are copied into the public Pages payload.


## Wird 3.1 calendar dependency (2026-10-20)

hijri_date 1.1.0 (https://pub.dev/packages/hijri_date/versions/1.1.0), copyright 2018 AHMED ALJOAID, BSD-2-Clause as supplied in the package. Complete unmodified notice: assets/licenses/HijriDate-BSD-2-Clause.txt. Used for offline Umm al-Qura calendar conversion and localized month names only; no IslamicEventsManager, moon-phase predictions or new religious-text claims are used. Transitive flutter_svg/vector_graphics components retain their published notices in Flutter's bundled dependency licence inventory. Native artwork timing metadata is updated to 3000ms; artwork checksums and the fixed verse are unchanged.

## 3.2 library additions (2026-10-21)
- assets/data/hisn-duas.json: 131 additional chapters / 283 entries from the cached original asellam/HisnElMuslim hisn.json. Text, Count, Reference retained exactly; audio links omitted. Only explicit positive-count, referenced entries are included. Stable chapter IDs derive from original titles. Existing session IDs/data remain unchanged. MIT, Copyright (c) 2021 Abdellah SELLAM; full notice assets/licenses/Hisn-MIT.txt. This dataset is a transcription, not a new scholarly authenticity assessment.
- Requested nawafalqari/ayah/src/data/adkar.json was inspected, not bundled: no repository license; upstream islambook.com cited without redistribution permission. Audit snapshots remain in build/qa/3.2, outside APK and public hosting.
- Four additional hosted Arabic hadith books: Abu Dawud, Tirmidhi, Nasai Sunan Sughra (al-Mujtaba), Ibn Majah. Pinned OpenITI RELEASE/v2025.1.9, CC BY-NC-SA 4.0; exact edition URLs, source SHA256, original headers and attribution in content manifest/JSON and CONTENT_SOURCES.md. Noncommercial/share-alike terms apply to these text payloads. No new audio assets added.

## 3.3 interface-only changes (2026-10-21)
No new audio, photographs, fonts or religious text added. The feature-tour spotlight is drawn by app code; existing Material icons, fonts and source content retain the licenses above. Source references remain available from the Adhkar information icon.


## Library expansion prepared 2026-10-22 (source changes, no APK build)

Source: OpenITI RELEASE v2025.1.9. Publisher licence statement:
https://github.com/OpenITI/documentation/blob/master/index.md#how-can-i-use-openiti-what-license-is-used
Licence: CC BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/).
Attribution to OpenITI and exact edition URI is retained in the manifest and every JSON part.
The conversion splits source text into JSON and removes no religious wording; original source header/page references remain.
The same licence applies to the derived text dataset. Non-commercial use only; no independently licensed PDF scans are included.
These are corpus transcriptions, not a claim of new scholarly proofreading or authentication of every narration.

| Work | Parts | Payload bytes | Exact edition | Original SHA256 |
|---|---:|---:|---|---|
| الزهد — أحمد بن حنبل | 8 | 1220770 | https://raw.githubusercontent.com/OpenITI/RELEASE/v2025.1.9/data/0241IbnHanbal/0241IbnHanbal.Zuhd/0241IbnHanbal.Zuhd.Shamela0008494-ara1.mARkdown | `625ec5d34b67183e7e0dd44bbdde4f3d2a2f51aa2636853c864a742c6f0a8292` |
| الرسالة — الشافعي | 38 | 521492 | https://raw.githubusercontent.com/OpenITI/RELEASE/v2025.1.9/data/0204Shafici/0204Shafici.Risala/0204Shafici.Risala.JK000143-ara1 | `6edc793c3f329c1fa9950e2ac52ddf1067a3a8e2a16de37958b8f74ca55ba793` |
| الأم — الشافعي | 140 | 11186679 | https://raw.githubusercontent.com/OpenITI/RELEASE/v2025.1.9/data/0204Shafici/0204Shafici.Umm/0204Shafici.Umm.JK000147-ara1 | `9e5e2a1c82a59d0c05f3b3bd697e94bce968571e7cf720a3de3c3667786948ff` |
| العبودية — ابن تيمية | 8 | 192961 | https://raw.githubusercontent.com/OpenITI/RELEASE/v2025.1.9/data/0728IbnTaymiyya/0728IbnTaymiyya.Cubudiyya/0728IbnTaymiyya.Cubudiyya.Shamela0022647-ara1 | `5537ec2845de487787489ddedb9adebb3c7911d0ed9c692bf601b089b3af27fe` |
| مقدمة في أصول التفسير — ابن تيمية | 4 | 98279 | https://raw.githubusercontent.com/OpenITI/RELEASE/v2025.1.9/data/0728IbnTaymiyya/0728IbnTaymiyya.MuqaddimaFiUsulTafsir/0728IbnTaymiyya.MuqaddimaFiUsulTafsir.Shamela0012081-ara1 | `eb5cf54102e9a301a87a83449c4f16c6913d0541fa071ab39c1533b18b195f0f` |
| العقيدة الواسطية — ابن تيمية | 4 | 56335 | https://raw.githubusercontent.com/OpenITI/RELEASE/v2025.1.9/data/0728IbnTaymiyya/0728IbnTaymiyya.CaqidaWasitiyya/0728IbnTaymiyya.CaqidaWasitiyya.JK000359-ara1 | `dc1e19adcacfcb5561ff01390b840305655edceb4596a899bbe073f343725d6f` |
| مسند أحمد بن حنبل | 1541 | 19230234 | https://raw.githubusercontent.com/OpenITI/RELEASE/v2025.1.9/data/0241IbnHanbal/0241IbnHanbal.Musnad/0241IbnHanbal.Musnad.Shamela0025794-ara1.mARkdown | `00ee0f74327d83af587153983d04ad45367fea42338566c82e871df30c2ceaa6` |

### Day/night splash contact sheet (2026-10-22)
- User reference: `C:/Users/majd alhafi/Downloads/Six Sacred Sites, Six Verses.png`.
- Edited with built-in image_gen: all lettering removed from six scenes; architecture/day-night composition retained. These are illustrative AI-edited scenes, not archival photographs.
- Project asset: `android/app/src/main/res/drawable-nodpi/wird_splash_six.png`.
- No independent third-party photograph licence is asserted; provenance is the user-supplied artwork.
- Exact prompt, SHA256, grid and text are recorded in `assets/licenses/reference-brand.json`.
- The original verse (Al-Baqarah 238) is rendered with bundled Amiri fonts by native code, outside generated imagery.
- Existing artwork files remain for compatibility; the new native renderer uses the six-scene sheet.

### Multiscript interface fonts (2026-10-22)
Original Noto Sans, Noto Sans Bengali, Noto Sans Devanagari, Noto Sans Tamil, Noto Sans Malayalam and Noto Sans SC variable TTF files from https://github.com/google/fonts/tree/main/ofl . Each carries SIL Open Font License 1.1. Files remain unmodified; original OFL/copyright notices are bundled as `assets/licenses/<family>-OFL.txt`. Exact download URLs, bytes, SHA256 and licence URLs are in `assets/licenses/ui-fonts.json`. Downloaded files were checked against repository Git blob hashes and actual font signatures. No runtime font download is required.

### 3.4.0 editorial and splash update
The current downloadable catalogue contains 28 editions, with only Tabari/Ibn Kathir/Baghawi tafsir; older entries documented above are historical and are no longer offered by the app. See CONTENT_POLICY.md. The user-reference six-scene PNG was edited with built-in image_gen to correct the wide Kaaba; exact prompt, SHA256 and provenance are in assets/licenses/reference-brand.json. This remains AI-edited illustrative artwork. The researched Wikimedia night photograph in tool/sources/makkah-original-photo.jpg was not used or bundled.
# Selected Quranpedia translations (2026-10-22)

Nine selected published editions now replace the earlier three-translation
catalogue. See [QURANPEDIA_TRANSLATIONS.md](QURANPEDIA_TRANSLATIONS.md) for exact
IDs, source snapshot, integrity checks and rights limitations. Reused under
[Quranpedia's data terms](https://quranpedia.net/dumps/LICENSE.md), with source
and version attribution in the downloadable content catalogue. Author/publisher
rights remain reserved; these translations are not labelled public domain or CC.
Original translation text and notes are preserved, stored on the content site,
and downloaded by surah on demand rather than bundled in the APK.


## Additional Sunni hadith references (2026-10-22)

Sahih Ibn Khuzaymah, Sahih Ibn Hibban (Ibn Balban arrangement), and Muwatta Malik are added as OpenITI v2025.1.9 text editions under the existing corpus CC BY-NC-SA 4.0 terms. Exact editions, reference links and limitations are recorded in ADDITIONAL_HADITH.md. Inclusion does not invent an authenticity grade for every report.


## Pending update 2026-10-24

- `assets/data/place-names.json`: verified GeoNames alternate names for 17,265 existing city IDs, in nine offered UI languages where available. GeoNames CC BY 4.0, attribution to GeoNames (https://www.geonames.org/), source https://download.geonames.org/export/dump/alternatenames/ and terms https://download.geonames.org/export/dump/readme.txt . Original coordinates/time zones are unchanged. Missing translated names retain the original name. Source archive hashes and coverage are in `assets/licenses/place-names.json`.
- Country display names use Unicode CLDR from unicode-org/cldr-json under Unicode License V3, bundled verbatim at `assets/licenses/Unicode-3.0.txt`. No runtime translation service.
- `android/app/src/main/res/font/wird_amiri.ttf` and `wird_amiri_bold.ttf` are exact copies of the existing licensed Amiri Regular/Bold assets under SIL OFL 1.1; original notices remain in assets/licenses. Widget geometry is app-authored native drawing; no new photograph is introduced.
- `ahmad_fadail_sahaba`: OpenITI v2025.1.9, `0241IbnHanbal.FadailSahaba.JK000482-ara1.mARkdown`, CC BY-NC-SA 4.0 with attribution to OpenITI. Text source, source SHA256 and per-part integrity records are in the content manifest and `sources/fadail-sahaba.json`. 925 source segments / 62 files, not a report-count claim. Noncommercial and share-alike restrictions apply. See LIBRARY_MANAGEMENT.md. The separately found IslamHouse PDF is NOT mirrored or bundled: no independent redistribution grant for that scan was established.

Islamic month and era UI labels use official Unicode CLDR `cldr-cal-islamic-full` for all nine interface languages, under Unicode-3.0. Exact source URLs and SHA256 are in assets/licenses/calendar-names.json. These are calendar labels, not translations of scripture.
