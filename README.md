<h1 align="center">
	<img
	width="150"
	src="/images/max-terminal.gif"></br>
	Getting started with DataWeave libraries in Anypoint Exchange<br>     
</h1>

<h4 align="center">
	<a href="#overview">Overview</a> |
	<a href="#installation-instructions">Install Me</a> |
	<a href="#contributing">Contribute</a>
</h4>
	
<h3 align="center">
	Learn how to publish and use DataWeave libraries in Exchange and a Mule application<br><br>
</h3>

## Tutorial and Video

For a step by step tutorial navigate to the MuleSoft developer website [here](https://developer.mulesoft.com/tutorials-and-howtos/dataweave/dataweave-libraries-in-exchange-getting-started/)

## Overview

The `Standard Date Formats` folder is a DataWeave library project example to run with the DataWeave extension in VSCode. 

Includes:
- A module `DateFormatConversion` with a function `dateTimeConversion`.
- A mapping file `DateFormatConversionMapping` to test the code live.
- Unit tests in `DateFormatConversionTest` for quality and CI/CD purposes.
- Required credentials in the `pom.xml` file to deploy to Exchange.

The `dw-lib` folder is a Mule project with a sample application to make use of the DataWeave library from Exchange.

Includes:
- Changes on the `pom.xml` to include the Exchange DataWeave library.
- A simple flow with a Transform Message component making use of the DataWeave library.

> **Note**: You need to change the `Organization ID` with your own. You need to follow the tutorial to learn how to set up your own Org ID.

## Installation Instructions

**For the DataWeave library:**

1. Download [Visual Studio Code](https://code.visualstudio.com/Download).

2. Install the **DataWeave** extension by **MuleSoft Inc**.

3. Clone this repository.

4. Open the `Standard Date Formats` folder in VSCode.

**For the Mule project:**

1. Set up your environment.

<a href="https://anypoint.mulesoft.com/login/signup" ><img width="250" src="/images/start-platform.png"><a>
	
<a href="https://www.mulesoft.com/lp/dl/studio" ><img width="250" src="/images/download-studio.png"><a>

2. Clone this repository.

3. In Anypoint Studio, select `File` > `Import` > `Anypoint Studio` > `Anypoint Studio project from File System` and click Next.

4. Select the `dw-lib` folder in the Project Root and make sure to **uncheck** the `Copy project into workspace` option.

5. Click on Finish.

## Contributing

Contributions are what make the MuleSoft community such an amazing place. Any contributions you make are **greatly appreciated**.
	
See [contributing.md](/contributing.md) for the MuleSoft Developer principles.

#### Code formatting

[Prettier](https://prettier.io/) is a code formatter used to ensure consistent formatting across your code base. To use Prettier with Visual Studio Code, install [this extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) from the Visual Studio Code Marketplace. The [.prettierignore](/.prettierignore) and [.prettierrc](/.prettierrc) files are provided as part of this repository to control the behavior of the Prettier formatter.
