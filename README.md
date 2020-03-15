
# Description

Demo project for highlighting the mACS process using the SimpleCateg & CoordCateg approaches.

It showcases all the output phases of mACS in a project in which an unallowed dependency is present.

The MVC unallowed dependedency resides in the [WrongView.swift](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/WrongView.swift) which is forbbiden in Apple's MVC.

This wrong dependency is correctly identified by mACS.

The SimpleCateg approach fails to detect correctly all the elements of the codebase since this demo uses a coordinating controller [AppDelegate](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/AppDelegate.swift).

## Codebase

* [Swift Project](https://github.com/dobreandl/wrong-dependencies-example/tree/master/demoWrongDependencies)

## Codebase components

* [Model](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/Model/Model.swift)
* [WrongView](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/WrongView.swift)
* [CorrectView](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/CorrectView.swift)
* [ViewController](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/ViewController.swift)
* [AppDelegate](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/AppDelegate.swift)


## Ground truth

The elements split by MVC layers

### Model

* [Model](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/Model/Model.swift)

### View

* [WrongView](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/WrongView.swift)
* [CorrectView](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/CorrectView.swift)

### Controller

* View Controller - [ViewController](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/ViewController.swift)
* Coordinating Controller - [AppDelegate](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/AppDelegate.swift)

## Approaches

* [SimpleCateg](https://github.com/dobreandl/wrong-dependencies-example/blob/master/simpleCateg.md)
* [CoordCateg](https://github.com/dobreandl/wrong-dependencies-example/blob/master/coordCateg.md)
