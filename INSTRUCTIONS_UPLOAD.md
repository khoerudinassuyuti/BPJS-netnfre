# Quick steps — Upload to GitHub and send link via email

1. Extract this archive.
2. Open the folder in Android Studio:
   - File → Open → select the folder.
   - Let Android Studio create missing Gradle files when prompted (or create a new Project and copy these sources into it).
3. Initialize Git and create remote repo:
   - git init
   - git add .
   - git commit -m "Initial commit - BPJS-NetInfra skeleton"
   - Create a new repository on GitHub (https://github.com/new) named `BPJS-NetInfra`
   - git remote add origin https://github.com/<your-username>/BPJS-NetInfra.git
   - git branch -M main
   - git push -u origin main
4. After pushing, copy the GitHub repo URL and paste it into the EMAIL_DRAFT.txt in place of &lt;PASTE_YOUR_GITHUB_LINK_HERE&gt;.
5. Send the email to the recruitment address (or to your own email to forward). Your email is: khoerudinassuyuti@gmail.com

Troubleshooting:
- If Android Studio asks to create Gradle settings, accept and sync.
- If you prefer I generate the APK and full Gradle project, reply "Build APK" and I'll prepare the APK file for download.
