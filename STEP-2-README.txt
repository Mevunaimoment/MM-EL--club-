STEP 2: HIDE THE TOP ADDRESS BAR ON ANDROID (DIGITAL ASSET LINKS)

1. Open your own 'assetlinks' file (from your PWABuilder 'MMCC RA 109 - Google Play package' folder) in Notepad and copy all the text inside.
2. Replace the placeholder inside '.well-known/assetlinks.json' with that copied text, OR follow the direct GitHub steps below:
   - Go to your GitHub repository -> click 'Add file' -> 'Create new file'.
   - Type '.well-known/assetlinks.json' as the filename.
   - Paste your copied assetlinks text and click 'Commit changes'.
3. Wait ~20 seconds for Vercel to deploy, then close and reopen 'MMCC RA 109' on your Android phone.

IMPORTANT: Keep 'signing.keystore' and 'signing-key-info' safe on your PC for future Google Play Store updates.
