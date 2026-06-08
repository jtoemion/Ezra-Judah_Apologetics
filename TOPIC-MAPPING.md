# Topic Mapping — Ezra-Judah Apologetics

## Database Sources
- `devotions.db` — Pak Erwien / Andar Ismail (1,634 entries)
- `ezra_devotions.db` — Ezra's Devotion (2,004 entries)

## Topic → Folder Mapping

### Core Apologetics Topics (existing folders)
| Topic in DB | Folder in Repo | Status |
|-------------|----------------|--------|
| Apologetics | `topics/apologetics/` | New folder |
| Existence of God | `topics/existence-of-god/` | Existing |
| Godship of Jesus | `topics/godship-of-jesus/` | Existing |
| Problem of Evil | `topics/problem-of-evil/` | Existing |
| Prophecy Fulfillment | `topics/prophecy-fulfillment/` | Existing |
| Resurrection Evidence | `topics/resurrection-evidence/` | Existing |
| Biblical Historical Cases | `topics/biblical-historical-cases/` | Existing |
| Case of the Bible | `topics/case-of-the-bible/` | Existing |
| Parakletos Counter Narrative | `topics/parakletos-counter-narrative/` | Existing |

### General / Devotional Topics
| Topic in DB | Folder in Repo | Notes |
|-------------|----------------|-------|
| ALKITAB | `topics/alkitab/` | Scripture reference |
| Cinta | `topics/cinta/` | Love |
| DUNIA KERJA | `topics/dunia-kerja/` | Work world |
| Doa | `topics/doa/` | Prayer |
| Faith | `topics/faith/` | Iman |
| General | `topics/general/` | Misc |
| Harapan | `topics/harapan/` | Hope |
| Iman | `topics/iman/` | Faith (Bahasa) |
| Kebahagiaan | `topics/kebahagiaan/` | Happiness |
| Kesabaran | `topics/kesabaran/` | Patience |
| Masalah | `topics/masalah/` | Problems |
| Roh Kudus dan Doa | `topics/roh-kudus-doa/` | Holy Spirit & Prayer |
| SEJARAH | `topics/sejarah/` | History |
| SOTERIA | `topics/soterias/` | Salvation |
| Syukur | `topics/syukur/` | Gratitude |
| TRINITAS | `topics/trinitas/` | Trinity |
| Kristologi | `topics/kristologi/` | Christology |

### Selamat Series (NEW — dedicated folder)
| Topic in DB | Folder in Repo |
|-------------|----------------|
| Selamat Bergereja | `topics/selamat/selamat-bergereja/` |
| Selamat Bergumul | `topics/selamat/selamat-bergumul/` |
| Selamat Berguna | `topics/selamat/selamat-berguna/` |
| Selamat Berhikmat | `topics/selamat/selamat-berhikmat/` |
| Selamat Berjuang | `topics/selamat/selamat-berjuang/` |
| Selamat Berkarunia | `topics/selamat/selamat-berkarunia/` |
| Selamat Berkarya | `topics/selamat/selamat-berkarya/` |
| Selamat Berkembang | `topics/selamat/selamat-berkembang/` |
| Selamat Berkerabat | `topics/selamat/selamat-berkerabat/` |
| Selamat Berkiprah | `topics/selamat/selamat-berkiprah/` |
| Selamat Berpadu | `topics/selamat/selamat-berpadu/` |
| Selamat Berpelita | `topics/selamat/selamat-berpelita/` |
| Selamat Berpulih | `topics/selamat/selamat-berpulih/` |
| Selamat Berteduh | `topics/selamat/selamat-berteduh/` |
| Selamat Berteman | `topics/selamat/selamat-berteman/` |
| Selamat Melayani Tuhan | `topics/selamat/selamat-melayani-tuhan/` |
| Selamat Memanusia | `topics/selamat/selamat-memanusia/` |
| Selamat Membarui | `topics/selamat/selamat-membarui/` |
| Selamat Menabur | `topics/selamat/selamat-menabur/` |
| Selamat Mengaku | `topics/selamat/selamat-mengaku/` |
| Selamat Mengikut Dia! | `topics/selamat/selamat-mengikut-dia/` |
| Selamat Mengindonesia | `topics/selamat/selamat-mengindonesia/` |
| Selamat Mewaris | `topics/selamat/selamat-mewaris/` |
| Selamat Natal | `topics/selamat/selamat-natal/` |
| Selamat Pagi Tuhan! | `topics/selamat/selamat-pagi-tuhan/` |
| Selamat Pagi, Tuhan? | `topics/selamat/selamat-pagi-tuhan-kritis/` |
| Selamat Panjang Umur | `topics/selamat/selamat-panjang-umur/` |
| Selamat Paskah | `topics/selamat/selamat-paskah/` |
| Selamat Sehati | `topics/selamat/selamat-sehati/` |
| Selamat Sejahtera | `topics/selamat/selamat-sejahtera/` |
| Selamat Bercinta | `topics/selamat/selamat-bercinta/` |
| Selamat Berbuah | `topics/selamat/selamat-berbuah/` |
| Tukang Cerita Selamat | `topics/selamat/tukang-cerita-selamat/` |
| Tukang Ngantar Selamat | `topics/selamat/tukang-ngantar-selamat/` |
| buku Selamat* | `topics/selamat/buku-selamat/` | Buku (book) sub-series |

### Ignored / Skip
| Topic | Reason |
|-------|--------|
| Unknown | No clear topic |
| _Ngapain_... | Identity note, not a devotion |

## Database Files
- `devotions.db` — Erwien/Andar Ismail source
- `ezra_devotions.db` — Ezra's Devotion source

## Implementation Note
SQLite databases stored as-is. Topic folders contain markdown exports of entries per topic.
Export script: `scripts/export_topics.py` (to be created).
