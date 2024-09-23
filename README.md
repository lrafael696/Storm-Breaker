<h1 align="center">
  <br>
  <a href="https://github.com/ultrasecurity/Storm-Breaker"><img src=".imgs/1demo.png" alt="StormBreaker"></a>

</h1>

<h4 align="center">A Tool With Attractive Capabilities. </h4>

<p align="center">

  <a href="http://python.org">
    <img src="https://img.shields.io/badge/python-v3-blue">
  </a>
  <a href="https://php.net">
    <img src="https://img.shields.io/badge/php-7.4.4-green"
         alt="php">
  </a>

  <a href="https://en.wikipedia.org/wiki/Linux">
    <img src="https://img.shields.io/badge/Platform-Linux-red">
  </a>

</p>

![demo](.imgs/screen1.jpeg)

### Features:

- Obtain Device Information Without Any Permission !
- Access Location [SMARTPHONES]
- Access Webcam
- Access Microphone

<br>

### Update Log:

- Fepository and original post: https://github.com/ultrasecurity/Storm-Breaker/
- Second ( latest) Update on october 11th , 2024 .
- The overall structure of the tool is programmed from the beginning and is available as a web panel (in previous versions, the tool was available in the command line).
- Previous version's bugs fixed !
- Auto-download Ngrok Added !
- The templates have been optimized !
- Logs can be downloaded (NEW) !
- Clear log Added !
- It can be uploaded on a personal host (you won't have the Ngork problems anymore)
- You can start and stop the listener anytime ! (At will)
- Beautified user interface (NEW) !

> We have deleted Ngrok in the new version of Storm breaker and entrusted the user with running and sharing the localhost . So please note that Storm breaker runs a localhost for you and you have to start the Ngrok on your intended port yourself .
> <br>

#### Attention! :

> This version can be run on both local host and your personal domain and host . However , you can use it for both situations. If your country has suspended the Ngrok service, or your country's banned Ngrok, or your victim can't open the Ngrok link (for the reasons such as : He sees such a link as suspicious, Or if this service is suspended in his country) We suggest using the tool on your personal host and domain .
> <br>

## Default username and password:

- `username` : `admin`
- `password` : `admin`
- You can edit the config.php file to change the username and password .
  <br>

### Dependencies

**`Storm Breaker`** requires following programs to run properly -

- `php`
- `python3`
- `git`
- `Ngrok`

<!-- ![demo](.imgs/Work3.gif) -->
<br>

### Platforms Tested

- Kali Linux 2024.2
- macOS Big Sur / M1
- Termux (android)
- Personal host (direct admin and cPanel)
  <br>

### Installation On Kali Linux 2024.2

```bash
git clone https://github.com/lrafael696/Storm-Breaker
cd Storm-Breaker
sudo bash install.sh
sudo python3 st.py
```

<br>

**`Possible installation errors** 

If you get the following error message: error: 
```bash
 error: externally-managed-environment
```
Run the following command:
```bash
  sudo rm /usr/lib/python3.*/EXTERNALLY-MANAGED
```

**`how to run personal host 👇`**

> Zip the contents of the storm-web folder completely and upload it to the public_html path .

> Note that the tool should not be opened in a path like this > yourdomain.com/st-web
> Instead , it should be opened purely in the public_html path (i.e. : don't just zip the storm-web folder itself, but manually zip its contents (the index.php file and other belongings should be in the public_html path)

#### Attention!:

> Note that to use this tool on your Localhost , You also need SSL . Because many of the tool's capabilities require SSL .

#### Attention!:

> To run ngrok on termux you need to enable your personal hotspot and cellular network.

### Create account on NGROK

```bash
https://dashboard.ngrok.com/login
```
![image](https://github.com/user-attachments/assets/74f0c346-1142-4b07-af40-b7a9ae718a00)

### Install NGROK

```bash
https://ngrok.com/download
```
![image](https://github.com/user-attachments/assets/17218842-e691-403e-b6e4-959b5eed2785)

or

### Install ngrok via Apt

```bash
https://dashboard.ngrok.com/get-started/setup/linux
```

```bash
curl -sSL https://ngrok-agent.s3.amazonaws.com/ngrok.asc | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null && echo "deb https://ngrok-agent.s3.amazonaws.com buster main" | sudo tee /etc/apt/sources.list.d/ngrok.list && sudo apt update && sudo apt install ngrok
```
![image](https://github.com/user-attachments/assets/1352243a-43ab-4053-bc70-15abab37a19f)


### Add authtoken and connect your count

```bash
ngrok config add-authtoken <token>
```
![image](https://github.com/user-attachments/assets/3904bf99-4a2c-4a5e-9cae-0b566f4d665b)


### Start a tunnel NGROK

```bash
ngrok http 2525
```
![image](https://github.com/user-attachments/assets/2626ed88-da7d-46d3-aef3-decd34dd29dc)


### Start a tunnel NGROK

```bash
sudo python3 st.py
```
![image](https://github.com/user-attachments/assets/f43f96c1-fbca-49f7-9cd5-3142185b0c26)

![image](https://github.com/user-attachments/assets/83eb306e-5cd8-494f-870a-f11c52077a9b)


Finally, you can use other tools to hide the original URL, this can be done with maskphish

## maskphish

![image](https://github.com/user-attachments/assets/a7e67d68-8788-42b7-a0fa-842763aa51a9)

URL: https://github.com/jaykali/maskphish 


</p>
