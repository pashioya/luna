# Luna

**A social period tracking app** that enables users to share their cycle information with close friends and family. Luna prioritizes user privacy while offering seamless integration with Apple HealthKit for comprehensive cycle tracking and sharing.

## Features

### Core Functionality
- Integration with **Apple HealthKit** for menstrual cycle data retrieval
- Secure sharing of cycle information with trusted connections
- Easy-to-use calendar view of cycle phases
- Private invitation system for establishing connections
- End-to-end data encryption for shared information

### Privacy & Security
- **Local data storage** options to safeguard user information
- Minimal collection of personal data
- No third-party advertising involvement
- User-friendly data deletion process
- Granular sharing permissions for user control

## Technical Specifications
- **Languages & Frameworks**: Swift, SwiftUI
- **Integrations**: HealthKit, CloudKit
- **Security Features**: End-to-end encryption
- **iOS Compatibility**: iOS 15.0 and above

## Key Components
- **HealthKitManager**: Manages all interactions with HealthKit.
- **CloudKitManager**: Handles data synchronization and sharing between users.
- **EncryptionService**: Responsible for encrypting and decrypting data.
- **ConnectionManager**: Oversees management of user connections and sharing permissions.

## Privacy Policy
- Only essential cycle data is collected for app functionality.
- All data is stored locally and secured with encryption.
- Users have full control over data sharing preferences.
- No third-party entities have access to personal data.
- A clear and straightforward data deletion process is in place.

## Acknowledgments
- [Apple HealthKit Documentation](https://developer.apple.com/documentation/healthkit)
- SwiftUI Framework
- CloudKit Framework

## Roadmap

### Version 1.0
- Basic HealthKit integration
- Initial cycle viewing functionality
- Core connection system implementation

### Version 1.1
- Enhanced sharing features
- UI/UX improvements
- Additional privacy controls for user data

### Version 2.0
- Support for widgets
- Companion app for WatchOS
- Advanced cycle analytics for deeper insights
