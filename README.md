# Elvis DAM Icecat panel plugin

This is a proof-of-concept integration.

The Icecat panel plugin links product specs from icecat.com to assets stored in Elvis. You can review all product specs by simply clicking an asset in Elvis. Product information is linked on a unique product id: the gtin number.

This sample plugin demonstrates how easy it is to show external asset information in a panel.

![show product information from Icecat](https://github.com/WoodWing/elvis_icecat_integration/blob/master/icecat-integration.gif "show product information from Icecat")

## Prerequisites

The integration requires:

* Fully installed and licensed [Elvis DAM server](https://www.woodwing.com/en/digital-asset-management-system) - v6.1 or higher. 
* Elvis administrator knowledge

## Installation

* Read the [instruction](https://helpcenter.woodwing.com/hc/en-us/articles/202965685-Plug-ins-introduction-management) on installing Elvis plug-ins.
* Download or clone this pacakge.
* If you downloaded the package: unpack the zip file and remove the GitHub branch postfix from the folder name (typically -master)
* Copy the folder to the Elvis Server plug-ins folder: `<Elvis Config>/plugins/active`.
* Activate the plug-in through the Elvis Management Console

## Usage

* Import one or more product images/videos in Elvis (you download them from icecat.com)
* Set the gtin metadata field with the correct product id
* Select an asset and open the Icecat panel

## Changelog

v1.0
* Initial implementation
