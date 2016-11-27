# freighter


<h2>Dropbox</h2>


<h3>Restore</h3>


<h4>Command Line</h4>


```sh
env BACKUP_PROVIDER_TOKEN=[BACKUP_PROVIDER_TOKEN] ./freighter restore --remotePath [REMOTE_FILE_PATH] --restoreFilePath [LOCAL_FILE_PATH] 
```


<h4>Docker</h4>

Run the following command to restore a backup from Dropbox:

```sh
docker run -u [USER] -v [LOCAL_VOLUME_MAPPING]:/tmp -e BACKUP_PROVIDER_TOKEN=[BACKUP_PROVIDER_TOKEN] \
  opinari/freighter restore --remotePath [REMOTE_FILE_PATH] --restoreFilePath /tmp/[LOCAL_FILE_PATH] 
```

<hr>
