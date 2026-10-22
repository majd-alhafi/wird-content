# Editorial selection — Wird 3.4.0

The user requested a specifically Sunni/Athari (Salafi) selection, rather than an ecumenical catalogue of all historical tafsir schools. This is an app editorial allow-list, not a declaration that all other Sunni authors are outside Sunni Islam, and not a guarantee that every report or transcription is sound.

## Sources used for selection

- Ibn Baz, recommended tafsir: https://binbaz.org.sa/fatwas/15685/افضل-كتب-تفسير-القران-الكريم . The first three specifically recommended works are Tabari, Ibn Kathir and Baghawi. The answer itself cautions that human-authored tafsir can contain errors and weak reports. We retain only those three tafsir in this conservative edition.
- Ibn Baz, the six hadith collections: https://binbaz.org.sa/fatwas/7521/المقصود-بالامهات-الست .
- Saudi al-Ifta hadith library, Musnad Ahmad: https://sunna.alifta.gov.sa/Book/Details?bookId=8 . This is not a claim that every narration in the Musnad is sahih.
- QuranEnc publisher declares its translations follow Ahl al-Sunnah wa-l-Jamaah: https://new.quranenc.com/ar/home . Retained translations are the already verified publisher editions, not generated translations.

## Retained catalogue (19 editions)

3 Quran translations (English Rowwad, English Noor International, Urdu Junagarhi); 3 tafsir (Tabari, Ibn Kathir, Baghawi); 7 hadith collections (Bukhari, Muslim, Abu Dawud, Tirmidhi, Nasai al-Sughra, Ibn Majah, Musnad Ahmad); 6 general classical books (Shafii Risala/Umm, Ahmad Zuhd, Ibn Taymiyya Wasitiyya/Ubudiyya/Introduction to Tafsir Principles).

The existing Arabic Hisn al-Muslim adhkar/duas and original Quran pages are preserved. See CONTENT_SOURCES.md and ASSET_CREDITS.md for exact editions, licences and metadata. No fresh scholarly authentication of individual reports is asserted.

## Excluded from the app catalogue

Zad al-Masir (Ibn al-Jawzi), Qurtubi, Nasafi, Baydawi, Razi, Zamakhshari, Jalalayn and Shawkani. Exclusion is conservative editorial scope in response to the user's request, not a blanket judgement on these authors or every passage in their works.

`ContentPolicy.allowedIds` filters the shipped, cached and refreshed catalogues. Unknown future titles are not silently admitted. The manifest and preparation script contain only the retained editions. Previously downloaded file bytes and reading preferences are not erased; excluded books are no longer reachable from the app catalogue.

OpenITI files remain attributed CC BY-NC-SA 4.0 transcriptions. Selection by original author is separate from licensing or the provenance of a particular digital edition; no retained source URI contains a Shia edition identifier.
