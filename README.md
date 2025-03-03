If you are using windows or Mac, you can download the font from this link https://cloud.erpgulf.com/files/Claudion.ttf

(⃀ U+20C0)  is the code.  You can add that code to a key-shortcut on Windows or mac for easy use. 


To setup up Frappe ERPNext server, please follow the below steps.


cd /usr/share/fonts/

sudo mkdir saudi

wget https://cloud.erpgulf.com/files/Claudion.ttf

sudo fc-cache -f -v


You can test the font by typing following command

echo -e "\u20C0"

You will get ⃀ as output


That's all for the installation
