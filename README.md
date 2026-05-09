# Bulk Upload to YouTube from Google Drive using Colab Notebooks

### Features
1. Now no need to download videos from drive and then upload to youtube.
2. Super fast upload speed directly using Google's network.
3. Does not use your local internet data.
4. **Bulk upload capability**: You can search for a folder by name (e.g., "Allen Videos", "Ecology") and it will recursively traverse all subfolders to find and upload all video files.
5. Interactive UI to input target folder, category, and privacy status.

### Usage:

Upload the `Bulk_YouTube_Uploader.ipynb` file to your Google Drive or run it in Google Colab directly.

1. Create OAuth credentials for your Google Cloud Project with the YouTube Data API v3 enabled.
2. Download your `client_secrets.json` and upload it to the notebook environment.
3. Follow the instructions inside the notebook to mount your drive, authenticate, and bulk upload your files.

---
If you face any problem, please raise an issue on GitHub.
