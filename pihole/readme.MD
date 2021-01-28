## pihole
Sets up a pihole container to block ads
 
--Setting Up--

1. Download the latest version: docker pull pihole/pihole
2. Remove the current container: docker rm -f pihole
3. Edit the script and add the admin login password: nano piholeDockerRun.sh
4. Make the script executable: chmod +x piholeDockerRun.sh
5. Run the script: ./piholeDockerRun.sh
