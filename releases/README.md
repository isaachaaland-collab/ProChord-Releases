# Release artifacts

Approved update archives will be stored by version, for example:

```
releases/
  0.8.0/
    ProChord-0.8.0.zip
    ProChord-Receiver-0.8.0.zip
    SHA256SUMS.txt
    RELEASE_NOTES.md
```

The update manifest/appcast should not reference an artifact until signing, checksum verification, and church-Mac testing are complete.
