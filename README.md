# Ali_Khatami_SmartContract_Lottery(learning from the video of Patrick Collins)

### Introduction

Here we are building an application that allow users completely decentralized to allow use to engage in a fair , verifiable random lottery <br>

This application will fix McDonald issue that we talked much earlier <br>

To do this to get a pure verifiable random number we gonna use Chainlink VRF to get pure verifiable random number <br>

Then we gonna use chainlink keepers to trigger the automation to automatically have one of these winners get <br>

picked every time one of those time intervals is up <br>


### Hardhat Setup
![l1](https://github.com/C191068/Ali_Khatami_Lottery/assets/89090776/d673276a-9eb6-469e-b1e7-f9e8f4ba00bb)
Here the above we opened a new folder <br>

![l2](https://github.com/C191068/Ali_Khatami_Lottery/assets/89090776/0cdbcbaf-9b2a-4d0c-8e8e-958f59f09b0d)

Then we run the above command ```yarn add --dev hardhat``` <br>

![l4](https://github.com/C191068/Ali_Khatami_Lottery/assets/89090776/1aa9735d-d9fe-4c2e-a864-b7b5f3f2b943)

Then we wil give the above command yarn hardhat and then select ```Create an empty hardhat.config.js``` <br>

because we gonna add customization to our project <br>

![l5](https://github.com/C191068/Ali_Khatami_Lottery/assets/89090776/b4d45b17-3c54-4ecf-85f7-8c307e5ead55)
Now we have here blank hardhat.config.js file <br>

![l6](https://github.com/C191068/Ali_Khatami_Lottery/assets/89090776/07b858b6-7461-48e3-9506-bdf0f13420a5)
To bring yarn.lock we give the above two commands <br>

![l7](https://github.com/C191068/Ali_Khatami_Lottery/assets/89090776/ce37199a-fde8-4532-b282-ab7b27c0fe61)

Then we give the below command above <br>

```
yarn add --dev @nomiclabs/hardhat-ethers@npm:hardhat-deploy-ethers ethers @nomiclabs/hardhat-etherscan @nomiclabs/hardhat-waffle chai ethereum-waffle hardhat hardhat-contract-sizer hardhat-deploy hardhat-gas-reporter prettier prettier-plugin-solidity solhint solidity-coverage dotenv

```

Remember at the end of the day the best for you and best for your job is the tool that you like the most <br>


![l8](https://github.com/C191068/Ali_Khatami_Lottery/assets/89090776/3b5c8e59-84d8-4502-8a72-664e01138cf8)

by going to the link below:

https://github.com/PatrickAlphaC/hardhat-smartcontract-lottery-fcc/blob/main/hardhat.config.js

we copy the above black arrow part <br>

![l9](https://github.com/C191068/Ali_Khatami_Lottery/assets/89090776/5998adf0-3a3c-4b26-a767-07e08bac0a75)

Then we paste it at the above hardhat.config.js file <br>





