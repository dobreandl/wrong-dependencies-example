
# Description

Demo project for highlighting the mACS process using the CoordCateg approach.

It showcases all the output phases of mACS in a project in which an unallowed dependency is present.

The MVC unallowed dependedency resides in the [WrongView.swift](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/WrongView.swift) which is forbbiden in Apple's MVC.

This wrong dependency is correctly identified by mACS.

The codebase uses an coordinator [AppDelegate](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/AppDelegate.swift) which is correctly detected by the CoordCateg approach.

## Codebase

* [Swift Project](https://github.com/dobreandl/wrong-dependencies-example/tree/master/demoWrongDependencies)

## Detection

* [Model](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/Model/Model.swift)
* [WrongView](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/WrongView.swift)
* [CorrectView](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/CorrectView.swift)
* [ViewController](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/ViewController.swift)
* [AppDelegate](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/AppDelegate.swift)


## Extraction Graph

![alt text](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/graphs/extraction.png)


## Categorisation

### Model

* [Model](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/Model/Model.swift)

### View

* [WrongView](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/WrongView.swift)
* [CorrectView](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/CorrectView.swift)

### Controller

* [ViewController](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/ViewController.swift)
* [AppDelegate](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/AppDelegate.swift)

## MVC Analysis

### Wrong dependencies graph

![alt text](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/graphs/wrongCoordinators.png)

### Analysis results

![alt text](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/results/coordCateg.png)


