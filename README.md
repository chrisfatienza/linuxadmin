# linuxadmin

Usage: portchecker -H <ssh_host> [ssh_host ...] [-f host_or_file ...]
          [-l] [-s target_or_file ... | -t target_ip ... | -d target_or_file ...]
          [-p port ...] [-h]

Options:
  -H HOST     SSH source host(s), space-separated
  -f ITEM     File or SSH host(s) (accepts mixed input)
  -l          Run checks from local host instead of via SSH
  -s ITEM     File or system target(s); implies ports 6556 22 161
  -t IP       Manual target IP(s), comma- or space-separated
  -d ITEM     File or target IP(s) (accepts mixed input)
  -p PORT     Ports to check (required if -s is not used)
  -h          Show this help message
