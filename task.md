# Tasks: Google Sign-In Integration

- [x] Implement Backend Google Auth API
  - [x] Add config route `GET /api/config` in `server.js`
  - [x] Add google login/signup route `POST /api/auth/google` in `server.js`
- [x] Implement Frontend Google Auth Integration
  - [x] Dynamically load GSI library script in `public/js/auth.js`
  - [x] Fetch server config in `public/js/auth.js`
  - [x] Update auth modal HTML to include Google Sign-In button container in `public/js/auth.js`
  - [x] Implement Google credential callback handler in `public/js/auth.js`
  - [x] Render the Google Sign-In button when GSI loads and config is present in `public/js/auth.js`
- [x] Local Verification
  - [x] Verify frontend renders button when Google Client ID is configured
  - [x] Verify backend verifies Google JWT and creates/logs in user successfully
- [x] Profile Page Updates (`profile.html` & `profile.js`)
  - [x] Show subscription tier badges and trial progress/expiry dates
- [x] Lobby Modal Updates (`lobby.html` & `lobby.js`)
  - [x] Block uploads and private room toggles for trial-expired free users
- [x] Commit and Push changes to GitHub
