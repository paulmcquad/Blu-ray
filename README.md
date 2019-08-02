# Blu-ray

---

How To Install Blu-ray Support on any system:

See [INSTALL.md](INSTALL.md)

---


### Configuration Files

### AACS:
Windows: put it in C:\ProgramData\aacs\

Mac OS X: put it in ~/Library/Preferences/aacs/ (create it if it does not exist)

Linux: put it in ~/.config/aacs/

---

### bdplus:
Windows: put it in C:\ProgramData\bdplus\

Mac OS X: put it in ~/Library/Preferences/bdplus/ (create it if it does not exist)

Linux: put it in ~/.config/bdplus/

---

### bluray:

Windows: put it in C:\ProgramData\bluray\

Mac OS X: put it in ~/Library/Preferences/bluray/ (create it if it does not exist)

Linux: put it in ~/.config/bluray/

---

### Decryption Scheme

The following is a picture some of you might already have seen. Its a main overview of the AACS protection system.

It shows the disc and the player and "all" the important keys involved in the decryption process.

[Advanced Access Content System](https://en.wikipedia.org/wiki/Advanced_Access_Content_System)

![Screenshot](/img/425x350AACS_dataflow.png)

MKB = Media Key Block

Process MKB = Subset-Difference Tree system

Km = Media Key

Kvu = Volume Unique Key

Encrypted Key = Encrypted Title Key

Kt = Title Key


 DiscID = VolumeName (MetaTitle) | D | DateDiscID | V | VUK | M | MEDIAKEY | I | VOLUMEID | U | 1-0xUnitKey | 2-0xUnitKey | n-0xUnitKey ; MKBrev/FindVUK 1.09 

---
### More Information

Advanced Access Content System Licensing Administrator, LLC (“AACS LA”)

https://aacsla.com/

https://aacsla.com/news/

---