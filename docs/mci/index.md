# TPP User Guide for BFC's Modified Customer Interface

## Introduction

BFC's Modified Customer Interface (MCI) enables a Third Party Provider (TPP) to access any of BFC's Payment Service User (PSU) payment accounts via a browser based access channel. 

Under PSD2 regulation, TPPs that are planning to connect to this interface require a compliant eIDAS certificate. BFC’s MCI requires a Qualified Web Authentication Certificate (QWAC) which will be validated by BFC Bank as part of the connection establishment process.

Upon succesful connection and validation of certificate, a TPP will then be required to get the PSU to authenicate (using their online banking credentials) in order to gain access to requested services.

## Production MCI endpoint

BFC's endpoint where a TPP can get authorised MCI access is: [mci.bfconline.bfcbank.co.uk](mci.bfconline.bfcbank.co.uk). This endpoint is only available to TPPs with a valid QWAC.

## Staging MCI endpoint

BFC has also provided a testing facility in the form of a staging link: [sandbox.mci.bfconline.bfcbank.co.uk](sandbox.mci.bfconline.bfcbank.co.uk). This endpoint is available to TPPs who have a test certificate from the [UK Open Banking Directory](https://www.openbanking.org.uk/providers/directory/).

[Home](../index)
