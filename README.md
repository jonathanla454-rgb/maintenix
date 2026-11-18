# Maintenix — Android project (v0.2)

Modernized bilingual maintenance management prototype, packaged as an Android Studio WebView application. Includes light/dark theme, work orders, preventive tasks, room history, local JSON export, and demo role controls. All records remain on the device in WebView localStorage.

## Important limitations
- **This is source code, not an APK.** An Android SDK, Gradle and Android build tools are required to compile it. Compilation has not been verified in this environment.
- **No actual user authentication, server-side permissions, or multiuser sync.** The role selector is a UI simulation, not a security boundary. Do not store sensitive company information or share it as a production application.
- No brand affiliations.

## Build
Open this directory in Android Studio, sync Gradle, then Build > Build APK(s). If a Gradle wrapper is needed, generate one using the installed Gradle version compatible with Android Gradle Plugin 8.7.3. The app targets SDK 35, minimum SDK 26.

## Next production milestones
Supabase Auth with email verification; row-level security with tenant isolation; invitations/approval; audit logs; secure photo storage; integration tests; release signing.
