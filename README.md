# LingoDew Spoken: Japanese word frequency for Yomitan

A [Yomitan](https://yomitan.wiki/) frequency dictionary that ranks Japanese words by how often they are actually spoken in the videos of the [LingoDew](https://www.lingodew.com/) library. This snapshot is from 2026-10-25.

Most frequency lists are built from written text, novels or anime subtitles. This one counts speech from 3,974 Japanese YouTube videos, so the words you hear most in real conversation come first.

## Install

1. Download `lingodew-spoken-frequency-ja-yomitan.zip` from the [latest release](https://github.com/lingodew/spoken-frequency/releases/latest). Keep it zipped.
2. Open Yomitan's **Settings**, go to **Dictionaries** and click **Configure installed and enabled dictionaries**.
3. Click **Import** and pick the zip file.

Lookups now show a **LingoDew Spoken** rank next to each word; a lower number means the word is spoken more often. To sort results by it, choose it as the frequency sorting dictionary in the **Dictionaries** settings. Yomitan's update check picks up new monthly revisions.

## Corpus

| | |
|---|---|
| Videos | 3,974 |
| Channels | 184 |
| Words spoken (tokens) | 3,948,810 |
| Words in the dictionary | 23,825 |

The videos are native-speaker YouTube videos on news, language learning, cooking, daily life, entertainment, travel and other topics. Speaking speed and level statistics for the same videos are on [lingodew.com/research/](https://www.lingodew.com/research/).

## Method

- Japanese text is segmented into dictionary words with [jpdb.io](https://jpdb.io/). Readings and dictionary forms come from JMdict, and conjugated forms count toward the dictionary form (食べた and 食べない count as 食べる).
- Words are ranked by total occurrences, then by the number of videos they appear in.
- A word must appear in at least 3 videos and at least 3 times to be listed, which keeps out one-off names and recognition errors.
- Numbers, counter words with digits, and stray single kana are left out.
- When two dictionary entries share the same spelling and reading, they are merged into one entry.

Known limits: transcription and segmentation errors are possible, mostly at the low end of the list.

## License and credits

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), see `LICENSE-CC-BY-SA-4.0.txt`. Share-alike applies because the dictionary forms and readings come from JMdict.

Please credit **LingoDew (lingodew.com)** when you use or share this dictionary.

- Japanese text segmented with [jpdb.io](https://jpdb.io/).
- This publication has included material from the JMdict (EDICT, etc.) dictionary files in accordance with the licence provisions of the Electronic Dictionaries Research Group. See <https://www.edrdg.org/>.

The dictionary contains only words, readings and ranks: no subtitle text, translations, audio, timings or video links.

## About LingoDew

[LingoDew](https://www.lingodew.com/) is an app for learning English and Japanese from real YouTube videos: subtitles aligned word by word, tap any word for its meaning, and review saved words with spaced repetition. New snapshots of this dictionary are published monthly.
