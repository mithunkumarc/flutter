# flutter install


mithun@linux:~$ mkdir android

mithun@linux:~$ cd android/

mithun@linux:~/android$ tar xf ~/Downloads/flutter_linux_v1.0.0-stable.tar.xz

mithun@linux:~/android$ export PATH=`pwd`/flutter/bin:$PATH

mithun@linux:~/android$ echo $PATH

        /home/mithun/android/flutter/bin:/home/mithun/.cargo/bin:/home/mithun/bin:/home/mithun/.local/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin:/home/mithun/.dotnet/tools:/opt/jdk-11//bin:/opt/jdk-10.0.1/bin

above will save flutter path temperory , to update flutter path permanently:

        1. goto place where flutter sdk extracted

        2. goto terminal , enter pwd command to get path

        3. open file : sudo nano ~/.bashrc

        4. update flutter path(below path) in bashrc file
           export PATH="/home/mithun/android/flutter/bin:$PATH"
           
           
           
reference : https://www.tutorialkart.com/flutter/flutter-install-on-linux-ubuntu/           
