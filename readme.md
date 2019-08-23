# This Repo contains productivity hacks and stuff.

### SQLite3 

* To import a csv as Table

```
sqlite> .mode csv /*table name*/
sqlite> .import /*file name*/ /*table name*/
```

### Unix/Linux -

* To get head of any file

```
$ head -n /*NUMBEROFLINES*/ filename
```

* Add a string after each line in file

```
$ sed -e 's/$/string after each line/' -i filename
```
> If this doesn't work, create a new updated file.
```
$ sed -e 's/$/string after each line/' -i filename >> new_filename
```