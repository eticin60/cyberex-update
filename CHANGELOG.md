# Changelog

All notable changes to the CyberEx Android Application will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Planned Features
- iOS version
- Apple Watch companion app
- Desktop application (Windows/Mac/Linux)
- Hardware wallet integration
- Advanced trading algorithms

---

## [1.4.3] - 2026-03-20

### 🚀 Performance & Connectivity Update

### Added
- **Veri Kotası Optimizasyonu**: Uygulamanın veri tüketimi büyük ölçüde optimize edildi ve kota aşımı sorunları giderildi.
- **Giriş Sorunu Düzeltildi**: Bazı durumlarda yaşanan "Unknown Error" giriş hatası çözüldü.
- **Daha Hızlı Veri Akışı**: Haberler ve piyasa güncellemeleri artık çok daha verimli ve akıcı bir şekilde aktarılıyor.

---

## [1.4.2] - 2026-02-22

### 🚀 Trading & Performance Update

### Added
- **Turbo Bot Optimization**: Enhanced the logic for manual trades to ensure accurate amount and leverage execution.
- **Smart AI Thresholding**: Automated confidence levels based on the selected trading timeframe for improved strategy success.
- **Live Market Integration**: Connected home screen analytics to real-time market data for accurate volatility tracking.
- **Financial Synchronization**: Resolved issues with exchange rate fetching and balance consistency.
- **Enhanced Access Control**: Modernized the security infrastructure for dynamic page management.

### Fixed
- Fixed internal logic conflicts during high-frequency trading data processing.
- Resolved data mapping issues in the backend management layer.
- Improved UI responsiveness and input field alignment for better user experience.

---

## [1.4.1] - 2026-02-07

### 🚀 Financial Ecosystem & Stability Update

### Added
- **P2P Internal Transfers**: Users can now send assets to each other instantly with zero fees within the platform.
- **MASAK Security Compliance**: Implemented a mandatory 48-hour withdrawal lock for security compliance and user safety.
- **Legal Categorization**: New "Legal" filter type added to the history and status pages of the web portal.

### Changed
- **Corporate Terminology**: Replaced informal labels (e.g., "Bakiye Yükleme") with corporate standards ("CyberEx" via Param).
- **Dialog System**: Refactored `ComplianceDialogManager` to use `MaterialAlertDialogBuilder` and optimized interaction chains.
- **Campaign Persistence**: KYC campaign dialog now remains active until stage completion, as per institutional requirements.

### Fixed
- Fixed screen dimming and overlay issues when multiple dialogs appear sequentially.
- Resolved Material 3 theme incompatibility in custom transparent dialogs.
- Corrected various text size and alignment issues in XML layouts.

---

## [1.4.0] - 2026-01-26

### 🚀 Legal & Infrastructure Update

### Changed
- **Legal Documentation**: Complete overhaul of Terms, Privacy, Risk, Security, and KVKK documents to professional standards.
- **QR Code System**: Updated dynamic QR codes to point to the correct v1.4.0 APK source.
- **Web Portal**: Updated all download links and version badges to reflect the latest beta status.
- **Help Center**: Expanded FAQ content and improved category layout.

### Fixed
- Fixed outdated APK download links in the landing page.
- Fixed version mismatch in footer badges.

---

## [1.3.9] - 2026-01-25

### 🎉 Major Feature Update

### Added
#### Advanced KYC System
- Manual data entry for identity verification
- ID card/passport scanning with ML Kit
- Liveness detection to prevent spoofing
- Enhanced security with face biometrics

#### Social Authentication
- Google Sign-In integration
- Apple Sign-In integration
- Facebook Login support
- Seamless account linking

#### Profile & UI Enhancements
- Modern Glassmorphism design for profile page
- VIP badge system for premium users
- Reorganized menu structure for better UX
- Customizable profile avatars

#### Trading Limits
- Daily, weekly, and monthly deposit/withdrawal limits
- Separate limits for Crypto, TL (Turkish Lira), and USD
- Real-time limit tracking in "Limits" section
- Automatic limit reset timers

#### AI Assistant (Gemini) Improvements
- Internet search capabilities (weather, time, news, etc.)
- Screen sharing and analysis features
- Enhanced conversation context
- Improved response accuracy

