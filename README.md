cd /usr/local/src/<br>
git clone https://github.com/cooliobr/peervpn<br>
cd peervpn<br>
sh peer_ssl_build.sh<br>
cp peervpn.service /etc/systemd/system/<br>
systemctl start peervpn.service<br>
service peervpn start<br>

