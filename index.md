---
title: MiniSteps Privacy Policy
---

# Privacy Policy - MiniSteps Mobile Application

**Last Updated: August 31, 2026**

...

# Privacy Policy - MiniSteps Mobile Application

**Last Updated: August 31, 2026**

## Introduction

ASHLAR USA ("we," "our," or "us") develops and operates MiniSteps ("MiniSteps" or the "App").

MiniSteps is a family routine, task, reward, and calendar application designed to help parents and children organize daily activities, manage routines, and track progress.

MiniSteps is designed so that a parent or adult account holder creates and manages the family account and child profiles. Children do not create traditional MiniSteps accounts or provide personal contact information.

This Privacy Policy explains what information MiniSteps collects, how that information is used and protected, the third-party services used by the App, and the choices available to parents and users.

This Privacy Policy applies to the MiniSteps mobile application available through the Apple App Store and, if released in the future, the Google Play Store.


## Information We Collect

### Information Provided by Parents or Adult Account Holders

Parents or adult account holders may provide or create the following information:

- **Account Information**: Email address and authentication information used to sign in to MiniSteps
- **Name Information**: Name information provided through Sign in with Apple or Google Sign-In, when made available by the authentication provider
- **Child Profile Information**: A child's first name, nickname, or other name entered by the parent
- **Routine and Task Information**: Daily routines, chores, activities, reminders, schedules, and tasks created for a child
- **Calendar Information**: Calendar events imported or selected by a parent from an authorized Apple or Google calendar
- **Progress Information**: Task-completion status and daily completion history
- **Reward Information**: Coins, medals, and other progress or reward information associated with task completion
- **Household Information**: Information necessary to associate authorized parents, child profiles, and paired child devices with the same MiniSteps household
- **Support Information**: Information provided when contacting MiniSteps for support or privacy-related requests

We encourage parents to use a child's first name or nickname and not enter unnecessary sensitive personal information into MiniSteps.


## Information Associated With Children

Children do not create traditional MiniSteps accounts and are not asked to provide:

- Email addresses
- Phone numbers
- Home addresses
- Precise location
- Photos
- Videos
- Voice recordings
- Social media accounts
- Payment information
- External calendar credentials

Parents create and manage the information contained in a child's profile.

A child may use a paired MiniSteps device to:

- View routines and assigned tasks
- Mark tasks or routines as completed
- View progress
- Earn and view MiniSteps coins and medals
- View calendar or routine information assigned to that child

When a child marks a task as completed, MiniSteps stores that completion status and related reward progress in the family's MiniSteps account.


### Child Device Authentication and Pairing

MiniSteps uses Firebase Anonymous Authentication on paired child devices.

This allows the App to assign a unique Firebase authentication identifier to a child device without requiring the child to provide a name, email address, password, or other contact information.

The anonymous authentication identifier is used for purposes such as:

- Identifying an authorized paired device
- Restricting access to the appropriate MiniSteps household and child profile
- Enforcing Firebase security rules
- Preventing unauthorized access to another family's data

MiniSteps may also store technical pairing information, including:

- Anonymous Firebase user/device identifier
- Associated household identifier
- Associated child-profile identifier
- Pairing status
- Date and time of pairing
- Pairing-related security information

Temporary pairing codes may also be used to connect a child device or another authorized adult to a household.

These identifiers and pairing data are used to provide and secure MiniSteps functionality and are not used for advertising or cross-app tracking.


## Information Collected Automatically

MiniSteps and its infrastructure providers may process limited technical information necessary to authenticate users, secure the App, prevent abuse, and provide reliable service.

This may include:

- App version
- Device type
- Operating system information
- IP address
- Firebase authentication identifiers
- Firebase installation or service identifiers
- Authentication tokens
- Security and device-attestation information
- Firebase App Check information
- Apple App Attest information
- Network and technical information necessary to communicate with Firebase services
- Technical timestamps associated with account, pairing, task, and synchronization activity

MiniSteps does not use this information to create advertising profiles about children or parents.


## Location Data

**MiniSteps does not collect precise or approximate geographic location data.**

MiniSteps does not use Apple's Location Services to determine a user's physical location.


## Advertising

**MiniSteps does not display behavioral or targeted advertising.**

MiniSteps does not:

