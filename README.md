LEO - RUST
The bootcamp was created on Coin Ex and Aleo to introduce developer to Leo Programming Language which is built on Rust. The programme was divided into three workshop as follows:

Workshop 1
The following processes were followed:

Process
Install rust on your user computer. This is after Microsoft Visual Studio Code has been downloaded.
Next, clone the leo repo from their official github page. git clone https://github.com/AleoHQ/leo
Leo Wallet extension was also installed.
Leo Wallet Discord Channel joined and tokens acquired.
Next cd leo
cargo install --path . to install the dependencies.
leo new lizzynewexample. Note: The name of your project must be in lowercase and can be any random name.
cd todolist
Next, change the PRIVATE_KEY in your .env file to your PRIVATE_KEY. PRIVATE_KEY is available on the wallet.
leo run
leo deploy
Transaction ID Generated after deployment was: at17h5p2697qwdvmdg7hj0xqq5u0fu79pqtts2ry7eqw6g7ssh0hs8q8rvqax


Workshop 2
Process
This workshop served to introduce the transfer process on leo.
Create a new project in examples leo new newproject. Note also: The name of your project must be in lowercase and can be any random name.
Next process is to input the following commands:
cd newproject
Change the PRIVATE_KEY in your .env file to as in Workshop one to yours.
leo run mint yourwalletaddress 1000u64 --network testnet
leo run transfer "token" yourwalletaddress 100u64 --network testnet
leo deploy
Transaction ID: at1ryp4mexwcrze2y8s403urcegrsaskmjlpk94ut72s4k9wjl5ayrqxz3lga


Workshop 3
Process
The final project was to demonstrate how an actual transfer works across sender and receiver wallets.
Create a new project in examples leo new newproject. Note also: The name of your project must be in lowercase and can be any random name.
cd newproject
Change the PRIVATE_KEY in your .env file to yours
leo run combine_hash_owner_reciever yourwalletaddress receiverwalletaddress
leo run
leo deploy
Transaction ID: at1r09xp4p7zqjqrsau9k559qvwwh8kaagxfu0zeafsd9wzj7x8zgqqewtdp9

