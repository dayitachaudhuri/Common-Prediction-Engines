In order to use the [Kaggle’s public API](https://github.com/Kaggle/kaggle-api#api-credentials), you must first authenticate using an API token. Go to the 'Account' tab of your [user profile](https://www.kaggle.com/settings/account) and select 'Create New Token'. This will trigger the download of kaggle.json, a file containing your API credentials.

If you are using the Kaggle CLI tool, the tool will look for this token at ~/.kaggle/kaggle.json on Linux, OSX, and other UNIX-based operating systems, and at C:\Users\<Windows-username>\.kaggle\kaggle.json on Windows. If the token is not there, an error will be raised. Hence, once you’ve downloaded the token, you should move it from your Downloads folder to this folder.

If you are using the Kaggle API directly, where you keep the token doesn’t matter, so long as you are able to provide your credentials at runtime.