- Sell personal information
- Sell children's personal information
- Use children's information for behavioral advertising
- Use personal information for cross-context behavioral advertising
- Use advertising identifiers to target advertisements
- Use Google Analytics for Firebase

MiniSteps does not use IDFA for targeted advertising or cross-app advertising tracking.


## Tracking

MiniSteps does not track users across apps or websites owned by other companies for advertising purposes.

MiniSteps does not use information collected from child profiles or child devices to build advertising profiles or to target advertisements.


## Device Permissions

MiniSteps may request device permissions necessary to provide optional functionality.

| Permission | Purpose | Required? |
|-----------|---------|-----------|
| Notifications | Send local reminders relating to MiniSteps use | Optional |
| Apple Calendar Access | Allow a parent to select and import events from calendars available through Apple EventKit | Optional |
| Google Account Authorization | Allow a parent to authenticate with Google and, when authorized, access Google Calendar information | Optional |

Users may change or revoke device permissions through iOS Settings or through the applicable account provider.


## Notifications

MiniSteps currently uses Apple's local notification system to provide reminders.

Local notifications are scheduled on the device using Apple system APIs.

MiniSteps does not currently use Firebase Cloud Messaging to send MiniSteps reminders to child devices.

Users may disable notifications at any time through their device settings.


## Parent Authentication

MiniSteps supports parent or adult account authentication using third-party identity providers.

### Sign in with Apple

Parents may choose to authenticate using Sign in with Apple.

MiniSteps may request:

- Name
- Email address
- Apple authentication credential or token

Apple may limit or relay the email address provided depending on the user's Apple privacy settings.

MiniSteps uses the resulting authentication credential to authenticate the parent through Firebase Authentication.


### Google Sign-In

Parents may choose to authenticate using Google Sign-In.

MiniSteps may receive information necessary to authenticate the parent, which may include:

- Google account identifier
- Email address
- Authentication tokens
- Information authorized through the Google authentication process

MiniSteps uses this information to authenticate the parent through Firebase Authentication.

The current version of MiniSteps may also request read-only Google Calendar authorization as part of the Google authorization process.


## Calendar Access and Imports

Calendar access is intended for parents and adult account holders.

Children are not asked to connect external calendar accounts.


### Apple Calendar

A parent may authorize MiniSteps to access calendars available through Apple's EventKit framework.

If permission is granted, MiniSteps may access information from calendars selected or available on the device, including:

- Calendar name
- Calendar identifier
- Event title
- Event start date and time
- Event end date and time
- Recurrence information
- Event identifiers necessary to manage imported events

MiniSteps uses this information to allow the parent to import selected calendar events as MiniSteps tasks or activities.

Imported calendar information may be stored in Cloud Firestore as part of the child's task or calendar information.

MiniSteps does not use Apple Calendar information for advertising.


### Google Calendar

MiniSteps may request read-only access to a parent's Google Calendar using Google's OAuth authorization system.

When authorization is granted, MiniSteps may access information necessary to display available calendars and import calendar events, including:

- Calendar identifiers
- Calendar names
- Event identifiers
- Event titles
- Start dates and times
- End dates and times
- Recurrence information

MiniSteps uses Google Calendar information only to provide calendar-related functionality requested by the parent.

Google Calendar information may be converted into MiniSteps tasks and stored in Cloud Firestore when a parent chooses to import those events.

MiniSteps does not:

- Sell Google Calendar information
- Use Google Calendar information for advertising
- Use Google Calendar information to build advertising profiles
- Permit children to connect Google Calendar accounts

MiniSteps' use and transfer of information received from Google APIs will adhere to the Google API Services User Data Policy, including applicable Limited Use requirements.

Parents may revoke MiniSteps' Google authorization through their Google Account permissions.

Revoking authorization prevents MiniSteps from obtaining new Google Calendar information. Calendar events previously imported into MiniSteps may remain in the MiniSteps account until they are removed by the parent or the associated account data is deleted.


## How We Use Information

We use information collected through MiniSteps to:

