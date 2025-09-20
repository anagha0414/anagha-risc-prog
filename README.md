# RISC-V-Tapeout-Program
<details>
<summary> Week 0 - Tools Installation </summary>
  <br>
<p>  In this VLSI System Design (VSD) program, setting up a development environment involves installing a suite of open-source Electronic Design Automation (EDA) tools. These tools are crucial for the various stages of the VLSI design flow, including Synthesis, Simulation, and Physical Design. First, install Oracle VirtualBox and set up an Ubuntu virtual machine, then proceed to install essential open-source tools:
</p>
  <ol>
  <li>Yosys</li>
  <li>lverilog</li>
  <li>gtkwave</li>
</ol>
  <h2> </h2>
  <h2>Yosys – Yosys Open Synthesis Suite</h2>
<p>
 <pre>$ git clone https://github.com/YosysHQ/yosys.git 
$ cd yosys 
$ sudo apt install make # (If make is not installed please install it) 
$ sudo apt-get install build-essential clang bison flex \ 
  libreadline-dev gawk tcl-dev libffi-dev git \ 
  graphviz xdot pkg-config python3 libboost-system-dev \ 
  libboost-python-dev libboost-filesystem-dev zlib1g-dev 
$ make 
$ sudo make install </pre>
  </p>
  <h2> </h2>
   <h2>Iverilog</h2>
  Steps to install IVerilog
  <p>
    <pre>sudo apt-get update
sudo apt-get install iverilog     </pre>
  </p>
  <h2> </h2>
  <h2>gtkwave</h2>
  Steps to install gtkwave
  <p>
    <pre>sudo apt-get update
sudo apt-get install iverilog    </pre>
</p>
  </details>
