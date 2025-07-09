Live Google Sheets Leaderboard for OBS

1. In your Google Sheet:
   - Click File > Share > Publish to the Web
   - Choose the sheet or whole document
   - Copy the published URL

2. Open leaderboard.html in a text editor
   - Replace YOUR_SPREADSHEET_ID in the script with your actual ID

3. Rename your leaderboard background image to:
   leaderboard-bg.png
   and put it in the same folder

4. In OBS:
   - Add a Browser Source
   - Point it to the local path of leaderboard.html
   - Set custom width/height to match your layout

The leaderboard will refresh every 10 seconds automatically.
