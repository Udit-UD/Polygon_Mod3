# Custom Circuit Using Circom

In this project, I've designed a custom circuit using `Circom` and deployed it on `Mumbai Testnet` i.e. on `Polygon Chain`.

## Description

This is basically a project submission of `Polygon [Advanced]` course provided by `Metacrafters`. In this project I have to create a custom circuit (shown in image below) by using `circom` language and then verify that circuit on custom inputs. Finally we have to deploy the verifier on `Mumbai Testnet`.

## Getting Started

### Installing

You use this project, you have to install some libraies. Follow the steps mentioned below: 

* Clone this repo, by using `git clone https://github.com/Udit-UD/Polygon_Mod3.git` command.
* Use `npm i` to install all npm neccessary packages.
* Create a `.env` file and store your `PRIVATE_KEY` and `API_KEY` there.

### Executing program

* You have to compile the CIRCOM file first, and for this you can run `npx hardhat circom`.
* Then, to deploy the file you can run: 
```
npx hardhat run scripts/deploy.ts --network mumbai
```
It will deploy your verifier on mumbai testnet.

## Help

`npx hardhat circom` command doesn't work on `WINDOWS`, you can use any other OS for this project, or you can use `GITPOD.io`.

## Authors

This project is created by UDIT GUPTA.
