# Bulk Upload to YouTube from Google Drive using Colab Notebooks

### Features
1. Now no need to download videos from drive and then upload to youtube.
2. Super fast upload speed directly using Google's network.
3. Does not use your local internet data.
4. **Bulk upload capability**: You can search for a folder by name (e.g., "Allen Videos", "Ecology") and it will recursively traverse all subfolders to find and upload all video files.
5. Interactive UI to input your target folder, category, privacy status, and API credentials.

### Usage:

Upload the `Bulk_YouTube_Uploader.ipynb` file to your Google Drive or run it in Google Colab directly.

1. Create OAuth credentials for your Google Cloud Project with the YouTube Data API v3 enabled. You need an "OAuth client ID (Desktop app)".
2. Open the notebook in Colab.
3. In the second cell's form fields, paste your `client_id` and `client_secret`, along with your desired folder name to search for (e.g., "Allen Videos").
4. Run the cells. It will mount your Drive, prompt you to authorize the app via a URL (giving you a code to paste back into Colab), search for the folder, and upload all videos it finds.

---
If you face any problem, please raise an issue on GitHub.
