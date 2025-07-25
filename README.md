# Google Drive API Wrapper

A simple Python wrapper for Google Drive API.

## Setup

1. Create a Google Cloud project and enable the Drive API.
2. Download your `credentials.json` and place it in this folder.
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run example usage in `drive_wrapper.py`.

Note:

This uses google-auth and google-api-python-client libraries.
You’ll need to download credentials.json from your Google Cloud Console.
For uploading files, add from googleapiclient.http import MediaFileUpload at the top if you use upload_file.
