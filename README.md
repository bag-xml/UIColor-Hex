# UIColor+Hex
 Hex string to UIColor RGB converter

## How do I use this?
First of all, this was made with the iOS 6.1 and 7.1 SDK in mind, so it may not work on anything that might be considered modern. 
To call this, import the header into your class and then call the convert function via `+ (UIColor *)colorWithHexString:(NSString *)hexString;`, aka. + `[UIColor colorWithHexString:(hex string goes here]`. The returned value will contain the r, g, b, and alpha values of the color already as a UIColor property.
