### IIFL Securities Open apis: Golang

**Project Requirement**
1. Golang (go1.15 +)
2. Visual Studio Code 

**How to install**

1) Install Golang (https://golang.org/doc/install)
2) Visual Studio Code (https://code.visualstudio.com/)
3) Install golang extension in visual studio (https://marketplace.visualstudio.com/items?itemName=golang.go#getting-started)
	i) Open Visual Studio Code then Navigate to the Extensions pane (Ctrl+Shift+X). 
	ii) Search for "Go" and install this extension (the publisher ID is golang.Go).
4) Note: Automatically some extension will be installed by Visual Studio Code. Install all that extension which are recommended.

Ones project dependency is installed, follow following step to run the program

1) Open Terminal in Visual Studio Code (Ctrl+Shift+`)
2) Enter this (go run main.go) in terminal.
	application will start in http://localhost:10000



### Location of main files

**API:**
1) main.go
2) class/CustomerLogin.go
3) class/MarketFeed.go
4) class/BackOff.go
5) class/Order.go
6) class/Report.go

**Auth**
1) class/Auth.go

**Properties of Request and Response**
1) class/class.go

**Send Request Methods**
1) class/UrlClient.go

**Extra function (To get the Config and IPAddress)**
1) class/funct.go


**All credentials values**
1) conf.json
