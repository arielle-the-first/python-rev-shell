1) In "shell-reversed.dll" and replace "x.x.x.x" with the public ip address of the server you will be litening for the reverse shell on
2) Host the file "shell-reversed.dll" in a github repo
3) Repalce "<LINK GOES HERE>" with the public link to your hosted file in "Reverse Shell.txt"
4) Run the command "nc -lvnp 10751" on the server you want to listen on
5) Execute The Payload
6) Once The Reverse Shell has been established, run the command "rm $env:TEMP\shell-reversed.dll". This will remove the file helping efforts to trace you down become more difficult.
