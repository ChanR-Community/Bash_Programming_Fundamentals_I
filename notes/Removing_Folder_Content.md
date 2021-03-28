### Removing Content from Folders

#### Method 1: rmdir

1. Move the contents from one folder to another.

```bash
# Make sure you're in the folder with the contents
mv * ..
```

2. Navigate one directory backwards.
```bash
cd ..
```
3. Remove the empty folder
```bash
rmdir folder_name
```

#### Method 2: Use the Garbage Utility

1. For Windows users:
```bash
RECYCLE folder_name
```

2. For Mac users:
```bash
trash folder_name
```

     
