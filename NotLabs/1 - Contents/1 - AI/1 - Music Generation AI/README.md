# NotAI

## 1 - Abstract

NotAI is a transformer based ML model. NotAI and its dataset shall be uploaded to HuggingFace.

## 2 - Contents

### 2.1 - Purpose

NotAI generates melodies which the rest of a song can be built around. It will generate the melodies to be played on an 88 key piano.

### 2.2 - Data

The training data for NotAI shall be sourced from MIDI files.

Said MIDI files shall be formatted into the note sequence format (NSF). NSF shall represent an untimed sequence of notes where said notes are specified by a number representing their index on an 88 key piano, said numbers being arranged in order and separated by commas. NSF files shall have a .txt extension.

Excluding their extensions, the file names of the source MIDI files and their corresponding NSF files shall consist of the name of the song followed by a period, followed by the genre and a period, followed by the composer's name and a period, and the year of publication.

(e.g. "Symphony No 5.Classical.Beethoven.1808.txt")

Additional tags may be incorporated into the file name as well, and will likewise be separated by periods.

For training purposes, the data encoded into the file names shall be tokenized and factored into the vectorized data during training. A portion of the data will be set aside for a testing set.

Prompts given to the model shall consist of a series of string tags. The output of the model shall consist of an NSF sequence produced sequentially, in a generative manner.