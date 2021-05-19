Doxygen documentation link: https://buevich-dmitry.github.io/otus3/

To download and install the latest version, run:
```
wget -O print_ip-Linux.deb https://github.com/buevich-dmitry/otus3/releases/latest/download/print_ip-Linux.deb
sudo dpkg -i print_ip-Linux.deb
```

Also you can build the project locally:
```
./build.sh
sudo dpkg -i bin/print_ip-*-Linux.deb
```

Then run ip_filter app:
```
print_ip
```
