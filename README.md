dnsmasq
=======


add dns-script option to your dnsmasq.conf

    dns-script=domain,script
    dns-script=apple.com,/opt/line1.sh
    dns-script=edu.cn,/opt/line2.sh

* when user query domain a record like: www.edu.cn
* will be execute: "/opt/line2.sh 202.112.0.36"
