# BasicCorePlotForPhys440 
...(see files within Shared folder for more details. This example should plot y = x with CorePlot.)

Start new project as usual

File -> New File -> File Templates Plotting (select all targets)
Delete File.swift

Copy from App to [nameOfActualApp], delete App
Copy from contentViewText to ContentView, delete contentViewText

File -> Swift Packages -> add dependency -> copy this link https://github.com/core-plot/core-plot/ and paste into XCode, click next -> type into Branch: "release-2.4"

Click main project -> Targets -> General -> Frameworks -> Add CorePlot
Click main project -> Targets -> Signing and Capabilities -> enable read/write

Tests -> Build Phases -> Link Binary w/ Lib -> Add CorePlot

Fix @ObservedObject in contentView
