<img width="1557" height="483" alt="image" src="https://github.com/user-attachments/assets/d397499a-8338-46da-89ca-1b08c2b4ff80" />

# Linux Directory and File Creation


## Creating Files
````
touch example.txt
````
- touch example.txt → Creates empty file example.txt 


- cat > file2.txt → Creates a new file file2.txt and waits for input. Press Ctrl+D to save.
````
cat > file2.txt
````
**Note:** 
- '>' will override file content   and
- '>>' will append (both old data and new will stay in file)

- echo "Hello World" > index.html → Creates a file index.html and writes Hello World into it.
````
echo "Hello World" > index.html
````

**Displaying File Content**
````
cat index.html
````
---

###  Creating Directories
```sh
mkdir pune
```


### Remove files/Dir

````
rm -rvf pune
````
- r recursive
- v verbose
- f forcefully

### Copy file to another file and dir
````
cp file1.txt  file2.txt
````

````
mv demo.txt Documents/
````

### Moving a File to Another Directory
```sh
mv index.html pune/
```


###  Renaming a File
```sh
mv samantha.txt samartha.txt
```
- Renames `samantha.txt` to `samartha.txt` 





