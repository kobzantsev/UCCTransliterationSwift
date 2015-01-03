UCCTransliterationSwift
=======================

Clean and focused Transliteration class for Swift

### Usage

as simple as this:

```swift
var u = UCCTransliteration()

u.transliterate("большой рамки") // = "BOLSHOI RAMKI"
u.transliterate("μεγάλη πλαίσιο") // = "megali plaisio"
u.transliterate("Fıstıkçı Şahap") // = "Fistikci Sahap"
```
