#  Proposed attack (name not yet determined)
## ⚔️ Overview
This attack exploits the integrity check value and size of the original data from unencrypted metadata in encrypted archive files. The attack can identify original data with these values by leveraging password cracking techniques such as brute-force attack, dictionary attack, and rainbow table attack.

## 🛠️ Affected archive utilities and archive formats
- ALZip (12.16.0.2): ZIP and EGG
- Bandizip (7.3): ZIP(X)
- 7-Zip (23.01): ZIP and 7z
- PeaZip (9.3.0): 7z and RAR4
- PKZIP (14.40.0028): ZIP(X)
- WinRAR (6.22): RAR4

## 🗃️ Sample files: Experimental dataset for proposed attack
The following two folders contain sample files for archive formats vulnerable to the proposed attack.
- poc: The encrypted file for demonstrating the proposed attack as a proof of concept. 
  - File name: attack_poc.zip
- exp: The encrypted files for confirming the effectiveness of the proposed attack.
  - File name: {archive format}\_{archive utilty}\_{integrity check algorithm}_{pw (optional)}

## ⚙️ Implementation : TBD

## 📚 Publications : TBD