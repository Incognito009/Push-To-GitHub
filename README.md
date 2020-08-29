<h1 align="center">Push To GitHub ❤️</h1> 

<hr>

> ## Make 'git push remote branch' easier then ever

### How to run this batch file from the terminal

- Locate the batch file then run:

```
<file_name> "<your commit message here> "
```

Ex: `push "Initial Commit"`

- But in this case we need to copy paste the batch file inside each local repo. To avoid this, we need to save this batch file in a separate folder and set the path variable. 

### Setting Up PATH Variable:

**Windows 10:**

- In Search, search for Environment Variables.
- Click `Edit the system environment Variables` and then click `Environment Variables`.
- In the section `System Variables`, find the `PATH` environment variable and select it. Then click Edit. If the PATH environment variable does not exist, click New and set `Variable Name` as `PATH` and `Variable Value` as `Path to the Batch File`.
- In the Edit System Variable window, click New and specify the path to the batch file and click OK and close all remaining windows by clicking OK.
- Now open your terminal anywhere and enter the filename and commit message and hit ENTER it will run the commands no matter where the batch file is.