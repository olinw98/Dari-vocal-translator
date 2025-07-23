# Dari-vocal-translator

The idea for this project came from my time volunteering to help a family of recent immigrants from Afghanistan. Only one of their children spoke any English at all and as far as we could tell, the mother was completely illiterate, making communication fairly difficult. AI and translation tools did help to a degree, but all required us to go through the child that knew English due to the mother's illiteracy and the lack of Dari text-to-speech capability on all translator platforms (that we could find). To bridge that gap and make direct conversation a little easier, I created this English to Dari voice translator. Since Dari was not available on mainstream open-source translation packages, I took the following approach for translating from English to Dari:

1. Take English speech (or text) and translate it to Persian (Persian or Farsi is an endonym of Dari, making it a close enough translation for simple communication purposes).
2. Use an Arabic text-to-speech tool to read the translated Persian out loud (neither Persian nor Dari text-to-speech was available, and while Arabic is a separate language under a different linguistic family, the phonetic pronunciation was once again close enough for simple communication purposes)

The Dari to English translation then did the opposite; recognizing Persian speech, translating it into English, and reading it back to close the translation loop.
