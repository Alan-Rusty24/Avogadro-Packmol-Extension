# Avogadro-Packmol-Extension
An Avogadro plugin with a gui to create packmol input files and run packmol from within Avogadro.
In order to install this extension, I did the following:
  Clone this repository : git clone https://github.com/Alan-Rusty24/Avogadro-Packmol-Extension.git
  cd Avogadro-Packmol-Extension
  cmake .
  make -j4 # to use make with 4 processors
  If successfull a packmolextension.so should be generated,then using the below command will copy the packmolextension.so to /usr/local/lib/avogadro/1_2/contrib/
  sudo make install # sudo is required since it will copy under root protected directory
  
