# arvan-interview-task


at first I should select an option for creating VMs in my local machine. 

my choices Are: 
1. virtualbox
2. parallels
3. multy pass 

because of the fact that parrallels is want licence and the integeration of virtualbox with teraform is not as easy as multypass, so i choose multypass! 
```
brew install --cask multipass
multipass launch --name ubuntu-server
```

first i costumize my vm with installing some tools in that like : 
1. ```sudo apt update && sudo apt upgrade -y```
2. ```sudo apt install net-tools -y```


