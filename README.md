# CamFish
Grab cam shots from target's phone front camera or PC webcam just sending a link.
![cheese](https://1.bp.blogspot.com/-YNCXam1vNOg/Xp7nZc1qkrI/AAAAAAAALGI/isv-n0Fc_JUyJ2h-J-sQg5ZapJo029hOQCLcBGAsYHQ/s1600/camfish.png)

![cheese](https://1.bp.blogspot.com/-xixXtmgafRY/Xp8AcP1s2YI/AAAAAAAALGU/Cqd-Hht2ZTkqj7ITb_JaRatltnm_4UcpQCLcBGAsYHQ/s1600/fishingpage.png)

# What is CamFish?
<p>CamFish is techniques to take cam shots of target's phone fornt camera or PC webcam. CamFish Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Perrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/firidon/CamFish
cd CamFish
bash camfish.sh
```

<p>CamFish is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.</p>
<p>CamFish is inspired by https://github.com/thelinuxchoice/ and https://github.com/techchipnet Big thanks to @thelinuxchoice and @techchipnet</p>
