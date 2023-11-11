## **A web server**

> Preferably Nginx or Apache

### **Nginx**

=== "Ubuntu/Debian"

    ```bash
    sudo apt update
    sudo apt install nginx
    ```

=== "CentOS/RHEL"

    ```bash
    sudo yum install nginx
    sudo systemctl start nginx
    sudo systemctl enable nginx
    ```

### **Apache**

=== "Ubuntu/Debian"

    ```bash
    sudo apt update
    sudo apt install apache2
    ```

=== "CentOS/RHEL"

    ```bash
    sudo yum install httpd
    sudo systemctl start httpd
    sudo systemctl enable httpd
    ```

PHP

MySQL or any equivalent
