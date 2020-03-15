
# Description

Demo project for highlighting the mACS process using the SimpleCateg approach.

It showcases all the output phases of mACS in a project in which an unallowed dependency is present.

The MVC unallowed dependedency resides in the [CustomView.swift](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/WrongView.swift) which is forbbiden in Apple's MVC.

This wrong dependency is correctly identified by mACS.

## Codebase

* [Swift Project](https://github.com/dobreandl/wrong-dependencies-example/tree/master/demoWrongDependencies)

## Detection

* [Model](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/Model/Model.swift)
* [WrongView]https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/WrongView.swift)
* [CorrectView](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/CorrectView.swift)
* [ViewController](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/ViewController.swift)
* [AppDelegate](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/AppDelegate.swift)


## Extraction phase output

* [Model](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/json/model.json)
* [View](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/json/view.json)
* [Controller](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/json/view_controller.json)

## MVC Analysis results

* [Results](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/results/Screenshot%202020-03-14%20at%2012.28.27.png)


