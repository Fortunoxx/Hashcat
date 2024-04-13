# Use a base image with the desired operating system and dependencies
FROM ubuntu:latest

# Install Hashcat and its dependencies
RUN apt-get update && apt-get install -y hashcat

# Set the entry point to Hashcat
ENTRYPOINT ["hashcat"]