#### Futures Trading Enhancements
- Dynamic order book with real-time updates
- Precision/decimal place settings
- Professional trading calculator
- Advanced position management

#### Google ML Kit Integration
- Automatic ID text extraction
- Face detection for KYC
- Improved liveness checks
- Enhanced security protocols

### Changed
- Improved UI/UX for Terms of Service dialogs
- Enhanced Privacy Policy dialog readability
- Background rendering optimizations
- Better coroutine management in async operations

### Fixed
- 🐛 Critical app crashes resolved
- 🐛 Theme inconsistencies fixed
- 🐛 Null pointer exceptions eliminated
- 🐛 Memory leaks patched
- 🐛 UI alignment issues on various screen sizes
- 🐛 Firestore transaction errors corrected

### Security
- Enhanced biometric authentication
- Improved data encryption
- Better session management
- Secure credential storage

### Performance
- Faster app startup time
- Optimized database queries
- Reduced memory footprint
- Smoother animations

### Known Issues
- ⚠️ TL Deposit service temporarily under investigation (Bank API integration)
- ⚠️ TL Withdrawal service temporarily under investigation (Bank API integration)
- ⚠️ KYC system undergoing maintenance (Algorithm updates)

---

## [1.0.0] - 2026-01-18

### 🎉 Initial Beta Release

### Added
#### Trading Features
- Spot Trading with real-time order matching
- Futures Trading with up to 100x leverage
- One-Click Trading for instant execution
- Advanced TradingView charts
- Trading Bots for automated strategies
- Risk Management tools
- Position monitoring
- Funding Rate monitor
- Liquidation tracker

#### Wallet & Finance
- Multi-asset crypto wallet
- TL (Turkish Lira) deposit/withdrawal integration
- Crypto deposit/withdrawal (BTC, ETH, USDT, etc.)
- NFT management
- Token swap functionality
- Gas fee tracker
- Transaction history
- Card management

#### Security & KYC
- KYC verification system with face matching
- Liveness detection
- 2FA authentication
- Device management
- Login history tracking
- Password management
- Biometric authentication (Fingerprint/Face ID)
- Multi-account support

#### Social Features
- Global chat
- Private messaging
- Crypto-specific group chats
- Friend requests & connections
- Social trading (copy trading)
- Trading competitions
- Leaderboards

#### AI & Analytics
- Google Gemini AI Smart Advisor integration
- Market sentiment analysis
- AI-powered technical indicators
- Automated chart analysis
- Smart trading insights

#### Portfolio & Reports
- Real-time portfolio tracking
- Profit/Loss calendar
- Tax reports
- Trading journal

#### Rewards & Gamification
- Points system
- Discount coupons
- KYC completion bonuses
- Profit-based rewards

#### Notifications
- Price alerts
- Smart notification system
- Push notifications
- Position alerts
- Activity notifications

#### Education
- Educational content
- Economic calendar
- Market news feed
- Fear & Greed Index

#### System
- Firebase integration
- Real-time WebSocket connection
- REST API client
- Data synchronization
- Multi-language support (Turkish/English)
- Customizable dashboard
- Profile & avatar system
- Dark mode

### Known Issues
- ⚠️ TL Deposit service temporarily unavailable (Bank API issue)
- ⚠️ TL Withdrawal service temporarily unavailable (Bank API issue)
- ⚠️ KYC system under maintenance (Algorithm updates)
- Some users may experience slow loading on first launch
- Minor UI alignment issues on tablets

### Security
- APK signed with official CyberEx certificate
- SHA-256 checksum available for verification
- All data transmitted over HTTPS
- End-to-end encryption for private messages

---

## Version Naming Convention

- **Major.Minor.Patch-Stage**
  - **Major**: Breaking changes or major feature releases
  - **Minor**: New features, backwards compatible
  - **Patch**: Bug fixes and minor improvements
  - **Stage**: alpha, beta, rc (release candidate), or stable

---

## Categories

### Added
New features that have been added to the application.

### Changed
Changes to existing functionality.

### Deprecated
Features that will be removed in future versions.

### Removed
Features that have been removed.

### Fixed
Bug fixes.

### Security
Security-related changes and fixes.

---

**Note**: This changelog will be updated with each new release. For real-time status updates, visit [status.cyberex.com.tr](https://cyberex.com.tr/status.html)
