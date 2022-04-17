## EXTRACTING
If you have received a file that contains a  message  that
       has  been  embedded with steghide, use the **extract** command
       to extract it. The following arguments can  be  used  with
       this command.


**-sf,** **--stegofile** _filename_
              Specify  the  stego  file  (the  file that contains
              embedded data). If  this  argument  is  omitted  or
              _filename_ is **-**, steghide will read a stego file from
              standard input.


**-xf,** **--extractfile** _filename_
              Create a file with the name _filename_ and write  the
              data that is embedded in the stego file to it. This
              option overrides the filename that is embedded  int
              the  stego  file.  If this argument is omitted, the
              embedded data will be saved to the  current  direc­
              tory under its original name.

## GETTING INFORMATION ABOUT A COVER/STEGO FILE

You can use the **info** command to get some information about
       a cover or stego file  (for  example  the  capacity).  You
       might want to use this if you have received a file and you
       are not sure if it contains an embedded message or if  you

## COMMON OPTIONS

The following options can be used with all commands (where
       it makes sense).


**-p,** **--passphrase**
              Use  the  string  following  this  argument  as the
              passphrase. If your passphrase contains whitespace,
              you  have  to enclose it in quotes, for example: **-p**
              **"a** **very** **long** **passphrase"**.


**-v,** **--verbose**
              Display detailed information about  the  status  of
              the embedding or extracting process.


**-q,** **--quiet**
              Supress information messages.


**-f,** **--force**
              Always overwrite existing files.


---
```
         $ steghide embed -cf picture.jpg -ef secret.txt
         Enter passphrase:
         Re-Enter passphrase:
         embedding "secret.txt" in "picture.jpg"... done
```
This  command  will embed the file secret.txt in the coverfile picture.jpg.
and you want to  get  some  information  about  it  before extracting it, use the info command:

```
		$ steghide info received_file.wav
        "received_file.wav":
           format: wave audio, PCM encoding
           capacity: 3.5 KB
         Try to get information about embedded data ? (y/n) y
         Enter passphrase:
           embedded file "secret.txt":
             size: 1.6 KB
             encrypted: rijndael-128, cbc
             compressed: yes

```