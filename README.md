## Usage


```
pip3 install -r requirements.txt
python3 update_verifier.py lineageos4microg_pubkey /path/to/zip
```

On Debian/Ubuntu you can instead install the Python packages from apt:

```
sudo apt-get install python3-rsa python3-pyasn1
python3 update_verifier.py lineageos4microg_pubkey /path/to/zip
```

Note that this script requires a recent version of pyasn1 (at least 0.4.2),
which is not yet present in some distributions (like Debian Stretch). In those
cases, use pip3 to install the dependencies.