- Authenticate parents and adult account holders
- Provide secure child-device pairing
- Create and manage MiniSteps households
- Create and manage child profiles
- Allow authorized adults to share access to a household
- Create and store routines and tasks
- Display routines and tasks to paired child devices
- Store task-completion information
- Calculate and display progress
- Calculate and display coins, medals, and other rewards
- Provide calendar functionality
- Import Apple Calendar events when authorized by a parent
- Access and import Google Calendar events when authorized by a parent
- Synchronize family information between authorized devices
- Send local reminders
- Protect MiniSteps against unauthorized access and abuse
- Authenticate devices using Firebase App Check and Apple App Attest
- Maintain the reliability and security of the App
- Respond to support and privacy requests
- Diagnose and address technical problems
- Improve App functionality
- Comply with applicable legal requirements

We do not use children's information for targeted advertising, behavioral advertising, or cross-app tracking.


## Children's Privacy

MiniSteps is designed for use by families and may be used by children under the supervision of a parent or legal guardian.

A parent or adult account holder creates and manages the family's MiniSteps account.

Parents determine:

- Which child profiles exist
- The name or nickname associated with each profile
- Which routines and tasks are assigned
- Which calendar information is imported
- Which devices are paired with a child profile
- Which other adults may be connected to the household

Children are not required to create a traditional account or provide personal contact information.

The primary information generated through a child's use of MiniSteps consists of:

- Task-completion status
- Progress information
- Coins and medals earned through task completion
- Technical identifiers necessary to authenticate and secure a paired child device

MiniSteps does not knowingly request unnecessary personal information directly from children.


## Children's Online Privacy and COPPA

The Children's Online Privacy Protection Act ("COPPA") establishes requirements concerning the online collection of personal information from children under 13.

MiniSteps is designed so that parents or legal guardians establish and manage the family account and provide information associated with child profiles.

Children are not asked to provide personal contact information.

MiniSteps does, however, use limited persistent technical identifiers on paired child devices through Firebase Anonymous Authentication and Firebase security services. These identifiers are used to support MiniSteps' internal operations, including authentication, security, device pairing, and access control.

They are not used for:

- Behavioral advertising
- Targeted advertising
- Cross-app advertising tracking
- Building commercial profiles of children

Where applicable law requires parental notice, authorization, or consent for a particular collection or use of children's information, MiniSteps will provide the required notice and obtain any required authorization before enabling that collection or use.


## Parental Rights

Parents and legal guardians may have the right to:

- Review information associated with their child
- Correct or update child profile information
- Delete routines and tasks
- Delete imported calendar events
- Delete or modify child profiles
- Review task-completion and progress information
- Request deletion of information associated with their child
- Remove or disconnect paired devices
- Request deletion of the family account and associated information
- Contact us regarding how information associated with their child is used

Parents may submit privacy-related requests by contacting:

**ministeps@ashlarusa.com**


## Household and Device Pairing

MiniSteps allows authorized devices and adults to be associated with the same household.

MiniSteps may generate temporary pairing codes for this purpose.

Pairing-related records may include:

- Temporary pairing code
- Household identifier
- Child identifier, when pairing a child device
- Parent or account identifier
- Anonymous child-device Firebase identifier
- Creation time
- Expiration time
- Last pairing time

Pairing codes are intended to be temporary and are used only to establish authorized access to the appropriate MiniSteps household.

MiniSteps restricts paired child devices to information associated with the household and child profile for which the device has been authorized.


## Third-Party Services

MiniSteps uses a limited number of third-party services necessary to authenticate users, store data, secure the App, and provide optional calendar functionality.


### Google Firebase

MiniSteps uses Google Firebase.

Services currently used include:

| Firebase Service | Purpose | Information Involved |
|-----------------|---------|----------------------|
| Firebase Authentication | Authenticate parents and anonymously authenticate paired child devices | Email address, authentication credentials, account identifiers, anonymous user identifiers, IP address, and related technical information |
| Cloud Firestore | Store MiniSteps family information | Household data, child profile names or nicknames, routines, tasks, completion information, reward information, imported calendar information, pairing information, and access-control information |
| Firebase App Check | Protect Firebase resources from unauthorized applications and abuse | App-attestation information, technical identifiers, and security information |
| Firebase Infrastructure | Provide backend storage, synchronization, authentication, and security functionality | Technical information necessary to provide Firebase services |

MiniSteps does **not** use Google Analytics for Firebase.

