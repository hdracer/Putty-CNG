# Putty-CNG
This project allows SSH connections to be initiated from Windows using CNG (Crypto API: Next Generation) keys (i.e., those stored in Key Storage Providers). Crypto API keys (i.e., those stored in Cryptographic Service Providers), and not to mention Putty keys stored in flat files, are also supported, thanks to the previous work done by https://risacher.org/putty-cac/ and http://www.chiark.greenend.org.uk/~sgtatham/putty/. 

Indeed, Putty-CNG constitutes only a minor addition to those projects, albeit an important one if you're using new cryptographic capabilities on Windows. Examples include virtual smart card, Trusted Platform Module (TPM), and http://www.jwsecure.com/technologies/strongnet/. 
