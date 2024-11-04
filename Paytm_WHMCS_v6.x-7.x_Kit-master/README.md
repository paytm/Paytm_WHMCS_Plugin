# Introduction

This integration kit is used in WHMCS PHP E-Commerce Application. This library provides support for Paytm payment gateway.

# Installation

Copy the files from this plugin into the corresponding folders on your installation, as mentioned below:
 1. Copy the Paytm/gateways/paytm.php file into your installation's /module/gateways/ folder
 2. Copy the Paytm/gateways/callback/paytm.php file into your installation's /module/gateways/callback folder.
 3. Copy the Paytm/gateways/paytm-sdk folder into your /module/gateways folder

See Video : https://www.youtube.com/watch?v=CBWWYawttE4

# Configuration

Provide the values for the following in the *Configuration Settings* of the Admin Panel.
 1. Merchant ID
 2. Website
 3. Merchant Key
 4. Channel ID
 5. Industry Type ID
 6. Transaction URL
 7. Transaction Status URL

# Paytm PG URL Details
	Staging	
		Transaction URL             => https://securestage.paytmpayments.com/theia/processTransaction
		Transaction Status Url      => https://securestage.paytmpayments.com/merchant-status/getTxnStatus

	Production
		Transaction URL             => https://secure.paytmpayments.com/theia/processTransaction
		Transaction Status Url      => https://secure.paytmpayments.com/merchant-status/getTxnStatus
