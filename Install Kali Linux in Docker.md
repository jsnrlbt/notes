Install and Run Kali Linux in Docker 

Once Docker is running, you can pull the official Kali Linux image from [Docker Hub](https://hub.docker.com/r/kalilinux/kali-rolling) and run it: 

1. **Pull the official Kali Linux image**:
    
    bash
    
    ```
    docker pull kalilinux/kali-rolling
    ```
    
    This downloads the latest rolling release image.
2. **Run an interactive container**:
    
    bash
    
    ```
    docker run -it kalilinux/kali-rolling /bin/bash
    ```
    
    - `-it` ensures an interactive terminal session.
    - `/bin/bash` runs the bash shell inside the container, dropping you into a Kali Linux prompt. 

Using Kali Linux in the Container

By default, the official images are minimal and do not include the full suite of tools. You can install specific tools or metapackages using `apt` inside the running container: 

- **Update within the container**:
    
    bash
    
    ```
    apt update
    ```
    
- **Install common tools**:
    - `kali-linux-headless`: Installs core command-line tools.
        
        bash
        
        ```
        apt install -y kali-linux-headless
        ```