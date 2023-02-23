# Food Lion - Load All To Card (Firefox version)

## Introduction

This is a browser extension that adds a "Load All To Card" button to the Food Lion [MVP Coupons Center](https://www.foodlion.com/coupons/). The Javascript action on this button will click on all the coupons in one shot, adding all of them to the card.

## Installation

To build the Firefox web extension:

* Install web-ext if necessary: ``npm install -g web-ext``
* Get the git repository: ``git clone git@github.com:mortonfox/food-lion-load-all-to-card-firefox.git``
* ``cd food-lion-load-all-to-card-firefox``
* Pack the extension: ``web-ext build``

The packed extension will be a zip file under the ``web-ext-artifacts`` folder.

To submit the Firefox add-on:

* Log in at <https://addons.mozilla.org>
* Pull down the menu under your name in the top right corner.
* Click on "Submit a New Add-on".
* For "How to Distribute this Version", select "On your own". Then click on "Continue".
* Under "Upload Version", click on "Select a file..." and pick the zip file that was generated by web-ext under ``web-ext-artifacts``.
* After the extension has been validated, click on "Continue".
* For "Do you use any of the following in your extension?", answer "No" and click on "Continue".
* Wait for the add-on to be reviewed.

Mozilla will send you an email once the extension has been reviewed.

To install the extension:

* Go to <https://addons.mozilla.org/en-US/developers/addons> and find the extension in the list.
* Click on the extension name.
* Click on "View All".
* Click on the version number.
* Click on the XPI file name to install it.

## Usage

Once you've installed and enabled this extension, go to the Food Lion MVP Coupons Center and find the "Load All To Card" button on the top left corner. Click on it and it will load all the coupons to your card.
