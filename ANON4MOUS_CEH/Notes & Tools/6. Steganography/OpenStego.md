## Possible options for `extract` command

Option

Description

`-sf`, `--stegofile <filename>`

Stego file containing the embedded message

`-xf`, `--extractfile <filename>`

Optional filename for the extracted data. Use this to override the filename embedded in the stego file

`-xd`, `--extractdir <dir>`

Directory where the message file will be extracted. If this option is not provided, then the file is extracted to current directory

`-p`, `--password <password>`

Password to be used for decryption. If this is not provided then prompt will be displayed for entry (if the message is encrypted)