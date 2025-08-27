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
 * Running on http://192.168.x.x:5000 (your local network IP)

Step 4: Access the Server
On your laptop → open a browser → go to
👉 http://127.0.0.1:5000
You’ll see:
✅ Hello! Your laptop is working as a server.

On another device in the same Wi-Fi (like your phone) → go to
👉 http://192.168.x.x:5000 (use the IP Flask shows).
