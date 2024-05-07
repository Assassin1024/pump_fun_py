# pump_fun_py

Decided to share my pump.fun codebase with the world because: 

1.) There are too many scammers out there on github and telegram.

2.) The IDL for pump.fun isn't public information, but it should be. 

Clone the repo, and add your Public Key (wallet), Private Key and RPC to the Config.py.

### Swap Layout
Do not change the hard-coded values as they are part of the actual swap instructions for the pump.fun program. 

**buy = 16927863322537952870**

**sell = 12502976635542562355**

To see for yourself, decode the "Instruction Raw Data" from any pump fun transaction using the find_instruction.py. 

### Contact

Contact me if you need help integrating the code into your own project. 

Telegram: Allen_A_Taylor (AL The Bot Father)

### FAQS

**What is the difference between buy and buy_jito? sell and sell_jito?**

Buy/Sell uses the user defined RPC set in the config.py file. Buy/Sell with Jito uses the Jito Endpoint to potentially speed up your transaction. Set your Jito Tip in Lamports.  

**What format should my private key be in?** 

The private key should be in the base58 string format, not bytes. 
