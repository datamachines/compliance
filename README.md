Origin:
wget https://copr-be.cloud.fedoraproject.org/results/openscapmaint/openscap-latest/epel-8-x86_64/01808555-scap-security-guide/scap-security-guide-0.1.53-1.el8.noarch.rpm
rpm2cpio scap-security-guide-0.1.53-1.el8.noarch.rpm | cpio -t | grep ssg-centos8-ds-1.2.xml
rpm2cpio scap-security-guide-0.1.53-1.el8.noarch.rpm | cpio -idmv ./usr/share/xml/scap/ssg/content/ssg-centos8-ds-1.2.xml
