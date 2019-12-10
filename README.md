# easy-esp32
wrapper function to easily install and configure esp32 development in ubuntu machines 

## Usage 
download wrappers.lib script to your computer preferably home director 

```
cd 
git clone https://github.com/aswinpajayan/easy-esp32
```
source the file manually or add it in your .bashrc file 

open your .bashrc file and add the following line 
```
source ~/easy-esp32/wrappers.lib
```

### installation 
open a new terminal and type
```
  esp32 --install 
```
adding a new project with hello-world template 

```
  esp32 --new testProject
 ```
 
 goto the project folder and do 
 
 ```
    make menuconfig
    make flash monitor
    
 ```
The script just follows the instructions given in https://docs.espressif.com/projects/esp-idf/en/latest/get-started/index.html#installation-step-by-step

# Eclipse IDE for ESP development 

After installing and testing ESP from commandline, you can use Eclipse IDE for your further development. Detailed instructions for setting up Eclipse IDE is given in [espressif/idf-eclipse-plugin](https://github.com/espressif/idf-eclipse-plugin/blob/master/README.md)
