# 1231

ansible-playbook play.yaml -i hosts.yaml -u root --ask-vault-pass
https://habr.com/ru/company/redhatrussia/blog/519452/

```
        su sudoers
    2  nano sudoers
    3  sudo gedit /etc/sudoers
    4  logout
    5  logout
    6  passwd
    7  logout
    8  sudo gedit /etc/sudoers
    9  su sudoers
   10  sudo visudo
   11  ansible localhost -m shell -a 'sudo apt upgrade -y'
   12  nano hosts.yaml
   13  nano ~/.ssh/config
   14  ssh root@192.168.202.9
   15  ssh root@192.168.202.10
   16  mkdir host_vars/jump
   17  ls
   18  mkdir group_vars
   19  nano  group_vars/ec_all.yaml
   20  nano ansible.cfg
   21  ansible -i hosts jump_sa -m ping
   22  ansible --version
   23  ansible-inventory -i hosts --graph
   24  ansible -i hosts jump_sa -m ping
   25  ansible-inventory -i hosts --host 192.168.202.9
   26  ansible-inventory -i hosts --host jump_sa
   27  mkdir host_vars/jump_sa
   28  mkdir host_vars
   29  mkdir host_vars/jump_sa
   30  cd host_vars/jump/
   31  nano vars.yaml
   32  ansible-vault create host_vars/jump_sa/vault.yaml
   33  ansible-inventory -i hosts --host jump_sa
   34  ls
   35  nano  group_vars/ec_all.yaml
   36  ansible-inventory -i hosts --host jump_sa
   37  ansible-inventory -i hosts --host 192.168.202.9
   38  ansible -i hosts ec -m ping -u root
   39  ssh root@192.168.202.9
   40  ssh-copy-id root@192.168.202.9
   41  ssh-copy-id root@192.168.202.10
   42  ssh root@192.168.202.9
   43  nano ~/.ssh/config
   44  ssh root@192.168.202.9
   45  ssh-copy-id jump_sa@178.124.06.53
   46  ssh jump_sa@178.124.206.53
   47  ssh-copy-id jump_sa@178.124.206.53
   48  ssh root@192.168.202.9
   49  ansible -i hosts ec -m ping -u root
   50  ansible -m ping all --ask-vault-pass
   51  nano ansible.cfg
   52  rm - r ansible.cfg
   53  ls
   54  rm - r group_vars/
   55  rm - r host
   56  rm - r hosts.yaml
   57  rm - r host_vars/
   58  ls
   59  rm - r host_vars/
   60  rm  host_vars/
   61  rm  -r host_vars/
   62  rm  -r group_vars/
   63  ls
   64  rm  -r vars.yaml
   65  mkdir 1
   66  cd 1
   67  nano ansible.cfg
   68  ansible --version
   69  nano hosts.yaml
   70  mkdir host_vars/jump_sa
   71  mkdir host_vars
   72  mkdir host_vars/jump_sa
   73  nano host_vars/jump/vars.yaml
   74  cd host_vars/jump/
   75  cd host_vars/
   76  cd jump/
   77  nano vars.yaml
   78  cd
   79  cd 1
   80  ansible-vault edit host_vars/jump_sa/vault.yaml
   81  ansible-vault edit 1/host_vars/jump_sa/vault.yaml
   82  ansible-inventory -i hosts --host jump_sa
   83  mkdir group_vars
   84  nano  group_vars/ec_all.yaml
   85  ansible-inventory -i hosts --host jump_sa
   86  ansible-inventory -i hosts --host 192.168.202.9
   87  ansible-inventory -i hosts.yaml --host jump_sa
   88  ansible-inventory -i hosts.yaml --host jump_sa --ask-vault-pass
   89  ansible localhost -m shell -a 'sudo apt upgrade -y' --ask-vault-pass
   90  logout
   91  ls
   92  logout
   93  ansible localhost -m shell -a 'sudo apt upgrade -y' --ask-vault-pass
   94  ssh-copy-id root@192.168.202.9
   95  ssh-copy-id root@192.168.202.10
   96  ansible -i 11.Ansible/hosts.yaml -m ping cw_1 --ask-vault-pass
   97  ansible -i hosts.yaml -m ping cw_1 --ask-vault-pass
   98  cd 1
   99  ansible -i hosts.yaml -m ping cw_1 --ask-vault-pass
  100  nano ansible.cfg
  101  ansible -i hosts.yaml -m ping cw_1 --ask-vault-pass
  102  nano ansible.cfg
  103  ansible -i hosts.yaml -m ping cw_1 --ask-vault-pass
  104  ssh root@192.168.202.10
  105  cd host_vars/
  106  nano cw_1.yaml
  107  cd ..
  108  ls
  109  cd group_vars/
  110  nano all.yaml
  111  cd
  112  ansible -m ping all --ask-vault-pass
  113  cd group_vars/
  114  cd 1
  115  ansible -m ping all --ask-vault-pass
  116  cd group_vars/
  117  rm -r ec_all.yaml
  118  cd ..
  119  ansible -m ping all --ask-vault-pass
  120  nano ansi
  121  cd host_vars/
  122  cd jump_sa/
  123  ls
  124  cd ..
  125  ls
  126  nano vars.yaml
  127  rm -r jump_sa/
  128  ls
  129  cd ..
  130  cd group_vars/
  131  nano ec_all.yaml
  132  cd ..
  133  ansible -m ping ec_all --ask-vault-pass
  134  ansible -m ping all --ask-vault-pass
  135  ansible -m ping cw --ask-vault-pass
  136  ansible -m ping cw_1 --ask-vault-pass
  137  ansible -i hosts.yaml -m ping cw_1 --ask-vault-pass
  138  ansible -i hosts.yaml -m ping cw --ask-vault-pass
  139  nano hosts.yaml
  140  ansible -m ping all --ask-vault-pass
  141  ansible -m ping ec_all --ask-vault-pass
  142  ansible -m ping ec --ask-vault-pass
  143  ansible -i hosts.yaml -m ping ec --ask-vault-pass
  144  nano hosts
  145  ansible -m ping ec --ask-vault-pass
  146  ansible -i hosts.yaml -m ping ec --ask-vault-pass
  147  nano ansible.cfg
  148  cd group_vars/
  149  nano ec_all.yaml
  150  cd ..
  151  ansible -i hosts.yaml -m ping ec --ask-vault-pass
  152  ansible -i hosts ec -m ping -u root
  153  ansible -i hosts.yaml ec -m ping -u root
  154  ansible -i hosts.yaml vms -m ping
  155  ansible -i hosts.yaml vms -m ping -u root
  156  ansible -i hosts.yaml ec -m ping -u root
  157  nano hosts.yaml
  158  ansible -i hosts.yaml qwe -m ping -u root
  159  ansible -i hosts.yaml qw_01 -m ping -u root
  160  ansible -i hosts.yaml qw_1 -m ping -u root
  161  nano hosts.yaml
  162  ansible -i hosts.yaml ec1 -m ping -u root
  163  nano hosts.yaml
  164  ansible -i hosts.yaml ec -m ping -u root
  165  nano hosts.yaml
  166  ansible -i hosts.yaml ec2 -m ping -u root
  167  ansible -i hosts.yaml qwe -m ping -u root
  168  nano hosts.yaml
  169  ansible -i hosts.yaml ec2 -m ping -u root
  170  ansible -m ping ec2 --ask-vault-pass
  171  ansible -m ping ec_all --ask-vault-pass
  172  ansible -m ping ec2 -u root --ask-vault-pass
  173  ansible -i hosts.yaml ec2 -m ping -u roo
  174  ansible -i hosts.yaml ec2 -m ping -u root
  175  ansible -i hosts.yaml ec2 -m ping -u root  --ask-vault-pass
  176  ansible -i 11.Ansible/hosts.yaml -m shell -a 'hostname && hostname -i' qw_1 --ask-vault-pass
  177  ansible -i 11.Ansible/hosts.yaml -m shell -a 'hostname && hostname -i' ec --ask-vault-pass
  178  ansible -i hosts.yaml ec2 shell -a 'hostname && hostname -i' -u root
  179  ansible -i hosts.yaml -m shell -a 'hostname && hostname -i' ec_all ec_all --ask-vault-pass
  180  ansible -i hosts.yaml -m shell -a 'hostname && hostname -i' qwe qwe --ask-vault-pass
  181  ansible -i hosts.yaml -m shell -a 'hostname && hostname -i' ec ec --ask-vault-pass
  182  ansible -i hosts.yaml -m shell -a 'hostname && hostname -i' ec  --ask-vault-pass
  183  ansible -i hosts.yaml -m shell -a 'hostname && hostname -i' ec2  --ask-vault-pass
  184  ansible -i hosts.yaml -m shell -a 'hostname && hostname -i' ec2
  185  ansible -i hosts.yaml ec2 -m ping
  186  ansible -i hosts.yaml -m shell -a 'hostname && hostname -i' ec2  -u root
  187  ansible -i hosts.yaml -m shell -a 'yum update -y' - u root
  188  ansible -i hosts.yaml qw_1 -m ping -u root
  189   ansible -i hosts.yaml -m shell -a 'yum update -y' centos
  190  ansible -i hosts.yaml -m shell -a 'yum update -y' qw_1
  191  nano hosts.yaml
  192   ansible -i hosts.yaml -m shell -a 'yum update -y' w_1
  193  ansible -i hosts.yaml -m shell -a 'yum update -y' w_1
  194  ansible -i hosts.yaml -m shell -a 'yum update -y' w_1 - u root
  195  ansible -i hosts.yaml -m shell -a 'yum update -y' w_1 -u root
  196  ansible -i hosts.yaml -m shell -a 'yum update -y' w_1
  197  ansible -i hosts.yaml -m shell -a 'apt-get update && apt-get upgrade' w_1
  198  ansible -i hosts.yaml -m shell -a 'apt-get update && apt-get upgrade' w_2
  199  ansible -i hosts.yaml -m shell -a 'yum update -y' ec2
  200  ansible -i hosts.yaml -m shell -a 'yum update -y' qwe
  201  nano hosts.yaml
  202  ansible -i hosts.yaml -m shell -a 'yum update -y'  worker_01
  203  ansible -i hosts.yaml -m shell -a 'yum update -y'  -u worker_01
  204  ansible -i hosts.yaml -m shell -a 'yum update -y'  worker_01 -u root
  205  ansible -i 11.Ansible/hosts.yaml -m shell -a 'yum upgrade -y' w_! --ask-vault-pass
  206  ansible -i 11.Ansible/hosts.yaml -m shell -a 'yum upgrade -y' w_1 --ask-vault-pass
  207  ansible -i hosts.yaml -m shell -a 'yum upgrade -y' w_1 --ask-vault-pass
  208  ansible w_1 -m shell -a "yum upgrade -y"  --ask-vault-pass
  209  ansible w_2 -m shell -a "yum upgrade -y"  --ask-vault-pass
  210  ansible -i hosts.yaml w_2 -m shell -a "yum upgrade -y"  --ask-vault-pass
  211  ansible -i hosts.yaml w_1 -m shell -a "yum upgrade -y"  --ask-vault-pass
  212  \mkdir 123
  213  ls
  214  cd 123
  215  echo "# 1231" >> README.md
  216  git init
  217  git add README.md
  218  git commit -m "first commit"
  219  git branch -M main
  220  cat ~/.ssh/id_rsa.pub
  221  git commit -m "first commit"
  222  git config --global user.email "salix731@egmail.com"
  223  git commit -m "first commit"
  224  git remote add origin git@github.com:Korolev731/1231.git
  225  git push -u origin main
  226  git branch -M main
  227  git remote add origin git@github.com:Korolev731/1231.git
  228  git push -u origin main
  229  cp -a /1/* /123
  230  ls
  231  cp -a /1/123
  232  ls
  233  cd
  234  cp -a /1/123
  235  cp -r ./1 ./123
  236  cd 123
  237  ls
  238  git add .
  239  git commit -m "1"
  240  git push
  241  cd 1
  242  nano user.yaml
  243  nano play.yaml
  244  git pull
  245  git add .
  246  git commit -m "1"
  247  git push
  248  history

```
