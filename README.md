# SoapInterface
A selfhost interface to connect to an RCC (only compatible with 2008) and to send commands<br>
<b>this is in HEAVY development, as i need to clean up the code before i release this</b>

# requirements
2008 rcc<br>
soapui for debugging (by p0s0, you can find it somewhere in the orc as it is no longer on github)<br>
php (must be added to PATH)

# patches needed
ns1, ns2, etc patched to roblox.com<br>
replacement gameserver.txt (will add when updated)<br>
file that starts the rcc (start.bat will be supplied)

# how 2 use?!?!?1/
if you're in the folder including the php files (index, soaprequest, etc), open a command prompt<br>
and type in `php -S 127.0.0.1:8000` or your chosen IP and Port to run the interface on<br>
<sub> fyi, this was made for running on a development environment, so xampp would work for this situation </sub>

