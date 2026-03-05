# Music Library System

A Python-based library system for managing and tracking song information, including artist and genre analytics.

## Features

- **Instance Management**: Track song name, artist, and genre.
- **Global Analytics**:
  - Total song count.
  - Unique artist and genre lists.
  - Frequency tracking per artist and genre.

## Usage

```python
from lib.song import Song

song1 = Song("99 Problems", "Jay Z", "Rap")
print(Song.count) # 1
print(Song.artist_count["Jay Z"]) # 1
```

## Testing

Run the automated test suite:

```bash
python3 -m pytest lib/testing/song_test.py
```
