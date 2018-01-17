# NodeJS-Class-MEST
QuickFix To My NODEJs Installation in Class The Other Day



This, when the v4.6 ddidnt want to upgrade to v8.9:

nodejs -v4.2.6
q@q-HP-Pavilion-Notebook:~$ 
q@q-HP-Pavilion-Notebook:~$ mv Downloads/node-v
node-v6.11.2/                 node-v8.9.4-linux-x64/
node-v6.11.2.tar.gz           node-v8.9.4-linux-x64.tar.xz
q@q-HP-Pavilion-Notebook:~$ mv Downloads/node-v8.9.4-linux-x64/ /opt
mv: cannot move 'Downloads/node-v8.9.4-linux-x64/' to '/opt/node-v8.9.4-linux-x64': Permission denied
q@q-HP-Pavilion-Notebook:~$ sudo !!
sudo mv Downloads/node-v8.9.4-linux-x64/ /opt
q@q-HP-Pavilion-Notebook:~$ sudo ln -sf /opt/node-v8.9.4-linux-x64/bin/node /usr/local/bin/
q@q-HP-Pavilion-Notebook:~$ sudo ln -sf /opt/node-v8.9.4-linux-x64/bin/npm /usr/local/bin/
q@q-HP-Pavilion-Notebook:~$ node -v
v8.9.4
q@q-HP-Pavilion-Notebook:~$ 

