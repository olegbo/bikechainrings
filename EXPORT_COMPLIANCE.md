# Export Compliance (Apple)

- Encryption usage: only standard system TLS provided by Apple APIs.
- No custom or added cryptography.
- `ITSAppUsesNonExemptEncryption = false` set in Info.plist.
- Answers in App Store Connect:
  - Does your app use encryption? Yes (standard)
  - Is your app exempt? Yes
