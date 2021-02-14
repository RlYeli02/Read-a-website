# Open TCP sockets from a bahs shell script

## Run the next commands : 

1. **exec 3<>/dev/tcp/www.google.com/80** and press enter
2. **echo -e "GET / HTTP/1.1\n\n" >&3** and press enter
3. **cat <&3** press enter and you gonna see a OK response and open socket