#       Challenge Objective                                                             Suggested COmmand Strategy
1       Install htop, launch it and record one detail it displays                       sudo apt install -y htop then run htop
2       Find out what version of apache2 is available without intsall it.               apt show apache2
3       Record the current count of packages installed on your VM right now.            apt list --installed | wc -l
4       Deploy an ephemeral container running alphine that print "Hello from alpine"    sudo docker run --rm alphine echo "Hello from alpine"
