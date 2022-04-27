# issue 3681
### Prerequisite
- Add `google-services.json`
### Summary
- Strict mode issues on `firebase-bom:29.3.1` specifically on `messaging` and `firestore`
### Steps to reproduce
1. After adding `google-services.json`, 
2. Open app
3. See logs


P.S. There are times when the StrictMode policy violation does not appear, best action to do is delete and make a fresh install every run.
