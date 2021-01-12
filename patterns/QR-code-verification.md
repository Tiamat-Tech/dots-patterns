## The Design Problem

Use QR codes to quickly scan and verify each other's key signatures. In a decentralized world, QR codes no longer have to link to a centralized shared item.
Instead, you can embed information directly in the QR code to share with peers.

Decentralized applications can rely upon very long strings of characters and/or numbers for cryptography, end-to-end encryption, or secret groups.
These very long URLS can be difficult to share in some cases.

## The Design Solution

Give users an option to generate, share, and scan QR codes as a way to transfer or share cryptographic keys. In a decentralized world, QR codes no longer have
to link to a centralized shared item. Instead, you can embed information directly in the QR code to share with peers. QR codes can also be exported or printed
as an image and sent over a third-party service such as WhatsApp, whereas BIP39 phrases can be quite long in many cases and confusing. BIP39 phrases are not
particularly memorable, and they are not accessible (literacy, language, bad eyesight, dyslexic, etc).

### Examples

Encrypted instant messaging services (Signal, Threema, Delta.Chat, Element)

## Why Choose QR Code Verifcation?

When you want to securely verify or transfer information between two peers

## Best Practice: How to Implement QR Code Verification

Tell users when the QR code is safe to share publicly or should only be shared with trusted peers.
Allow users to load the QR code as an image in case their camera is broken or unusable.

## Potential Problems with QR Code Verification

For usability, manually copying BIP39 phrases is more complex than showing and scanning a QR code or importing a backup file, so QR codes are recommended
in most cases. However, BIP39 may be useful instead of QR codes in low-bandwidth scenarios where MMS is not available as it can be sent over SMS. If used,
BIP39 should be translated into the user's native language.

## The Take Away

## References & Where to Learn More

https://www.usenix.org/system/files/conference/soups2018/soups2018-vaziripour.pdf

## Tags

app, identity
