````markdown
```markdown
# Titans X - Minimal Flutter Scaffold

Overview:
- Mobile app for tournaments with user & admin panels.
- Backend: Firebase Auth + Firestore + Storage
- Local caching: shared_preferences

How to run:
1. Create Firebase project and enable Authentication (Email/Password), Firestore, Storage.
2. Add Android & iOS apps and place google-services config files.
3. Update Firebase initialization options in lib/main.dart if needed.
4. flutter pub get
5. flutter run

Admin credentials (for prototype only):
- Email: alishayal1290@gmail.com
- Password: ali1290

Notes:
- This scaffold stores admin credential check on sign-in (email match + password). For production move admin guard to Firebase custom claims.
- Implement secure handling for host credentials (tournament passwords) — encrypt or send via secure channel.

Next steps:
- Implement full UI polish and animations.
- Implement admin web panel (React) or admin-only screens.
- Automated tests and deployment (play store/app store).
