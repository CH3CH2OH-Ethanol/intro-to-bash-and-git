# Intro to Bash and Git





## Bash



### Open the terminal

#### Windows

- Open Power Shell

#### MacOS

- Open Terminal



### Try Out Commands

`~`		  Home

`.`		  Current directory

`..`		Previous directory

`ls`		List directory contents

`cd`		Change the current directory

`pwd`	      Print the current directory

`mkdir`	  Create a new folder

`rm`		Delete files or or folders 

`rmdir`	  Delete an empty folder

`touch`	  Create an empty file or update its time

`cp`		Copy files and directories

`mv`		Move or rename files

`cat`	      Display file contents

`echo`	    Print out

Now, try to delete every file in the `bash-test` folder.



### `.sh` file

You can put bash commands into a `.sh` file using `echo` command as: 

```bash
echo "ls" > run.sh
echo "touch aaaaa" >> run.sh
echo "rm aaaaa" >> run.sh
```

Now the `run.sh` file looks like this:

```bash
ls
touch aaaaa
rm aaaaa
```

To mark the file `run.sh` as executable, run:

```bash
chmod +x run.sh
```

Now you can run the executable file `run.sh` by simply:

```bash
./run.sh
```

and the system will automatically execute:

```bash
ls
touch aaaaa
rm aaaaa
```

which shows contents in current dirrectory, creates a file `aaaaa` and then remove it.

Now, try to delete every file in the `runable-sh-test` folder using a `.sh` file.



## Git