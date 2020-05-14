# OCR17

Ground truth and models for 17th c. French prints.

## Organisation of the repo
```
|-Models
  |-Kraken
  |-Calamari
|-Testing_data
  |-XIX
  |-XVI
  |-XVIII
|-Training_data
  |-72dpi
    |-Print_1
      |-extracted
      |-training_data
      |-README.md
      |transcription.txt
    |-Print_2
  |-400dpi
  |-400dpi_MUFI
  |-600dpi
```

## Corpus

Most of the training data are taken from literary texts, and especially plays, printed throughout the 17th century. Each print is described in depth in its own folder.

## Transcriptions
Transcripts are almost diplomatic. Long *ſ* is maintained ( *plaiſir* and not *plaisir*).
Ligatures which have disappeared ( *ſt*, *st*, *ct*) are not kept, but not those that are maintained in contemporary French (*œ*, *æ*).

For certain prints only, unicode and MUFI ligatures are maintained (folder ```400dpi_mufi```) for testing purposes. Ground truth is provided both with and without them.

## Licence
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution 4.0 International Licence</a>.

## Thanks
Special thanks to Thibault Clérice for his magic xslt stylesheets (and many other things)!

