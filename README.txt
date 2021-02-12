# cosX2

Start new project as usual

File -> New File -> File Templates Plotting (select all targets)
Delete File.swift

Copy from App to [nameOfActualApp], delete App
Copy from contentViewText to ContentView, delete contentViewText

File -> Swift Packages -> add dependency -> webpage{GitHub core-plot core-plot} release 2.4

Click main project -> General -> Frameworks -> Add CorePlot

Tests -> Build Phases -> Link Binary w/ Lib -> Add CorePlot

Fix @ObservedObject in contentView