Firebase services may process technical information necessary to authenticate users, secure requests, prevent abuse, and operate Firebase infrastructure.

MiniSteps does not use Firebase services for behavioral advertising.


### Apple Services

MiniSteps may use Apple services including:

- Sign in with Apple
- Apple EventKit for calendar access
- Apple App Attest through Firebase App Check
- Apple local notification APIs

Apple processes information associated with these services according to Apple's own privacy policies and platform rules.


### Google Services

MiniSteps may use:

- Google Sign-In
- Google OAuth
- Google Calendar API

These services are used only for parent authentication and parent-authorized calendar functionality.

Google may independently process information associated with a user's Google Account under Google's own privacy policies.


## Google API User Data

MiniSteps' use of information received from Google APIs is limited to providing functionality requested by the user.

Google Calendar information accessed by MiniSteps is used to:

- Identify calendars available to the authorized parent
- Display calendar sources
- Retrieve selected calendar events
- Convert authorized events into MiniSteps tasks or calendar items
- Maintain metadata necessary to manage imported events

MiniSteps does not use Google API data for advertising.

MiniSteps does not sell Google API data.

MiniSteps does not use Google API information to create advertising profiles.

MiniSteps does not transfer Google Calendar information to unrelated third parties except where necessary to provide MiniSteps functionality, comply with law, protect users or MiniSteps, or where the user has expressly authorized the transfer.

MiniSteps' use and transfer of information received from Google APIs adheres to the Google API Services User Data Policy, including the Limited Use requirements.


## Data Storage

MiniSteps primarily uses Google Firebase Cloud Firestore to store family and App information.

Data stored in Firestore may include:

- Parent account identifiers
- Household identifiers
- Child profile information
- Tasks and routines
- Task schedules
- Task-completion history
- Reward totals
- Coins and medals
- Imported calendar event information
- Calendar import metadata
- Device-pairing identifiers
- Pairing activity
- Authorized-adult household information

Some device-pairing information is also stored locally on the paired device to allow MiniSteps to remember which household and child profile that device is associated with.


## Data Security

We use reasonable administrative and technical safeguards designed to protect MiniSteps information.

Current security measures include:

- Firebase Authentication
- Firebase security rules and authenticated access
- Firebase Anonymous Authentication for paired child devices
- Firebase App Check
- Apple App Attest on supported production devices
- HTTPS/TLS connections provided by Firebase and API providers
- Authentication tokens
- Short-lived pairing codes
- Household- and child-specific access controls
- Restricted access to MiniSteps backend resources

No method of electronic storage or transmission is completely secure, and we cannot guarantee absolute security.


## Data Retention

We retain information only for as long as reasonably necessary to provide MiniSteps, maintain account functionality, secure the service, comply with applicable law, and resolve disputes.

In general:

| Data Type | Retention |
|-----------|-----------|
| Parent account information | While the account remains active and as reasonably necessary following deletion |
| Child profile information | Until removed by the parent or the associated household/account is deleted |
| Tasks and routines | Until removed by an authorized parent or the associated data is deleted |
| Task-completion information | Until deleted or the associated profile/account data is deleted |
| Reward information | Until deleted or the associated child profile/account data is deleted |
| Imported calendar information | Until removed by the parent or the associated account data is deleted |
| Pairing information | For as long as necessary to maintain authorized pairing and security |
| Temporary pairing codes | For a short period necessary to complete pairing or until they expire or are removed |
| Authentication identifiers | For as long as necessary to maintain account or paired-device access |
| Security and App Check information | As necessary for authentication, abuse prevention, security, and Firebase service operation |
| Support communications | As reasonably necessary to respond to and document the request |

Some information may temporarily remain in system backups, logs, or infrastructure operated by our service providers before being deleted or overwritten.

We may retain limited information longer where required by law or reasonably necessary for security, fraud prevention, dispute resolution, or enforcement of our rights.


## Account and Data Deletion

MiniSteps provides account-deletion functionality for signed-in parent accounts.

For security, the App may require the parent to have authenticated recently before an account can be deleted.

When an eligible parent account deletion is completed, MiniSteps is designed to delete the associated Firebase Authentication account and applicable Firestore records associated with that account and household.

Depending on household configuration, deletion may include information such as:

