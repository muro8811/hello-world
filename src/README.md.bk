# What is Whitebox SDK?

The R-Car S4 Whitebox SDK is an integrated development platform that accelerates the development of connected services applications.
 
All software is provided as an all-in-one package under a Free of Charge (FoC) license, which facilitates testing and can be widely used in advanced development. In addition, since the software is mainly open source, users are free to modify the source code as they wish.

Please refer to the official webpage:

- https://www.renesas.com/whitebox-sdk

# Table of contents

- [Setup](#Setup)
- [Tool setup](#Tool-setup)
- [Build](#Build)
- [LICENSE](#LICENSE)
- [Documentation](#Documentation)
- [Support](#Support)
  - [FAQ](#FAQ)
  - [Community Q&A forum](#Community-QA-forum)

# Setup
Execute the following command:

	bash -c "$(wget -O- https://raw.githubusercontent.com/renesas-rcar/whitebox-sdk/v5.0/tool/repo_init.sh )"

# Tool setup
Since GUI operation is required during installation, it must be run on an Ubuntu PC.
Please obtain the compiler in advance; "RH850 Compiler CC-RH V2.05.00 for e2 studio" is available from the following site.

https://www.renesas.com/us/en/software-tool/c-compiler-package-rh850-family#download

Save the downloaded file (CC-RH_V20500_setup-doc.zip) in the "tool" folder. Execute the following command.

	cp CC-RH_V20500_setup-doc.zip ./whitebox-sdk/tool

Obtain "ICUMX Loader and Flash writer Package for R-Car S4 Starter Kit". If the newest release is published more than v3.16.1 on web site, please use the latest one. In that case, the description of version information should be replaced to its version.

https://www.renesas.com/us/en/products/automotive-products/automotive-system-chips-socs/y-ask-rcar-s4-1000base-t-r-car-s4-starter-kit#design_development

Save the downloaded file (ICUMX_Loader_and_Flashwriter_Package_for_R-Car_S4_Starter_Kit_SDKv3.16.1.zip) in the "tool" folder. Execute the following command.

	cp ICUMX_Loader_and_Flashwriter_Package_for_R-Car_S4_Starter_Kit_SDKv3.16.1.zip ./whitebox-sdk/tool

Execute the following command:

	cd ./whitebox-sdk/tool
	./setup_whitebox.sh

# Build
Execute the following command:

	cd whitebox-sdk
	./build_whitebox_v5.0.sh  <BOARD>

`BOARD` is "spider" or "s4sk"

#You can check the generated image with the following command:

	ls -l deploy

# LICENSE

If there is a directory that contains file which notices about license information(such as LICENSE/COPYING/Readme and so on),
all files in that directory are licensed under its license.

And, if file has license information(such as spdx information, comment in header, and so on),
its license has priority to other license information(such as license of this repository, license file in the directory, and so on).

Except for the above, all files in this repository are licensed under the [MIT License](./COPYING.MIT).


Ex.) License priority:

File's license information > License notification in the directory > License of this repository

# Documentation
 
The user's manuals are available for free, please download it from the official website
 
https://www.renesas.com/whitebox-sdk#documents

# Support

## FAQ

- En: https://en-support.renesas.com/knowledgeBase/category/31891/subcategory/31856
- Ja: https://ja-support.renesas.com/knowledgeBase/category/31892/subcategory/31857

## Community Q&A forum

- En: https://community.renesas.com/automotive/gateway/

