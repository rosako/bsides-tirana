# Tools to install

1. Binwalk

```bash
git clone https://github.com/ReFirmLabs/binwalk.git
cd binwalk
sudo ./deps.sh
sudo python3 setup.py install

```

2. sasquatch

```bash
sudo apt-get install zlib1g-dev liblzma-dev liblzo2-dev
git clone https://github.com/devttys0/sasquatch
cd sasquatch
wget https://raw.githubusercontent.com/devttys0/sasquatch/82da12efe97a37ddcd33dba53933bc96db4d7c69/patches/patch0.txt
mv patch0.txt patches
./build.sh
```

3. flashrom

```bash
apt install flashrom
```