- Parent account references
- Child profiles
- Routines and tasks
- Daily progress
- Rewards
- Household information
- Pairing information
- Imported calendar information

Deletion behavior may account for situations where multiple authorized adults share access to the same household so that one adult's deletion request does not improperly delete information belonging to another authorized account where continued storage is permitted or required.

Users may also request deletion by contacting:

**ministeps@ashlarusa.com**

We will process verified requests as required by applicable law.


## Revoking Calendar Access

### Apple Calendar

Parents may revoke MiniSteps' Apple Calendar permission through iOS Settings.

After permission is revoked, MiniSteps will no longer be able to access calendar information through EventKit.

Events already imported into MiniSteps may remain as MiniSteps tasks until the parent removes them.


### Google Calendar

Parents may revoke MiniSteps' Google account or Google Calendar authorization through their Google Account settings.

After authorization is revoked, MiniSteps will no longer be able to retrieve new Google Calendar data using the revoked authorization.

Previously imported MiniSteps tasks may remain until deleted from MiniSteps.


## Apple App Store Privacy

For the iOS version of MiniSteps:

- MiniSteps does not use Google Analytics for Firebase
- MiniSteps does not display behavioral advertising
- MiniSteps does not sell personal information
- MiniSteps does not use child information for targeted advertising
- MiniSteps does not use IDFA for behavioral advertising
- Calendar access is used to provide parent-requested calendar functionality
- Firebase identifiers are used for authentication, security, synchronization, and App functionality

The App Privacy disclosures provided through App Store Connect will reflect the functionality and data practices of the version of MiniSteps submitted for review.


## Apps for Children

MiniSteps may provide functionality intended for children.

Parents are responsible for establishing and managing child profiles and pairing child devices.

MiniSteps is designed to minimize information requested directly from children and does not include third-party advertising or third-party behavioral analytics.

Any distribution of MiniSteps within Apple's Kids Category will be subject to Apple's applicable Kids Category requirements.


## California Privacy Rights

Depending on applicable California law, California residents may have rights relating to their personal information, including rights to:

- Know or access certain personal information
- Correct inaccurate information
- Request deletion
- Receive information concerning the categories and purposes of information collection

MiniSteps does not sell personal information.

MiniSteps does not share personal information for cross-context behavioral advertising.


## EEA and United Kingdom Privacy Rights

Where applicable, individuals located in the European Economic Area or United Kingdom may have rights concerning their personal information, including rights to:

- Access personal information
- Correct inaccurate information
- Request deletion
- Restrict certain processing
- Object to certain processing
- Request data portability
- Withdraw consent where processing relies upon consent

Users may also have the right to lodge a complaint with an applicable data-protection authority.


## Other Privacy Rights

Users in other jurisdictions may have additional rights under applicable privacy laws.

To exercise a privacy right, contact:

**ministeps@ashlarusa.com**

We may need to verify the identity and authority of the person making the request before responding.


## International Data Processing

MiniSteps uses Google Firebase and other service providers that may process information in countries other than the user's country of residence.

Firebase Authentication is operated through infrastructure in the United States, while services such as Cloud Firestore and Firebase App Check may use Google's global infrastructure. :contentReference[oaicite:1]{index=1}

Where required by applicable law, appropriate safeguards will be used for international processing or transfers of personal information.


## No Sale of Personal Information

ASHLAR USA does not sell personal information collected through MiniSteps.

We do not sell children's personal information.

We do not provide child-profile information to data brokers.

We do not use child-profile information for targeted or behavioral advertising.


## Changes to This Privacy Policy

We may update this Privacy Policy as MiniSteps changes.

If we make material changes, we may provide notice through one or more of the following:

- An in-app notification
- A notice displayed when MiniSteps is opened
- Email to a parent or adult account holder
- An updated Privacy Policy posted at our published Privacy Policy URL

The "Last Updated" date at the top of this Privacy Policy indicates when this policy was most recently revised.


## Contact Us

If you have questions, concerns, parental requests, account-deletion requests, or other privacy inquiries, contact:

**ASHLAR USA**

**Email:**  
ministeps@ashlarusa.com

**Mailing Address:**  
2508-A Verona Pl.  
Ellicott City, MD 21042  
United States

---

*Last updated: August 31, 2026*
