# Change-Java-on-Ubuntu-that-cant-connect-in-server

```
nano ~/.bashrc
```

#In bashrc, write this on the last row and save

```
export JAVA_HOME=/home/<username>/<your java file>
```
```
export PATH=$JAVA_HOME/bin:$PATH
```

#Check alternative Java
```
sudo update-alternatives --config javac
```

```
source .bashrc
```

#Check your java version
```
java -version
```
