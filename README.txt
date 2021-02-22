# BasicCorePlotForPhys440 - see files within Shared folder here if anything is unclear. This example should plot y = x with CorePlot.

Start new project as usual

File -> New File -> File Templates Plotting (select all targets)
Delete File.swift

Copy from App to [nameOfActualApp], delete App
Copy from contentViewText to ContentView, delete contentViewText

File -> Swift Packages -> add dependency -> webpage{https://github.com/core-plot/core-plot/} release-2.4

Click main project -> Targets -> General -> Frameworks -> Add CorePlot
Click main project -> Targets -> Signing and Capabilities -> enable read/write

Tests -> Build Phases -> Link Binary w/ Lib -> Add CorePlot

Fix @ObservedObject in contentView
