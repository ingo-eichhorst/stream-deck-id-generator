
`ID Generator` copies a random ID with one tab to the clipboard.

# Description

ID Generator is a highly versatile application designed for Stream Deck, allowing users to generate and copy a wide range of unique identifiers with a single tap. This tool is ideal for various professionals and enthusiasts who require quick access to random and unique IDs for diverse purposes. Below are the key features and use cases where the app proves to be exceptionally useful.

## Features

Single-Tap ID Generation: With a single tap on the Stream Deck, generate and copy a variety of IDs directly to the clipboard, enhancing productivity and efficiency.

Wide Range of ID Types: The app supports generating multiple types of identifiers, including:
- Random Numbers: 4, 8, 16, and 32-digit random numbers.
- UUIDs: Universally Unique Identifiers, both time-based (v1) and random-based (v4, default).
- MAC Address: Media Access Control address for network interfaces.
- IP Addresses: Both IPv4 and IPv6 formats.
- URN: Uniform Resource Name, a unique identifier for resources.
- DOI: Digital Object Identifier, primarily used for academic and professional publications.
- OID: Object Identifier, used in various standards and protocols.

## Use Cases

Software Development:
- Database Testing: Generate unique identifiers for testing database operations, ensuring no duplication and maintaining data integrity.
- Session IDs: Create unique session IDs for managing user sessions in web applications.
- API Development: Quickly generate test data for APIs requiring unique identifiers.

Network Administration:
- MAC Address Generation: Useful for configuring network devices or simulating network environments.
- IP Address Assignment: Quickly generate IPv4 and IPv6 addresses for configuring networks or devices.

Cybersecurity:
- Random Number Generation: Useful for creating secure tokens, passwords, or encryption keys.
- UUIDs for Secure Transactions: Ensure secure and unique identifiers for transactions and logs.

Academic and Research:
- DOI Generation: Quickly generate DOIs for referencing academic papers and datasets.
- URNs for Digital Libraries: Assign unique identifiers to digital resources in libraries and repositories.

General Productivity:
- File Naming: Generate unique names for files to avoid conflicts and ensure organization.
- Tagging and Labeling: Create unique tags and labels for organizing data and resources.


# Development

Code is avaialabe at [Github](https://developer.elgato.com/documentation/stream-deck/).

Add plugin to Streamd Deck
```bash
ln -s $(pwd)/src/com.betterbegreat.id-generator.sdPlugin ~/Library/Application\ Support/com.elgato.StreamDeck/Plugins/
```

Set Streamdeck in debug mode
```bash
defaults write com.elgato.StreamDeck html_remote_debugging_enabled -bool YES
```

Open debugger in Chrome
http://localhost:23654/
and press CMD+r to reload
