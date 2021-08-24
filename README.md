## spring-webshell
> Spring Boot based webfrontend for local shell access ✨  
> Dependencies: Java 11 JDK, Maven 3.5  
</br>

### Build Service Config
#### Build java archive file (IntelliJ)
```sh
Maven > Lifecycle > package
```
#### Java archive file path
```sh
$ /spring-webshell/target/webshell-0.0.2-SNAPSHOT.jar
```
#### jar File Execution (Linux)
```sh
$ java -jar ./target/webshell-0.0.2-SNAPSHOT.jar
```
</br>

### Connect Shell throuh Browser
- URL: localhost:8001/login
- ID: korkeep, Password: korkeep
> ![image](https://user-images.githubusercontent.com/20378368/130558876-1be604a0-b352-47e3-ae1e-f0c258a66437.png)
</br>

### Input shell command
```sh
$ pwd
```
> ![image](https://user-images.githubusercontent.com/20378368/130559592-ada69685-12a0-4642-bebe-6cfdadf210f2.png)