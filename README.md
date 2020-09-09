cd /usr/local/src/</p>
git clone https://github.com/cooliobr/peervpn
cd peervpn
sh peer_ssl_build.sh
cp peervpn.service /etc/systemd/system/
systemctl start peervpn.service
service peervpn start

