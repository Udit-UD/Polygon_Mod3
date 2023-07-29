# Custom Circuit Using Circom

In this project, I've designed a custom circuit using `Circom` and deployed it on `Mumbai Testnet` i.e. on `Polygon Chain`.

## Description

This is basically a project submission of the `Polygon [Advanced]` course provided by `Metacrafters`. In this project, I have to create a custom circuit (shown in the image below) by using `circom` language and then verify that circuit on custom inputs. Finally, we have to deploy the verifier on `Mumbai Testnet`.

![circom circuit](https://github.com/Udit-UD/Polygon_Mod3/assets/97906706/707277c5-a2a0-40f3-8903-6b9fb4a84777)


## Getting Started

### Installing

If you use this project, you have to install some libraries. Follow the steps mentioned below: 

* Clone this repo, by using the `git clone https://github.com/Udit-UD/Polygon_Mod3.git` command.
* Use `npm i` to install all npm necessary packages.
* Create a `.env` file and store your `PRIVATE_KEY` and `API_KEY` there.

### Executing program

* You have to compile the CIRCOM file first, and for this, you can run:
```
  npx hardhat circom
```
* Then, to deploy the file you can run: 
```
npx hardhat run scripts/deploy.ts --network mumbai
```
It will deploy your verifier on the Mumbai Testnet.
* You can modify the inputs by modifying `input.json` file.

## Help

The `npx hardhat circom` command doesn't work on `WINDOWS OS`, you can use any other OS for this project, or you can use `GITPOD.io`.

## Authors

This project was created by UDIT GUPTA.
