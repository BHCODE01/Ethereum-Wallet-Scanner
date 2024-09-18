Ethereum Waller Cracker
=======================

This project, conducted for research purposes, is now distributed in response to numerous requests from individuals interested in this project.


TO-DO Before starting  
=====================  
You must register an account of Etherscan.io in order to get an API KEY  
That will allow you to make 5 calls per seconds on THEIR blockchain server.  
Register and goto https://etherscan.io/myapikey  to generate your API KEY.  
Paste your API KEY in the file named " apikey-01.txt " save and close the file.  

  
How It Works?
=============
The tool generates a random Ethereum address and checks its balance.  
If a balance is found, a sound alert is triggered and the result is written in the "results.txt" file.  
Users need to create a free account on etherscan.io to obtain an API key to check the balance of each generated Ethereum address.  

  
EWS Options
=========== 

1 - "Decrypt or BruteForce KeyStore JSON file"  
==============================================
This tool is to Brute Force an Ethereum Keystore JSON file with a text dictionary of passwords.
The dictionary should be a regular text file with one password per line.


2 - "Generate One Ethereum Wallet Address"  
==========================================
Generate just one Ethereum address with its private key in offline mode (no online balance check).
You can run it offline, no internet, no network, in a virtual environment or anywhere else.

  
3 - "Generate Ethereum Address from Mnemonic Seed 12 words"  
===========================================================
This option will generate one ethereum address based on the mnemonic 12 words seed provided.
You can use a password to add more entropy to the wallet generation.


4 - "Generate Ethereum Address from Private Key"  
================================================
This option will generate one ethereum address based on the private key you will provide.  
A private key consist of 64 characters long string with only ABCDEF0123456789 characters accepted, if you enter your private key and click the "Create" button it will give you the associated Ethereum Address derivated from this private key.  


5 - "Incremental PrivateKey Hack"  
=================================
This option tries all possible private key starting from 0000000000000000000000000000000000000000000000000000000000000001 until the last Ethereum Private Key Possible.  
This means all possible keys are foundable with this method!  
  
Only hexadecimal characters are accepted ( Characters: ABCDEF0123456789 )  
You can type any key that you want and it will incrementally calculate new key based on the one you just entered!  
The program will check the balance of each generated key, each time a key is found with balance a sound alert will be played and the wallet address + private key will be added to the text file "results.txt"  
The last searched private key will be saved in the file "lastprvkey.dat"  
  
You have the option to "Create database OFFLINE", this option will save all generated Ethereum private keys + addresses in a text file named "db0000001.txt".  
When this file has reached the size of 5MB the recording will start under another file name "db0000002.txt" ...  
  
  
6 - "Random Wallet Bruteforce"  
==============================
This function will generate 20 ethereum wallets address and check their balance online in bulk at a speed of more than 100 wallets per seconds if you have a good computer and internet connection.  
There is billions of possibilities so it's like playing the Lottery!  
  
. - "Watchlist Monitoring"  
This function allows you to check each ETH address that you added in the "watchlist.txt" file.
Imagine you have a list of Ethereum addresses that you want to search.
Fill in the "watchlist.txt" file with the list of ETH addresses you are looking for, check the "Watchlist Monitoring" box and click the START button. The software will generate addresses, check their balance and at the same time check that the generated addresses are not present in your watchlist. If an address in your WatchList is found wille generating it will be saved in your "results.txt" file.
  
. - "Offline"  
This function allows you to verify the addresses that the software will generate with the addresses you are looking for in the "watchlist.txt" file in OFFLINE MODE (No balance checking) at an incredible speed.

    
Where is the file containing the found wallets?  
================================================  
All wallet with balance are added to the results.txt file inside the program directory.  
  
  
Limitation / Full version?  
==========================
This software is limited to scan/check 10.000 address per day freely.
To unlock the software in order to be able to scan unlimited Ethereum Addresses send $40 in Ethereum to the following Ethereum (Mainnet) address : 0x349eaBB45f2Cb9DD39e5e24711339ad6E1f86243

**WARNING, SEND ONLY ETHEREUM (MainNET) TO THIS ADDRESS**

Once your payment is done, simply send your "Ethereum Transaction ID" + your "Sofware ID" by mail to " ews.unscented268@passinbox.com "  
We will reply to your mail with your Software Registration Code in order to fully unlock all limits.

---------------------------------------------------------------------------------------  

System Requirements
-----------------------------
Windows 7/8/10/11
.NET Framework 4.6

                                          ---------------------------------------------------------------------------------------  
  
  
History  
=======
Version 3.2.9 - 07.2024- Improvements  
Version 3.2.4 - 06.2024- Bugfixes  
Version 3.2.1 - 05.2024- Various speed improvements  
Version 3.2 - 04.2024- Bugfixes  
Version 2.9 - 01.2024- Incremental Private Key Attack (Hack)  
Version 2.5 - 12.2023 - Generate Ethereum from Mnemonic Seed 12 words  
Version 2.5 - 06.2023 -  bugfixes + some improvements  
Version 2.5 - Keystore Bruteforce funtion update  
Version 2.4.5 - Keystore Bruteforce funtion  
Version 2.4 - Keystore decryption funtion update  
Version 2.3 - Keystore decryption funtion  
Version 2.3  - Bug fix, code  update  
Version 2.0 - Bug fix and internal problems  
Version 1.7.5 - Fix memory leak / Adding new functionality  
Version 1.7.4 - Bug fix unknow bugs  
Version 1.7.2 - Replacing function "to search a specific eth address" by an "ETH Addresses Watchlist function" & Offline function  
Version 1.7.1 - Minor bugfixes + Speed improvement  
Version 1.7.1 - 07.2021  
Version 1.6 - 07.2021  
Version 1.5 - 05.2021  
Version 1.3 - 04.2021  
Version 0.9 - 04.2021  
