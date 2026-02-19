# v0.3.0

## New Features

### Encrypted Vault
- Password-protected vault file stores multiple seeds and an address book
- AES-256-GCM encryption with Argon2id key derivation
- Create, unlock, lock, and delete vault from the top bar
- Switch between stored seeds without re-entering them

### Address Book
- Save contacts with custom labels to the vault
- Manage contacts in Settings (add, rename, delete)
- All address input fields across the app now feature autocomplete with saved identities and contacts
- Save unknown addresses directly from any address input dropdown
- After successful transactions, prompts to save the destination address

### Send to Many Templates
- Save the current recipient list as a named template
- Load, overwrite, and delete templates
- Templates support recipients with zero amounts (address-only lists)
- Stored in the encrypted vault alongside seeds and contacts

### QR Code on Receive Page
- QR code displayed for your identity address
- Copy QR as PNG image to clipboard

### Community Voting
- View active proposals and their options
- Cast votes with your identity

### SC Auctions
- View available smart contract auction slots
- Place bids on smart contract slots

### Settings Page
- Consolidated settings: backend selection, peer management, label sources
- Theme toggle (light/dark)
- Address book management
- Database import/export

## Improvements

- Unified `AddressInput` component with autocomplete across all pages (Send, Send to Many, Assets, QX Trading, Qswap, MSVault, Voting)
- Consistent address display format (`AAAA...ZZZZ`) throughout the app
- Send to Many: import recipients from text (paste tab/comma-separated lists)

## Downloads

| Platform | File |
|----------|------|
| Windows x64 | `Qubic.Net.Wallet-0.3.0-win-x64.zip` |
| macOS Intel | `Qubic.Net.Wallet-0.3.0-osx-x64.zip` |
| macOS Apple Silicon | `Qubic.Net.Wallet-0.3.0-osx-arm64.zip` |
| Linux x64 | `Qubic.Net.Wallet-0.3.0-linux-x64.zip` |

Verify downloads with the `.sha256` files included alongside each zip.
