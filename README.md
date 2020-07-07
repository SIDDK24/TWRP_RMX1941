# TWRP Device Tree for Realme C2
The Realme C2 (codenamed "RMX1941","RMX1945"& "RMX1943") is a budget smartphone from Realme, announced in April 2019.

Working:

1.Backup and Restore

2.Flash GSI

3.Screenshots

4.OTG

5.MTP

Not working:

1.Decryption

To Build

cd <source-dir>;  export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch omni_RMX1941-eng; mka recoveryimage
