# Orature Example

This contains the current output from Orature.

## Limitations

### Audio Format Limitations:
  - MP3
    - 44.1khz sample rate
    - mono
  - WAV
    - 44.1khz sample rate
    - 16 bit PCM
    - mono

### Marker Limitations:
    - Book Title
    - Chapter Title
    - Verse

### Burrito Support Usage Limitations

Currently Orature requires existence of certain internal Orature state for restoring project backups for resuming work 
on either Narrations or Translations regardless of container format (natively Orature uses Door43 Resource Containers).

As such, Orature imports of Scripture Burrito are used as source audio for use in oral to oral translation.

### Burrito Support Status

##### Timing Support

- [x] u23003 parsing for supported markers
- [ ] Support for multiple conventions of the timing file format such as hoisting

##### Audio Burrito Support

- [x] Import and Export of Orature Audio Scripture Burrito
- [x] Import of non-chapter audio
- [ ] Import of other implementations of Audio Scripture Burrito

##### Burrito Wrapper Support

- [ ] Import of Burrito Wrapper
- [ ] Export of Burrito Wrapper