# -2
Python function that uses multi-threading, Paramiko, Netmiko, and PyAudio to list all open devices and radio appliances in a given area of occupation
This function scans a given area of occupation for open devices and radio appliances using multi-threading.
It uses the scapy library to scan for devices and radio appliances on the network.

It also attempts to connect to each device via SSH using the paramiko library and runs the show version command on each device using the netmiko library.
It uses the pyaudio library to record audio from each device's microphone.
