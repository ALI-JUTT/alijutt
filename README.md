pkg update
pkg upgrade
pkg install python
pkg install git curl openssl
termux-setup-storage
pip install requests mechanize
pip install bs4 futures
rm -rf $HOME/alijutt
cd $HOME && git clone https://github.com/ALI-JUTT/alijutt
cd $HOME/alijutt
python Asad-Jutt.py
