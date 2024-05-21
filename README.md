# PSoC6 UDB-Components
UDB Components for PSoC6

Not tested thoroughly. Use at own risk!

Currently available:

| Component                | Notes  |
|--------------------------|--------|
|UDB UART for PSoC6        |The UDB UART for PSoC6 currently only works with an external clock. Use an external clock with 8 times the desired baudrate.|
|UDB I2C for PSoC6         |        |
|UDB PWM for PSoC6         |        |
|UDB SPI Master for PSoC6  |        |
|UDB Timer PSoC6           |        |

# Importing the components
The components can be either imported all together as a dependency or per component itself.

## Method 1: Adding the project dependency
- [Download and unzip the UDB_Components.cylib.zip](https://github.com/onethinx/UDB-Components/raw/master/UDB_Components.cylib.zip)
- Add the dependency reference to the cyprj project file:
![Creator_Import_Component](https://github.com/onethinx/Readme_assets/blob/main/UDB-import-project.png?raw=true)

## Method 2: Adding a single component
- Import the component into your design.
![Creator_Import_Component](https://github.com/onethinx/Readme_assets/blob/main/UDB-import-component.png?raw=true)
- Select the component (.cycomp) and click OK.

## Usage
Use them from the Onethinx tab.<br>
![Creator_Import_Component](https://github.com/onethinx/Readme_assets/blob/main/UDB-Onethinx-tab.png?raw=true)
<br>And have fun!
