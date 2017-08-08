# darknode

<b>Repository under construction</b>

cluster/ - START HERE - build your nodes and dispatcher using this branch<br>
darknode/ - setup your nodes and dispatcher with the software and point evolution to the associated branches<br>
<pre>
cluster/
  esp8266/
    setup/
      *README - specs, form factor list [ESP01, etc.], how to flash using FTDI, links
      *Flashing diagram
      *Node schematics
      *Steps to build
      micropython/
        *README - info on micropython, links, basic commands
        *<current tested distro>.bin
      
    evolve/
      *manifest
    
  raspberrypi/
    setup/
      *README - distro credits, walkthrough on SD install and configuration, necessary hardware
      *Pi schematics for GPIO use
      *Steps to build
      
    evolve/
      *manifest
  
darknode/
  node/
    *boot.py 
    *main.py  
    evolve/
    
  dispatcher/
    os/
      *README - distro credits, configuration walkthrough
      *darkdsp.iso
    *boot.py
    *main.py
    evolve/
</pre>
  
  
