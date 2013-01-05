
To generate a list of all installed RPMs - use the following command:
  rpm -qa

To retrieve details about a particular RPM (from the RPM itself), run:
  rpm -qi package_name

To check for and report potential conflicts and dependencies when deleting an RPM, run:
  rpm -e --test package_name


Networking
  netstat -tulp
  nmap -sTU remote_host
  lsof -i -n | egrep 'COMMAND|LISTEN|UDP|TCP'

  chkconfig -l | grep on


Kernel
  http://publib.boulder.ibm.com/infocenter/lnxinfo/v3r0m0/index.jsp?topic=%2Fliaai%2Frealtime%2Fliaairtconfigkernel.htm
