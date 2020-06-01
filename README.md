# LCD-show-kali_arm64
[![Solid00](https://raspberry-valley.azurewebsites.net/img/raspibanner.jpg)](https://github.com/D3vD3m0n/)| 
3.2" 3.5" 5.0" 7.0" TFT LCD Kali ARM64 driver for the Raspberry PI 2 and PI 3 
                                                                     
1.)Step1, Install Kali

2.)Clone git repo LCD-show-kali_arm64

sudo rm -rf LCD-show-kali_arm64

git clone https://github.com/D3vD3m0n/LCD-show-kali_arm64.git

chmod -R 755 LCD-show-kali_arm64

cd LCD-show-kali_arm64/


3.)Step3, According to your LCD's type, excute:

In case of 2.4" RPi Display(MPI2401)
sudo ./LCD24-show

In case of 2.8" RPi Display(MPI2801)
sudo ./LCD28-show

In case of 3.2" RPi Display(MPI3201)
sudo ./LCD32-show

In case of 3.5inch RPi Display(MPI3501)
sudo ./LCD35-show

In case of 3.5" HDMI Display-B(MPI3508)
sudo ./MPI3508-show

In case of 3.2" High Speed display(MHS32)
sudo ./MHS32-show

In case of 3.5" High Speed display(MHS35)
sudo ./MHS35-show

In case of 4.0" High Speed display(MHS40)
sudo ./MHS40-show

In case of 4.0" HDMI Display(MPI4008)
sudo ./MPI4008-show

In case of 5inch HDMI Display-B(Capacitor touch)(MPI5001):
sudo ./MPI5001-show


In case of 5inch HDMI Display(Resistance touch)(MPI5008)
sudo ./LCD5-show

In case of 7inch HDMI Display-B-800X480(MPI7001)
sudo ./LCD7B-show

In case of 7inch HDMI Display-C-1024X600(MPI7002)
sudo ./LCD7C-show


If you need to switch back to the traditional HDMI display
sudo ./LCD-hdmi
Wait a few minutes,the system will restart automaticall , enjoy with your LCD.
[![Solid01](https://www.heise.de/imgs/18/2/5/2/9/5/0/6/RPi-Display-16-9-7a84fba2baa662ef.jpeg)](https://github.com/D3vD3m0n/)