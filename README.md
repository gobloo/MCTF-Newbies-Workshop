# MCTF-Newbies-Workshop

## Requirement:
- linux machine de preference Parrrot 
  [Lien de telechargement](https://www.parrotsec.org/download/,true))
 
- Creerun compte THM [sign up](https://tryhackme.com/signup,true))
- Installer Openvpn dans Parrot 
   ```
  apt update && apt -y install ca-certificates wget net-tools gnupg
	wget -qO - https://as-repository.openvpn.net/as-repo-public.gpg | apt-key add -
	echo "deb http://as-repository.openvpn.net/as/debian bullseye main">/etc/apt/sources.list.d/openvpn-as-repo.list
	apt update && apt -y install openvpn-as
   ```
