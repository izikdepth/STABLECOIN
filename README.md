this is a stablecoin that's 
-anchored or pegged to the $USD, [use a chainlink feed to set a function that'll exchange btc&eth to our stablecoin]

-we'll use an algorithmic mechanism to maintain the peg
    People can only mint with enough collateral {hardcoded into the system}

-collateral type is exogenous {crypto collateral} 
    note: The term "exogenous" refers to something that originates externally or outside of a particular system or process.
    our collateral will be in 
    1. wbtc, and 
    2. weth

to install forge run
``forge install``

to initialize run
``forge init``

to install openzeppelin run
``forge install openzeppelin/openzeppelin-contracts@v4.8.3 --no-commit``

start a local node on anvil
``make anvil``

to deploy
``make deploy``

to run test
``forge test``

to deploy to sepolia
``make deploy ARGS="--network sepolia"``

note: you should put your rpc url in a .env file and also your sepolia network private key

# STABLECOIN
