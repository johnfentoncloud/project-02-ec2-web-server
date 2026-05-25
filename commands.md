# Project 02 - EC2 Web Server Commands

## Connect to Instance

```bash
ssh -i "project02-key.pem" ec2-user@PUBLIC-IP
```

---

## Navigate to Website Directory

```bash
cd /var/www/html
ls
```

---

## Install Apache

```bash
sudo yum update -y
sudo yum install httpd -y
```

---

## Start Apache

```bash
sudo systemctl start httpd
sudo systemctl enable httpd
sudo systemctl status httpd
```

---

## Edit Website File

```bash
sudo nano index.html
```

---

## View Website Code

```bash
cat index.html
```

---

## Restart Apache

```bash
sudo systemctl restart httpd
```