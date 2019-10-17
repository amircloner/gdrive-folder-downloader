# google-drive-folder-downloader

Download Google Drive folder without google zipping!

## Getting Started

You need to enable the Drive `API` to use the script.
The enabling instructions can be found on [Python Quickstart](https://developers.google.com/drive/api/v3/quickstart/python).<br/>
The `credentials.json` file will be needed in the working directory.

## Requirements

```
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
```
```
pip install google-auth-oauthlib
```
```
pip install google-api-python-client
```

### Python 3.6+

```
$ python3 download.py folder_name_on_google_drive [google drive path]
```

## Example

Your folder name is `Example` and its shareable url (to get shareable link left click on folder and select `get shareable link`) is https://drive.google.com/drive/u/0/folders/12KurDmdB5_Jtrk6Y3zplBafVQZzq-G7K

#### Windows

```
$ python download.py Example `12KurDmdB5_Jtrk6Y3zplBafVQZzq-G7K`
```

#### Linux
```
$ python3 download.py Example `12KurDmdB5_Jtrk6Y3zplBafVQZzq-G7K`
```
