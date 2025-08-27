Step 1: Install venv (if not already)
sudo apt update
sudo apt install python3-venv -y

Step 2: Create a Virtual Environment
python3 -m venv myenv

Step 3: Activate the Virtual Environment
source myenv/bin/activate

Now your prompt will look like:
(myenv) root@DESKTOP-T6I6DAE:~#

Step 4: Install Flask inside venv
pip install flask

Step 5: Run Your Flask Server
python server.py

It will show:
* Running on http://127.0.0.1:5000

root@DESKTOP-T6I6DAE:~# sudo apt update
sudo apt install python3-venv -y
Get:1 http://security.ubuntu.com/ubuntu noble-security InRelease [126 kB]                                            
Hit:2 http://archive.ubuntu.com/ubuntu noble InRelease 
Get:3 http://archive.ubuntu.com/ubuntu noble-updates InRelease [126 kB]
Get:4 http://archive.ubuntu.com/ubuntu noble-backports InRelease [126 kB]
Get:5 http://security.ubuntu.com/ubuntu noble-security/main amd64 Packages [1083 kB]
Get:6 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 Packages [1370 kB]
Get:7 http://security.ubuntu.com/ubuntu noble-security/main Translation-en [187 kB]
Get:8 http://security.ubuntu.com/ubuntu noble-security/main amd64 Components [21.6 kB]
Get:9 http://security.ubuntu.com/ubuntu noble-security/universe amd64 Packages [881 kB]
Get:10 http://security.ubuntu.com/ubuntu noble-security/universe Translation-en [195 kB]                                                   
Get:11 http://security.ubuntu.com/ubuntu noble-security/universe amd64 Components [52.2 kB]                                                
Get:12 http://security.ubuntu.com/ubuntu noble-security/restricted amd64 Packages [1631 kB]                                                
Get:13 http://archive.ubuntu.com/ubuntu noble-updates/main Translation-en [271 kB]                                                         
Get:14 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 Components [175 kB]                                                       
Get:15 http://archive.ubuntu.com/ubuntu noble-updates/universe amd64 Packages [1126 kB]                                                    
Get:16 http://security.ubuntu.com/ubuntu noble-security/restricted Translation-en [361 kB]                                                 
Get:17 http://archive.ubuntu.com/ubuntu noble-updates/universe Translation-en [288 kB]                                                     
Get:18 http://security.ubuntu.com/ubuntu noble-security/restricted amd64 Components [212 B]                                                
Get:19 http://security.ubuntu.com/ubuntu noble-security/multiverse amd64 Components [208 B]                                                
Get:20 http://archive.ubuntu.com/ubuntu noble-updates/universe amd64 Components [378 kB]                                                   
Get:21 http://archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Packages [1773 kB]                                                  
Get:22 http://archive.ubuntu.com/ubuntu noble-updates/restricted Translation-en [395 kB]                                                   
Get:23 http://archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Components [212 B]                                                  
Get:24 http://archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Components [940 B]                                                  
Get:25 http://archive.ubuntu.com/ubuntu noble-backports/main amd64 Components [7084 B]                                                     
Get:26 http://archive.ubuntu.com/ubuntu noble-backports/universe amd64 Packages [30.2 kB]                                                  
Get:27 http://archive.ubuntu.com/ubuntu noble-backports/universe Translation-en [17.4 kB]                                                  
Get:28 http://archive.ubuntu.com/ubuntu noble-backports/universe amd64 Components [19.2 kB]                                                
Get:29 http://archive.ubuntu.com/ubuntu noble-backports/restricted amd64 Components [216 B]                                                
Get:30 http://archive.ubuntu.com/ubuntu noble-backports/multiverse amd64 Components [212 B]                                                
Fetched 10.6 MB in 16s (679 kB/s)                                                                                                          
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
179 packages can be upgraded. Run 'apt list --upgradable' to see them.
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
python3-venv is already the newest version (3.12.3-0ubuntu2).
The following package was automatically installed and is no longer required:
  libllvm17t64
Use 'sudo apt autoremove' to remove it.
0 upgraded, 0 newly installed, 0 to remove and 179 not upgraded.
root@DESKTOP-T6I6DAE:~# python3 -m venv myenv
root@DESKTOP-T6I6DAE:~# ls
Embeded_System  Study_Room  myenv  tts-env
root@DESKTOP-T6I6DAE:~# source myenv/bin/activate
(myenv) root@DESKTOP-T6I6DAE:~# pip install flask
Collecting flask
  Downloading flask-3.1.2-py3-none-any.whl.metadata (3.2 kB)
Collecting blinker>=1.9.0 (from flask)
  Downloading blinker-1.9.0-py3-none-any.whl.metadata (1.6 kB)
Collecting click>=8.1.3 (from flask)
  Downloading click-8.2.1-py3-none-any.whl.metadata (2.5 kB)
Collecting itsdangerous>=2.2.0 (from flask)
  Downloading itsdangerous-2.2.0-py3-none-any.whl.metadata (1.9 kB)
Collecting jinja2>=3.1.2 (from flask)
  Downloading jinja2-3.1.6-py3-none-any.whl.metadata (2.9 kB)
Collecting markupsafe>=2.1.1 (from flask)
  Downloading MarkupSafe-3.0.2-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (4.0 kB)
Collecting werkzeug>=3.1.0 (from flask)
  Downloading werkzeug-3.1.3-py3-none-any.whl.metadata (3.7 kB)
Downloading flask-3.1.2-py3-none-any.whl (103 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 103.3/103.3 kB 892.3 kB/s eta 0:00:00
Downloading blinker-1.9.0-py3-none-any.whl (8.5 kB)
Downloading click-8.2.1-py3-none-any.whl (102 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 102.2/102.2 kB 2.6 MB/s eta 0:00:00
Downloading itsdangerous-2.2.0-py3-none-any.whl (16 kB)
Downloading jinja2-3.1.6-py3-none-any.whl (134 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 134.9/134.9 kB 3.1 MB/s eta 0:00:00
Downloading MarkupSafe-3.0.2-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (23 kB)
Downloading werkzeug-3.1.3-py3-none-any.whl (224 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 224.5/224.5 kB 2.3 MB/s eta 0:00:00
Installing collected packages: markupsafe, itsdangerous, click, blinker, werkzeug, jinja2, flask
Successfully installed blinker-1.9.0 click-8.2.1 flask-3.1.2 itsdangerous-2.2.0 jinja2-3.1.6 markupsafe-3.0.2 werkzeug-3.1.3
(myenv) root@DESKTOP-T6I6DAE:~# 
