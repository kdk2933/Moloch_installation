# Moloch_installation
Moloch is an open source, large scale, full packet capturing, indexing, and database system.    
Moloch is a large scale, open source, indexed packet capture and search system.
Moloch augments your current security infrastructure to store and index network traffic in standard PCAP format, providing fast, indexed access. An intuitive and simple web interface is provided for PCAP browsing, searching, and exporting. Moloch exposes APIs which allow for PCAP data and JSON formatted session data to be downloaded and consumed directly. Moloch stores and exports all packets in standard PCAP format, allowing you to also use your favorite PCAP ingesting tools, such as wireshark, during your analysis workflow.

Moloch is built to be deployed across many systems and can scale to handle tens of gigabits/sec of traffic. PCAP retention is based on available sensor disk space. Metadata retention is based on the Elasticsearch cluster scale. Both can be increased at anytime and are under your complete control.

I have placed the required files here https://mega.nz/#!tI0znQxQ and the decryption key is 

-zS1chvKBVGBp_ZN6McybBolDU5dFfiIRkoH5djRFtI

place it in a file in your centos 7.5 /home/user or somewhere and extract.

dependency rpm for the installtion.
Openssl_1.0.2 rpm here https://rpmfind.net/linux/rpm2html/search.php?query=libcrypto.so.10(OPENSSL_1.0.2) 

--------------------------------------

 How to install HTOP

    Log into your server with root access via SSH.
    Add the htop repository to your servers repo list.
    wget dl.fedoraproject.org/pub/epel/7/x86_64/Packages/e/epel-release-7-11.noarch.rpm
    rpm -ihv epel-release-7-11.noarch.rpm
    Install htop.
    yum install htop
    Once the installation is complete you may just run the command below to get started.
    htop

    Once you have Htop up and running you should see something similar the image to the right. As you can see in the image to the right HTOP displays how many cores your computer/server has while also including the load on each core. Below your CPU information you can see the RAM being used and the total amount. You can also run the command “man htop” and it will provide you with more options while running this tool.
