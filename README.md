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
