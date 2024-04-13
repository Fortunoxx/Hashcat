# commands
- `docker build -t hashcat .`
- `docker run --rm -it hashcat -h`
- `docker run --rm -it -v .\jwt.short.txt:/etc/jwt.txt hashcat --entrypoint "/bin/bash"`
- `docker run --rm -it -v .\jwt.short.txt:/etc/jwt.txt hashcat /etc/jwt.txt -m 16500 -a 3 -w 2 ?d?d?d?d --show`