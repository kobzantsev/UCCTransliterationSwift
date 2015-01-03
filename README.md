UCCTransliterationSwift
=======================

Clean and focused Transliteration class for Swift

### Usage

as simple as this:

```swift
var u = UCCTransliteration()

u.transliterate("большой рамки") // returns "BOLSHOI RAMKI"
u.transliterate("μεγάλη πλαίσιο") // returns "megali plaisio"
u.transliterate("Fıstıkçı Şahap") // returns "Fistikci Sahap"
```
