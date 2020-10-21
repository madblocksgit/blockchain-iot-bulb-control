# blockchain-iot-bulb-control
Controlling a device through Blockchain, where the device is plugged to Raspberry Pi.

# Brief Intro
In this project, there is a need of Laptop where local blockchain (ganache) is running and also there is a need of Raspberry Pi to which a bulb is connected at GPIO21. When you press Bulb On button on UI, then the bulb connected to Raspberry Pi will be on and the respective transaction hash would be displayed on the UI and same applies to Bulb Off.

# Requirements on Laptop
sudo pip3 install web3 <br/>
sudo pip3 install paho-mqtt <br/>
sudo pip3 install flask <br/>

# Requirements on Raspberry Pi
sudo pip3 install paho-mqtt

# Usage
1. Open Ganache Blockchain
2. truffle compile
3. truffle migrate
4. Copy the Contract Address once the contracts are migrated onto the Ganache
5. Paste that Contract address in src/app.py where there would be a variable which holds the contract address
6. and finally run python3 app.py or sudo python3 app.py



